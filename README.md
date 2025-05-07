# Employee-Analysis-Python-Project
# Employee Data Analysis Project

## 📁 Project Overview

This project analyzes employee data from ABC Company to uncover patterns in workforce structure, compensation, and demographics. The dataset includes details such as age, team, position, salary, and more, for 458 employees. The analysis is designed to help the company understand employee distribution, salary expenses, and demographic trends.

---

## 🔧 Preprocessing Steps

1. **Handled Missing Values:**

   * Filled missing values in `salary`  with median.
     
   * Categorical column College  filled with mode .

2. **Removed Duplicate Records:**

   * Ensured dataset integrity by dropping exact duplicates.

3. **Generated Random Heights:**

   * Height values were randomized between 150 and 180 cm as per project guidelines.

4. **Checking Outliers**


---

## 📊 Analysis Tasks & Visualizations

### 1. **Team Distribution**

* Counted employees per team.
* Calculated percentage representation.
* **Visualization:** Pie chart of employee count by team.

### 2. **Position Segregation**

* Grouped employees by position.
* **Visualization:** Bar chart of employee count by position.

### 3. **Predominant Age Group**

* Binned employees into age groups (21-30, 31-40, etc.).
* Identified the most common group.
* **Visualization:** Bar chart of age group distribution.

### 4. **Salary Expenditure by Team and Position**

* Summed total salary paid per team and position.
* Identified top contributors.
* **Visualizations:**

  * Bar chart: Salary by team
  * Bar chart: Salary by position

### 5. **Age-Salary Correlation**

* Computed correlation between age and salary.
* **Visualization:** Scatter plot showing the relationship.

---

## 📈 Insights Gained

* **Team Concentration:** A few teams dominate the employee count, reflecting company priorities.
* **Position Structure:** The majority of employees hold operational roles, with fewer leadership positions.
* **Age Demographics:** Most employees fall in the 31–40 range, suggesting a mid-career workforce.
* **Salary Distribution:** Salary expenditure is concentrated in core teams and senior roles 
* **Correlation:** There is a mild positive correlation between age and salary.

---

## 💻 Tools Used

* Python (Pandas, NumPy, Matplotlib, Seaborn)
* Jupyter Notebook
* Excel


> **Note:** This project was submitted as a part of the final module assessment for the Python programming course.
