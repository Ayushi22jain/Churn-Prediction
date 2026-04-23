# Churn Prediction
  
This project focuses on predicting customer churn using historical data. By analyzing customer behavior and demographics, the goal is to identify patterns that lead to attrition and build predictive models to help businesses retain their customers.

## 🚀 Workflow

1. **Data Cleaning & Preprocessing**
    * **Outlier Correction:** Implemented the Standard Box Plot method to identify and handle outliers, ensuring the data is robust for modeling.
    * **Exploratory Data Analysis (EDA):**
        * **Univariate Analysis:** Examining the distribution of individual variables.
        * **Bivariate Analysis:** Identifying relationships between features and the target churn variable.

2. **Machine Learning Models**
    The project evaluates the performance of multiple classification algorithms:
    * **Logistic Regression:** A baseline linear model for binary classification.
    * **Decision Tree:** A non-linear model that captures complex decision boundaries.
    * **Random Forest:** An ensemble method used to improve accuracy and reduce overfitting.

## 🛠️ Tech Stack

* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
* **Platform:** Jupyter Notebook / Google Colab

## 📊 Dataset

The analysis is performed on the `Churn_Modelling.csv` file, which contains features like credit score, geography, gender, age, tenure, balance, and more.

## 📁 Repository Structure

* `ChurnPredictions.ipynb`: The main notebook containing data cleaning, EDA, and model implementation.
* `Churn_Modelling.csv`: The dataset used for training and testing.
* `README.md`: Documentation for the project.

## ⚙️ How to Use

1. **Clone this repository:**
   ```bash
   git clone [https://github.com/Ayushi22jain/Churn-Prediction.git](https://github.com/Ayushi22jain/Churn-Prediction.git)
