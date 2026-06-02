# 🚢 Titanic Data Analysis

![Python](https://img.shields.io/badge/Python-3.11-blue?style=for-the-badge&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Latest-green?style=for-the-badge&logo=pandas)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Latest-orange?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-Latest-red?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=for-the-badge)

> A complete exploratory data analysis (EDA) of the famous Titanic dataset — uncovering survival patterns based on gender, age, class, and fare.

---

## 📁 Project Structure

```
titanic-analysis/
│
├── Titanic-Dataset.csv       # Raw dataset
├── titanic_analysis.py       # Main analysis script
├── survival_analysis.png     # Survival charts
├── fare_class_analysis.png   # Fare & class charts
├── heatmap.png               # Correlation heatmap
└── README.md                 # Project documentation
```

---

## 📊 Analysis Overview

| # | Analysis | Description |
|---|----------|-------------|
| 1 | **Basic Info** | Shape, missing values, statistics |
| 2 | **Survival Analysis** | Survival by gender, age, and class |
| 3 | **Fare & Class** | Ticket price vs survival rate |
| 4 | **Correlation Heatmap** | Relationship between all features |
| 5 | **Key Insights** | Important survival statistics |

---

## 🔍 Key Findings

- 🚺 **Female survival rate** was much higher than male (~74% vs ~19%)
- 👑 **1st Class passengers** had the highest survival rate (~63%)
- 👶 **Children** had a better chance of survival than adults
- 💰 **Higher fare** passengers were more likely to survive
- 📉 **3rd Class passengers** had the lowest survival rate (~24%)

---

## 🛠️ Technologies Used

- **Python 3.11**
- **Pandas** — Data manipulation
- **Matplotlib** — Data visualization
- **Seaborn** — Statistical plots

---

## ⚙️ Installation & Setup

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/titanic-analysis.git
cd titanic-analysis
```

### 2. Install Required Libraries
```bash
pip install pandas matplotlib seaborn
```

### 3. Run the Analysis
```bash
python titanic_analysis.py
```

---

## 📈 Visualizations

### Survival Analysis
- Overall survival count
- Survival by gender
- Survival by passenger class
- Survival by age distribution

### Fare & Class Analysis
- Fare distribution by class (boxplot)
- Survival rate percentage by class

### Correlation Heatmap
- Relationship between all numerical features

---

## 📌 Dataset Info

| Column | Description |
|--------|-------------|
| `PassengerId` | Unique ID for each passenger |
| `Survived` | 0 = Died, 1 = Survived |
| `Pclass` | Ticket class (1st, 2nd, 3rd) |
| `Name` | Passenger name |
| `Sex` | Gender |
| `Age` | Age in years |
| `SibSp` | Siblings/spouses aboard |
| `Parch` | Parents/children aboard |
| `Ticket` | Ticket number |
| `Fare` | Passenger fare |
| `Cabin` | Cabin number |
| `Embarked` | Port of embarkation |

---

## 👨‍💻 Author

**Ashutosh Dubey**

[![GitHub](https://img.shields.io/badge/GitHub-AshutoshDubey-black?style=flat&logo=github)](https://github.com/your-username)

---

## 📜 License

This project is open source and available under the [MIT License](LICENSE).

---

⭐ **If you found this helpful, please give it a star!** ⭐
