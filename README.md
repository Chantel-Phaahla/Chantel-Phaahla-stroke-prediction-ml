# Chantel-Phaahla-stroke-prediction-ml
 Stroke Prediction (Group Project)
This repository contains a machine learning group project focused on predicting stroke risk using clinical and demographic patient data. The project includes data preprocessing, exploratory data analysis, supervised machine learning models, and unsupervised clustering for patient segmentation.

Dataset source: Kaggle Stroke Prediction Dataset

📌 Project Objectives
Build predictive models to classify stroke occurrence.
Explore important features influencing stroke risk.
Apply unsupervised learning (K-Means) to discover natural patient groupings.
My main role in this project was implementing K-Means clustering to segment patients into distinct health-based groups.

Used StandardScaler to scale numerical features for distance-based clustering.
Applied the Elbow Method to determine the optimal number of clusters (k = 4).
Assigned cluster labels to patients and analysed cluster distribution.
Visualised clusters using:
Scatter plots (Age vs Glucose, BMI vs Glucose, Age vs BMI)
PCA (2D projection) for dimensionality reduction and cluster validation
Performed basic cluster interpretation to identify common patient patterns.
⚙️ Technologies Used
Python
Pandas, NumPy  

Scikit-learn
Matplotlib, Seaborn
Yellowbrick (Elbow Method)
PCA (Dimensionality Reduction)

🚀 How to Run Install requirement:

1.pip install -r requirements.txt

2.Launch Jupyter Notebook:

python -m notebook

3.Open the notebooks/ folder and run the clustering/modelling notebook.

📊 Results Summary
K-Means clustering identified 4 distinct patient groups
PCA visualisation showed clear cluster separation
Avg glucose level contributed strongly to cluster segmentation

👥 Team Project Note
This is a group project .This repository highlights the overall project, while emphasising my personal contribution to the clustering analysis.
