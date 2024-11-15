# Classic Models Data SQL Techniques Used <br>
Aggregations: SUM, COUNT, AVG for summarising data.<br>
Joins: INNER JOIN, LEFT JOIN to combine data from multiple tables.<br>
Subqueries: Used for calculating derived values like averages.<br>
Temporary Tables: To simplify and structure multi-step calculations.<br>
Filtering: WHERE, BETWEEN, LIKE for conditional selection.<br>
Sorting and Limiting: ORDER BY and LIMIT to manage output.<br>

# Entity Relationship Diagrams and Normalisation SQL Techniques Used <br>
Primary Keys:
Define unique identifiers for entities (e.g., EmployeeID, DepartmentID, ProjectCode, ClientID).<br>
Foreign Keys:
Use foreign keys to establish relationships:
Employee.DepartmentID references Department.DepartmentID.
Project.ProjectManagerID references Employee.EmployeeID.<br>
One-to-Many Relationships:
Represented by foreign keys:
One department has many employees.
One client can have multiple projects.<br>
Many-to-Many Relationships:
Intermediate tables (EmployeeProject) resolve many-to-many relationships:
Employees working on multiple projects.
Each project having multiple employees.<br>
Attributes:
Columns in tables for storing details like project duration, employee assignments, and customer data.<br>

# Spark SQL AirBnB SQL Techniques Used <br>

## Spark Core Techniques<br>

Data Loading: Import data into RDDs and structure it for queries.<br>
Aggregation: Group and summarise data for metrics like counts and sums.<br>
Sorting: Order results for clarity and insight.<br>
Filtering: Extract subsets of data based on conditions.<br>
Calculation: Perform operations like averages and percentages on RDDs.<br>

## Spark SQL Techniques<br>

DataFrame Creation: Use schemas to structure data for SQL-like operations.<br>
Selection: Retrieve specific columns for targeted analysis.<br>
Filtering: Apply conditions to refine datasets.<br>
Aggregation: Group data and compute summary metrics like averages and totals.<br>
Optimisation: Leverage Spark SQL's optimiser for efficient query execution.<br>

# Grand Slam Data SQL Techniques Used <br>

## Data Preparation<br>

Data Cleaning: Remove blank rows, unwanted cells, and foreign characters.<br>
Table Creation: Define columns with appropriate data types.<br>
Data Import: Load cleaned CSV data into the database.<br>

## Query Techniques<br>

Filtering (WHERE): Extract data based on tournaments, years, or conditions.<br>
Aggregation (GROUP BY, COUNT, AVG): Summarise data like wins or average seedings.<br>
Sorting (ORDER BY): Rank data, such as top winners.<br>
String Functions: Use CONCAT() for winner-runner-up combinations or match tie-break analysis.<br>
Subqueries: Compare rankings against average rankings.<br>
Distinct Values (DISTINCT): Count unique players or events.<br>






