# SQL Homework - Employee Database: A Mystery in Two Parts 

## Background
Data Engineering & Data Analysis were used to treat data from employees salaries, title, department and other HR related info.


#### Data Modeling & Data Engineering

A tool  [http://www.quickdatabasediagrams.com] was used to ceate an ERD of the data provided. An image of the relationship was generated (QuickDBD-export.png)

A table schema for each of the six CSV files was created, saves as QuickDBD-export.sql.

#### Data Analysis

In Postgres, a Data_analysis.sql file was created. The analysis includes:

1. List the following details of each employee: employee number, last name, first name, sex, and salary.

2. List first name, last name, and hire date for employees who were hired in 1986.

3. List the manager of each department with the following information: department number, department name, the manager's employee number, last name, first name.

4. List the department of each employee with the following information: employee number, last name, first name, and department name.

5. List first name, last name, and sex for employees whose first name is "Hercules" and last names begin with "B."

6. List all employees in the Sales department, including their employee number, last name, first name, and department name.

7. List all employees in the Sales and Development departments, including their employee number, last name, first name, and department name.

8. In descending order, list the frequency count of employee last names, i.e., how many employees share each last name.

## Importing the Data to Pandas (Bonus)


1. The SQL database was imported into Pandas in a file called sql_challenge_bonus.ipynb. 

The following charts were created:

2. A histogram to visualize the most common salary ranges for employees.

3. A bar chart of average salary by title.
#