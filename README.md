 Auto MPG Prediction using Polynomial Regression

Project Overview

This project predicts the **fuel efficiency (Miles Per Gallon - MPG)** of vehicles using **Polynomial Regression**. The model analyzes different vehicle characteristics to understand how they influence fuel efficiency.

Polynomial regression is used in this project because the relationship between vehicle features and fuel efficiency is often **non-linear**.

 Dataset

The dataset used is the **Auto MPG dataset**, which contains information about various car specifications and their fuel efficiency.

Dataset Source:
https://www.kaggle.com/datasets/uciml/autompg-dataset

 Features Used

The following features are used as predictors:

* Displacement – Engine displacement
* Horsepower – Engine power
* Weight – Vehicle weight
* Acceleration – Time taken to accelerate from 0–60 mph

Target Variable

* MPG – Miles per gallon (fuel efficiency)

Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-learn

 Steps Performed

1. Loaded the dataset using pandas.
2. Explored the dataset and checked for missing values.
3. Selected important features and defined the target variable.
4. Split the dataset into **training (80%)** and **testing (20%)** sets.
5. Applied **PolynomialFeatures (degree = 2)** to capture non-linear relationships.
6. Trained a **Linear Regression model** on the polynomial features.
7. Predicted MPG values on the test dataset.
8. Evaluated the model using **Mean Squared Error (MSE)** and **R² score**.
9. Visualized the relationship between **actual and predicted MPG values**.

Results

The polynomial regression model helps capture non-linear patterns between vehicle features and fuel efficiency, improving prediction accuracy compared to simple linear regression.

Visualization

A scatter plot is used to compare **actual MPG values** and **predicted MPG values** to evaluate model performance.


