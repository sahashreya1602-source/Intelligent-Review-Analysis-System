# Intelligent-Review-Analysis-System
AI-driven review analysis system with automated complaint detection and solution recommendation engine.

## Overview
This project is an end-to-end AI-powered customer review intelligence system. It analyzes real app reviews using transformer-based NLP models to detect sentiment, classify complaints, prioritize issues by severity, and generate automated resolution recommendations.

The system converts unstructured customer feedback into structured business insights.

## Key Features
- Real review data scraping using Google Play Scraper
- Transformer-based multilingual sentiment analysis
- Complaint categorization using rule-based taxonomy
- Severity scoring for prioritization
- Automated action recommendation system
- Executive summary reporting

## Tech Stack
- Python
- Pandas
- Transformers (HuggingFace)
- Scikit-learn
- NLTK
- Matplotlib
- Google Play Scraper

## Pipeline Architecture
1. Data Collection
2. Text Cleaning & Preprocessing
3. AI Sentiment Analysis
4. Complaint Type Detection
5. Severity Scoring
6. Automated Resolution Suggestion
7. Executive Summary Generation
8. Report Export

## Key Insights
- Automated detection of negative and critical reviews
- Structured classification of customer complaints
- Priority-based resolution mapping
- Business-ready CSV output for decision-making

## How to Run
Install dependencies:

pip install -r requirements.txt

Run the notebook:

Ai_Review_Analysis.ipynb

## Output
- AI_Review_Analysis_Report.csv
- Sentiment Distribution
- Complaint Distribution
- Severity Analysis
- Recommended Business Actions
