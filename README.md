# Happiness Index Prediction: A Regression Analysis Approach

## Overview
This project aims to analyze, visualize, and model happiness data using regression techniques. The primary goal is to predict the **Life Ladder (Happiness Score)** of a country based on multiple socio-economic and psychological factors, such as GDP, social support, life expectancy, and perceptions of corruption. 

The dataset used for this analysis contains happiness-related data for multiple countries across various years, providing insights into the factors contributing to happiness.

## Source Dataset

## Dataset Description
The dataset includes the following attributes:

- **Country name**: Name of the country.
- **Year**: Year when the data was collected (not used for prediction).
- **Life Ladder**: The target variable representing the happiness score.
- **Log GDP per capita**: Logarithmic scale of market values of goods and services in a country.
- **Social support**: Measures the level of support people feel from those around them.
- **Healthy life expectancy**: Rank of a country based on life expectancy.
- **Freedom to make life choices**: Indicates how freedom contributes to happiness.
- **Generosity**: Whether people have donated money (an indicator of generosity).
- **Perceptions of corruption**: People's perception of corruption in their society.
- **Positive affect**: Level of positive emotions such as happiness, laughter, and enjoyment.
- **Negative affect**: Level of negative emotions such as worry, anger, or sadness.

The task is to predict the **Life Ladder** based on all other attributes except for the year.

## Key Objectives
1. Explore and summarize the dataset.
2. Perform data visualization and assess the statistical properties of attributes.
3. Analyze relationships between attributes using Pearson Correlation Coefficient (PCC) and scatter plots.
4. Split the data into training and testing sets, ensuring representativeness.
5. Train and evaluate models using:
   - Linear Regression (closed-form solution and Stochastic Gradient Descent).
   - Polynomial Regression.
   - Regularization techniques (Ridge, Lasso, Elastic Net).
6. Fine-tune hyperparameters like penalty terms, batch size, and learning rate.
7. Evaluate model performance on test data using appropriate metrics.
8. Discuss insights and explore potential improvements.

## Steps to Run the Notebook
1. Download the Notebook and Source Data csv file.
2. Import the data from csv file in the notebook.
3. Execute the notebook.
