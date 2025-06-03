# Carbon Emissions Prediction for Climate Action (SDG 13)

## Project Overview

This project addresses **UN Sustainable Development Goal 13: Climate Action** by predicting carbon emissions based on energy consumption and industrial output data. Accurate forecasting of emissions supports policymakers in designing effective climate strategies to reduce global warming.

## Machine Learning Approach

We use **supervised learning** with a **linear regression model** to predict carbon emissions. The model was trained on sample data including energy consumption and industrial output metrics.

## Dataset

A simplified mock dataset with 10 records was used for demonstration:

| Energy_Consumption | Industrial_Output | Carbon_Emissions |
|--------------------|-------------------|------------------|
| 100                | 80                | 90               |
| 150                | 120               | 140              |
| ...                | ...               | ...              |

*(You can replace this with larger real-world datasets from World Bank or Kaggle.)*

## Results

- Mean Absolute Error (MAE): 4.38 metric tons
- R² Score: 0.98 (Excellent prediction accuracy)

The scatter plot comparing actual vs predicted emissions is included in the `screenshots/` folder.

## Ethical Considerations

- The model relies on historical data, which may be biased or incomplete for certain regions.
- Ongoing data updates and validation are crucial for fairness and accuracy.
- Predictive insights can guide fair and sustainable climate policies globally.

## How to Run

1. Install Python dependencies: `pandas`, `scikit-learn`, `matplotlib`.
2. Run `carbon_emissions_prediction.py`.
3. View output metrics and graph.
