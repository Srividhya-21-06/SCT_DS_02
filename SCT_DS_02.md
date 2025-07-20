# 📊 Task 2 – Data Cleaning & Exploratory Data Analysis on Titanic Dataset
**Internship Track:** Data Science  
**Intern Name:** Sri Vidhya  
**Repository Name:** `SCT_DS_02`
---
## 📝 Task Objective
The goal of this task is to perform **data cleaning** and **exploratory data analysis (EDA)** on a dataset of our choice. For this task, I used the **Titanic dataset** from [Kaggle](https://www.kaggle.com/competitions/titanic/data), which contains passenger information and survival outcomes from the Titanic disaster.

---
## 📁 Dataset Used

- **File:** `train.csv`
- **Source:** [Titanic: Machine Learning from Disaster – Kaggle](https://www.kaggle.com/competitions/titanic/data)
- **Size:** ~60 KB
- **License:** CC BY-NC-SA 4.0
> ⚠️ **Note:** Please download the dataset from Kaggle and place `train.csv` in the same directory as the Python script before running it.
---
## 🧹 Data Cleaning Performed
- Filled missing **Age** values using the **median**.
- Filled missing **Embarked** values using the **mode**.
- Dropped the **Cabin** column due to excessive missing values.
- Verified dataset has no remaining null values in critical columns.
---
## 📊 EDA & Visualizations
The following visualizations and analysis were performed:
1. **Distribution of Gender** – Count of male and female passengers.
2. **Survival Distribution** – Count of survivors vs non-survivors.
3. **Survival by Gender** – Comparative survival rate by gender.
4. **Survival by Passenger Class** – Survival rate based on Pclass.
5. **Distribution of Age** – Histogram showing distribution of ages.
6. **Correlation Heatmap** – Relationships between numerical variables like Age, Fare, Pclass, and Survived.
---
## 🔍 Key Insights
| Insight | Details |
|--------|---------|
| **Gender and Survival** | Females had a much higher survival rate than males. |
| **Class and Survival** | First-class passengers were more likely to survive. |
| **Age Trend** | Younger passengers had slightly higher survival chances. |
| **Fare Correlation** | Passengers with higher fare tended to have better survival rates. |
---
## 🛠️ Tools and Libraries Used
- Python
- Google Colab
- `pandas` for data handling
- `matplotlib` and `seaborn` for data visualization
- `numpy` for numerical operations
---
## 📂 Repository Structure
```bash
SCT_DS_02/
│
├── titanic_task2.py      # Python script with full data cleaning and EDA code
├── README.md             # Documentation for Task 2
└── train.csv             # Dataset (NOT included; user must download from Kaggle)
