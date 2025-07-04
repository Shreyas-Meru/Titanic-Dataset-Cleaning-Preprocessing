# Titanic Dataset Cleaning & Preprocessing 🛳️

This repository contains a Jupyter Notebook focused on the cleaning and preprocessing of the famous Titanic dataset, commonly used for data science and machine learning practice. The goal is to prepare the raw dataset for model training by handling missing data, encoding categorical variables, and performing exploratory data analysis (EDA).

## 📁 Repository Structure

```
Titanic-Dataset-Cleaning-Preprocessing/
│
├── Titanic Data Preprocessing.ipynb   # Main notebook with preprocessing code
├── README.md                          # You're here!
```

## 📌 Features

- Loads the Titanic dataset using pandas
- Performs exploratory data analysis (EDA)
- Handles missing values (e.g., Age, Cabin, Embarked)
- Encodes categorical variables (e.g., Sex, Embarked)
- Drops irrelevant or redundant features (e.g., Ticket, Cabin)
- Prepares dataset for use in machine learning models

## 🧰 Technologies Used

- Python 3.x
- Jupyter Notebook
- pandas
- seaborn
- matplotlib
- numpy

## 📊 Preprocessing Overview

1. **Handling Missing Data**  
   - Fills missing `Age` using median values grouped by `Pclass` and `Gender`
   - Fills missing `Embarked` values with mode
   - Drops `Cabin` and `Ticket` columns due to excessive missing values

2. **Feature Engineering**  
   - Encodes `Sex` and `Embarked` as numerical values
   - Creates new features (e.g., Family size could be added in future updates)

3. **Outlier and Correlation Analysis**  
   - Visualizations using seaborn for feature distributions and correlation

4. **Final Output**  
   - Cleaned DataFrame ready for training ML models

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Shreyas-Meru/Titanic-Dataset-Cleaning-Preprocessing.git
cd Titanic-Dataset-Cleaning-Preprocessing
```

### 2. Install Required Libraries

You can install the required libraries via pip:

```bash
pip install pandas matplotlib seaborn numpy
```

### 3. Run the Notebook

Open the notebook in Jupyter:

```bash
jupyter notebook Titanic\ Data\ Preprocessing.ipynb
```

## 🙌 Acknowledgements

- [Kaggle Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset?select=Titanic-Dataset.csv)

---
