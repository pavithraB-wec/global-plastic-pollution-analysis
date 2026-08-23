# 🌍 Global Plastic Pollution Analysis

## 📌 Project Overview

This project analyzes global per-capita plastic waste and investigates
the relationship between plastic waste generation and GDP per capita.

The project uses Python and data science techniques including data
cleaning, exploratory data analysis, data visualization, correlation
analysis, and machine learning.
<img width="990" height="590" alt="country-comparison" src="https://github.com/user-attachments/assets/b09ed066-35ab-4826-bef4-5e39423eef7a" />
<img width="799" height="393" alt="Box Plot of Per-Capita Plastic Waste" src="https://github.com/user-attachments/assets/0bac4f80-042c-4e16-af5e-b559613c559c" />
<img width="989" height="590" alt="top10-plastic-waste" src="https://github.com/user-attachments/assets/28ecdada-6251-4cfa-82ce-1fcfa2ec78c9" />
<img width="841" height="547" alt="plastic-waste-distribution" src="https://github.com/user-attachments/assets/5a0807ce-9e70-43e5-9bc7-ec81db1530f9" />
<img width="989" height="590" alt="gdp-vs-plastic-waste" src="https://github.com/user-attachments/assets/147a62f4-d400-46fd-93c2-655a88318084" />
<img width="700" height="547" alt="actual-vs-predicted" src="https://github.com/user-attachments/assets/1c53e122-9b5f-494b-ba39-b2f4c0d3aa70" />

## 🎯 Objectives

- Analyze global plastic waste generation
- Identify countries with high and low plastic waste
- Compare plastic waste across countries
- Study the relationship between GDP per capita and plastic waste
- Build a Linear Regression model
- Evaluate the predictive performance of the model

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## 📊 Dataset

The dataset contains information about:

- Country/Entity
- Year
- Per-capita plastic waste
- GDP per capita
- Population
- Continent

The plastic-waste analysis focuses on 2010 observations.

## 🔍 Key Findings

- Average per-capita plastic waste: approximately 0.180 kg/person/day
- Median: approximately 0.144 kg/person/day
- Correlation between GDP per capita and plastic waste: 0.3466
- The relationship is weak-to-moderately positive
- Linear Regression R² score: 0.1448

## 🤖 Machine Learning

A Linear Regression model was developed using GDP per capita to predict
per-capita plastic waste.

### Model Performance

| Metric | Result |
|---|---:|
| MAE | 0.0813 |
| MSE | 0.01139 |
| RMSE | 0.1067 |
| R² | 0.1448 |

The relatively low R² score indicates that GDP per capita alone is not
sufficient to accurately predict plastic waste.

## 📈 Visualizations

The project includes:

- Top 10 countries by plastic waste
- Plastic waste distribution
- Country comparison
- GDP vs plastic waste
- Actual vs predicted plastic waste

## 🚀 Future Scope

- Use multi-year plastic pollution data
- Add recycling and waste-management indicators
- Include urbanization and consumption data
- Apply Random Forest and other ML algorithms
- Develop an interactive Streamlit dashboard
- Perform geographical analysis

## 👩‍💻 Author

B Pavithra
