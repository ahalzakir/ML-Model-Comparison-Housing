# Advanced House Price Prediction: Feature Engineering & Model Optimization

## Project Overview
In this second phase of the California Housing project, the focus shifted from basic training to professional model optimization. [cite_start]The goal was to implement an industry-aligned Machine Learning pipeline that includes data preprocessing and a rigorous comparison of multiple regression algorithms[cite: 13, 28].

## Key Objectives
* [cite_start]**Data Preparation:** Correctly preparing data for Machine Learning by separating features and target variables[cite: 14, 74].
* [cite_start]**Feature Scaling:** Implementing `StandardScaler` to ensure all features exist on a common scale, preventing model instability[cite: 15, 80, 88].
* [cite_start]**Model Benchmarking:** Training and comparing multiple algorithms to identify the most effective solution[cite: 16, 17, 32].

## Technical Methodology
1. [cite_start]**Feature Scaling:** Applied scaling to normalize features like Population and Median Income, ensuring fair learning across the model[cite: 31, 37, 81].
2. [cite_start]**Algorithm Comparison:** Evaluated three specific models[cite: 96, 97]:
   * [cite_start]**Linear Regression:** Established as the baseline performance metric[cite: 105].
   * [cite_start]**Ridge Regression:** Utilized to help reduce potential overfitting[cite: 101, 106].
   * [cite_start]**Decision Tree Regressor:** Implemented to capture non-linear relationships within the dataset[cite: 102, 107].

## Performance Results
| Model | RMSE | R² Score |
| :--- | :--- | :--- |
| Linear Regression | 0.745581 | 0.575788 |
| Ridge Regression | 0.745554 | 0.575819 |
| **Decision Tree (Selected)** | **0.724234** | **0.599732** |

[cite_start]*Note: The Decision Tree was selected as the final model due to its superior explanatory power[cite: 125, 126].*

## Deliverables
* [cite_start]**`AI_ML_Task2_Model_Comparison.ipynb`**: Jupyter Notebook containing the full optimization workflow.
* [cite_start]**`House_Price_Prediction_Task2_Report.pdf`**: Professional methodology and results summary[cite: 150].
* [cite_start]**`best_house_price_model.pkl`**: The optimized model serialized using `joblib`[cite: 152].
* **`requirements.txt`**: List of dependencies for project reproducibility.

## Skills Demonstrated
* [cite_start]Data Preprocessing & Feature Scaling[cite: 6, 142].
* [cite_start]Multi-model Benchmarking & Evaluation[cite: 6, 143].
* Model Serialization & Deployment Readiness[cite: 152].