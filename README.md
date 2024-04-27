# Fuel Consumption Prediction Project

## Overview
This project involves building and training a machine learning model to predict fuel consumption based on various vehicle characteristics. The model is built using PyTorch.

## Features
The model predicts fuel consumption using the following features:
- CO Emissions
- Engine Size
- Number of Cylinders

## Requirements
- Python 3.x
- PyTorch
- Pandas
- NumPy
- Matplotlib

## Installation
To set up the project environment, run the following commands:
```bash
pip install torch pandas numpy matplotlib
```

## Usage
To train the model, run:
```python
python train_model.py
```

## Model Training
The model is trained using linear regression with regularization techniques to prevent overfitting. The training process involves the following steps:
- Splitting the dataset into training and testing sets.
- Normalizing the feature variables.
- Training the model using the Mean Squared Error (MSE) loss function.
- Using an SGD optimizer with a learning rate of 0.01 and l1 regularization.