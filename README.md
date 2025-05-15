# Heart Disease Classification Project

This project demonstrates how to build a machine learning model to predict the presence of heart disease using a real-world dataset. It covers the full pipeline from data preprocessing to model training, dimensionality reduction with PCA, and visualization of results.

## Project Overview

- Load and clean the heart disease dataset
- Handle categorical data with label encoding and one-hot encoding
- Apply feature scaling
- Train classification model(Logistic Regression)
- Use Principal Component Analysis (PCA) for dimensionality reduction
- Visualize the classification results before and after PCA
- Compare model performance with and without PCA

## How to Use

1. Open the Jupyter notebook (`Heart_Disease_Classification.ipynb`) in Google Colab or Jupyter locally.
2. Run the cells step-by-step to see data preprocessing, model training, and visualization.
3. Modify or extend the notebook for further experiments or different models.

## Findings and Insights

- PCA helps reduce the number of features, simplifying the model while keeping most of the variance.
- Classification results with PCA showed clearer separation between classes in the 2D plot.
- There may be a slight trade-off in accuracy when using PCA, but the computation is more efficient.

## Requirements

- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

---

Feel free to explore, modify, and improve this project.  
If you have questions or suggestions, please reach out!

---

**Author:** Nidal Boumeija 
**Date:** 2025-05-15
To build a machine learning pipeline that predicts the presence of heart disease and assess the impact of PCA (Principal Component Analysis) on model performance.
