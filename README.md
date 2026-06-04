# 📊 Employees Data Analysis Project

This project focuses on **Data Cleaning**, **Exploratory Data Analysis (EDA)**, and **Data Visualization** of an employees dataset (`employees.csv`). The goal is to clean the missing values, analyze the salary distribution across different departments, and find the highest-paid employees in each team.

---

## 🚀 Features & Workflow

1. **Data Cleaning**: 
   * Handled missing values (`NaN`) in columns (`First Name`, `Gender`, `Senior Management`, `Team`) by replacing them with the **Mode** (most frequent value) of each column.
   * Verified that there are no duplicate records in the dataset.
2. **Data Aggregation**:
   * Calculated the **Average Salary** for each department/team.
   * Identified the **Highest-Paid Employee** and their maximum salary within each team.
3. **Data Visualization**:
   * Created a clean bar plot using `seaborn` and `matplotlib` to visualize and compare the average salaries across different teams.

---

## 📊 Insights & Summary Statistics

The analysis revealed that the **Engineering** department has the highest average salary, while **Finance** and **Human Resources** host some of the highest-paid individuals overall.

### Department-wise Salary Breakdown

| Team | Average Salary | Highest Paid Employee | Max Salary |
| :--- | :---: | :---: | :---: |
| **Engineering** | $94,269.20 | Ruby | $147,362 |
| **Finance** | $92,219.48 | Katherine | $149,908 |
| **Sales** | $92,173.44 | Marilyn | $149,654 |
| **Business Development** | $91,866.32 | Harold | $147,417 |
| **Human Resources** | $90,944.53 | Rose | $149,903 |
| **Marketing** | $90,435.59 | Russell | $149,456 |
| **Legal** | $89,303.61 | James | $148,985 |
| **Client Services** | $88,957.07 | Charles | $148,291 |
| **Product** | $88,665.51 | Cynthia | $149,684 |
| **Distribution** | $88,500.47 | Andrea | $149,105 |

---

## 🛠️ Tech Stack & Libraries

* **Python 3**
* **Pandas**: For data manipulation and cleaning.
* **Matplotlib & Seaborn**: For designing data visualizations.

---

## 💻 How to Run the Analysis

1. Clone this repository:
```bash
   git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
