# Heart Disease Prediction using Neural Networks

## Project Overview
This tutorial demonstrates the impact of different activation functions—Sigmoid, Tanh, and ReLU—on the performance of a deep neural network. The model is trained to predict heart failure using clinical data, highlighting how choice of activation affects convergence speed and classification accuracy.
This project demonstrates how activation functions affect the performance of neural networks in a healthcare prediction task.

The model is trained on a heart failure prediction dataset and compares three activation functions:
- Sigmoid
- Tanh
- ReLU

## Technical Architecture
The neural network was implemented using the Keras Sequential API with a TensorFlow backend.
-Input Layer: Designed to receive clinical features such as age, cholesterol, and blood pressure.
-Hidden Layers: Two dense layers with 32 and 16 neurons respectively. These layers use the activation function being tested (Sigmoid, Tanh, or ReLU).
-Output Layer: A single neuron using a Sigmoid activation to produce a probability for binary classification.
-Optimization: The model utilizes the Adam optimizer and binary cross-entropy loss function over 30 training epochs.

## Installation & Requirements
To reproduce these results, ensure you have Python 3.x and the following libraries installed:
pip install tensorflow scikit-learn pandas numpy matplotlib seaborn

## How to Run
Clone the Repository: Download the project files to your local machine.

Dataset: Ensure the file heartdataset.csv is located in the same root directory as the notebook.

Execute: Open the Jupyter Notebook (ML_tutorial_Assigment.ipynb) and run all cells sequentially.

Verification: The code will output three visualizations comparing class distribution, convergence speed, and final accuracy.

## Results Summary
Experimental results show that ReLU (Rectified Linear Unit) achieved the highest accuracy in the shortest amount of time. This is due to its non-saturating gradient, which effectively avoids the vanishing gradient problem that causes Sigmoid and Tanh to train significantly slower on large input values.

## Accessibility Features
This project was designed with accessibility in mind:

High Contrast: Figures use high-contrast color schemes for readability.

Color-Blind Friendly: Visualizations are labeled clearly to ensure data is interpretable for users with color vision deficiencies.

Clear Labels: Short, descriptive titles and labels are used throughout all figures.

## Dataset Source
The data used is the Heart Failure Prediction Dataset sourced from Kaggle.

Link: https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction

## Author
Ibrahim Olayinka Abdulsalam
