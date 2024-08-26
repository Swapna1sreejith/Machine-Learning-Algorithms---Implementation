# **Machine-Learning-Algorithms---Implementation**
This repository is created for implementing different Machine Learning algorithms on a car price dataset using regression algorithms.

### Scenario:
A Chinese automobile company aspires to enter the US market by setting up their manufacturing unit there and producing cars locally to give competition to their US and European counterparts. They have contracted an automobile consulting company to understand the factors on which the pricing of cars depends. Specifically, they want to understand the factors affecting the pricing of cars in the American market, since those may be very different from the Chinese market. Essentially, the company wants to know:
- Which variables are significant in predicting the price of a car.
- How well those variables describe the price of a car.
Based on various market surveys, the consulting firm has gathered a large dataset of different types of cars across the American market.

### Dataset 
The dataset used for analysis can be accessed from here[Click here]( https://drive.google.com/file/d/1FHmYNLs9v0Enc-UExEMpitOFGsWvB2dP/view?usp=drive_link)

## **1. Loading and Preprocessing**
The dataset, containing various features related to car specifications and their corresponding prices, was loaded for analysis. Preprocessing steps included handling missing values, encoding categorical variables and scaling numerical features to ensure that the data was in the optimal format for model training. The data was then split into training and testing sets to evaluate model performance.

## **2. Model Implementation**
Implemented the following five regression algorithms:
 1) Linear Regression
 2) Decision Tree Regressor
 3) Random Forest Regressor
 4) Gradient Boosting Regressor
 5) Support Vector Regressor
### ***Linear Regression***
A simple yet effective model to understand the linear relationship between the features and car prices.
### ***Decision Tree Regressor***
A non-linear model that creates a tree structure to make predictions based on decision rules inferred from the data.
### ***Random Forest Regressor***
An ensemble learning method that builds multiple decision trees and merges them to improve prediction accuracy.
### ***Gradient Boosting Regressor***
Another ensemble technique that builds models sequentially, with each new model correcting errors made by the previous ones.
### ***Support Vector Regressor***
A model that attempts to fit the data within a certain margin, optimizing for the best boundary.

## **3. Model Evaluation**
The train-test split technique is used to train and test the datasetusing different methods.The training set is used to train the model, while the test set is used to evaluate the final model's performance and generalization capabilities. Each model's performance was evaluated using R-squared, Mean Squared Error (MSE), and Mean Absolute Error (MAE) metrics. These metrics provided insights into the accuracy and robustness of each model. The comparison allowed for the identification of the best-performing model as Random Forest Regressor.

## **4. Feature Importance Analysis**
The analysis is conducted to determine which variables are significant in predicting the price of a car. Feature importance was evaluated using methods like feature importance scores from ensemble models (Random Forest and Gradient Boosting) and correlation analysis. This step provided valuable insights into which features are most influential in determining car prices.And finally from this steps insights driven were the critical role of engine size and curb weight in car pricing. These findings can guide the management to focus on these aspects when designing or pricing new vehicles. Features with negligible importance might not need as much attention in terms of cost optimization or marketing.

## **5. Hyperparameter Tuning**
The best-performing model underwent hyperparameter tuning to further enhance its performance. Techniques such as Grid Search or Randomized Search were used to find the optimal set of hyperparameters, resulting in improved model accuracy and reliability.

               The project successfully identified the relationships between car prices and various independent variables, providing the management with a powerful tool to understand and predict car pricing dynamics. The insights gained from the feature importance analysis and the best-performing model's predictions can guide future business strategies and market entry decisions.
