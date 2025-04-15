# 🔥 Algerian Forest Fire Prediction

A machine learning project to predict the occurrence of forest fires in the Algerian region based on meteorological and environmental data.

## 📌 Overview

Forest fires pose serious threats to biodiversity, air quality, and human life. This project utilizes the **Algerian Forest Fires Dataset** to build a classification model that can predict whether a fire will occur on a given day.

The end goal is to aid in early fire detection and prevention efforts using data-driven techniques.

---
## 🧠 Technologies Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Streamlit (for web app)
- Jupyter Notebook

---

## 📊 Dataset Description

The dataset includes observations from two Algerian regions: **Bejaia** and **Sidi Bel-Abbes**. Each data point contains:

- Meteorological indices: FFMC, DMC, DC, ISI
- Weather features: Temperature, RH (Relative Humidity), Wind, Rain
- Target variable: `Fire` (Yes/No or 1/0)

Source: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Algerian+Forest+Fires+Dataset+)

---

## 🚀 Workflow

1. **Data Preprocessing**
   - Merging regional data
   - Handling null/missing values
   - Encoding categorical features

2. **Exploratory Data Analysis (EDA)**
   - Feature correlation
   - Visualizations for trends and patterns

3. **Model Training**
   - Algorithms: Logistic Regression, Random Forest, SVM, etc.
   - Model tuning & cross-validation

4. **Evaluation**
   - Accuracy, Precision, Recall, F1-score
   - Confusion Matrix and ROC Curve

5. **Deployment**
   - Built a simple UI using Streamlit for predictions based on user input

---

## 🖥️ How to Run Locally

1. Clone the repo:
   ```bash
   git clone https://github.com/surya53038/algerian-forest-fire-prediction.git
   cd algerian-forest-fire-prediction

