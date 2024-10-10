Calories Burned Prediction - Machine Learning Project

Project Overview

This project focuses on predicting the number of calories burned during physical activities based on various features such as exercise duration, age, weight, heart rate, and more. The goal is to build and evaluate multiple machine learning models to accurately predict calories burned, using regression techniques like Linear Regression, Decision Tree Regression, and Random Forest Regression.

Dataset

The dataset contains the following features:

- Age: Age of the individual (years)
- Weight: Weight of the individual (kg)
- Height: Height of the individual (me)
- Duration: Duration of the physical activity (hours)
- Heart Rate: Heart rate during exercise (beats per minute)
- Calories Burned: Target variable, the number of calories burned (cal)
- Fat Percentage: Percentage of Fat in users body
- Water Intake : amount of water consumed (Liters)
- Workout Frequency: How many days a person works out
- BMI (Body Mass Index)
- Gender: Male or Female 

 Models Used

- Linear Regression: A baseline model to understand the linear relationships between features and target variables.
  
- Decision Tree Regression: A non-linear model that captures more complex patterns in the data.
  
- Random Forest Regression: An ensemble method that improves prediction accuracy by averaging the outputs of multiple decision trees.

Model Evaluation

The performance of each model is evaluated using the following metrics:

- Mean Squared Error (MSE): Measures the average squared difference between predicted and actual values.
  
- Mean Absolute Error (MAE): Measures the average amount by which predictions differ from the true values.
  
- R-squared (R²): Represents the proportion of variance in the dependent variable explained by the model.

In addition to the default evaluations, cross-validation was used to ensure the models’ performance is generalized across different data splits. Grid Search was implemented for hyperparameter tuning to optimize the models further.
