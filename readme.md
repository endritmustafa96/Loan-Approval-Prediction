# Loan Approval Prediction

---

<div align="center">
    <img src="https://quickzy.com.au/wp-content/uploads/2024/07/loan-rejection-loan-approved-Quickzy-Finance.png" />
</div>

This repository contains the code and data for the Kaggle competition "Playground Series - Season 4, Episode 10". The goal of this competition is to predict whether an applicant is approved for a loan based on various features. 

Submissions are evaluated based on the area under the ROC curve (AUC) using predicted probabilities and the ground truth targets.

The Submissions generated from the models in this code are among top 13% of candidates.

## Repository Structure

<code>Data</code>: Contains the datasets required for the competition. All necessary files, including training and test data, are available here.

<code>Notebook</code>: Contains Jupyter notebook that cover:

* Data cleaning
* Exploratory data analysis (EDA)
* Feature engineering
* Model training and evaluation
    
<code>Prediction</code>: Stores the generated prediction files ready for submission.

## Models Used

This project leverages various machine learning models to achieve the best possible performance. Key models and techniques include:

* **LightGBM**: A gradient boosting framework that uses tree-based learning algorithms, optimized for speed and efficiency.
* **CatBoost**: A boosting algorithm that handles categorical features naturally, enhancing prediction performance.
* **Hill Climbing**: Applied to improve the performance of individual models through optimization.
* **AutoGluon (tabular)**: An automated machine learning (AutoML) tool to simplify model training and selection.

## Usage

Clone the repository and navigate to it

Data Preparation: Ensure the data files are in the Data directory. You can download the dataset from Kaggle if not included.

Running the Notebooks: Open and execute the Jupyter notebook in the Notebook directory to preprocess data, train models, and generate predictions. The notebook is structured with detailed comments to guide you through each step.

Making Predictions: Once models are trained, save predictions in the Prediction folder. Follow the instructions in the notebook to generate predictions that can be submitted to Kaggle.

## Results and Evaluation

This project’s performance is assessed using the AUC-ROC metric, as it measures the model's ability to distinguish between positive and negative classes.

## Competition Link

https://www.kaggle.com/competitions/playground-series-s4e10

---
Endrit Mustafa

