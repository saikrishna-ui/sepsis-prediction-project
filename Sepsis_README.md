# 🧠 Sepsis Prediction Using ICU Data

This project uses machine learning to predict sepsis using ICU patient data. Built as a follow-up to Stanford’s “Machine Learning for Healthcare” course.

## 🧪 What’s Inside
- Data cleaning and feature selection from a large ICU dataset
- Logistic regression model for binary classification (Sepsis / No Sepsis)
- Model evaluation using precision, recall, f1-score
- Model saved as `.pkl` file for reuse

## 📊 Dataset
- MIMIC-based patient data (simulated ICU data from a Kaggle dataset)
- Over 1.5 million records and 44 features
- Features include heart rate, oxygen saturation, blood pressure, and more
 ⚠️ The original `Sepsis.csv` file is too large to upload to GitHub (over 100MB).

You can download the dataset manually from the kaggle:  
🔗(https://www.kaggle.com/datasets/salikhussaini49/prediction-of-sepsis)

## 💡 Outcome
- Achieved 74% accuracy
- Precision for Sepsis class: 0.04 (due to data imbalance)
- Explored correlation heatmaps and classification reports

## 📁 Files
- `sepsis_prediction.ipynb` → the full code notebook
- `sepsis_prediction_model.pkl` → saved model
- `README.md` → this file

## 🛠️ Tools Used
- Python, Pandas, Seaborn, scikit-learn, Matplotlib

## 🔗 Author
Sai Krishna Prasad Vibudi — Master's Student in Business Analytics at UNT  
(https://www.linkedin.com/in/sai-krishna-prasad-vibudi-5a0227211/)
