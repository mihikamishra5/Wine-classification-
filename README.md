# Wine Class Classification Repository

Welcome to the Wine Class Classification Repository! This repository is dedicated to a comprehensive machine learning and deep learning project focusing on the classification of wine types based on various chemical features. The dataset used is the "Wine Class Classification" dataset, originally donated to the Data Science community in June 1991 and available from the UC Irvine Machine Learning Repository.

# Repository Structure

The repository is structured into two main sections: Exploratory Data Analysis (EDA) and Model Building.

## 1. Exploratory Data Analysis (EDA)
In this section, you will find Jupyter/Colab notebooks containing detailed exploratory data analysis performed on the wine dataset. The notebooks follow these steps:

### Data Preparation: 
Scripts for cleaning and preparing the dataset for modeling. This includes handling missing values, null records, and transforming data to ensure all entries are numeric.
### Data Analysis: 
Identification and visualization of data types, including numeric and categorical data.
### Advanced EDA:
Utilization of TensorFlow Data Validation (TFDV) along with traditional EDA techniques using Pandas and Numpy libraries. This includes visualizing dependencies and correlations among features and identifying key features (Feature Importance) for the target label.
## 2. Machine Learning/Deep Learning Model
This section includes a deep learning model for multi-class classification of wine types, based on TensorFlow’s modeling approaches. The notebooks guide through:

### Model Architecture: 
Description of the typical architecture of the classification neural network used in this project.
Model Training and Evaluation: Detailed steps for creating, compiling, and fitting the model on the dataset. Also includes evaluation metrics such as loss and accuracy curves, and confusion matrix.
Model Tuning: Instructions and scripts for tuning the model on parameters like activation functions, learning rate, and number of epochs.
# Prerequisites
Before you begin, ensure you have the following installed:

TensorFlow Data Validation (tensorflow_data_validation)
Apache Beam (apache-beam)
GraphViz
Dataset

The dataset can be downloaded from the UC Irvine Machine Learning Repository. It includes results of a chemical analysis of wines grown in Italy, derived from three different cultivars, and the quantities of 13 constituents found in each type of wine.

