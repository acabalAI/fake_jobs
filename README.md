# Fake Job Detection-Model and Visualization

Developing a Fake Job Detection Model and Visualization toolset aimed at identifying fraudulent job postings across various job portals, using data analysis and visualization tools to aid job seekers.

## Data and Libraries Import

Essential libraries like imblearn, transformers, umap-learn, hdbscan, along with standard data processing and visualization libraries (numpy, pandas, matplotlib, seaborn) are used.

## Data Acquisition

Data is fetched and loaded into Pandas DataFrame from a specified URL.

## EDA (Exploratory Data Analysis)

Includes data verification, null value checks, and basic statistical analysis.

## Data Preprocessing

Focuses on text preprocessing of job titles and descriptions, including removal of stopwords and other standard NLP preprocessing techniques.
## Model Building

Various machine learning models are employed, including Random Forest, Naive Bayes, Logistic Regression, and others. Model evaluation includes accuracy, precision, recall, F1 score, and more.
## Visualization

Includes Word Cloud generation and Topic Modeling-Clustering using techniques like UMAP and HDBSCAN.
## Semantic Interpretation

Interprets the clusters identified in the topic modeling stage, providing insights into different groups of job postings.
## App Demo (WIP)

An application demonstration involving a user interface is in progress.
## Summary

Outlines the methodologies and techniques used for fake job detection and job seeker guidance, including resampling for a balanced dataset and the use of Random Forest for classification.
## Future Directions

Discusses potential enhancements like incorporating Language Model for Personalized Guidance and Interactive User Interfaces for improved job seeker assistance.
