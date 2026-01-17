# 🪨 Rock vs 💣 Mine Prediction using Machine Learning

This project is a **binary classification machine learning system** that predicts whether an object detected by **SONAR signals** is a **Rock** or a **Mine**.
It uses **Logistic Regression** to learn patterns from numerical sonar frequency data and make accurate predictions.

The project demonstrates the **end-to-end machine learning workflow**, including data preprocessing, model training, evaluation, and prediction.

---

## 📌 Problem Statement

SONAR signals are used in underwater exploration to detect objects.
Based on the returned signal frequencies, the task is to classify the object as:

* **R** → Rock
* **M** → Mine

This is a classic **supervised learning classification problem** widely used to demonstrate ML fundamentals.

---

## 🚀 Features

* Loads and processes real-world sonar dataset
* Performs exploratory data analysis
* Splits data into training and testing sets
* Trains a **Logistic Regression** classifier
* Evaluates model accuracy on training and test data
* Predicts the class of a new, unseen sonar signal

---

## 🧠 Machine Learning Workflow

1. **Data Collection**

   * Sonar dataset with 60 numerical features per sample
   * Each row represents a sonar signal response

2. **Data Preprocessing**

   * Separation of features and labels
   * Statistical analysis and class distribution check

3. **Train-Test Split**

   * 90% training data
   * 10% testing data
   * Stratified split to preserve class balance

4. **Model Training**

   * Logistic Regression model trained on numerical features

5. **Model Evaluation**

   * Accuracy score calculated for:

     * Training data
     * Test data

6. **Prediction System**

   * Accepts new sonar signal input
   * Predicts whether the object is a Rock or Mine

---

## 🛠 Tech Stack Used

### Programming Language

* **Python 3**

### Libraries

* **NumPy** – Numerical computations
* **Pandas** – Data manipulation and analysis
* **Scikit-learn**

  * `LogisticRegression`
  * `train_test_split`
  * `accuracy_score`

### Tools

* Google Colab / Jupyter Notebook
* Git & GitHub

---

## 📊 Model Performance

* **Training Accuracy**: High accuracy indicating good learning
* **Test Accuracy**: Strong generalization on unseen data

*(Exact values depend on dataset split and random state)*

---

## ▶️ How to Run the Project

### 1️⃣ Install Dependencies

```bash
pip install numpy pandas scikit-learn
```

### 2️⃣ Run the Script

```bash
python rock_vs_mine_prediction.py
```

---

## 🧪 Example Prediction

```text
Input: Sonar signal values (60 frequency-based features)
Output: The object is a Rock / Mine
```

---

## 📈 Dataset Details

* **Features**: 60 numerical sonar signal attributes
* **Target Column**:

  * `R` → Rock
  * `M` → Mine
* Dataset commonly used for ML classification practice

---

## 🔮 Future Improvements

* Add feature scaling (StandardScaler)
* Compare with other classifiers (SVM, Random Forest)
* Add confusion matrix & classification report
* Convert to a Flask / FastAPI web app
* Deploy the model for real-time prediction

---

## 👨‍💻 Author

**Diganta Ghosh**
B.Tech – Computer Science Engineering (AI)
Aspiring Machine Learning & AI Engineer

---

