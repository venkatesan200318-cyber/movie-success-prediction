# 🎬 IMDB Movie Success Prediction

## 📌 Project Overview

This project focuses on **predicting movie success** based on IMDB-related features such as budget, gross revenue, duration, number of user votes, and IMDB score. Movies are categorized into **Hit, Average, or Flop** classes using a supervised machine learning approach.

The notebook demonstrates a **complete end-to-end data science workflow**, including data preprocessing, exploratory data analysis (EDA), feature engineering, model building, and evaluation.

---

## 🎯 Objective

* Analyze IMDB movie data to understand factors influencing movie success
* Convert continuous IMDB scores into categorical success classes
* Build and evaluate machine learning models to classify movie success
* Provide insights useful for production houses and investors

---

## 🗂️ Dataset Description

The dataset contains movie-related attributes such as:

* `movie_title`
* `duration`
* `budget`
* `gross`
* `num_voted_users`
* `imdb_score` (Target for classification)

### 🎯 Target Variable

**IMDB Class** (derived from `imdb_score`):

* **Flop**: IMDB score between 1–3
* **Average**: IMDB score between 3–6
* **Hit**: IMDB score between 6–10

---

## 🔍 Project Workflow

### 1️⃣ Import Required Libraries

Essential Python libraries such as Pandas, NumPy, Matplotlib, Seaborn, and Scikit-learn are used for data handling, visualization, and modeling.

### 2️⃣ Target Variable Creation

* IMDB scores are binned into categorical classes using defined thresholds
* A new column `IMDB_Class` is created

### 3️⃣ Data Quality Checks

* Identification of missing values
* Detection of inconsistent data types

### 4️⃣ Data Cleaning

* Removal of duplicate records
* Handling missing values
* String cleanup for movie titles

### 5️⃣ Data Preprocessing

* Selection of relevant numerical features
* Scaling of numerical data where required
* Encoding of categorical target variable

### 6️⃣ Exploratory Data Analysis (EDA)

* Distribution analysis of numerical features
* Relationship between movie attributes and IMDB class
* Visualization using boxplots and histograms

### 7️⃣ Model Building

Machine learning models applied:

* Logistic Regression
* Random Forest Classifier

### 8️⃣ Model Evaluation

Evaluation metrics include:

* Accuracy Score
* Confusion Matrix
* Classification Report (Precision, Recall, F1-score)

---

## 📊 Results & Insights

* Random Forest performs better in handling non-linear relationships
* Budget, gross revenue, and number of user votes significantly influence movie success
* Class imbalance impacts prediction performance

---

## 🛠️ Technologies Used

* **Python**
* **Pandas & NumPy** – Data manipulation
* **Matplotlib & Seaborn** – Visualization
* **Scikit-learn** – Machine Learning models and evaluation
* **Jupyter Notebook** – Development environment

---

## ▶️ How to Run the Project

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/imdb-movie-success-prediction.git
   ```
2. Navigate to the project directory
3. Open the Jupyter Notebook:

   ```bash
   jupyter notebook
   ```
4. Run cells step-by-step in the notebook

---

## 📁 Repository Structure

```
├── IMDB_Movie_Success_Prediction.ipynb
├── README.md
└── dataset.csv
```

---

## 🚀 Future Improvements

* Handle class imbalance using SMOTE
* Try advanced models (XGBoost, Gradient Boosting)
* Hyperparameter tuning
* Deploy model using Flask or Streamlit

---

## 👤 Author

**Venkatesan**
Aspiring Data Scientist

---

## 📄 License

This project is for educational purposes.

---

⭐ *If you find this project useful, consider giving it a star on GitHub!*
