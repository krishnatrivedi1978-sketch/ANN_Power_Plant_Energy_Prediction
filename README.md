ANN Power Plant Energy Prediction

Project Overview

This project uses an Artificial Neural Network (ANN) built with PyTorch to predict electrical power output using the Combined Cycle Power Plant dataset. It is a supervised machine learning regression problem because the target variable contains continuous numerical values.

Dataset Description

The dataset contains five columns:

- AT: Ambient Temperature
- V: Exhaust Vacuum
- AP: Ambient Pressure
- RH: Relative Humidity
- PE: Electrical Power Output (Target Variable)

Technologies Used

- Python
- PyTorch
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook

Model Description

An Artificial Neural Network regression model is developed using PyTorch to learn the relationship between environmental conditions and electrical power output.

Input Features

- Ambient Temperature (AT)
- Exhaust Vacuum (V)
- Ambient Pressure (AP)
- Relative Humidity (RH)

Output

- Predicted Electrical Power Output (PE)

Project Workflow

1. Import required libraries.
2. Load the dataset.
3. Perform exploratory data analysis (EDA).
4. Preprocess the dataset.
5. Split the dataset into training and testing sets.
6. Build an ANN model using PyTorch.
7. Train the neural network.
8. Evaluate model performance.

Evaluation Metrics

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

Project Files

- "ANN_regressor.ipynb" – Jupyter Notebook containing the ANN regression implementation.
- "11) Powerplant_dataset.csv" – Dataset used for training and testing.

How to Run

1. Clone the repository

git clone https://github.com/krishnatrivedi1978-sketch/ANN_Power_Plant_Energy_Prediction.git

2. Install the required libraries

pip install torch numpy pandas matplotlib scikit-learn jupyter

3. Launch Jupyter Notebook

jupyter notebook

4. Run the Notebook

Open "ANN_regressor.ipynb" and execute the cells.

Objective

The main objective of this project is to predict electrical power output using an Artificial Neural Network developed with PyTorch.
