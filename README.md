# Churn-Predictor
A churn prediction model developed using TensorFlow and Keras offers a powerful tool for credit card companies to identify and retain customers effectively. By leveraging deep learning techniques, the model can capture intricate patterns in customer behavior and transaction history, enabling proactive churn management strategies.

# The Dataset
The dataset used in this study comprises various attributes of credit card customers, including demographic information, transaction history, and account details. Key features include customer age, dependent count, credit limit, transaction amounts, and churn status. The dataset is preprocessed to handle missing values, encode categorical variables, and normalize numeric features, ensuring compatibility with the neural network architecture.
link : https://www.kaggle.com/datasets/anwarsan/credit-card-bank-churn.

# Model Architecture:
The churn prediction model is constructed using a series of dense layers in a neural network architecture. The input layer accepts the preprocessed feature vectors, which are then passed through multiple hidden layers, each consisting of densely connected neurons. The activation function, typically ReLU (Rectified Linear Unit), introduces non-linearity, enabling the model to learn complex relationships between features. The final output layer predicts the probability of churn using a sigmoid activation function, producing a binary classification result.
