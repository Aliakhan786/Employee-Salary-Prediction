# 💼 Salary Prediction using Machine Learning

This project is a **machine learning-based classification system** that predicts whether an individual's income exceeds $50K/year using the **Adult Census Income dataset**. It demonstrates the complete ML pipeline including data cleaning, preprocessing, model training, and evaluation using Python and scikit-learn.

## 📌 Project Objective

To build a binary classification model that predicts whether a person earns `>50K` or `<=50K` annually based on demographic features.

---

## 🛠️ System Requirements

- OS: Windows / Linux / macOS  
- Python: 3.7 or above  
- RAM: Minimum 4 GB  
- Tools: Jupyter Notebook / VS Code / Google Colab

---

## 📚 Libraries Used

- `pandas` – Data manipulation  
- `numpy` – Numerical operations  
- `scikit-learn` – ML models & preprocessing (`LogisticRegression`, `RandomForestClassifier`, etc.)  
- `matplotlib` / `seaborn` – (Optional) Visualization  

---

## 🧩 Dataset Used

- **Adult Income Dataset** from UCI Machine Learning Repository
- Features include: `age`, `education`, `workclass`, `marital-status`, `occupation`, `hours-per-week`, etc.
- Target variable: `income` (`<=50K` or `>50K`)

---

## 🚀 Step-by-Step Procedure

1. **Import Libraries**: Load essential Python libraries.
2. **Load Dataset**: Read the dataset using `pandas`.
3. **Data Cleaning**: Handle missing values and drop irrelevant columns.
4. **Feature Engineering**: Encode categorical variables and scale numerical features.
5. **Modeling**:
   - Logistic Regression (baseline)
   - Random Forest Classifier (improved model)
6. **Pipeline**: Use `Pipeline` and `ColumnTransformer` for structured preprocessing.
7. **Evaluation**: Evaluate with accuracy score and classification report.

---

## 📈 Model Performance

- Baseline Model: **Logistic Regression**
- Improved Model: **Random Forest Classifier**
- Evaluation Metrics: **Accuracy**, **Precision**, **Recall**, **F1-Score**

---

## 📷 Sample Output Screenshots

#### ✅ Data Cleaning and Preprocessing
![Data Cleaning](screenshots/sample%20op1.png)

#### ✅ Model Performance Summary and Final Output
![Model Performance](screenshots/sample%20op2.png)


---

## Developed by Aaliya Khan 

