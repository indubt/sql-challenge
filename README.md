# sql-challenge
Repo for Module9 - SQL Challenge

## Repo Structure

sql-challenge
|
|__EmployeeSQL
|   |__ERD.png
|   |__queries.sql
|   |__Schema.sql
|
|__Resources
    |
    |__departments.csv
    |__employees.csv
    |__titles.csv
    |__salaries.csv
    |__dept_emp.csv
    |__dept_manager.csv

## Data Modeling

After Analyzing the given csv files under the [Resources Folder](Resources) and create an Entity Relationship Diagram(ERD) using the tool [ERD Tool](https://app.quickdatabasediagrams.com/) and the screenshot of the diagram is here. [ERD.png](EmployeeSQL/ERD.png)

## Data Engineering

Based on the ERD Diagram, created the database schema. Schema File is as shown here -[Schema](EmployeeSQL/Schema.sql)

Imported the data from csv files to the database using the in-built import function in PGAdmin in a specific order to not violate foreign key constraints.

## Data Analysis

[queries.sql](EmployeeSQL/queries.sql) file shows the SQL queries for all the below analysis questions requested in the challenge. Also, created a view to use for questions 6 and 7.

1. List the employee number, last name, first name, sex, and salary of each employee.

2. List the first name, last name, and hire date for the employees who were hired in 1986.

3. List the manager of each department along with their department number, department name, employee number, last name, and first name.

4. List the department number for each employee along with that employee’s employee number, last name, first name, and department name.

5. List first name, last name, and sex of each employee whose first name is Hercules and whose last name begins with the letter B.

6. List each employee in the Sales department, including their employee number, last name, and first name.

7. List each employee in the Sales and Development departments, including their employee number, last name, first name, and department name.

8. List the frequency counts, in descending order, of all the employee last names (that is, how many employees share each last name).