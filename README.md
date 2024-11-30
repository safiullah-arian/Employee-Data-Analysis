# Employee Data Analysis

This repository contains a Python-based analysis of employee data using pandas and matplotlib. The dataset includes various attributes like salary, performance scores, job satisfaction, and department details. The purpose of this project is to demonstrate exploratory data analysis (EDA) and basic visualization techniques.

---

## **Dataset Description**

The dataset (`DIKW_HW_Activity.csv`) contains 9 columns and several rows, with the following features:

| Column Name        | Description                                     |
|--------------------|-------------------------------------------------|
| EmployeeID         | Unique identifier for each employee.           |
| EmployeeName       | Name of the employee.                          |
| Department         | The department the employee works in.          |
| JoiningDate        | Date when the employee joined the company.      |
| Salary             | Employee's annual salary (in USD).             |
| Gender             | Gender of the employee.                        |
| Country            | Country where the employee is based.           |
| PerformanceScore   | Performance evaluation score (scale 0-100).    |
| JobSatisfaction    | Job satisfaction level (scale 1-5).            |

---

## **Key Insights from the Analysis**

1. **Data Types**
   - The dataset contains a mix of categorical and numerical variables:
     - Categorical: `EmployeeName`, `Department`, `Gender`, `Country`.
     - Numerical: `Salary`, `PerformanceScore`, `JobSatisfaction`.

2. **Average Salary by Department**
   - Calculated the average salary for each department.

3. **Employee Distribution by Country**
   - Found the number of employees in each country.

4. **Average Performance Score**
   - Computed the overall average performance score of employees.

5. **Highest Performing Department**
   - Identified the department with the highest average performance score.

6. **Country with the Highest Job Satisfaction**
   - Determined which country had the highest job satisfaction score.

7. **Department with the Lowest Job Satisfaction**
   - Found the department with the lowest average job satisfaction score.

8. **Salary Analysis by Gender**
   - Analyzed the average salary by gender within each department.

---

## **Visualizations**

1. **Average Salary by Department**
   - A bar chart showing the average salary for each department.
   
2. **Average Performance Score by Department**
   - A bar chart showing the average performance score for each department.

3. **Average Job Satisfaction by Country**
   - A bar chart displaying job satisfaction scores across different countries.

---

## **Project Files**

- `Safiullah Arian DIKW Assignement.ipynb` - The Python script containing the analysis code.
- `DIKW_HW_Activity.csv` - The dataset used for the analysis.

---

## **How to Run**

1. Clone this repository:
   ```bash
   git clone https://github.com/safiullah-arian/employee-data-analysis.git
   cd employee-data-analysis
   ```

2. Install the required dependencies:
   ```bash
   pip install pandas matplotlib
   ```

3. Run the Python script:
   ```bash
   python Safiullah Arian DIKW Assignement.ipynb
   ```

4. View the output in the console and the generated visualizations.

---

## **Conclusion**

This analysis showcases how Python can be used for data exploration and visualization. It provides actionable insights about employee performance, salary distribution, and satisfaction levels, which can be valuable for HR and management.
