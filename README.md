# 🎓 Predicting Student Performance

## 🏫 Shri Ramswaroop Memorial University

**Submitted by:**
- **Ranvijay Singh** (Roll No: 202210101150050)  
- **Mohd Shadan** (Roll No: 202210101150034)

---

## 📘 Overview
This project aims to **predict student academic performance** using demographic, social, and academic factors.  
By applying machine learning techniques, we explore which variables most strongly influence a student’s final grade.  
The dataset is based on student data from a Portuguese secondary school (UCI Machine Learning Repository).

---

## 🧠 Objectives
- Analyze and understand factors affecting student grades  
- Build predictive models using **Linear Regression** and **Random Forest Regression**  
- Evaluate model performance using standard regression metrics  
- Visualize relationships and insights for better interpretability  
- Generate an **automated PDF report** summarizing findings  

---

## ⚙️ Technologies Used
- **Python 3**
- **Google Colab / Jupyter Notebook**
- **Libraries:**
  - pandas  
  - numpy  
  - scikit-learn  
  - matplotlib  
  - seaborn  
  - fpdf  

---

## 📂 Project Structure

---

## 🚀 Steps Followed

### Step 1: Data Loading & Exploration
- Loaded dataset (`student-mat.csv`)
- Explored numerical and categorical features
- Checked for null values and data consistency

### Step 2: Preprocessing
- Encoded categorical variables using `OneHotEncoder`
- Scaled numeric features with `StandardScaler`
- Used `ColumnTransformer` for a clean preprocessing pipeline

### Step 3: Model Training
- Built two models:
  - **Linear Regression**
  - **Random Forest Regression**
- Trained on 80% of the dataset and tested on 20%

### Step 4: Evaluation
- Evaluated using:
  - **RMSE (Root Mean Squared Error)**
  - **MAE (Mean Absolute Error)**
  - **R² Score**
- Compared results between both models

### Step 5: Visualization
- Created plots for:
  - Feature Importance (Random Forest)
  - Predicted vs Actual values
  - Error Distribution

### Step 6: Report Generation
- Automatically generated a detailed **PDF report** (`Student_Performance_Report.pdf`)
- Included model metrics, insights, and key features

---

## 📊 Results Summary

| Model | RMSE | MAE | R² |
|:------|------:|------:|------:|
| Linear Regression | *(see notebook output)* | *(see notebook output)* | *(see notebook output)* |
| Random Forest     | *(see notebook output)* | *(see notebook output)* | *(see notebook output)* |

> ✅ The **Random Forest model** outperformed Linear Regression, providing better accuracy and generalization.

---

## 🌟 Key Insights
- **Study time**, **failures**, and **absences** strongly affect student grades  
- **Parental education** and **family support** correlate with higher performance  
- **Random Forest** offers reliable predictions and interpretable feature importance  

---

## 🏁 Conclusion
This project demonstrates how **machine learning** can be used to predict academic outcomes and identify students who may need additional support.  
By leveraging data-driven insights, educators can focus on factors that truly impact learning performance.

---

## 📈 How to Run
1. Open the notebook in [Google Colab](https://colab.research.google.com/).  
2. Upload the dataset `student-mat.csv`.  
3. Run all cells in order.  
4. The notebook will automatically:
   - Train models  
   - Show evaluation metrics  
   - Generate the final **PDF report**

---

## 👨‍💻 Authors
- **Ranvijay Singh** (Roll No: 202210101150050)  
- **Mohd Shadan** (Roll No: 202210101150034)  

**Department of Computer Science & Engineering**  
**Shri Ramswaroop Memorial University**

---


---

## 🧾 Acknowledgements
- Dataset Source: [UCI Machine Learning Repository – Student Performance Data Set](https://archive.ics.uci.edu/ml/datasets/Student+Performance)
- Tools: Google Colab, Python, scikit-learn, matplotlib, seaborn

