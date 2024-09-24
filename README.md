# Heart Disease Exploratory Data Analysis (EDA)

This repository contains a Jupyter notebook that performs Exploratory Data Analysis (EDA) on a heart disease dataset. The dataset contains information about individuals' health, lifestyle factors, and their association with heart disease.

## Dataset
The dataset used in this analysis is `heart_2020_cleaned.csv`, which contains 319,795 rows and 18 columns of various health indicators. These include information on:
- Heart disease status
- Body Mass Index (BMI)
- Smoking habits
- Alcohol consumption
- Stroke history
- Physical and mental health
- Walking difficulties
- Gender, Age, and Race
- Diabetes, Asthma, Kidney Disease, Skin Cancer
- General health and sleep habits

## Key Steps in the Analysis
1. **Data Loading:** The data is imported using `pandas`.
2. **Data Exploration:**
   - `df.head()` is used to preview the data.
   - `df.info()` provides an overview of the data types and missing values.
   - `df.shape` provides information on the dataset size.
3. **Visualizations:** The notebook leverages `matplotlib` and `seaborn` for visualizing the relationships between different features and heart disease occurrence.
4. **Eigen Value and Eigen Vector:** Calculated Eigen value and Eigen Vector
5. **Chi-Square Test:** Performing Chi_square of target attribute(Heart Disease) with all other attribute to find out the usefullness of data for prediction 
