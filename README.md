# Retail Customer Segmentation and Sales Forecasting

## Project Overview
This project analyzes retail transaction data to identify customer segments and forecast future weekly revenue. It combines RFM analysis, K-Means clustering, exploratory data analysis, and time-series forecasting to generate actionable business insights.

## Objectives
- Analyze retail sales and customer purchasing behavior.
- Segment customers using Recency, Frequency, and Monetary (RFM) analysis.
- Apply K-Means clustering to identify distinct customer groups.
- Analyze weekly revenue trends.
- Compare forecasting models and generate an eight-week revenue forecast.

## Tools and Technologies
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Statsmodels
- Jupyter Notebook

## Customer Segmentation
Four customer segments were identified:

| Segment | Description |
|---|---|
| Inactive / Low Spend | Customers with long periods since their last purchase and low spending |
| Recent / Occasional | Customers who purchased recently but buy less frequently |
| High-Value Loyal | Frequent customers who contribute substantial revenue |
| Cooling-Off | Previously active customers who may need re-engagement |

## Sales Forecasting
The project evaluates multiple forecasting approaches:
- Naive Forecast
- Seasonal Naive Forecast
- SARIMA
- Holt-Winters Exponential Smoothing

Models are compared using Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and Mean Absolute Percentage Error (MAPE), where applicable.

## Key Findings
- K-Means clustering identified four customer segments with different purchasing patterns.
- High-Value Loyal customers contributed the greatest total revenue among the identified segments.
- SARIMA performed better than the other tested forecasting models based on the reported MAE and RMSE.
- Weekly revenue forecasting provides a starting point for inventory and sales planning.

## Project Structure
- `Retail_Customer_Segmentation_Forecasting.ipynb` — analysis, customer segmentation, visualizations, and forecasting.

## How to Run
1. Clone or download this repository.
2. Install the required Python libraries.
3. Open the notebook in Jupyter Notebook or JupyterLab.
4. Place the dataset in the appropriate location and update the file path in the notebook if necessary.
5. Run the notebook cells in order.

## Notes
The dataset used for this project is not included in this repository. Forecasting performance may vary with different data, model configurations, and validation periods.
