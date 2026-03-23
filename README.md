# Heart-Disease-Prediction
Heart Disease Prediction Using KNN Algorithm

# ❤️ Heart Disease Prediction using KNN Classifier

## 📌 Project Overview

This project focuses on predicting the presence of heart disease using a **K-Nearest Neighbors (KNN)** machine learning algorithm. The goal is to analyze patient health data and identify patterns that can help in early detection of heart disease.

The project includes **data preprocessing, feature scaling, model training, hyperparameter tuning, and data visualization** to extract meaningful insights.


## 📊 Dataset

* The dataset contains medical attributes such as:

  * Age
  * Sex
  * Chest Pain Type (`cp`)
  * Resting Blood Pressure (`trestbps`)
  * Cholesterol (`chol`)
  * Maximum Heart Rate (`thalach`)
  * And more...

* **Target Variable:**

  * `0` → No Heart Disease
  * `1` → Heart Disease


## ⚙️ Technologies Used

* Python 🐍
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn


## 🔍 Exploratory Data Analysis (EDA)

The following visualizations were used to understand the dataset:

* 📌 Correlation Heatmap → Identifies relationships between features
* 📌 Heart Disease Distribution → Checks class balance
* 📌 Gender vs Heart Disease → Compares disease occurrence by gender
* 📌 Cholesterol vs Heart Disease → Analyzes cholesterol impact
* 📌 Heart Disease Percentage by Age Group → Shows age-wise disease trend


## 🧠 Key Insights

* Heart disease is **not dependent on a single feature**, but a combination of multiple factors.
* **Age groups (40–70 years)** show higher occurrence of heart disease.
* **Males** have a higher number of heart disease cases in the dataset.
* **Cholesterol and blood pressure alone** are not strong predictors due to overlapping values.
* Features like **chest pain type and maximum heart rate** show stronger influence.


## 🔧 Data Preprocessing

* Checked for missing values
* Feature scaling applied:

  * **MinMaxScaler**
  * **StandardScaler**
* Data split into training and testing sets


## 🤖 Model Building

* Algorithm Used: **K-Nearest Neighbors (KNN)**
* Distance Metric:

  * Euclidean Distance (`p=2`)
  * Manhattan Distance (`p=1`)


## ⚡ Hyperparameter Tuning

* Applied:

  * **GridSearchCV**
  * **RandomizedSearchCV**

* Tuned Parameters:

  * `n_neighbors`
  * `p` (distance metric)


## 📈 Model Evaluation

The model was evaluated using:

* ✅ Accuracy Score
* ✅ Confusion Matrix
* ✅ Classification Report
* ✅ ROC-AUC Score


## 📊 Results

* Achieved good classification performance using KNN
* Hyperparameter tuning improved model accuracy
* ROC curve indicates good class separability


## 🚀 Conclusion

* KNN performs well for this dataset when proper scaling is applied
* Feature engineering and visualization helped in understanding data patterns
* Heart disease prediction requires multiple medical attributes rather than relying on a single factor



## 🙌 Author

**Mandar Borhade**

