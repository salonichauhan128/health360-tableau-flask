# Health360: Comprehensive Healthcare Risk & Disease Analysis

An end-to-end healthcare analytics platform embedding interactive Tableau Public visualizations into a Python Flask web application.

## Overview
- **Dataset**: Smart Healthcare Dataset (5,000 patient records across 17 clinical and lifestyle metrics)
- **Tableau Visualizations**: 9 specialized sheets (KPIs, blood pressure distributions, BMI correlations, lifestyle risk factors, and fatigue prevalence)
- **Tableau Story**: Multi-step narrative presenting key findings and clinical risk insights
- **Web Application**: Flask web service integrating Tableau views via embedded JavaScript objects

## Project Structure
```text
health360-tableau-flask/
│
├── app.py
├── requirements.txt
├── README.md
└── templates/
    ├── index.html
    ├── dashboard.html
    └── story.html
