# ❤️ Heart Disease Prediction using Machine Learning

This project analyzes health survey data from the [Heart Disease Health Indicators dataset](https://www.kaggle.com/datasets/alexteboul/heart-disease-health-indicators-dataset) to predict the likelihood of heart disease.

The notebook walks through **data preprocessing**, **exploratory data analysis**, and **training multiple classification models** including:
- Logistic Regression
- Random Forest
- XGBoost
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Decision Tree
- Gaussian Naive Bayes

Model performance is evaluated using:
- Accuracy
- ROC-AUC
- Confusion Matrix
- Classification Report

## 📂 Files
- **Heart_Diseases_project_V_01.ipynb** — Main Jupyter Notebook with data exploration, preprocessing, model training, and evaluation.
- **heart_disease_health_indicators.csv** — Dataset file (download from Kaggle and place in this folder).
- **requirements.txt** — Python dependencies.
- **README.md** — Project description and usage.

## ▶️ How to Run
1. Download the dataset from Kaggle and save it as `heart_disease_health_indicators.csv` in this folder.
2. Install the dependencies:
```bash
pip install -r requirements.txt
```
3. Open the notebook:
```bash
jupyter notebook Heart_Diseases_project_V_01.ipynb
```
4. Run all cells to reproduce the analysis.

## 🙌 Acknowledgements
- Kaggle dataset by Alex Teboul
- scikit-learn, XGBoost, pandas, matplotlib, seaborn
