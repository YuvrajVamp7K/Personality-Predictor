# Personality-Predictor

A simple machine learning project to classify personality types (Introvert vs Extrovert) using behavioral and social features. Built with Python, Pandas, and scikit-learn.

## Features
- Cleans and preprocesses raw CSV data:
  - Maps categorical values to numeric
  - Handles missing data with interpolation and mean filling
  - Drops unnecessary columns (like IDs)
- Splits dataset into training and testing sets
- Trains two models:
  - **Random Forest Classifier** (main model)
  - **Gaussian Naive Bayes** (baseline)
- Evaluates accuracy on test set
- Makes predictions on unseen test data and saves results to `submission.csv`

## Project Structure
- **train.csv** – Training data  
- **test.csv** – Test data for final predictions  
- **submission.csv** – Output predictions file  
- **main script** – Data cleaning, model training, and prediction steps  

## How to Run
1. Clone the repo:  
   ```bash
   git clone https://github.com/YOUR-USERNAME/Personality-Predictor.git
   cd Personality-Predictor

## install dependencies
pip install pandas numpy scikit-learn
