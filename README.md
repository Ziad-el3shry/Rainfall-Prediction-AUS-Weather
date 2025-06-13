# Rainfall Prediction in Australia

![Python](https://img.shields.io/badge/Python-3.7%2B-blue)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.0.2-orange)
![Pandas](https://img.shields.io/badge/Pandas-1.3.0-red)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.4.2-yellow)

A machine learning project to predict rainfall in Australia using weather data from 2008-2017.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Project Overview
This project develops a classifier to predict whether it will rain the next day in Australia using:
- Data preprocessing and feature engineering
- Exploratory Data Analysis (EDA)
- Machine learning models (Random Forest, Logistic Regression)
- Model evaluation and optimization

## Dataset
Source: [Australian Government Bureau of Meteorology](http://www.bom.gov.au/climate/dwo/)
- Contains daily weather observations from 2008-2017
- 23 features including temperature, humidity, pressure, etc.
- Target variable: RainTomorrow (Yes/No)

## Features
- Data cleaning and missing value imputation
- Feature engineering (seasonal features, weather trends)
- Model training with hyperparameter tuning
- Performance evaluation (accuracy, precision, recall)
- Confusion matrix visualization

## Installation
1. Clone the repository:
```bash
git clone https://github.com/yourusername/rainfall-prediction.git
cd rainfall-prediction
