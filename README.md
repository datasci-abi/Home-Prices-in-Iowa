Predicting Home Prices in Ames, Iowa
Overview
This project aims to predict house sale prices in Ames, Iowa using machine learning models. The goal is to develop a model that can accurately estimate sale prices based on various house features like size, location, and year sold.
Installation
To run this project, you will need to install the following libraries:
•	category_encoders
•	numpy
•	pandas
•	matplotlib
•	scikit-learn
If you're using Google Colab, you can install these libraries using pip commands.
Project Structure
The project is organized into several tasks:
1.	Data Wrangling: Load and clean the dataset.
2.	Data Visualization: (Optional) Create visualizations like scatter plots to explore relationships between features and sale prices.
3.	Feature Selection: Split the dataset into features (X) and the target (y), where y is the sale price.
4.	Train-Test Split: Divide the data into training and validation sets based on the year sold.
5.	Baseline Model: Calculate a baseline mean absolute error (MAE) by predicting the average sale price.
6.	Linear Regression: Build and train a linear regression model to predict sale prices.
7.	Ridge Regression: Build and train a ridge regression model to improve predictions.
8.	Model Evaluation: Compare the performance of both models using MAE and R² scores to see how well they predict sale prices.
9.	Model Prediction: Use the best model to make predictions on a test dataset.
10.	Feature Importance: (Optional) Visualize the most important features that influence house prices.
Results
•	Baseline Mean Absolute Error: ~59,000
•	Linear Regression: Trained successfully but overfit, resulting in a poor validation score.
•	Ridge Regression: Performed well with an MAE of ~17,987 for the validation set.
•	Key Features: Certain features like the size of the living area (Gr_Liv_Area) were important for predicting sale prices.
How to Run
1.	Load the dataset and clean it.
2.	Train both linear and ridge regression models.
3.	Evaluate the models and select the best one based on performance.
4.	Make predictions on the test dataset using the chosen model.
Requirements
•	category_encoders
•	numpy
•	pandas
•	matplotlib
•	scikit-learn
Conclusion
This project demonstrates how machine learning models can predict home sale prices in Ames, Iowa. Ridge regression was the better model, providing more accurate predictions compared to linear regression. Future improvements can include hyperparameter tuning and exploring more advanced models.
Feel free to clone the repository and experiment with the models!

