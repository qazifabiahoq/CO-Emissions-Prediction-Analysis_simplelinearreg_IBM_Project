# CO₂ Emissions Prediction Analysis

## Project Overview

This project explores how different car attributes relate to CO₂ emissions. Specifically, it focuses on understanding which feature — Engine Size or Fuel Consumption — better predicts vehicle CO₂ emissions. Linear regression models were developed and compared to identify the stronger predictor.

## Who Will Benefit and Why

* **Environmental researchers** can use these insights to better understand vehicle emissions drivers.
* **Automotive manufacturers** can prioritize factors that reduce emissions during vehicle design.
* **Policy makers and regulators** gain data-driven evidence to shape environmental standards.
* **Consumers** may better appreciate how car features influence emissions, aiding eco-friendly choices.

This project helps identify which vehicle characteristic more directly impacts emissions, enabling more targeted actions to reduce carbon footprints.

## Objective

Determine which feature, Engine Size or Fuel Consumption, provides more accurate predictions of CO₂ emissions using regression models and evaluation metrics.

## How It Was Done

* Explored relationships between CO₂ emissions and features (Engine Size, Fuel Consumption, Cylinders) via scatter plots, confirming positive linear trends.
* Built two separate linear regression models: one with Engine Size and one with Fuel Consumption as the predictor.
* Evaluated model accuracy using Mean Absolute Error (MAE), Residual Sum of Squares (MSE), and R² Score.
* Compared models to identify which feature predicts CO₂ emissions more effectively.

## Key Findings

1. **Does Engine Size predict CO₂ emissions well?**
   Yes, with a positive relationship. The model explained 76% of the variation in emissions (R² = 0.76), but had a higher average prediction error (MAE = 23.00).

2. **Is Fuel Consumption a better predictor?**
   Yes. The model using Fuel Consumption showed a lower MAE (20.36), indicating more accurate predictions. Although the R² score wasn’t explicitly calculated, the lower error suggests stronger predictive power.

3. **What does this mean for understanding emissions?**
   Fuel Consumption better reflects real-world driving factors affecting emissions compared to just engine size, which is a more static measurement.

## Conclusion

Fuel Consumption is a more reliable and accurate predictor of CO₂ emissions than Engine Size. While both features are positively correlated with emissions, Fuel Consumption provides stronger predictive accuracy, making it a better metric for estimating vehicle emissions.

## Recommendations

Focus on fuel efficiency improvements as a key strategy to reduce CO₂ emissions. Future analyses could explore combining features or incorporating additional variables to enhance predictive accuracy further.

## Data Source

* [CO₂ Emissions Dataset from Canadian Government Open Data Portal](https://open.canada.ca/data/en/dataset/98f1a129-f628-4ce4-b24d-6f16bf24dd64)

## Acknowledgements

* Project developed by Saeed Aghabozorgi
* Contributions by Joseph Santarcangelo and Azim Hirjani

## Author

Qazi Fabia Hoq
(as part of the IBM Data Science Professional Certificate on Coursera)
