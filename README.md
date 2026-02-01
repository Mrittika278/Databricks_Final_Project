# Databricks_Final_Project
I built this project Exploratory data analysis using PySpark in Databricks Community Edition as part of the Databricks 21 Days Data + AI Challenge final learning project.


@Databricks @Codebasics @Indiandataclub #DatabricksWithIDC
______________________________________________

📊 Exploratory Data Analysis & Insight Generation using PySpark in Databricks
---------------------------------------
📌 Project Overview

This project is a learning-oriented exploratory data analysis (EDA) application built using Databricks Community Edition and PySpark.
The objective is to understand how real-world transactional data can be loaded, explored, validated, and analyzed at scale using Apache Spark, and how meaningful business insights can be derived using both PySpark and Spark SQL.

The project focuses on analysis and insight generation, rather than building production pipelines or machine learning systems.

-----------------------------------------------------------
🎯 Objectives

Load and explore a real e-commerce transactions dataset in Databricks

Perform basic data quality validation as part of EDA

Clean and prepare data for analysis

Derive comparative and behavioral insights using PySpark and Spark SQL

Create notebook-based visual dashboards using Databricks visualizations

🏷️ Domain

E-Commerce & Retail

----------------------------------------------------------------------

📂 Dataset Description

The dataset represents synthetic e-commerce transaction data with 50,000 records.

Columns:

Transaction_ID – Unique identifier for each transaction

User_name – Customer identifier

Age – Customer age

Country – Customer country

Product_Category – Category of purchased product

Purchase_Amount – Transaction amount

Payment_Method – Payment type used

Transaction_Date – Date of transaction

The dataset was uploaded and accessed directly within Databricks using a managed storage path.

----------------------------------------------------------------------------------

🧱 Project Structure

This project is implemented as a single Databricks notebook, structured logically using markdown and code cells:

- Data Loading & Inspection
- Basic Data Quality Checks
- Data Cleaning
- Analytical Aggregations
- Derived Feature Analysis
- Visual Insight Generation (Notebook Dashboards)


----------------------------------------------------------------------------------

🔍 Data Quality Validation

As part of exploratory analysis, the following checks were performed:

Null value checks across all columns

Validation of Purchase_Amount values

Logical consistency checks (age ranges, transaction validity)

The dataset was found to be clean, with no missing values.
This validation step confirmed that the data was reliable for downstream analysis.

Data quality checks were used for validation, not as a standalone quality system.


----------------------------------------------------------------------------------


📈 Analytical & Derived Insights

Beyond basic KPIs, the project focuses on derived and comparative insights, including:

Revenue and transaction distribution across product categories

Customer spending tier analysis (Low / Medium / High spenders)

Country-wise and demographic comparisons

Payment method preferences by age group

Customer purchase frequency vs average spend

Weekend vs weekday spending behavior

Revenue concentration across customers

These insights were generated using:

PySpark DataFrame transformations

Spark SQL queries

Derived attributes (age groups, spend tiers, behavior segments)

----------------------------------------------------------------------------------


📊 Visualization & Dashboarding


Notebook-based visual dashboards

Built-in Databricks visualizations:

Bar charts

Line charts

Pie charts

Heatmaps

Scatter plots

The notebook is structured to function as a visual analytics dashboard, and can be viewed in Presentation Mode for clarity.

----------------------------------------------------------------------------------

🛠️ Tools & Technologies Used

Databricks Community Edition

Apache Spark

PySpark

Spark SQL

Databricks Notebook Visualizations

----------------------------------------------------------------------------------


📌 Key Learnings

Understanding Spark DataFrames and lazy execution

Performing EDA at scale using PySpark

Validating data quality as part of analysis

Creating derived features for deeper insights

Combining PySpark and SQL effectively

Building dashboard-style visual insights inside Databricks notebooks

----------------------------------------------------------------------------------



✅ Conclusion

This project demonstrates how Databricks and PySpark can be used effectively for exploratory data analysis and insight generation on transactional data.
By moving beyond basic KPIs and deriving comparative insights, the project highlights how structured thinking and feature-driven analysis lead to meaningful business understanding.

----------------------------------------------------------------------------------
