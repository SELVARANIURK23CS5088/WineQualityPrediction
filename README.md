# 🍷 Wine Quality Prediction

This project uses machine learning techniques to predict the quality of wine based on physicochemical tests. The dataset is sourced from Kaggle and includes features such as acidity, alcohol content, and pH.

---

## 📌 Project Overview

- **Goal**: Predict wine quality scores (0–10) using chemical properties.
- **Techniques Used**: Data cleaning, exploratory data analysis (EDA), feature scaling, and classification algorithms.
- **Models Applied**:
  - Random Forest Classifier
  - Stochastic Gradient Descent (SGD)
  - Support Vector Classifier (SVC)

---

## 📁 Dataset

- **Source**: [Kaggle - Wine Quality Dataset (Red & White)](https://www.kaggle.com/datasets/ruthgn/wine-quality-data-set-red-white-wine)
- **Files Used**: `winequality-red.csv`
- **Features**:
  - Fixed acidity, Volatile acidity, Citric acid, Residual sugar, Chlorides
  - Free sulfur dioxide, Total sulfur dioxide, Density, pH, Sulphates, Alcohol
- **Target**:
  - `quality` (score from 0 to 10)

---

## 🧪 Libraries Used

```python
pandas
numpy
matplotlib
seaborn
scikit-learn
📊 Exploratory Data Analysis
Missing values checked and handled

Heatmap of correlations between features

Distribution plots of wine quality

Feature importance explored via Random Forest

🔍 Model Training & Evaluation
Model	Accuracy (example)
Random Forest	~71%
SGD Classifier	~63%
SVC	~65%

Metrics used:

Accuracy

Classification report (Precision, Recall, F1-score)

Confusion matrix

📈 Visualizations
Bar chart of wine quality distribution

Correlation heatmap of features

Confusion matrices for each model

✅ Insights
Alcohol and volatile acidity are highly influential features.

Wines with higher alcohol and lower volatile acidity tend to get higher quality ratings.

Random Forest performs the best in this classification task.


🚀 How to Run
Download the dataset from Kaggle.

Clone this repository or download the notebook.

Place winequality-red.csv in the same directory as the notebook.

Run all cells in Jupyter Notebook or Google Colab.
