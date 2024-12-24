# NFHS5_Alcohol_Tobacco_ML_Comparison
Analysis of alcohol and tobacco consumption among Indian adults using the NFHS-5 dataset, employing multiple machine learning models and neural networks for comparative evaluation.

Here's how you can structure your GitHub README for the second file, describing your project comprehensively:

Alcohol and Tobacco Consumption Analysis in India Using NFHS-5 Dataset
This repository contains a detailed analysis of alcohol and tobacco consumption among Indian adults aged 15 years and above, based on the NFHS-5 (2019-2021) dataset. The project extends previous work by incorporating multiple machine learning models and deep learning techniques to compare performance metrics and provide actionable insights.

Project Overview
Objectives
Analyze alcohol and tobacco consumption patterns across genders and regions in India.
Preprocess the dataset to handle missing values, outliers, and inconsistencies.
Compare the performance of various machine learning models on predicting alcohol and tobacco consumption.
Use neural networks to achieve optimal performance metrics, such as Mean Absolute Error (MAE) and R-squared values.
Visualize the results for better interpretation and insights.
Features
Dataset: NFHS-5 dataset focusing on alcohol and tobacco consumption percentages in men and women.
Target Variable: Combined alcohol consumption percentage for men and women, calculated as:
python
Copy code
df['alcohol_consumption_percentage'] = (df['Men age 15 years and above who consume alcohol (%)'] + df['Women age 15 years and above who consume alcohol (%)']) / 2
Algorithms:
Linear Regression
K-Nearest Neighbors (KNN)
Random Forest
Decision Tree
Gradient Boosting
Neural Networks
Metrics: Mean Squared Error (MSE), R-squared, and Mean Absolute Error (MAE).
Key Steps
Data Preprocessing:

Handled missing data and removed outliers.
Feature selection based on domain relevance.
Normalized data where necessary.
Machine Learning Models:

Applied multiple ML algorithms to predict alcohol consumption.
Compared MSE and R-squared values for each algorithm.
Visualized performance metrics side by side for better insights.
Neural Networks:

Built a deep learning model to optimize prediction accuracy.
Evaluated using MAE and R-squared values to determine the best-fit model.
Extended Analysis:

Performed a similar analysis for tobacco consumption among men and women.
Visualization:

Side-by-side comparisons of MSE and R-squared values across models.
Graphical representation of alcohol and tobacco consumption trends across states.
Results

Best ML Model: [Specify the model] achieved the lowest MSE and the highest R-squared value for predicting alcohol consumption.
Deep Learning Insights: Neural networks provided better accuracy compared to traditional ML algorithms, particularly for tobacco consumption.
How to Use
Clone the repository:
bash
Copy code
git clone https://github.com/your-username/your-repo-name.git
Open the Jupyter Notebook (HealthCare_Advanced_Analysis.ipynb) for step-by-step execution.
Install required libraries:
bash
Copy code
pip install -r requirements.txt
Run the notebook to explore data preprocessing, model implementation, and visualization.
Requirements
Python 3.8+
Jupyter Notebook
Libraries: pandas, numpy, matplotlib, seaborn, sklearn, tensorflow
Insights and Applications
Helps policymakers and health organizations understand consumption trends.
Aids in targeted interventions for reducing alcohol and tobacco use.
Future Work
Extend the analysis to other datasets for generalization.
Explore advanced deep learning models such as LSTM for time-series trends.
