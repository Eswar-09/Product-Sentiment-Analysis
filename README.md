# Product Sentiment Analysis Project - Project Name

## Overview

This project focuses on sentiment analysis for various brands and products using user-generated tweets. Users have provided evaluations, categorizing sentiments as positive, negative, or neutral. Additionally, contributors have identified the specific brand or product targeted by the conveyed emotion.

## Dataset

The dataset comprises user-assessed tweets related to different brands and products. Contributors have labeled sentiments as positive, negative, or neutral, and have also identified the specific brand or product mentioned in the tweet. Two main files are utilized:

1. **Data Cleaning and Augmentation:**
   - File Name: `Product_Sentiment Analysis_Pre-Processing.ipynb`
   - Procedures: Data cleaning, exploratory data analysis (EDA), text preprocessing, and dataset augmentation.
   - Outputs: `Train_Balanced_Cleaned.csv` and `Test_Balanced_Cleaned.csv`.

2. **Model Training:**
   - File Name: `Product_Sentiment Analysis_Pre-Model.ipynb`
   - Model: Utilizes a BERT model for sentiment analysis.
   - Input: Train and test datasets (`Train_Balanced_Cleaned.csv` and `Test_Balanced_Cleaned.csv`).
   - Procedures: Model training, evaluation, and prediction.


## Usage

1. **Data Cleaning and Preprocessing:**
   - Open and run `Product_Sentiment Analysis_Pre-Processing.ipynb`.
   - Input: `raw_train.csv` and `raw_test.csv`.
   - Output: `Train_Balanced_Cleaned.csv` and `Test_Balanced_Cleaned.csv`.

2. **Model Training and Prediction:**
   - Open and run `Product_Sentiment Analysis_Pre-Model.ipynb`.
   - Input: `Train_Balanced_Cleaned.csv` and `Test_Balanced_Cleaned.csv`.
   - Output: Trained BERT model (`sentiment_model.pth`) and evaluation results.

## Requirements

- Python 3.x
- Jupyter Notebooks
- Seaborn
- nlpaug
- transformers
- torch
- wrap

## Acknowledgments

- Mention any credits or acknowledgments.




