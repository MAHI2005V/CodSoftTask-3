## 💳 Credit Card Fraud Detection – CodSoft Internship


---

## 📌 Project Overview

This project is a part of my **Data Science Internship with CodSoft**, focused on detecting fraudulent transactions using machine learning techniques.
The dataset is highly imbalanced, and the objective was to identify rare fraudulent transactions from genuine ones with maximum accuracy and minimal false alarms.

---

## 🎯 Objective

To build and evaluate a classification model that can accurately detect **fraudulent credit card transactions** based on features derived from real-world anonymized credit card transaction data.

---

## 🛠️ Tools & Libraries Used

* `Python`
* `Pandas`, `NumPy`
* `Matplotlib`, `Seaborn`
* `scikit-learn` (Logistic Regression, train\_test\_split, SMOTE, confusion\_matrix, classification\_report, etc.)

---

## 📊 Model Pipeline

| Step                  | Description                                                         |
| --------------------- | ------------------------------------------------------------------- |
| ✅ Data Exploration    | Checked dataset structure and class imbalance                       |
| 🧹 Data Preprocessing | No nulls, normalization where needed                                |
| ⚖️ Class Imbalance    | Handled using **SMOTE (Synthetic Minority Oversampling Technique)** |
| 🔀 Data Splitting     | `train_test_split()` with `stratify=y` for balanced test sets       |
| 🧠 Model Used         | `LogisticRegression()`                                              |
| 📈 Evaluation         | Confusion Matrix, Precision, Recall, F1-score                       |

---

## 📌 Results

* ✅ **No null values** in dataset
* ⚠️ **Heavily imbalanced** classes (Genuine ≫ Fraudulent)
* ✔️ Model trained with **oversampling using SMOTE**
* 🎯 **Evaluation Metrics**:

  * **Precision**: High precision to reduce false positives
  * **Recall**: Carefully balanced to catch most frauds
  * **F1-score**: Balanced score considering both precision & recall
* 🔥 **Confusion Matrix Heatmap**: Custom color-coded for better visualization

---

## 📁 File Structure

📦credit-card-fraud-detection
┣ 📄 fraud\_detection.ipynb # Jupyter Notebook
┣ 📄 README.md # Project summary and documentation

---

## 🔗 Links

* 📂 View Notebook on GitHub : https://github.com/MAHI2005V/CodSoftTask-3/blob/main/credit-card-fraud-detection-checkpoint.ipynb
* 💼 Connect on LinkedIn : www.linkedin.com/in/maheshwari-d-378aab325

---

## 💡 Learnings

This project deepened my understanding of:

* Real-world class imbalance in financial datasets
* The importance of using **recall over accuracy** in fraud detection
* How **SMOTE** can improve minority class performance
* Evaluation with confusion matrix and classification report
* How to build practical fraud detection systems using supervised learning

---

### 🏷️ Tags

\#CreditCardFraud #MachineLearning #FraudDetection #SMOTE #LogisticRegression #DataScience #Python #MLProjects #CodSoftInternship #CodSoftTasks

---
