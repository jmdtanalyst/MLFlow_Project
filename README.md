
# Iris Classification with MLflow

A simple demonstration project showcasing MLflow for tracking machine learning experiments using Logistic Regression on the classic Iris dataset.

## Project Overview

This project serves as a learning example for MLflow implementation, demonstrating:
- Experiment tracking
- Model logging
- Hyperparameter tuning
- Model registry basics

## Dataset

Using the classic Iris dataset which includes:
- 150 samples
- 3 different species of Iris
- 4 features: sepal length, sepal width, petal length, and petal width

## Requirements

```
python>=3.7
mlflow
scikit-learn
pandas
numpy
```


2. View MLflow UI:
```bash
mlflow ui
```
Navigate to `http://localhost:5000` to view experiments

## Project Structure

```
├── README.md
├── requirements.txt
├── train.py
├── data/
│   └── iris.csv
└── mlruns/
```

## Features

- Data preprocessing
- Model training using LogisticRegression
- MLflow experiment tracking
- Model performance metrics logging
- Model serialization

## License

This project is licensed under the MIT License - see the LICENSE file for details

## Acknowledgments

- Iris dataset from UCI Machine Learning Repository
- MLflow documentation
- scikit-learn documentation
``` 
