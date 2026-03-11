# Predicting Sleep Disorders using Machine Learning

## Project Overview
This project focuses on predicting sleep disorders using machine learning techniques. Sleep disorders such as insomnia and sleep apnea can significantly impact human health and daily productivity. By analyzing lifestyle, health, and sleep-related data, this project builds predictive models that identify patterns associated with sleep disorders.

The objective of this project is to apply data science methodologies including data preprocessing, exploratory data analysis, machine learning modeling, and visualization to better understand sleep-related health conditions.

---

## Dataset
The dataset contains various attributes related to a person's lifestyle, health condition, and sleep habits.

### Key Features
- Age
- Gender
- Occupation
- Sleep Duration
- Quality of Sleep
- Physical Activity Level
- Stress Level
- BMI Category
- Blood Pressure
- Heart Rate
- Daily Steps
- Sleep Disorder (Target Variable)

---

## Project Workflow

### 1. Data Collection
The dataset was collected and stored in CSV format for analysis.

### 2. Data Cleaning
- Handling missing values
- Removing duplicate records
- Data formatting and transformation

### 3. Exploratory Data Analysis (EDA)
Data visualization and statistical analysis were performed to identify relationships between lifestyle factors and sleep disorders.

### 4. Feature Engineering
Relevant features were selected and categorical variables were encoded to prepare the dataset for machine learning models.

### 5. Machine Learning Models
Several machine learning algorithms were implemented and compared:

- Logistic Regression
- Decision Tree
- Random Forest

### 6. Model Evaluation
The models were evaluated using performance metrics such as:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

### 7. Data Visualization Dashboard
A Power BI dashboard was created to visualize important insights from the dataset, including:

- Sleep disorder distribution
- Occupation vs sleep disorder
- Stress level impact on sleep
- Sleep duration analysis
- Lifestyle vs sleep patterns

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Power BI
- Jupyter Notebook

---

## Project Structure

Predicting-Sleep-Disorders/

dataset/  
└── sleep_dataset.csv  

notebooks/  
└── sleep_analysis.ipynb  

models/  
└── trained_models.pkl  

dashboard/  
└── sleep_dashboard.pbix  

README.md

---

## Results
The machine learning models were able to identify patterns between lifestyle habits and sleep disorders. Among the tested models, Random Forest produced better predictive performance compared to other models.

---

## Future Improvements
- Hyperparameter tuning for better accuracy
- Implementation of deep learning models
- Using larger and more diverse datasets
- Building a real-time sleep disorder prediction system

---

