## Colon Cancer Classification

## Overview

This project applies a **Decision Tree Classifier** to classify colon cancer cases as **benign** or **malignant** based on gene expression levels. The model uses a **Decision Tree Classifier** to predict cancer classification. The dataset consists of **64 gene types** with their expression levels and **804 colon tissue samples**, with the **DAO gene** used for classification.

---

## Dataset
- **Number of Samples**: 804 samples
- **Number of Genes**: 64 genes
- **Target Variable**: 
  - `0` → Benign
  - `1` → Malignant

- **Key Feature Used**:
  - **DAO**: The **DAO gene** was specifically used in the classification model.
  - Other genes (ADH1C, DHRS11, UGP2, etc.) were part of the feature set.

---

## Data Preprocessing

- **Exploratory Data Analysis (EDA)**: EDA was conducted to understand the dataset structure and gene expression levels.
- **Data Splitting**: The dataset was divided into **training** and **testing** sets using **train_test_split** to ensure proper evaluation of the model’s performance.

---

## Model Development

### Model Training & Selection

- **Decision Tree Classifier** was chosen for classification due to its interpretability and ability to handle both numerical and categorical data.

### Model Evaluation

- **Accuracy Score**: The model achieved an accuracy of **92.9%** on the test set.
- **Visualizing the Decision Tree**: The trained decision tree was visualized using `plot_tree` to understand how the model makes decisions.
- **Performance Metrics**: Metrics like accuracy, precision, recall, and F1 score were used to assess the model's performance.

