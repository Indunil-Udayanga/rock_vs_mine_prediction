# 🪨 Rock vs Mine Prediction using Machine Learning

This project predicts whether an object detected by SONAR is a **Rock** or a **Mine** using machine learning techniques.  
It is a **binary classification problem** solved using **Logistic Regression**.

---

## 📌 Problem Statement

Submarines use SONAR signals to detect objects underwater.  
Based on the reflected signals, the goal is to classify the object as:

- **Rock (R)**
- **Mine (M)**

Accurate classification is critical for naval safety and defense systems.

---

## 📊 Dataset Information

- Dataset: **SONAR Dataset**
- Total Samples: 208
- Features: 60 numerical attributes
- Target Labels:
  - `R` → Rock
  - `M` → Mine

Each feature represents the energy of the SONAR signal at a particular frequency.

---

## 🧠 Machine Learning Workflow

1. **Data Loading**
2. **Data Preprocessing**
   - Label encoding
   - Train-test split
3. **Model Training**
   - Logistic Regression
4. **Model Evaluation**
   - Accuracy score

---

## 🛠️ Technologies Used

- **Programming Language:** Python 🐍
- **Libraries:**
  - NumPy
  - Pandas
  - Scikit-learn

---

## 📈 Model Used

- **Logistic Regression**
  - Suitable for binary classification problems
  - Simple and effective baseline ML algorithm

---

## ✅ Results

- The trained model successfully classifies SONAR signals as Rock or Mine.
- Performance is evaluated using **accuracy score** on training and test data.

---

## ▶️ How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/machine-learning-projects.git
