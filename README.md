# Drug Consumption Classification Project

## Project Overview
This project applies machine learning techniques to predict the likelihood of drug consumption across a variety of substances, ranging from legal (alcohol, nicotine, chocolate) to illicit (crack, heroin, cannabis). The primary goal is to analyze the relationship between user features (demographics/personality traits) and drug usage, while addressing significant **class imbalance** challenges inherent in the dataset.

## Repository Structure and methodology

* **`Data/`**: Contains the orginal data and data versions created for different purposes in the project. Explanations in the codes
* **`Data_Preprocessing.ipynb`**: Loading and discovering the structure of the data
* **`EDA.ipynb`**: Investigating the skew in the data, correlations between features, visualisations of drugs usage across the groups, discovering potential important signals
* **`Modelling_1.ipynb`**: Training classifiers for each individual drug, hyperparameters tuning, presenting the results from the test set
* **`Drug classification metrics analysis.xlsx`**: A consolidated report of model performance (Accuracy, Balanced Accuracy, Precision, Recall) across all drugs and algorithms.
