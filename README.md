# Neural Network for Iris Dataset
This repository contains the code for implementing an Artificial Neural Network (ANN) on the Iris dataset using Google Colab. The code is written in Python using the Keras library. 
- Platform - Google Colab.

## Steps to Reproduce:

### 1. Data Preparation:

- Load the Iris dataset.
- Split the dataset into features (X) and target labels (y).
- Perform one-hot encoding on the target labels.
  
### 2. Build the Neural Network:

- Create a sequential model.
- Add Dense layers with appropriate activation functions for hidden layers.
- Use the softmax activation function for the output layer.
- Compile the model with categorical cross-entropy loss and an optimizer (e.g., RMSprop).
- Train the model on the training data.

### 3. Evaluate the Model:

- Evaluate the model on the test dataset.
- Print the test loss and accuracy.

### 4. Make Predictions:

- Make predictions on a subset of the test dataset.
- Print the raw predictions and thresholded output.

## Files:

- `P1_ANN_on_Iris.ipynb`: Jupyter notebook containing the entire code.
- `iris_dataset.csv` : Iris Dataset used in this project.
- `README.md`: This README file.

## Instructions for Use:

1. Save the Iris dataset as a CSV file in your Google Drive.
2. Open the Jupyter notebook `P1_ANN_on_Iris.ipynb` in Google Colab.
3. Mount your Google Drive using the provided code cell to access the dataset.
4. Follow the code cells sequentially for data preparation, model building, evaluation, and predictions.
5. Modify parameters or experiment as needed.
6. Save the notebook if you make changes.

## Note:

- Ensure you have the necessary Python libraries installed.
- Modify file paths and names accordingly.
- Adjust dataset loading code based on your CSV file structure.
