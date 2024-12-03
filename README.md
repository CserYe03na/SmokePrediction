# Smoke Prediction
- `README.md`: The markdown file containing instructions and a project overview.
- `train.csv`: traning dataset with the binary target smoking and bio-signals that had been proposed to identify smokers who had a better chance of quitting
- `test.csv`: test dataset to predict the probability of positive smoking
- `Cali Fire and AQI.ipynb`: the working jupyter notebook file with data loading, EDA, data preprocessing, and prediction analysis. Please see this file for the project details!!
## Project Overview
It is a kaggle competition: https://www.kaggle.com/competitions/short-term-paper-4/overview
Our task is to use binary classification to predict a patient's smoking status given information about various other health indicators.
## Project Insights
At the very beginning, we believed that modeling was the most important part of the machine learning process. We tried multiple models and adjusted the parameters a lot. However, it did not respond with a significant change in performance and accuracy. Then, we started to figure out the context and background of smoking and the relationships between each pair of features. We introduced different feature engineering techniques, such as inserting new columns or combining relevant features. Now, we could say that both modeling and feature engineering are very critical.
