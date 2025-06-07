# Retail Sales Forecasting Project

## 📋 Problem Statement
A retail company wants to optimize inventory management by accurately forecasting sales for its products. Inconsistent sales predictions lead to overstock or stockouts, negatively impacting overall revenue and customer satisfaction.
----

## 🎯 Objectives
1. Develop a machine learning model to forecast product sales.
2. Minimize stockouts and overstock situations by improving forecast accuracy.
3. Provide insights into seasonality, trends, and external factors influencing sales.
----

## 🔑 Key Tasks
- Analyze historical sales data for different products.
- Preprocess data, handling missing values and outliers.
- Engineer features such as seasonality and trends.
- Build a time-series forecasting model using Prophet and XGBoost.
- Evaluate and fine-tune the model for accuracy.
----

## 📈 Goals
- Achieve a forecasting accuracy of at least 90%.
- Reduce stockouts by 15% and overstock situations by 10%.
- Provide actionable insights for inventory optimization.
----

## ⚙️ Scope
- Data analysis and preprocessing.
- Feature engineering and model development.
- Model evaluation and optimization.
- Insights generation and recommendations.
----

- ## 📊 Power BI Dashboard Preview

Here’s a preview of the Power BI dashboard created to visualize the forecasted sales against actual sales. This dashboard helps in understanding sales trends, seasonal patterns, and forecasting accuracy.

![Power BI Dashboard](powerbi_dashboard.png)

----

## 🛠️ Tools and Libraries Used
- Python (pandas, numpy, matplotlib, seaborn, Prophet, XGBoost, scikit-learn)
- Power BI for data visualization and dashboard creation

----
## 📂 Dataset
- Kaggle Store Item Demand Forecasting Challenge  
  [Link to dataset](https://www.kaggle.com/competitions/store-item-demand-forecasting)

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/Ani511/Retail-Sales-Forecasting.git
2. Install required Python packages:
    pip install pandas numpy matplotlib seaborn prophet xgboost scikit-learn
    Run the Jupyter notebook Retail_Sales_Forecasting.ipynb to preprocess data, build models, and generate forecast outputs.
3. Load the generated forecast_output.csv into Power BI for visualization and analysis.

## 📊 Power BI Dashboard Preview
Here’s a snippet of the Power BI dashboard built using the forecasted and actual sales data:
📂 Repository Contents
train.csv - Original sales data
Retail_Sales_Forecasting.ipynb - Complete notebook for data processing and modeling
forecast_output.csv - Model predictions for Power BI visualization
powerbi_dashboard.png - Screenshot of Power BI dashboard
README.md - Project documentation

## 🔍 Insights and Recommendations
- Seasonality and trend components play a key role in sales fluctuations.
- XGBoost model shows strong predictive performance with RMSE and R² within desired goals.
- Insights from the forecast help reduce inventory costs by balancing stock levels.
