# Fake Reviews Detection

This repository contains code and data for detecting fake reviews in the home appliances domain. The project involves preprocessing raw review data, applying count vectorization, performing TF-IDF transformation, and using three machine learning pipelines (Random Forest, Support Vector Machine, and Logistic Regression) for classification.

## Project Structure

- **Fake Reviews Detection.ipynb**: Main Jupyter notebook for the fake review detection workflow.
- **home appliances reviews.csv**: Raw dataset of home appliances reviews used for analysis.
- **Preparation of Preprocessed Data.ipynb**: Notebook for preprocessing data before model training.
- **Preprocessed Home Appliances Reviews Dataset.csv**: Preprocessed dataset generated from raw data, ready for model input.

## Project Workflow

1. **Data Preprocessing**: Preprocess the raw reviews dataset to make it suitable for analysis.
2. **Count Vectorization and TF-IDF Transformation**: Transform the text data using count vectorization and TF-IDF.
3. **Machine Learning Pipelines**: Apply three different machine learning pipelines:
   - **Random Forest**
   - **Support Vector Machine (SVM)**
   - **Logistic Regression**
   
Each pipeline provides a different approach to classify reviews as genuine or fake, aiming for optimal model performance.

## Usage

For viewing `.ipynb` files properly on GitHub, use [nbviewer](https://nbviewer.org/), as it provides a more reliable rendering of Jupyter notebooks.

## Requirements

- Python 3.x
- Jupyter Notebook
- Libraries:
  - `numpy`
  - `pandas`
  - `seaborn`
  - `matplotlib`
  - `nltk`
  - `scikit-learn`
