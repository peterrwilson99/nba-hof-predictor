# Predicting Future NBA Hall of Famers using Supervised Machine Learning

This repository contains a Python script to predict which players from the National Basketball Association (NBA) might become future inductees to the Hall of Fame. It uses various supervised machine learning algorithms to create an optimized model based on historical player data.

## Purpose

The purpose of this script is to take various factors into account (like player statistics, awards, all-star appearances, etc.) and use machine learning techniques to predict the likelihood of a player being inducted into the NBA Hall of Fame in the future.

## Data

The data used in this script includes player statistics for each season played from 1950 - 2022, All-Star data, Hall of Fame statistics for training the labels, and Season MVP statistics. Most of the data was found on Kaggle.

## Machine Learning Models

Several machine learning models are used and compared for this task, including Logistic Regression, Random Forest Classifier, Decision Tree Classifier, Gaussian Naive Bayes, Support Vector Classification, and K-Nearest Neighbors Classifier. Grid search is employed to optimize the hyperparameters of the best performing model.

## Report

A detailed report on the methodology, process, results, and discussions can be found in `report.md` in this repository.

## Requirements

This script requires Python 3.x and the following Python libraries installed:

- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

To install these libraries, you can simply run `pip install -r requirements.txt`.

## Usage

You can run the script in the command line by using the following command:

```bash
python predict_hof.py
```

## Results

The results of the predictions for current active players can be found in the output of the script.

Please note that the results are based on the data up until 2023, and performance may vary when updated with new data.