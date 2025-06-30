# Synthetic Heart Disease Prediction (ML + Healthcare)

This project generates a synthetic heart disease dataset inspired by real-world clinical features, trains a logistic regression model, and evaluates its performance using scikit-learn.

## Features

- Biologically inspired synthetic data generation (20,000 samples)
- Features include age, cholesterol, max heart rate (thalach), thalassemia type, and others
- Generates binary target labels based on a simple risk score with noise
- Trains and evaluates a logistic regression model
- Metrics reported: Accuracy, Precision, Recall, ROC AUC
- Code modularized and ready for further improvement

## Current Results

- Accuracy: ~59%
- ROC AUC: ~0.62

## Future Improvements

- Use advanced models like Random Forest or XGBoost
- Add feature engineering and interaction terms
- Balance synthetic dataset if needed
- Add model explainability tools (SHAP, LIME)
- Tune hyperparameters for better accuracy

## Files

- `heart_disease_synthetic.py` — main Python code for data generation and modeling

## Author

Krrish — passionate about applying machine learning to healthcare challenges.

## Contributions

Feel free to open issues or submit pull requests for improvements!
