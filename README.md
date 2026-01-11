# VK RecSys Challenge
## Building a model that will predict future likes/dislikes of users
This repository contains a machine learning project aimed at predicting whether a user will like or dislike a particular content based on their historical interactions. The model utilizes two powerful algorithms: CatBoost and LSTM, followed by stacking with Logistic Regression to improve performance.

## Project Structure
├── src/
│   ├── data_preprocessing.py       # Script for preprocessing raw data
│   ├── feature_engineering.py      # Script for engineering features
│   ├── model_training.py           # Script for training models
│   └── model_evaluation.py         # Script for evaluating trained models
├── notebooks/
│   ├── EDA.ipynb                 # Notebook for exploratory data analysis
│   ├── Feature_Engineering.ipynb   # Notebook for feature engineering
│   ├── Modeling.ipynb              # Notebook for modeling and evaluation
│   └── Stacking_Model.ipynb        # Notebook for stacking models
├── requirements.txt                # List of required packages
├── README.md                      # This file└── .gitignore                     # Git ignore file

## Dependencies

To run this project, you need to install the following dependencies listed in requirements.txt:

pip install -r requirements.txt

## Usage

Data Preprocessing:

Run src/data_preprocessing.py to clean and prepare the raw data for modeling.

Feature Engineering:

Run src/feature_engineering.py to generate new features from the preprocessed data.

Model Training:

Train individual models (CatBoost and LSTM) using src/model_training.py.

Model Evaluation:

Evaluate the performance of each model using src/model_evaluation.py.

Stacking:

Combine the predictions from CatBoost and LSTM models using logistic regression in notebooks/Stacking_Model.ipynb.
