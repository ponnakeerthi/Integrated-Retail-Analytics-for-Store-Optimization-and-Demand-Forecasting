# Integrated-Retail-Analytics-for-Store-Optimization-and-Demand-Forecasting
Retail sales analysis, exploratory data visualization, store segmentation, anomaly investigation, and demand forecasting using Python and machine learning.
Integrated Retail Analytics for Store Optimization and Demand Forecasting

Project Overview

This individual data analytics project explores historical retail sales data to identify sales trends, understand store and department performance, investigate unusual sales patterns, and develop weekly sales forecasting models.

The project combines sales records with store characteristics, promotional markdowns, holiday information, and external economic and environmental variables to generate insights that can support retail planning and operational decisions.

Business Objectives

Analyze weekly sales trends and seasonal patterns.

Compare performance across stores, departments, and store types.

Investigate holiday effects and promotional markdown patterns.

Examine relationships between sales and external factors.

Identify unusual sales observations for further investigation.

Segment stores based on performance characteristics.

Build and evaluate machine learning models for weekly sales forecasting.

Translate analytical findings into practical business recommendations.

Datasets

The project uses three related datasets:

Sales: Weekly sales records by store and department.

Features: Temperature, fuel price, markdown variables, CPI, unemployment, and holiday information.

Stores: Store identifiers, store types, and store sizes.

The datasets are integrated using appropriate store and date keys.

Tools and Technologies

Python

Pandas and NumPy

Matplotlib and Seaborn

Scikit-learn

Jupyter Notebook / Google Colab

GitHub

Project Workflow

Data loading and initial inspection

Data quality assessment and missing-value analysis

Data cleaning and preprocessing

Feature engineering and dataset integration

Exploratory Data Analysis (EDA)

Statistical hypothesis testing

Sales anomaly investigation

Store segmentation

Department-level sales co-movement analysis

Regression modelling and weekly sales forecasting

Hyperparameter tuning and model evaluation

Business recommendations and conclusions

Exploratory Data Analysis

The notebook contains 15 visualizations covering sales distributions and trends, store and department performance, holiday and monthly patterns, store characteristics, markdown activity, and relationships between sales and external variables.

Each visualization is accompanied by an explanation of the chart choice, key observations, and potential business implications.

Machine Learning

Three regression approaches are evaluated:

Ridge Regression

Random Forest Regression

HistGradientBoosting Regression

Model performance is assessed using Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R-squared (R²). Chronological splitting and time-aware validation are used to better reflect forecasting on later periods. Hyperparameter tuning is used to compare baseline and tuned performance.

Business Applications

The findings can help inform:

Inventory and replenishment planning

Holiday staffing and demand preparation

Store-specific operational strategies

Review of unusual sales observations

Promotional performance investigation

Weekly demand monitoring

These recommendations require further validation with current operational data before implementation.

Important Limitations

The datasets cover a historical period and do not include customer identifiers, transaction-level purchase baskets, product-level purchase records, or real-time inventory information. Therefore, the project does not claim genuine customer-level segmentation or transaction-based market basket analysis.

Sales relationships and model feature importance indicate patterns in the available data, not necessarily causal effects. Forecasting performance should be validated on additional future periods before operational deployment.

Project Notebook

https://colab.research.google.com/drive/16Fj8JPPxWUkud6uhAloqdekepM6myqi7

Author

Ponna Keerthi

Individual Data Analytics Project
