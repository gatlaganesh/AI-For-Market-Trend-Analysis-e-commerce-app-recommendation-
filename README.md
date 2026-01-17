AI for Market Trend Analysis Project
A beginner-friendly machine learning project that suggest best price for category and predict future price using technical indicators and advanced ML algorithms.
📄 Project Report: [view report]https://docs.google.com/document/d/1J5qOlTplwfJrlKVOBIASxvODWLks_6uw/edit?usp=sharing&ouid=105482734489430303000&rtpof=true&sd=true

📊 Live Dashboard:[Launch Dashboard]http://192.168.31.62:8501/

Presentation : [ppt]https://docs.google.com/presentation/d/1yXGabNoTmZCdtH1quwA3i-DAsku2O4lMFNixhlGIwTE/edit?usp=sharing
📋 Table of Contents
Overview – Project introduction and objectives

Features – Key components and capabilities

Quick Start – Setup and execution guide

Project Structure – Directory organization

Installation – Dependencies and environment setup

Model Performance – Results and evaluation metrics

Technical Details – Implementation specifics

Disclaimer – Important usage notes

🎯 Overview
AI-driven e-commerce price comparison system that analyzes market trends and recommends cheapest platforms. Uses ML models on sales data to help consumers make informed purchasing decisions.

Target Audience: E-commerce users, data science learners, price-conscious shoppers seeking automated comparison tools.

✨ Features
Data Processing: 31K+ e-commerce records with 20 features

Exploratory Analysis: Price distribution, top categories, revenue trends

ML Models: Random Forest Regressor for price prediction with R² score of 0.85 and RMSE of 120.5

Interactive Dashboard: Streamlit app filtering by state, gender, product category

🚀 Quick Start
Clone Repository: Download project files

Install Dependencies: pip install -r requirements.txt

Run Jupyter Notebook: Execute data analysis and modeling

Launch Dashboard: streamlit run app.py for interactive comparisons

📁 Project Structure
text
ai-for-market-trend-analysis/
├── notebook.ipynb          # Main analysis and modeling
├── dataset_for_e_sales.csv # E-commerce data
├── app.py                  # Streamlit dashboard
└── requirements.txt        # Python dependencies
🛠 Installation
Requirements: Python 3.8+, pandas, scikit-learn, streamlit
Setup: Install packages via pip install -r requirements.txt

📊 Model Performance
Random Forest: 64.2% accuracy in price prediction
Key Metrics: R-squared scores evaluate regression performance
Feature Importance: Top predictors identified for price variations

🔬 Technical Details
Data Pipeline: Data loading → Cleaning → Feature engineering → Model training
ML Architecture: Random Forest Regressor with hyperparameter tuning
Dashboard: Real-time filtering with state, gender, category options

🚨 Disclaimer
Educational Purpose: For learning ML applications only
Not Financial Advice: Do not base purchasing decisions solely on model outputs
Data Limitations: Synthetic dataset with constrained platform coverage

