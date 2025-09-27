🌊 Flood Risk Classifier
📌 Project Overview

Flooding is one of the most destructive natural disasters, affecting millions of people each year.
This project aims to predict flood risk in districts using weather and geographic data.
By leveraging machine learning models such as Logistic Regression, Random Forest, and XGBoost,
we classify areas into risk levels (e.g., Low, Medium, High).

The goal is to help in disaster preparedness and resource allocation.

🎯 Objectives

Combine datasets (rainfall, elevation, river proximity, etc.).

Clean and preprocess data for modeling.

Train multiple classification models.

Evaluate using metrics: Accuracy, Precision, Recall, F1-score.

Identify top contributing features to flood risk.

Provide visualizations of risk distribution.

1. Data Collection

Datasets include rainfall, river proximity, soil type, land use, and elevation.

Target variable: Flood Risk Level (Low, Medium, High).

2. Data Preprocessing

Handle missing values.

Encode categorical variables using LabelEncoder.

Normalize/scale numerical features if necessary.

Split dataset into Train (80%) and Test (20%).

3. Model Training

We trained multiple models for comparison:

Logistic Regression – baseline linear model.

Random Forest – ensemble of decision trees.

XGBoost – gradient boosting model (final best-performing).

4. Model Evaluation

Metrics: Accuracy, Precision, Recall, F1-score.

Confusion Matrix to visualize predictions.

Feature Importance to identify key contributors (e.g., rainfall, river distance).

5. Results & Insights

XGBoost outperformed other models with the highest accuracy.

Rainfall and river proximity were the most influential features.

Predictions can help authorities focus on high-risk zones for better disaster management.

📊 Visualizations

Confusion matrix for classification performance.

Feature importance bar chart.

Flood risk distribution across regions.
