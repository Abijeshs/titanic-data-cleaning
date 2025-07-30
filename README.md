
# Titanic Data Cleaning

This project demonstrates how to clean and preprocess real-world data using the famous Titanic dataset. It focuses on handling missing values, encoding categorical variables, feature engineering, and preparing the dataset for further analysis or modeling using Python libraries **Pandas** and **NumPy**.

---

## 📂 Dataset

- Source: [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data)
- File Used: `train.csv`

---

## 🧹 Cleaning Steps Performed

- Loaded and explored the dataset
- Handled missing values (`Age`, `Embarked`, dropped `Cabin`)
- Dropped irrelevant columns (`PassengerId`, `Ticket`, `Name`)
- Encoded categorical features (`Sex`, `Embarked`)
- Created new features (`FamilySize`, `IsAlone`)
- Removed duplicate entries
- Saved the cleaned dataset as `cleaned_titanic.csv`

---

## 📦 Libraries Used

- `pandas`
- `numpy`

---

## 🧠 Skills Practiced

- Data inspection and summarization
- Null value handling
- Data type conversion
- Categorical encoding
- Feature engineering
- Dataset export and cleanup

---

## 📁 Project Structure

```
titanic-data-cleaning/
├── train.csv                # Raw dataset from Kaggle
├── cleaned_titanic.csv      # Cleaned output dataset
└── titanic_cleaning.ipynb   # Data cleaning notebook
```

---

## ✅ How to Run

1. Clone this repo:
   ```
   git clone https://github.com/your-username/titanic-data-cleaning.git
   ```
2. Open the notebook:
   ```
   titanic_cleaning.ipynb
   ```
3. Run all cells to clean the data and generate `cleaned_titanic.csv`.

---

## 📌 Future Improvements

- Add data visualizations (using Seaborn, Matplotlib)
- Build a logistic regression model to predict survival
- Deploy using Streamlit or Flask

---

## 🔗 Related Resources

- [Kaggle Titanic Competition](https://www.kaggle.com/c/titanic)
- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [NumPy Documentation](https://numpy.org/doc/)
