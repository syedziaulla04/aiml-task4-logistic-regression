# 🧠 AI & ML Internship – Task 4  
## Binary Classification using Logistic Regression

---

## 📌 Objective
The objective of this task is to build a **binary classification model** using Logistic Regression to predict whether a tumor is **Malignant (Cancerous)** or **Benign (Non-Cancerous)**.

---

## 📂 Dataset
The project uses the **Breast Cancer Wisconsin Dataset**.

- Target Variable: `diagnosis`
  - M → Malignant (1)
  - B → Benign (0)
- Total Features: 30 numerical features
- Total Samples: 569

---

## 🛠 Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## 🔄 Project Workflow

### 1️⃣ Data Preprocessing
- Removed unnecessary columns (`id`, `Unnamed: 32`)
- Converted categorical target values to numerical (M → 1, B → 0)

### 2️⃣ Train-Test Split
- 80% Training Data
- 20% Testing Data

### 3️⃣ Feature Scaling
- Applied `StandardScaler` to standardize features

### 4️⃣ Model Training
- Used Logistic Regression from Scikit-learn
- Set `max_iter=1000` to ensure convergence

### 5️⃣ Model Evaluation
The model was evaluated using:
- Confusion Matrix
- Accuracy
- Precision
- Recall
- ROC-AUC Score
- ROC Curve Visualization

### 6️⃣ Threshold Tuning
- Adjusted classification threshold to analyze performance changes

### 7️⃣ Sigmoid Function
Logistic Regression uses the sigmoid function:

σ(z) = 1 / (1 + e^(-z))

The sigmoid function converts linear outputs into probability values between 0 and 1.

---

## 📊 Model Performance

- **Accuracy:** 97.37%
- **Confusion Matrix:**

