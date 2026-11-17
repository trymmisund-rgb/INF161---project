# INF161---project
INF161 course project (UiB, fall 2026): exploratory data analysis and modelling of a 10,000-persona LLM-generated survey dataset in Python/pandas.

What does a language model believe about history?

Course project in INF161 Introduction to Data Science at the University of Bergen, fall 2026.

A language model role-played 10,000 famous people (real and fictional) and answered a 62-question survey about personality, politics, values and preferences. The project consists of an exploratory data analysis of the answers and two models:

Regression: predict a person's birth year from their answers (test: median absolute error 74 years) Classification: predict a person's occupation category from their answers (test: macro F1 ≈ 0.70)

The notebook and report are written in Norwegian.

Files prosjekt-endelig.ipynb – the full analysis rapport-endelig.pdf – final report persona_survey.csv – the dataset Running bash pip install -r requirements.txt jupyter notebook prosjekt-endelig.ipynb

Run Restart & Run All (about 15 minutes). All random steps use SEED = 0.

Tools: Python, pandas, scikit-learn, Plotly
