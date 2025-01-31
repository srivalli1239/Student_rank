Project Overview

This project analyzes quiz performance data and predicts a student's NEET rank based on their quiz history. Additionally, it provides insights into strengths, weaknesses, and expected college admission chances based on predicted rank.

Features

Quiz Performance Analysis: Evaluates accuracy by topic and difficulty.

NEET Rank Prediction: Uses linear regression to predict rank based on past data.

College Admission Prediction: Maps predicted rank to potential college options.

API Integration: Fetches quiz data from online endpoints with error handling.

Setup Instructions

Prerequisites

Python 3.x

Required Libraries:

pip install pandas numpy scikit-learn requests

Steps to Run the Project

Clone the Repository

git clone https://github.com/your-repo/neet-rank-prediction.git
cd neet-rank-prediction

Run the Script

python neet_rank_prediction.py

View the Output

Accuracy by topic and difficulty

Predicted NEET Rank

Expected College Admission

Approach Description

1. Data Collection

Current Quiz Data: Fetches user’s latest quiz submission.

Historical Quiz Data: Analyzes last 5 quiz performances.

NEET Past Data: Uses previous years’ scores and ranks for prediction.

2. Data Processing

Computes accuracy based on correct responses.

Aggregates past quiz scores for trend analysis.

Handles API failures with fallback data.

3. Rank Prediction

Uses Linear Regression to map quiz scores to NEET ranks.

Standardizes inputs using StandardScaler.

Predicts expected rank based on recent quiz scores.

4. College Prediction

Maps predicted rank to previous NEET cutoffs.

Provides college admission likelihood based on thresholds.

Accuracy distribution across subjects.

Performance trends over time.

Rank prediction vs. actual NEET score mapping.

Future Enhancements

Implement Deep Learning models for improved prediction.

Incorporate time-based quiz analytics.

Enhance college mapping using real-time cutoffs.
