# Student Pass Prediction

This project predicts whether a student will **pass or fail** using a **Logistic Regression** machine learning model based on academic and lifestyle features.

---

## Features Used
- **Study Hours** – Number of hours the student studies
- **Attendance** – Attendance percentage
- **Past Score** – Previous exam score
- **Sleep Hours** – Average daily sleep hours

---

## Dataset
- File: `ML prac - Sheet1.csv`  
- Contains the columns mentioned above plus the target column **Passed** (0 = Fail, 1 = Pass)  
- This dataset is **synthetic / sample data** for educational purposes  

---

## How It Works
1. Features are scaled using **StandardScaler**  
2. Logistic Regression model is trained using **scikit-learn**  
3. Model predicts whether a student will pass or fail based on input values  

---

## How to Run
1. Make sure you have Python installed (version 3.7+)  
2. Install required libraries if not already installed:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
