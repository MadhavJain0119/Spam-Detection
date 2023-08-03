# SMS Spam Detection

## Overview

The SMS Spam Detection project is a machine learning model that aims to classify SMS messages as either "spam" or "non-spam" (ham). The model explores various algorithms, such as K-Nearest Neighbors, Random Forest, Logistic Regression, AdaBoost, XGBoost, Naive Bayes, and Support Vector Classifier, to find the best-performing approach. The Extra Trees Classifier (ETC) achieved the highest accuracy of 97.68% on the test dataset.

## Dataset

The dataset used to train and test the SMS Spam Detection model contains labeled SMS messages. Each message is annotated as "spam" or "ham" to facilitate supervised learning.
Project Structure

## Requirements

- Python (>= 3.6)
- NumPy
- Pandas
- Scikit-learn
- XGBoost

## Installation

1. Clone the repository to your local machine:

```bash

git clone https://github.com/your-username/SMS-Spam-Detection.git
cd SMS-Spam-Detection
```

2. Install the required dependencies:

```
pip install -r requirements.txt
```

## Usage

- Ensure you have installed all the dependencies.
- Run the main.py script to launch the user interface.
- Use the interface to enter a new SMS message for spam detection.
- The model will predict whether the message is "spam" or "ham" and display the result.

## Model Evaluation

The SMS Spam Detection model has been evaluated using a variety of performance metrics, including accuracy, precision, recall, F1-score, and ROC-AUC. The ETC algorithm demonstrated the highest accuracy of 97.68% on the test dataset.

## Best Model

The Extra Trees Classifier (ETC) has been identified as the best-performing algorithm for SMS Spam Detection, achieving an accuracy of 97.68%. The ETC is an ensemble learning method that combines multiple decision trees to make predictions.
