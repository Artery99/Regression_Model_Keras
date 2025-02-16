# Regression Model with Keras
This Jupyter Notebook focuses on implementing a regression model using Keras with TensorFlow as the backend. Below are the key components:

1. Load Dependencies:
Uses numpy, pandas, tensorflow.keras, and sklearn for data handling, model building, and evaluation.
2. Load and Prepare the Dataset:
The dataset is loaded from an online source (https://cocl.us/concrete_data).
Features (X) and target variable (y, labeled as "Strength") are extracted.
Data is standardized using StandardScaler to improve model performance.
The dataset is split into training and testing sets.
3. Define and Train the Model:
A Sequential Neural Network is built with Dense layers:
a. Fully connected layers with ReLU activation.
b. The output layer has a single neuron (for regression tasks).
c. The model is compiled with mean_squared_error loss and an Adam optimizer.
d. The model is trained using the fit function.
4. Model Evaluation:
Predictions are generated on the test set.
Mean Squared Error (MSE) is calculated to assess model performance.
