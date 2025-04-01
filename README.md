# Walmart Sales Performance Analysis


## Description
This project analyzes Walmart's sales performance across three states (Georgia, Virginia, and Washington) from 2001 to 2015. The report identifies sales growth trends and provides region-specific product profitability strategies to enhance Walmart’s sales and profitability.

## Getting Started
### Prerequisites
To run this analysis, you need the following:
-  MySQL or a similar relational database management system (RDBMS) to store and analyze sales data.
-  Python (with libraries like pandas, SQLAlchemy, matplotlib for data manipulation and visualization).
-  Basic knowledge of SQL queries for data extraction and transformation.
-  Jupyter notebook or any Python IDE for running the analysis.

## Installing
1. Install MySQL Workbench or any preferred RDBMS to manage the walmartsales database.
2. Install Python and necessary libraries: pip install pandas sqlalchemy matplotlib
3. Download the data and ensure it’s in .csv format, as MySQL requires CSV files for importing data.
4. Import the CSV data into the database using the MySQL Workbench.
5. Connect to the database using Python's SQLAlchemy to run queries and extract data.

## Running the Tests
### Breakdown of Tests

The tests and analysis conducted include:
#### Sales Growth Analysis: 
- A time series analysis of Walmart’s sales growth from 2001 to 2015 across Georgia, Virginia, and Washington.
- SQL queries are used to fetch the data for each state.
- A graph is plotted to visualize the sales growth over the years.
#### Product Profitability Analysis:
-   Identification of high-performing products in different regions.
-   Products with the highest profit in the East, South, West, and Central regions are analyzed and highlighted.
#### Operational Challenges:
- Tests around data conversion (from Excel to CSV) and the handling of column names with spaces and special characters.
- Finding an online source to convert Excel/CSV files to SQL statements.

## Deployment
This project is designed to run locally or on any server with MySQL and Python setup. To deploy:
1. Set up a MySQL server or use a cloud database (e.g., AWS RDS, Google Cloud SQL).
2. Upload the sales data to the database.
3. Set up Python environment on your deployment server.
4. Run the Python script to perform data extraction, analysis, and generate reports.

## Author
This report and analysis was created by Vincent Gordon and group members from college. The project was initiated to assist Walmart in improving their strategic decisions regarding sales growth and product profitability.

## Acknowledgement
Thanks to Professor Omar Al-Trad who provided the dataset, the knowledge towards the analysis and the necessary techniques used for this project. 
