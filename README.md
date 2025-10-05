# Project-Rosetta
Project Rosetta was developed for the NASA Space Apps Challenge 2025 under the theme “A World Away: Hunting for Exoplanets with AI.”

Our goal of this project is to automate exoplanet detection using NASA’s open datasets (Kepler KOI, TESS TOI). By leveraging Machine Learning ensembles, we classify planetary candidates, confirmed planets, and false positives which will help reduce the reliance on manual vetting and accelerating discoveries.

<img width="1920" height="1080" alt="NSAC" src="https://github.com/user-attachments/assets/3be8a1c7-2ab9-4607-a160-368efc228a5e" />
Fig: Identifying Exoplanets in Light Curves, Source: (Shallue & Vanderburg 2018)
      
🎯 Objectives
Train AI/ML models on Kepler KOI dataset, validate generalization on TESS TOI.
Handle extreme class imbalance in exoplanet data.
Provide a user interface for researchers and enthusiasts to test data.
Deliver explainable AI (feature importance, SHAP values) for transparency.

📂 Data Sources
Kepler Objects of Interest (KOI)
TESS Objects of Interest (TOI)
NASA Exoplanet Archive – Open data of confirmed exoplanets, candidates, and false positives.

🧠 Methodology
-- Data Preprocessing --
Feature scaling & normalization.
Balanced datasets using SMOTE oversampling.
-- Models Implemented --
Baseline: Logistic Regression, KNN.
Ensembles: Random Forest, XGBoost.
Final: Stacking Ensemble (RF + XGB + Logistic Regression meta-learner) → best performance.
-- Evaluation Metrics --
Accuracy, Precision, Recall, F1-Score.
Confusion Matrix, ROC & Precision-Recall curves.

🖥️ Features
Dashboard for data visualization and user testing.
Upload option → test new data samples on trained model.
Model explainability → feature importance & SHAP values.
Metrics visualization → confusion matrix, ROC, PR curves.

⚙️ Tech Stack
Languages: Python
Libraries: scikit-learn, XGBoost, imbalanced-learn, seaborn, matplotlib
Data: NASA Kepler KOI, TESS TOI

✨ “Project Rosetta — Decoding hidden worlds beyond our solar system.”

