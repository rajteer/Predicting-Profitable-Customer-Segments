# Predicting profitable customer groups

The goal of this project was to predict which customer groups are profitable for a company. The data was downloaded from [Kaggle](https://www.kaggle.com/datasets/tsiaras/predicting-profitable-customer-segments) and contains informations retrieved before and after a marketing campaign. Given dataset provide informations about two groups of customers and whether they are profitable or not and if they are profitable, which of them is more. 

The project consisted of two parts. In the first part, I used the data recorded before the marketing campaign to predict the data recorded after the campaign was run. In the second part, I used the data recorded before and after the campaign to predict which customer groups are the most profitable for the company.

To do so I followed the following steps:

1. Data cleaning and preprocessing
2. Exploratory data analysis
3. Feature engineering
4. Model selection
5. Model evaluation

## Used libraries
This project uses the following libraries:
- `pandas` - for data manipulation, analysis and visualization the models performance,
- `numpy` - for data manipulation,
- `matplotlib` and `seaborn` - for data visualization,
- `sklearn` - for machine learning related tasks (model selection, evaluation, preprocessing, etc.),
- `xgboost` - for regression and classification models,
- `tensorflow` and `keras` - for deep learning approach.