# Car-Price-Prediction

This project aims to create an artificial neural network model to predict the prices of used cars. The project is conducted on a dataset obtained from Kaggle.

## Dataset

The dataset is published on Kaggle under the name "Used Cars Dataset". It contains various features of vehicles such as brand, model, year, mileage, fuel type, transmission type, and price.

### Data Preprocessing

During the data preprocessing phase, the following steps were taken:

- Checking and cleaning missing data
- Correcting inconsistent or meaningless data
- Transforming categorical variables using one-hot encoding
- Dropping unnecessary columns
- Scaling the data

## Model Development

An artificial neural network was used as the machine learning model. The development of the model involved the following steps:

- Creating a Sequential model
- Adding layers and specifying activation functions
- Compiling the model (optimizer, loss function)
- Training the model on the training data
- Evaluating the performance of the model

## Requirements

Before running the project, make sure the following libraries are installed:

pandas==1.3.3
numpy==1.21.2
matplotlib==3.4.3
seaborn==0.11.2
scikit-learn==0.24.2
tensorflow==2.6.0
