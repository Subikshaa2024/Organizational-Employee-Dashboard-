# Organizatonal Employeee Dashboard
## Objective:
     Developed an end-to-end data analysis solution using Power BI to create an interactive and insightful dashboard. The goal was to transform the given organizational dataset into a well-structured data model and produce a visually appealing Power BI report that provides valuable insights into employee salary-related aspects, segmented by gender and ethnicity.
## Dataset Tables:
     Organizational Data
     Employee Details
     Department and Units
     Ethnicity
     Country and City
## Key features and Extension:
### Data Modelling:
* Defined the fact and dimensional tables.
* Created relationships between primary and foreign key columns to ensure logical organization and support efficient querying.
* **Fact Table:** Organizational Data (containing salary-related information).
* **Dimensional Tables:** Employee Details, Department and Units, Ethnicity, Country and City.
### Data Transformation:
* Used Power Query Editor to cleanse, transform, and structure the data, ensuring data quality and consistency.
* Addressed missing values, corrected data types, and created necessary attributes for comprehensive analysis.
### Interactive Power BI Report:
#### Report Pages:
* Page 1 (Home): Displays data of the organization.
* Page 2 (Male): Displays data exclusively for male employees.
* Page 3 (Female): Displays data exclusively for female employees.
#### Slicers: 
* Integrated four slicers for dynamic filtering using dimensional tables:
* Department
* Unit
* Country
* City
#### Visuals:
* **Card:**  Showcases overall annual salary, minimum salary, and maximum salary.
* **Bar Chart:**  Presents country and city-wise annual salary with drilldown capabilities.
* **Pie Chart:**  Displays department-wise annual salary, filtered to show only employees aged above 37.
* **Matrix:** Shows the employee department, unit, country, city, annual salary, and bonus with conditional formatting:
1. Red if bonus % is 0.
2. Green if bonus % is above 0.
### Custom Tooltip: 
* Implemented a custom tooltip for pie chart to provide additional context and insights when hovering over data points.
### Bookmarks and Navigation Buttons:
* Created bookmark pages for each ethnicity.
* Each bookmark page includes one visual of choice displaying relevant data and an image button to return to the main page.
### Visual Design and Formatting:
* Created meaningful titles for all visuals.
* Applied attractive visual-level formatting to enhance readability and engagement.
* Ensured the dashboard is user-friendly and visually appealing, using consistent color schemes and layout designs.



