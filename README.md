# Churn-Predictor

A churn prediction model developed using TensorFlow and Keras offers a powerful tool for credit card companies to identify and retain customers effectively. By leveraging deep learning techniques, the model can capture intricate patterns in customer behavior and transaction history, enabling proactive churn management strategies.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Churn prediction is crucial for credit card companies to proactively manage customer retention. This project utilizes a neural network model developed with TensorFlow and Keras to predict customer churn based on various attributes, including demographic information, transaction history, and account details.

## Dataset

The dataset used in this study comprises various attributes of credit card customers, including demographic information, transaction history, and account details. Key features include customer age, dependent count, credit limit, transaction amounts, and churn status. The dataset is preprocessed to handle missing values, encode categorical variables, and normalize numeric features, ensuring compatibility with the neural network architecture.

Dataset link: [Credit Card Bank Churn Dataset](https://www.kaggle.com/datasets/anwarsan/credit-card-bank-churn)

## Model Architecture

The churn prediction model is constructed using a series of dense layers in a neural network architecture. 

- **Input Layer**: Accepts the preprocessed feature vectors.
- **Hidden Layers**: Multiple hidden layers with densely connected neurons. The activation function, typically ReLU (Rectified Linear Unit), introduces non-linearity, enabling the model to learn complex relationships between features.
- **Output Layer**: Predicts the probability of churn using a sigmoid activation function, producing a binary classification result.

## Installation

### Prerequisites

- Python 3.7 or higher
- TensorFlow
- Keras
- Pandas
- NumPy
- Scikit-learn

### Setup

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/churn-predictor.git
    cd churn-predictor
    ```

2. Install the required packages:
    ```sh
    pip install tensorflow keras pandas numpy scikit-learn
    ```

3. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/anwarsan/credit-card-bank-churn) and place it in the project directory.

## Usage

1. **Preprocess the Data**:
    - Run the preprocessing script to handle missing values, encode categorical variables, and normalize numeric features.

2. **Train the Model**:
    - Run the training script to train the churn prediction model.

3. **Evaluate the Model**:
    - Run the evaluation script to assess the model's performance on the test dataset.

4. **Predict Churn**:
    - Use the prediction script to predict churn for new customer data.

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create your feature branch: `git checkout -b feature/my-feature`.
3. Commit your changes: `git commit -m 'Add my feature'`.
4. Push to the branch: `git push origin feature/my-feature`.
5. Open a pull request.

