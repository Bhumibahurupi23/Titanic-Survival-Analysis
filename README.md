# 🚢 Titanic Survival Analysis using Python, Machine Learning & Power BI

## 📌 Project Overview

This project analyzes the famous Titanic dataset to identify the factors that influenced passenger survival. The project combines Exploratory Data Analysis (EDA), statistical analysis, machine learning, and an interactive Power BI dashboard to derive meaningful insights from the data.

The objective is to understand passenger demographics, discover survival patterns, build predictive models, and present the findings through a professional business intelligence dashboard.

---

## 🎯 Objectives

- Perform Exploratory Data Analysis (EDA)
- Clean and preprocess the dataset
- Handle missing values
- Apply feature engineering
- Train and evaluate Machine Learning models
- Compare model performance
- Build an interactive Power BI dashboard
- Present business insights through visualizations

---

## 📂 Dataset

Dataset Source:
- Kaggle Titanic Dataset

Files Used:
- `train.csv`
- `test.csv`

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- Power BI

---

## 📊 Exploratory Data Analysis

The analysis includes:

- Dataset inspection
- Missing value analysis
- Survival count analysis
- Survival by gender
- Survival by passenger class
- Age distribution
- Fare distribution
- Embarked port analysis
- Family size analysis
- Correlation analysis

---

## 🧹 Data Preprocessing

The following preprocessing steps were performed:

- Removed Cabin column due to excessive missing values
- Filled missing Age values using Median
- Filled missing Embarked values using Mode
- Encoded categorical variables
- Created a new feature:
  - FamilySize = SibSp + Parch + 1

---

## 🤖 Machine Learning Models

The following classification models were implemented:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

Models were evaluated using:

- Accuracy
- Confusion Matrix
- Classification Report
- Precision
- Recall
- F1 Score

---

## 📈 Model Performance

| Model | Accuracy |
|--------|----------|
| Logistic Regression | 81% |
| Decision Tree | *(Update with your result)* |
| Random Forest | *(Update with your result)* |

---

## 📊 Power BI Dashboard

The dashboard provides an interactive overview of the Titanic dataset including:

- Total Passengers
- Total Survivors
- Total Deaths
- Survival Rate
- Average Age
- Average Fare
- Survival by Gender
- Survival by Passenger Class
- Family Size vs Survival
- Embarked vs Survival
- Interactive Filters

---

## 📷 Dashboard Preview

> Add a screenshot of your Power BI dashboard here.

Example:

```
screenshots/dashboard.png
```

After uploading the screenshot, display it like this:

```markdown
![Dashboard](screenshots/dashboard.png)
```

---

## 💡 Key Insights

- Female passengers had significantly higher survival rates than male passengers.
- First-class passengers were more likely to survive than lower-class passengers.
- Passenger class strongly influenced survival probability.
- Most passengers boarded from Southampton.
- Family size had an impact on survival patterns.

---

## 📁 Project Structure

```
Titanic-Survival-Analysis/
│
├── data/
├── notebooks/
├── dashboard/
├── screenshots/
├── README.md
├── requirements.txt
└── .gitignore
```

---

## 🚀 How to Run

1. Clone the repository

```bash
git clone https://github.com/yourusername/Titanic-Survival-Analysis.git
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Open the notebook

```
notebooks/Titanic_Survival_Analysis.ipynb
```

4. Open the Power BI dashboard

```
dashboard/Titanic_Survival_Dashboard.pbix
```

---

## 📌 Future Improvements

- Hyperparameter tuning
- Feature importance analysis
- Cross-validation
- Additional ML models
- Dashboard enhancements

---

## 👤 Author

**Bhumi Bahurupi**

GitHub: (https://github.com/Bhumibahurupi23)

---

⭐ If you found this project helpful, consider giving it a star!
