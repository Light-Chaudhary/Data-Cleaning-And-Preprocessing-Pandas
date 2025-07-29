# 🧼 Titanic Data Cleaning with Pandas

This project demonstrates how to clean and preprocess the Titanic dataset using Python and Pandas. It focuses on preparing real-world data for analysis and machine learning by handling missing values, transforming features, and improving data quality.

---

## 📁 Dataset

- Source: [Titanic dataset](https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv)
- Format: CSV

---

## ✅ Tasks Performed

1. **Load the dataset** using `pandas.read_csv()`.
2. **Identify and handle missing values**:
   - Dropped rows with missing `Age` or `Embarked`.
   - Filled missing `Cabin` with `"Unknown"`.
3. **Feature cleaning and transformation**:
   - Converted `Name` to lowercase.
   - Extracted `Last_Name` from `Name`.
   - Mapped `Sex`: `'male' → 0`, `'female' → 1`.
   - Replaced `Embarked` codes with full port names.
4. **Feature engineering**:
   - Created a new column `Is_child` → `1 if Age < 18`, else `0`.
5. **Converted data types**:
   - Converted `Survived` to string.
   - Converted `Fare` to integer.
6. **Removed duplicate rows**.

---

## 📊 Output

- Cleaned and preprocessed Titanic dataset ready for analysis or modeling.
- All major issues like missing values, inconsistent formatting, and categorical encoding have been addressed.

---

## 🚀 Tools Used

- Python 3.x
- Pandas
- Jupyter Notebook / Anaconda

---

## 📌 Future Work

- Data visualization (with seaborn/matplotlib)
- Feature selection
- Predictive modeling (e.g., logistic regression or random forest)

---

## 📸 Preview

_See screenshots of the code and output in the `/images` folder or on [LinkedIn](https://linkedin.com/in/yourprofile)._  
