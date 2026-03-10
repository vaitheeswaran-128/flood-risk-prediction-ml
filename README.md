# 🌊 Flood Risk Classifier

## 📌 Project Overview
Flooding is one of the most destructive natural disasters, affecting millions of people worldwide each year. Early identification of flood-prone areas can help governments and disaster management teams take preventive measures.

This project aims to predict **flood risk levels in different districts** using environmental and geographic data. By applying machine learning models such as **Logistic Regression, Random Forest, and XGBoost**, the system classifies regions into risk categories such as **Low, Medium, and High**.

The objective of this project is to support **disaster preparedness, risk assessment, and resource allocation** using data-driven insights.

---

## 🎯 Objectives
- Combine environmental datasets such as rainfall, elevation, and river proximity.
- Clean and preprocess the dataset for machine learning models.
- Train multiple classification models for flood risk prediction.
- Evaluate model performance using **Accuracy, Precision, Recall, and F1-score**.
- Identify important features influencing flood risk.
- Visualize prediction results and model performance.

---

## 📂 Dataset Information
The dataset contains environmental and geographic attributes that influence flooding.

Key features include:
- Rainfall
- River proximity
- Soil type
- Land use
- Elevation

The target variable is **Flood Risk Level**, categorized as:
- Low
- Medium
- High

---

## ⚙️ Project Workflow

### 1. Data Collection
Environmental and geographic datasets were collected including rainfall patterns, terrain elevation, river distance, soil conditions, and land usage data.

### 2. Data Preprocessing
Data preprocessing steps included:
- Handling missing values
- Encoding categorical variables using **LabelEncoder**
- Feature scaling for numerical attributes
- Splitting the dataset into **Training (80%)** and **Testing (20%)** sets

---

### 3. Model Training
Multiple machine learning models were trained and compared:

- **Logistic Regression** – baseline classification model
- **Random Forest** – ensemble model using multiple decision trees
- **XGBoost** – gradient boosting algorithm for improved performance

---

### 4. Model Evaluation
Models were evaluated using the following metrics:

- Accuracy
- Precision
- Recall
- F1-score

A **Confusion Matrix** was used to visualize the classification performance.

---

### 5. Results & Insights
Key findings from the analysis:

- **XGBoost achieved the best performance among all models**
- Rainfall and river proximity were identified as the most influential factors
- The model successfully classified regions into different flood risk levels

These insights can help authorities focus on **high-risk zones and improve disaster management strategies**.

---

## 📊 Visualizations
The project includes several visualizations to understand the dataset and model performance:

- Confusion Matrix for classification performance
- Feature importance charts
- Distribution plots of environmental factors

---

## 🛠 Tools & Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook

---

## 📌 Conclusion
This project demonstrates how machine learning can be applied to environmental data to predict flood risk levels. By analyzing important factors such as rainfall and river proximity, the model can identify regions that are more vulnerable to flooding.

Such predictive systems can support **disaster preparedness, urban planning, and resource allocation**, helping authorities take proactive measures to minimize flood damage.

---
