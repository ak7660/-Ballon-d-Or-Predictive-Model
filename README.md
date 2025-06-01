# Ballon d'Or Predictive Model  

## Overview

This project aims to build a predictive model for the Ballon d'Or award winner using historical football statistics and player performance metrics. By leveraging machine learning models and data preprocessing techniques, we explore which factors contribute most strongly to a player's likelihood of winning the award.

## Objectives

- Build a robust dataset of Ballon d’Or nominees and key football statistics.
- Perform exploratory data analysis (EDA) to uncover important features.
- Train multiple classification models to predict Ballon d’Or outcomes.
- Evaluate model performance and interpret results.

## Data Sources

- **Ballon d'Or Data:** Historical nominee/winner data from France Football and Kaggle datasets.
- **Player Stats:** Aggregated seasonal player statistics (goals, assists, minutes played, trophies, etc.) from FBref, Transfermarkt, and official league databases.

## Methodology

### 1. Data Preparation
- Merged Ballon d'Or nominee data with seasonal performance data.
- Engineered features including trophy count, G+A per 90 minutes, league coefficients, and more.
- Normalized and filtered data to include players nominated between 2010–2022.

### 2. Exploratory Data Analysis
- Analyzed distributions and correlations for key variables.
- Visualized feature importance and trends over time.

### 3. Modeling
- Trained the following models:
  - Logistic Regression
  - Random Forest Classifier
  - Gradient Boosting (XGBoost)
- Evaluated models using accuracy, precision, recall, F1-score, and AUC-ROC.

### 4. Feature Importance
- Identified most predictive variables: goals scored, trophies won, international tournament wins, and club success.
- Used SHAP and permutation importance for interpretation.

## Results

- **Best model:** Gradient Boosting achieved ~92% accuracy on the test set.
- Features with highest impact: team trophies, international accolades, and goal contribution metrics.
- Models struggled when players had similar stats but differed in intangible qualities (e.g., narrative or sentiment).

## Limitations

- Subjective factors (media bias, sentiment, legacy) not fully captured.
- Smaller sample size due to limited number of annual awards.
- Some stats unavailable for earlier years.

## Future Work

- Integrate NLP analysis from media coverage to include sentiment features.
- Expand dataset to include nominees beyond the top 30.
- Explore deep learning techniques for ranking rather than binary classification.


