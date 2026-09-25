# Deep Learning - Credit Card Customer Churn Prediction

A beginner Deep Learning project built to understand the practical implementation of an Artificial Neural Network (ANN/MLP) using TensorFlow and Keras.

## 🎯 Project Goal

The main purpose of this project was to learn how to build, train, and evaluate a neural network and understand how different layers and activation functions affect the model.

This project was developed and executed on **Kaggle**.

## 🧠 Model Architecture

```text
Input Features
      ↓
Dense Layer (11 neurons, ReLU)
      ↓
Dense Layer (11 neurons, ReLU)
      ↓
Output Layer (1 neuron, Sigmoid)
```

## 🔧 Concepts Learned

* Data preprocessing
* Categorical feature encoding
* Feature scaling
* Train-test split
* Building an ANN using TensorFlow/Keras
* Dense layers
* ReLU activation function
* Sigmoid activation function
* Binary Cross-Entropy loss
* Adam optimizer
* Model training and validation
* Making predictions
* Evaluating model performance
* Experimenting with neural network layers and neurons

## 📊 Result

**Test Accuracy: 86.4%**

The model was trained to predict whether a credit card customer would churn.

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* TensorFlow
* Keras
* Kaggle

## 📁 Project Files

```text
deep-learning-churn-prediction/
│
├── churn-prediction-praveer-singh.ipynb
└── README.md
```

## 📊 Dataset

The project uses the **Credit Card Customer Churn Prediction** dataset available on Kaggle.

The notebook was executed using Kaggle's dataset environment, so the original dataset path used in the notebook is:

```text
/kaggle/input/datasets/rjmanoj/credit-card-customer-churn-prediction/Churn_Modelling.csv
```

To reproduce the notebook on Kaggle, attach the same dataset to the notebook and run the cells.

## 📌 Note

This project was primarily created as a **learning exercise** to understand the implementation of Artificial Neural Networks and experiment with different layers, neurons, and activation functions. It is not intended to be a production-ready churn prediction system.
