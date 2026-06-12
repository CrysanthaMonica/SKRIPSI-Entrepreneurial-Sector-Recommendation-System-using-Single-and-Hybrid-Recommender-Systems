# Entrepreneurial Sector Recommendation System using Single and Hybrid Recommender Systems

## 📌 Research Overview

This project presents a prototype entrepreneurial sector recommendation system developed for the BONE (Business Operation Networking and Entrepreneurship) platform. The system aims to help aspiring entrepreneurs identify business sectors that align with their entrepreneurial characteristics and personality profiles. By leveraging explicit questionnaire data, the solution addresses common recommender system challenges such as information overload and the cold-start problem, where historical interaction data is unavailable.

---

## 🧠 Methodology

This research compares two recommendation approaches to evaluate their effectiveness in generating personalized entrepreneurial sector recommendations.

### Knowledge-Based Filtering (Single Approach)

A rule-based recommendation strategy that utilizes explicit user inputs, entrepreneurial characteristics, and personality traits to generate recommendations based on predefined domain knowledge.

### Cascade Hybrid Filtering

A multi-stage recommendation approach that combines Knowledge-Based Filtering with Content-Based Filtering techniques. This method incorporates TF-IDF vectorization and similarity analysis to refine recommendations and improve recommendation diversity.

### User Profiling

The recommendation process evaluates compatibility between users and entrepreneurial sectors based on:

- Big Five Personality Traits (OCEAN)
- Self-Efficacy
- Innovativeness
- Locus of Control
- Need for Achievement

The system applies Euclidean Distance calculations to determine similarity between user profiles and sector characteristics.

---

## 🛠️ Technology Stack

### Programming Language
- Python

### Data Processing & Machine Learning
- Pandas
- NumPy
- Scikit-Learn

### Database
- TiDB (Distributed SQL Database)

### Web Framework
- Streamlit

### Visualization
- Altair

---

## 🚀 Key Features

### Personality-Based Profiling
Generates entrepreneurial profiles from questionnaire responses using psychological and entrepreneurial assessment frameworks.

### Personalized Recommendation Engine
Provides top entrepreneurial sector recommendations by combining personality characteristics and entrepreneurial attributes.

### Hybrid Recommendation Framework
Implements TF-IDF and similarity-based ranking to enhance recommendation relevance and recommendation diversity.

### Cold-Start Support
Generates recommendations without requiring historical user interaction data, making it suitable for first-time users.

### Explainable Recommendations
Provides recommendation scores, personality cluster insights, and sector descriptions to improve transparency and decision-making.

---

## 📊 Evaluation & Results

The prototype was evaluated using a user-centered evaluation approach involving **84 respondents** from various backgrounds, including students, professionals, aspiring entrepreneurs, and SME owners.

### Key Findings

- Knowledge-Based Filtering achieved higher overall user ratings and demonstrated stronger consistency in matching user preferences.
- Hybrid Filtering produced more diverse recommendations and showed potential for improving recommendation variety in cold-start scenarios.
- Both approaches received positive feedback regarding recommendation relevance, usability, and decision-support capabilities.
- The study highlights the trade-off between recommendation consistency and recommendation diversity in entrepreneurship-focused recommender systems.

---

## 🎯 Project Objective

The primary goal of this research is to explore how personality traits and entrepreneurial characteristics can be integrated into recommender systems to support entrepreneurial decision-making and help users discover business sectors that align with their strengths, interests, and entrepreneurial potential.

---

## 👨‍💻 Authors

- Crysantha Monica Lim
- Cherylene Callista Reksohartono
- Aan Albone

---

## 📄 Research Focus

- Recommender Systems
- Knowledge-Based Filtering
- Hybrid Recommender Systems
- Content-Based Filtering
- Personality Analytics
- Big Five Personality Traits (OCEAN)
- Entrepreneurship Recommendation
- Cold-Start Problem
- User-Centered Evaluation
