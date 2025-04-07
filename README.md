# Code_Alpha_Sales-Prediction-using-Python

## Description

This project demonstrates the use of **machine learning** techniques to predict **sales** based on advertising expenditure across multiple media channels. Using a **Linear Regression** model in Python, the goal is to analyze how different types of advertising spending (TV, Radio, Newspaper) influence sales performance and to build a predictive model that estimates future sales based on these inputs.

The project helps businesses and marketers make informed decisions by utilizing data preprocessing, visualization, and predictive modeling techniques to forecast sales, optimize marketing spend, and improve advertising strategies.

## About the Dataset

The dataset used for this project is **Advertising.csv**, which contains data on advertising expenditures in three different media channels (TV, Radio, and Newspaper) along with the corresponding sales figures. Here's a detailed breakdown of the dataset:

### Columns:
- **TV**: Amount spent on TV advertising (in thousands of dollars).
- **Radio**: Amount spent on Radio advertising (in thousands of dollars).
- **Newspaper**: Amount spent on Newspaper advertising (in thousands of dollars).
- **Sales**: Sales figures (in thousands of units) resulting from the advertising spend.

### Overview:
- **Data Size**: The dataset contains **200 rows** and **5 columns**.
- **Usability**: The dataset is clean and well-structured, making it ideal for performing linear regression analysis and predicting sales based on advertising spend.
- **Tags**: Business, Marketing, Linear Regression, Predictive Modeling, Data Science.

## Related Analysis

### Predictive Modeling:
The core of this project is building a **Linear Regression** model that predicts sales based on the advertising spend across TV, Radio, and Newspaper. The dataset provides insights into how the amount spent on each platform influences overall sales figures.

### Data Visualization:
- **Pairplot**: A pairwise comparison of all variables to visually explore relationships between features and sales.
- **Correlation Heatmap**: A heatmap to analyze the correlation between different variables, helping identify which advertising channels have the most significant impact on sales.

### Feature Importance:
By analyzing the model, we can evaluate the importance of each advertising channel (TV, Radio, Newspaper) in predicting sales and understand how changes in spending affect the target variable.

### Model Evaluation:
The model's accuracy is assessed using the following metrics:
- **Mean Absolute Error (MAE)**: Measures the average error between predicted and actual sales.
- **Mean Squared Error (MSE)**: Measures the average squared difference between predicted and actual sales, giving more weight to larger errors.
- **R-squared (R²)**: Indicates the proportion of variance in the sales data explained by the model. A higher R² value indicates a better model fit.

### Visualization of Predictions:
- Scatter plots are created to compare the **actual** vs **predicted** sales for each advertising platform (TV, Radio, Newspaper). Regression lines are also plotted to visualize how the model predicts sales based on different advertising spends.

## Summary

This project provides a practical demonstration of **Linear Regression** applied to a real-world business problem: predicting sales based on advertising expenditure. By analyzing and predicting the impact of different advertising channels on sales, businesses can better allocate their marketing budgets and optimize advertising strategies for greater revenue.

The **Advertising.csv** dataset is a classic example used to teach regression analysis and predictive modeling in data science. It is an excellent resource for anyone learning about machine learning, business analytics, and the relationship between marketing spend and sales performance.
