
# Autism Spectrum Disorder Analysis

This project analyzes a dataset related to Autism Spectrum Disorder (ASD). It involves data preprocessing, exploratory data analysis, and building predictive models using various machine learning techniques.

## Table of Contents

- [Dataset Description](#dataset-description)
- [Project Overview](#project-overview)
- [Installation](#installation)
- [Usage](#usage)
- [Model Evaluation](#model-evaluation)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Dataset Description

The dataset used in this project contains information related to ASD. It includes the following columns:

- **Case_No**: Unique identifier for each case
- **A1_Score** to **A10_Score**: Scores from a questionnaire
- **Age**: Age of the individual
- **Q-chat-10**: Q-CHAT-10 score
- **Gender**: Gender of the individual
- **Ethnicity**: Ethnicity of the individual
- **Jaundice**: History of jaundice at birth
- **Family_mem_with_ASD**: Family members with ASD
- **Test_Person**: Person who completed the test
- **ASD_Traits**: Presence of ASD traits (target variable)

## Project Overview

The project involves the following steps:

1. **Data Importing and Initial Exploration**: Import necessary libraries and load the dataset.
2. **Data Cleaning and Preprocessing**:
   - Handle missing values
   - Encode categorical variables
   - Perform feature scaling
3. **Exploratory Data Analysis (EDA)**:
   - Visualize data distribution
   - Analyze relationships between variables
4. **Model Building**:
   - Train and evaluate multiple machine learning models:
     - Logistic Regression
     - Random Forest Classifier
     - AdaBoost Classifier
     - Support Vector Machine (SVM)
     - K-Nearest Neighbors (KNN)
     - Decision Tree Classifier
5. **Model Evaluation**:
   - Compare models based on accuracy, precision, recall, and F1 score

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/Autism-Spectrum-Disorder-Analysis.git
   cd Autism-Spectrum-Disorder-Analysis
   ```
2. Open the provided Google Colab notebook link or upload the `Autism_Spectrum_Disorder_Analysis.ipynb` file to your Google Drive.
3. Open the notebook with Google Colab.

## Usage

1. Open the Google Colab notebook.
2. Upload the dataset (`Autism_Data.csv`) to your Google Colab session.
3. Run the cells in the notebook sequentially to preprocess the data, visualize it, and build predictive models.

## Model Evaluation

The following models were evaluated on the dataset:

| Model                     | Accuracy | Precision | Recall | F1 Score |
|---------------------------|----------|-----------|--------|----------|
| Logistic Regression       | 0.94     | 0.94      | 0.99   | 0.97     |
| Random Forest Classifier  | 0.96     | 0.96      | 0.99   | 0.97     |
| AdaBoost Classifier       | 0.95     | 0.95      | 0.99   | 0.97     |
| Support Vector Machine    | 0.95     | 0.95      | 0.99   | 0.97     |
| K-Nearest Neighbors       | 0.94     | 0.94      | 0.99   | 0.97     |
| Decision Tree Classifier  | 0.95     | 0.95      | 0.99   | 0.97     |

---
