# Project Description:
This project involves the creation of a comprehensive HR Attrition Dashboard using Apache Superset for visualization and PostgreSQL as the backend data source. The dashboard is designed to analyze various HR metrics and key performance indicators (KPIs) related to employee attrition, providing valuable insights into the organization’s workforce dynamics.

#### The key objective of this project is to answer the following critical questions around employee attrition: (tried to answer a few questions from the list below)

1. What is the Attrition trend Month on Month over past years?
2. What is the overall Attrition rate in the organization?
3. Which department sees the most attrition?
4. How does income distribute across different departments?
5. Is there any pattern with respect to income and attrition? Specifically, which income group—low, average, or high—sees the most attrition?
6. What is the attrition rate across different hierarchical levels?
For example, what is the attrition among employees who belong to the Sales department, specialize in Life Sciences, and work as Sales Executives?
7. Does gender have a significant impact on the attrition rate?
8. Is there any significant difference between churners and non-churners with respect to business travel and distance from home?
9. What is the attrition rate across different age groups within the organization?

#### The project leverages various charts, including:
* Line Chart
* Bar Chart
* Stacked Bar Chart
* Histogram
* Sunburst Chart
* Box Plot

Skills Used:
* Apache Superset: Used for creating an interactive, user-friendly dashboard to visualize key HR metrics and analyze trends related to employee attrition.
* PostgreSQL: A powerful relational database used for storing and querying HR data, ensuring efficient handling of large datasets and complex analytical queries.
* Data Visualization: Creation of insightful charts and graphs, enabling users to interact with and explore the data for trend analysis and decision-making.
* SQL: Writing complex SQL queries to filter, aggregate, and analyze the data stored in PostgreSQL, providing the necessary data for visualizations.
* Business Intelligence (BI): Using Superset for in-depth analysis of attrition and employee-related metrics to guide business strategies and HR interventions.
* Statistical Analysis: Analyzing patterns and correlations in attrition data with respect to various employee characteristics, such as income, age, gender, job satisfaction, and more.

#### Data Columns Used:
The dataset for this project includes the following columns that provide valuable data points related to employee attrition and various employee characteristics:
* Age: The age of the employee.
* Attrition: Whether the employee has left the organization (Yes/No).
* BusinessTravel: The frequency of business travel for the employee.
* Department: The department in which the employee works.
* DistanceFromHome: The distance (in kilometers) the employee lives from the office.
* Education: The education level of the employee (e.g., High School, Bachelor’s Degree, etc.).
* EducationField: The field of education (e.g., Life Sciences, Business, Medical).
* EmployeeNumber: A unique identifier for each employee.
* EnvironmentSatisfaction: The level of satisfaction with the work environment (scale from 1 to 4).
* Gender: The gender of the employee.
* JobInvolvement: The level of involvement in the job (scale from 1 to 4).
* JobLevel: The job level (e.g., entry, mid-level, senior, etc.).
* JobRole: The employee's role within the organization (e.g., Sales Executive, Research Scientist).
* JobSatisfaction: The level of job satisfaction (scale from 1 to 4).
* MaritalStatus: The marital status of the employee (e.g., Married, Single).
* MonthlyIncome: The monthly salary of the employee.
* NumCompaniesWorked: The number of companies the employee has worked for.
* Over18: Whether the employee is over 18 years of age.
* OverTime: Whether the employee works overtime (Yes/No).
* PercentSalaryHike: The percentage increase in the employee’s salary in the last year.
* PerformanceRating: The performance rating of the employee (scale from 1 to 4).
* RelationshipSatisfaction: The level of satisfaction with the relationship with coworkers (scale from 1 to 4).
* StandardHours: The standard working hours for the employee.
* StockOptionLevel: The level of stock options available to the employee.
* TotalWorkingYears: The total number of years the employee has worked.
* TrainingTimesLastYear: The number of training sessions attended by the employee in the past year.
* WorkLifeBalance: The employee’s work-life balance satisfaction (scale from 1 to 4).
* YearsAtCompany: The number of years the employee has been with the company.
* YearsInCurrentRole: The number of years the employee has been in their current role.
* YearsSinceLastPromotion: The number of years since the employee's last promotion.
* YearsWithCurrManager: The number of years the employee has worked with their current manager.
* Date_of_resignation: The date on which the employee resigned (if applicable).

This project helps in answering important HR-related questions while providing actionable insights into employee retention, satisfaction, and overall organizational dynamics.
