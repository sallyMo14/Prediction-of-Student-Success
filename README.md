# Prediction-of-Student-Success


# Student Performance Analysis & Prediction

This project explores and models a student dataset to better understand factors affecting academic performance and to build predictive models.

## Notebook Outline

### Imports & Setup
- Load required Python libraries.
- Define custom helper functions.

### Part One: Exploratory Data Analysis (EDA)
- **Data Cleaning:** Check for null values and duplicates.
- **Feature Exploration:** Analyze distributions for:
  - Gender
  - Highest education
  - IMD band
  - Age band
  - Number of previous attempts
  - Studied credits
  - Disability
  - Passed course
- **Clustering:** Group students into clusters (2, 3, 4, and 5 clusters) to find hidden patterns.

### Part Two: Modeling
- **Data Preparation:**
  - Scale features.
  - Check target balance.
  - Feature selection (correlation, variance, constant/quasi-constant removal).
  - Dimensionality reduction with PCA.
- **Modeling with Keras:**
  - Baseline model.
  - Model with dropout.
  - Hyperparameter tuning.
- **Evaluation:**
  - Assess performance on test data.

## Tools & Libraries
- Python (Google Colab)
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (scaling, PCA, clustering, feature selection)
- Keras (deep learning models)

## Results
* The model does a great job at finding students who will pass their courses.

* However, it performs poorly in identifying students who are at risk of failing—it misses about 70% of the students who actually fail.

 This means the model is more reliable for confirming success than for predicting who needs extra support.
