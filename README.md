# Drug Consumption Classification Project

## Project Overview
This project applies machine learning techniques to predict the likelihood of drug consumption across a variety of substances, ranging from legal (alcohol, nicotine, chocolate) to illicit (crack, heroin, cannabis). The primary goal is to analyze the relationship between user features (demographics/personality traits) and drug usage, while addressing significant **class imbalance** challenges inherent in the dataset.

## Repository Structure and methodology

* **`Data_Preprocessing.ipynb`**: Loading and discovering the structure of the data
* **`EDA.ipynb`**: Investigating the skew in the data, correlations between features, visualisations of drugs usage across the groups, discovering potential important signals
* **`Modelling_1.ipynb`**: Training classifiers for each individual drug, hyperparameters tuning, presenting the results from the test set
* **`Drug classification metrics analysis.xlsx`**: A consolidated report of model performance (Accuracy, Balanced Accuracy, Precision, Recall) across all drugs and algorithms.
* **`Classification.pptx`**: PowerPoint slides with the key findings and algorithms results

## Data

* **`X.csv`**: Initial, already encoded set of independent variables
*  **`y.csv`**: Initial set of drugs usage scores (0-6), target variables
* **`X_decoded.csv`**, **`y_decoded.csv`**, **`df_decoded.csv`**: decoded initial data - made for clearness and readability of EDA
* **`y_binary.csv`**: drug usage scores reduced to binary format - recent drug user (used in the last 12 months) vs not
