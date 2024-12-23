## Federated Learning for Heart Disease Prediction

This project demonstrates a federated learning system for predicting heart disease risk using the Flower framework. Federated learning allows multiple clients (e.g., clinics) to collaboratively train a machine learning model without sharing sensitive patient data.

## Features

- **Privacy-Preserving**: Data remains decentralized across clients, ensuring patient privacy.
- **Heart Disease Prediction**: Utilizes the UCI Heart Disease dataset to train a binary classification model.
- **Scalable**: Easily extendable to include more clients or additional privacy techniques.

## Technologies Used

- [Flower](https://github.com/adap/flower): Federated Learning framework
- TensorFlow: Neural network implementation
- Scikit-learn: Data preprocessing
- Pandas: Data manipulation

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/ay0788/federated-heart-disease
   cd federated-heart-disease
