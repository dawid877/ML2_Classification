# Drug Consumption Classification Project

## Project Overview
This project applies machine learning techniques to predict the likelihood of drug consumption across a variety of substances, ranging from legal (alcohol, nicotine, chocolate) to illicit (crack, heroin, cannabis). The primary goal is to analyze the relationship between user features (demographics/personality traits) and drug usage, while addressing significant **class imbalance** challenges inherent in the dataset.

## Repository Structure

* **`Data/`**: Contains the raw dataset used for training and testing.
* **`Data_Preprocessing.ipynb`**: Notebook for data cleaning, encoding categorical variables, and feature scaling.
* **`EDA.ipynb`**: Exploratory Data Analysis. Visualizes usage distributions, correlations, and feature importance.
* **`Modelling_1.ipynb`**: The core training loop. Implements classification models and generates performance metrics.
* **`Drug classification metrics analysis.xlsx`**: A consolidated report of model performance (Accuracy, Balanced Accuracy, Precision, Recall) across all 18 substances.

## ⚙️ Methodology

1. **Preprocessing**: Loading and discovering the structure of the data
2. **EDA**: Investigating the skew in the data, correlations between features, visualisations of drugs usage across the groups, discovering potential important signals
3. **Modeling**: Training classifiers for each individual drug, hyperparameters tuning, presenting the results from the test set

