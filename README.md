# HousePricePrediction

## Project Overview

This project is focused on predicting house prices in the USA using various machine learning models. The dataset used is `USA_Housing.csv`, which contains features such as average area income, house age, number of rooms, etc.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Acknowledgements](#acknowledgements)

## Features

- Data Cleaning and Preprocessing
- Exploratory Data Analysis
- Model Training (Linear Regression)
- Model Evaluation
- Web Interface for Predictions (using Django)

## Installation

1. Clone the Repository

```
git clone https://github.com/SumayyaAli11/HousePricePrediction.git
cd HousePricePrediction
```

2. Set Up a Virtual Environment
```
python -m venv .venv
source .venv/bin/activate   # On Windows use: .venv\Scripts\activate
```
4. Install Dependencies
   
```
pip install -r requirements.txt
```
## Usage

1. Running the Web Application
To run the Django web application, navigate to the project directory and use the following command:

```
python manage.py runserver
```
Then, open your browser and go to http://127.0.0.1:8000 to access the application.

2. Making Predictions
The web application allows users to input various features of a house and get a price prediction based on the trained model.

## Acknowledgements
Kaggle for providing the dataset.
Scikit-Learn for the machine learning library.
Django for the web framework.
