# 🚢 Titanic - Exploratory Data Analysis (EDA)

![Python](https://img.shields.io/badge/Python-3.x-blue?style=flat&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green?style=flat&logo=pandas)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-orange?style=flat)
![Google Colab](https://img.shields.io/badge/Google%20Colab-Notebook-yellow?style=flat&logo=googlecolab)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=flat)

---

## 📌 About This Project

This project performs an **Exploratory Data Analysis (EDA)** on the famous Titanic dataset.
The goal is to explore the data, clean it, and find out **what types of passengers were more likely to survive** the Titanic disaster using charts and visualizations.

> 🗓️ The RMS Titanic sank on **April 15, 1912** after hitting an iceberg.
> Out of 2,224 passengers and crew, only **710 people survived**.

---

## 🎯 Objectives

- Load and explore the Titanic dataset
- Find and fix missing values in the data
- Analyze survival rates based on gender, age, and passenger class
- Create charts and visualizations to show patterns in the data
- Draw meaningful conclusions from the analysis

---

## 📂 Dataset

| File | Description |
|------|-------------|
| `train.csv` | Main dataset with 891 passengers and survival info |
| `test.csv` | Test dataset with 418 passengers (no survival column) |

**Source:** [Titanic Dataset on GitHub](https://raw.githubusercontent.com/franklaercio/titanic_machine_learning/master/train.csv)

### 📋 Columns in the Dataset

| Column | Description |
|--------|-------------|
| `PassengerId` | Unique ID for each passenger |
| `Survived` | 0 = Did not survive, 1 = Survived |
| `Pclass` | Ticket class (1 = First, 2 = Second, 3 = Third) |
| `Name` | Full name of passenger |
| `Sex` | Gender of passenger |
| `Age` | Age of passenger |
| `SibSp` | Number of siblings or spouse on board |
| `Parch` | Number of parents or children on board |
| `Fare` | Ticket price paid |
| `Cabin` | Cabin number |
| `Embarked` | Port of boarding (S = Southampton, C = Cherbourg, Q = Queenstown) |

---

## 🛠️ Technologies Used

| Tool | Purpose |
|------|---------|
| **Python** | Main programming language |
| **Pandas** | Loading and cleaning the data |
| **NumPy** | Numerical calculations |
| **Matplotlib** | Creating charts and graphs |
| **Seaborn** | Advanced visualizations like heatmaps |
| **Scikit-learn** | Machine learning models (Decision Tree, Random Forest) |
| **Google Colab** | Cloud based notebook to run the project |

---

## 📊 Key Findings

- ✅ **Female passengers** had a survival rate of around **75%**
- ✅ **1st class passengers** had a **65% survival rate** vs only 24% for 3rd class
- ✅ **Children (under 18)** had a higher survival rate than adults
- ✅ **Age alone** did not strongly affect survival chances
- ✅ **Fare paid** was positively correlated with survival

---

## 📈 Visualizations in This Project

- 🥧 Pie chart — Overall survival rate
- 📊 Bar charts — Survival by gender and passenger class
- 📦 Box plots — Age distribution by gender
- 🔥 Heatmap — Correlation between all numeric columns
- 📉 Histogram — Age distribution of survivors vs non-survivors

---

## ▶️ How to Run This Project

### Option 1 — Open in Google Colab *(Recommended)*
1. Click the link below to open directly in Google Colab
2. Click **Runtime → Run All**
3. All charts and results will appear automatically ✅

### Option 2 — Run Locally
```bash
# 1. Clone this repository
git clone https://github.com/YOUR_USERNAME/titanic-eda.git

# 2. Install required libraries
pip install pandas numpy matplotlib seaborn scikit-learn

# 3. Open the notebook
jupyter notebook Titanic_EDA.ipynb
```

---

## 📁 Project Structure

```
titanic-eda/
│
├── Titanic_EDA.ipynb     ← Main notebook (open this in Colab)
├── README.md             ← You are reading this!
└── images/               ← Screenshots of charts (optional)
```

---

## 🙋 About Me

- 👨‍🎓 **Student:** [Nagajyothi Uppula]
- 🏫 **Course:** Computer Science and Engineering (Cyber Security)
- 📧 **Email:** [uppulanagajyothi@gmail.com]
- 🔗 **GitHub:** [https://github.com/Nagajyothiuppula]

---

## 📜 License

This project is for **educational purposes** as part of a university assignment.
Dataset credits go to [franklaercio](https://github.com/franklaercio/titanic_machine_learning).
