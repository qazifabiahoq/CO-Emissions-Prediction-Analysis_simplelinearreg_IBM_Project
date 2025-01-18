# CO₂ Emissions Prediction Analysis

## Project Overview:
This project is part of the **IBM Data Science Professional Certificate** on Coursera. The goal was to explore the relationship between various car attributes and **CO₂ emissions**, using two primary features: **Engine Size** and **Fuel Consumption**. The objective was to build linear regression models to predict **CO₂ emissions** and evaluate which feature had a stronger predictive power.

## Objective:
The primary goal of this analysis was to determine which car feature, between **Engine Size** and **Fuel Consumption**, better predicts **CO₂ emissions**. By comparing the prediction accuracy of both models, we sought to uncover which attribute most directly affects **CO₂ emissions** in vehicles.

## Methodology:
Two linear regression models were built using the following car attributes as features:

- **Engine Size**: The size of the engine (measured in liters).
- **Fuel Consumption**: The combined fuel consumption (measured in liters per 100 kilometers).

Before building the models, I first explored the relationship between each feature and **CO₂ emissions** using scatter plots. The scatter plots for **Engine Size**, **Fuel Consumption**, and **Cylinders** all showed a **positive linear relationship** with **CO₂ emissions**, indicating a potential for a strong predictive model.

- **Engine Size vs. CO₂ Emissions**: Positive linear relationship.
- **Cylinders vs. CO₂ Emissions**: Positive linear relationship.
- **Fuel Consumption vs. CO₂ Emissions**: Positive linear relationship.

Both models were evaluated using several metrics, including **Mean Absolute Error (MAE)** and **R² Score**, which provided insight into the accuracy and reliability of the predictions.

### Evaluation Metrics:
- **Mean Absolute Error (MAE)**: This metric measures the average absolute difference between predicted and actual values. A lower MAE indicates more accurate predictions.
- **Residual Sum of Squares (MSE)**: This metric calculates the squared differences between predicted and actual values. A lower MSE indicates a better fit of the model.
- **R² Score**: This score represents how well the model's predictions match the actual values. An R² score closer to 1 indicates a better fit.

## Findings:

### Model 1: **Engine Size**:
The model trained using **Engine Size** to predict **CO₂ emissions** had the following evaluation results:
- **Mean Absolute Error (MAE)**: 23.00
- **Residual Sum of Squares (MSE)**: 893.09
- **R² Score**: 0.76

These results indicate that while **Engine Size** has a positive relationship with **CO₂ emissions**, the model's accuracy was not perfect. The **R² score** of 0.76 suggests that 76% of the variation in **CO₂ emissions** could be explained by **Engine Size**.

### Model 2: **Fuel Consumption**:
The model trained using **Fuel Consumption** to predict **CO₂ emissions** showed improved performance:
- **Mean Absolute Error (MAE)**: 20.36

This model demonstrated a **lower MAE**, indicating that **Fuel Consumption** was a more accurate predictor for **CO₂ emissions** than **Engine Size**. Although the **R² score** was not explicitly calculated in the code, the lower **MAE** suggests that **Fuel Consumption** offers a stronger predictive relationship.

## Conclusion:
- The analysis revealed that **Fuel Consumption** is a more reliable predictor for **CO₂ emissions** compared to **Engine Size**. The model trained on **Fuel Consumption** produced more accurate predictions, as indicated by a lower **Mean Absolute Error (MAE)**.
- **Engine Size**, while still a significant factor, did not provide as precise predictions for **CO₂ emissions** as **Fuel Consumption** did. The **R² score** for **Engine Size** (0.76) was relatively good but still lower than the potential of **Fuel Consumption**.

## Data Source:
- **[CO₂ Emissions Dataset](https://open.canada.ca/data/en/dataset/98f1a129-f628-4ce4-b24d-6f16bf24dd64)**

## Acknowledgements:
- **Author**: Saeed Aghabozorgi
- **Other Contributors**:
  
  - Joseph Santarcangelo
  - Azim Hirjani

## Completed by:
**Qazi Fabia Hoq**  
(as part of the Data Science Professional Certificate by IBM on Coursera)
