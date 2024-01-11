# Walmart-Sales-Forecasting-Using-Machine-Learning
This project focuses on sales forecasting for Walmart, employing machine learning models to predict weekly sales accurately. Sales forecasting is crucial for effective resource planning, decision-making, and identifying market trends. The analysis utilizes the Walmart Store Sales dataset, covering 45 stores and 99 departments over a three-year.

## Overview
This project delves into the realm of sales forecasting, a critical aspect for businesses, using machine learning models to predict weekly sales accurately. By analyzing the Walmart Store Sales dataset spanning three years, we explore trends, conduct time series analysis, and evaluate the performance of various machine learning models.

## Key Features
1. **Comprehensive Data Analysis:** Addressed missing values, merged datasets, and performed exploratory data analysis to uncover monthly sales trends, top-performing stores, and departments.
2. **Data Normalization:** Ensured fair feature scaling, preventing dominance based on feature magnitudes.
3. **Machine Learning Models:**
   - *Linear Regression:* Achieved 90.92% accuracy, offering insights into the linear relationship between features and weekly sales.
   - *Random Forest Regression:* Impressive 96.85% accuracy, demonstrating the model's effectiveness in capturing complex relationships.
   - *K Neighbors Model:* Provided reasonable accuracy (86.55%) for predicting weekly sales.

## Models Used

### Linear Regression Model
Linear regression is a simple and commonly used model that assumes a linear relationship between the independent variables and the target variable. It works well when there is a linear relationship between the features and the target variable.

- **Accuracy:** Achieved an accuracy of 90.92% (R-squared score) on the test data.
- **Metrics:**
  - Mean Absolute Error: Approximately 0.00398
  - Root Mean Square Error: Approximately 0.00981
- **Visualization:** The graph displays the predicted sales (blue line) and the actual sales (red line) over the span of 365 days.

### Random Forest Regression Model
Random forest regression is an ensemble model that combines multiple decision trees to make predictions. It is effective for capturing non-linear relationships and handling complex datasets.

- **Accuracy:** Achieved a high accuracy of 96.85% (R-squared score) on the test data.
- **Metrics:**
  - Mean Absolute Error: Low
  - Root Mean Square Error: Low
- **Visualization:** The graph showcases the predicted sales (blue line) and the actual sales (red line) over the span of 365 days.

### K Neighbors Model
K Neighbors, or K-Nearest Neighbors (KNN), is a simple yet effective supervised learning algorithm that can be used for both classification and regression tasks. In the case of regression, it predicts the value of a target variable by finding the average or weighted average of the K nearest neighbors in the feature space.

- **Accuracy:** Achieved an accuracy of 86.55% (R-squared score) on the test data.
- **Metrics:**
  - Mean Absolute Error: Relatively low
  - Root Mean Square Error: Relatively low
- **Insight:** The R-squared score of 0.86546416 indicates that approximately 87% of the variance in the target variable can be explained by the model.

### Model Comparison
While the Linear Regression and K Neighbors models performed well, they had a lower accuracy compared to the Random Forest model. However, they still provide reasonable predictions and can be considered as alternative models for predicting the weekly sales of Walmart.

It's important to note that the choice of parameters, such as the number of neighbors (K) and the weighting scheme, can affect the performance of the K Neighbors model. Experimenting with different parameter values may lead to improved accuracy and better predictions.

Overall, the Random Forest Regression model demonstrates strong performance in predicting the weekly sales of Walmart, providing accurate and reliable predictions.

## Usage
1. Clone the repository: `git clone https://github.com/your-username/your-repo.git`
2. Navigate to the project directory: `cd your-repo`
3. Explore the Jupyter notebooks for in-depth analysis and model evaluations.

## Conclusion
This project concludes with valuable insights into Walmart's sales dynamics and the practical application of machine learning for accurate forecasting. The Random Forest model emerges as a strong performer, providing businesses with a robust tool for decision-making, resource optimization, and profitability maximization based on precise sales predictions.

Feel free to explore, contribute, or adapt the code for your own forecasting endeavors! If you have any questions or suggestions, reach out to the project author, Mohamed Kharma.

Happy forecasting! 🚀
