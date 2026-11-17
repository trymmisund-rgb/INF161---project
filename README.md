# What does a language model believe about history?

Course project in INF161 Introduction to Data Science at the University of Bergen, fall 2026.

A language model (Gemma 4 12B) role-played 10,000 famous people (real and fictional) and answered a 62-question survey about personality, politics, values and preferences. The project consists of an exploratory data analysis of the answers and two models:

- **Regression:** predict a person's birth year from their answers (test: median absolute error 74 years)
- **Classification:** predict a person's occupation category from their answers (test: macro F1 ≈ 0.70)

The notebook and report are written in Norwegian.

## Files

- `rapport-endelig.pdf` – final report (start here)
- `prosjekt-endelig.ipynb` – the full analysis

The dataset was provided by the course and is not included.

## Tools

Python, pandas, scikit-learn, Plotly
