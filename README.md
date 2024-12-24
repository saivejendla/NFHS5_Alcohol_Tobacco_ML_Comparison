# NFHS5_Alcohol_Tobacco_ML_Comparison
Analysis of alcohol and tobacco consumption among Indian adults using the NFHS-5 dataset, employing multiple machine learning models and neural networks for comparative evaluation.

Alcohol and Tobacco Consumption Analysis in India Using NFHS-5 Dataset

This repository contains a detailed analysis of alcohol and tobacco consumption among Indian adults aged 15 years and above, based on the NFHS-5 (2019-2021) dataset. The project extends previous work by incorporating multiple machine learning models and deep learning techniques to compare performance metrics and provide actionable insights.

Project Overview--

Objectives:

1. Analyze alcohol and tobacco consumption patterns across genders and regions in India.

2. Preprocess the dataset to handle missing values, outliers, and inconsistencies.

3. Compare the performance of various machine learning models on predicting alcohol and tobacco consumption.

4. Use neural networks to achieve optimal performance metrics, such as Mean Absolute Error (MAE) and R-squared values.

5. Visualize the results for better interpretation and insights.

Features
Dataset: NFHS-5 dataset focusing on alcohol and tobacco consumption percentages in men and women.

Target Variable: Combined alcohol consumption percentage for men and women, calculated as:

df['alcohol_consumption_percentage'] = (df['Men age 15 years and above who consume alcohol (%)'] + df['Women age 15 years and above who consume alcohol (%)']) / 2

Algorithms:

1. Linear Regression

2. K-Nearest Neighbors (KNN)

3. Random Forest

4. Decision Tree

5. Gradient Boosting

6. Neural Networks

7. Metrics: Mean Squared Error (MSE), R-squared, and Mean Absolute Error (MAE).

Key Steps--

Data Preprocessing:

1. Handled missing data and removed outliers.

2. Feature selection based on domain relevance.

3. Normalized data where necessary.

Machine Learning Models:

1. Applied multiple ML algorithms to predict alcohol consumption.

2. Compared MSE and R-squared values for each algorithm.

3. Visualized performance metrics side by side for better insights.

Neural Networks:

1. Built a deep learning model to optimize prediction accuracy.

2. Evaluated using MAE and R-squared values to determine the best-fit model.

Extended Analysis:

Performed a similar analysis for tobacco consumption among men and women.

Visualization:

1. Side-by-side comparisons of MSE and R-squared values across models.

2. Graphical representation of alcohol and tobacco consumption trends across states.

Results:

1. Best ML Model: Linear regression achieved the lowest MSE and the highest R-squared value for predicting alcohol consumption.

2. Deep Learning Insights: Neural networks provided better accuracy compared to traditional ML algorithms, particularly for tobacco consumption.

How to Use
Clone the repository:

1. git clone https://github.com/your-username/your-repo-name.git

2. Open the Jupyter Notebook (HealthCare_Advanced_Analysis.ipynb) for step-by-step execution.

3.Install required libraries:
pip install -r requirements.txt

4.Run the notebook to explore data preprocessing, model implementation, and visualization.

Requirements:
1. Python 3.8+

2. Jupyter Notebook

3. Libraries: pandas, numpy, matplotlib, seaborn, sklearn, tensorflow

Insights and Applications:
1. Helps policymakers and health organizations understand consumption trends.

2. Aids in targeted interventions for reducing alcohol and tobacco use.

Future Work:
1. Extend the analysis to other datasets for generalization.

2. Explore advanced deep learning models such as LSTM for time-series trends.
