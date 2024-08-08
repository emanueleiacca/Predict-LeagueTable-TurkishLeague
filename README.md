# Predict League Table - Turkish League

This project aims to predict the league table of the Turkish League for the lattest match of the 2022/2023 season using machine learning techniques. The model is trained on historical data and tested to forecast the final standings.

## Dataset

The dataset contains match results, team statistics, and other relevant information for the seasons 20/21, 21/22, and 22/23. The data includes features such as goals scored, goals conceded, home/away performance, and more.

## Model
The model is built using the CatBoost library, which is well-suited for handling categorical data, it's chosen for its efficiency and performance with the given dataset.

## Feature Engineering

Feature engineering involves creating new features from the raw data to improve the model's performance. This includes aggregating statistics over various periods, encoding categorical variables, and normalizing numerical features. Detailed steps and code are provided in the model.ipynb notebook.

##Hyperparameter Tuning

Hyperparameter tuning is performed to optimize the model's performance. We use a powerfull framework like Optuna to find the best combination of hyperparameters for the CatBoost model. The tuning process is documented in the notebook.

## Evaluation
The model is evaluated using various metrics such as accuracy, precision, recall, and F1-score. Additionally, the predicted league table is compared with the actual standings to assess the model's effectiveness. Visualizations and analysis of the results are included in the notebook.

## Results
The results of the model predictions are documented in the notebook. Further analysis and visualizations can also be found there. The model's predictions are compared against actual league standings to highlight its predictive power.
