# 🍷 Wine Quality Prediction using Machine Learning

## 📌 Project Overview

This project focuses on predicting the quality of red wine using Machine Learning classification algorithms. The prediction is based on the physicochemical properties of wine such as acidity, density, alcohol content, pH, sulphates, and more.

The project includes Exploratory Data Analysis (EDA), feature engineering, model training, performance evaluation, and comparison of three classification models to identify the best-performing algorithm.

---

## 🎯 Objective

- Analyze the Wine Quality dataset.
- Perform data preprocessing and exploratory data analysis.
- Handle class imbalance through feature engineering.
- Train multiple machine learning classification models.
- Compare model performance.
- Identify the most important features affecting wine quality.

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📂 Dataset

**Dataset:** Wine Quality Dataset (Red Wine)

- Source: UCI Machine Learning Repository
- Records: **1,599**
- Features: **11**
- Target Variable: **Quality**

Features include:

- Fixed Acidity
- Volatile Acidity
- Citric Acid
- Residual Sugar
- Chlorides
- Free Sulfur Dioxide
- Total Sulfur Dioxide
- Density
- pH
- Sulphates
- Alcohol

Target:

- Quality Score

---

## 📊 Exploratory Data Analysis (EDA)

The following analyses were performed:

- Dataset overview
- Missing value analysis
- Duplicate value check
- Class distribution visualization
- Distribution plots for all features
- Correlation heatmap
- Class imbalance analysis

---

## ⚙️ Feature Engineering

The original quality scores were converted into binary classes:

- **0 → Bad Quality Wine**
- **1 → Good Quality Wine (Quality ≥ 7)**

This simplifies the prediction task and improves model performance.

---

## 🤖 Machine Learning Models

Three classification algorithms were implemented:

1. Random Forest Classifier
2. Stochastic Gradient Descent (SGD) Classifier
3. Support Vector Classifier (SVC)

---

## 📈 Model Evaluation

Each model was evaluated using:

- Accuracy Score
- Classification Report
- Confusion Matrix

Additionally,

- Random Forest Feature Importance
- Model Accuracy Comparison Table
- Accuracy Comparison Bar Chart

were generated.

---

## 📊 Results

The performance of all three models was compared.

The Random Forest Classifier achieved the best overall performance and demonstrated strong predictive capability for wine quality classification.

---

## 💡 Key Insights

- Alcohol content is one of the strongest predictors of wine quality.
- Sulphates and volatile acidity also significantly influence wine quality.
- The dataset is imbalanced, with most samples belonging to the medium-quality category.
- Stratified train-test splitting preserved class distribution during model training.

---

## ✅ Conclusion

- Successfully completed data preprocessing and exploratory analysis.
- Built and compared three classification models.
- Random Forest outperformed SGD and SVC in overall performance.
- Feature importance analysis provided valuable insights into the factors affecting wine quality.

---

## 🚀 Future Improvements

- Apply GridSearchCV for hyperparameter tuning.
- Perform K-Fold Cross Validation.
- Use advanced boosting algorithms like XGBoost or LightGBM.
- Predict original multiclass quality scores instead of binary labels.
- Deploy the model using Flask, FastAPI, or Streamlit.

---

## 📁 Project Structure

```
Wine_Quality_Prediction/
│
├── Wine_Quality_Prediction.ipynb
├── winequality-red.csv
├── README.md
└── requirements.txt
```

---

## ▶️ How to Run

1. Clone the repository.

```
git clone <repository-url>
```

2. Install the required libraries.

```
pip install -r requirements.txt
```

3. Open Jupyter Notebook.

```
jupyter notebook
```

4. Run all cells in **Wine_Quality_Prediction.ipynb**.

---

## 📌 Libraries Required

```
pandas
numpy
matplotlib
seaborn
scikit-learn
jupyter
```

---

## 👩‍💻 Author

**Boyapati Sathwika**

Artificial Intelligence & Data Science Student

---