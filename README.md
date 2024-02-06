# ETL-Project

# Description
This project involves creating a comprehensive database for managing crowdfunding campaign information. The process is divided into several key steps: creating Category and Subcategory DataFrames, a Campaign DataFrame, and a Contacts DataFrame from the provided Excel data. These DataFrames are then exported as CSV files and used to construct a PostgreSQL database, crowdfunding_db, with properly defined relationships.

Create the Category and Subcategory DataFrames
- Extracting and Transforming Data: Use pandas to read crowdfunding.xlsx and create Category and Subcategory DataFrames with specific columns as instructed.
- Exporting DataFrames: Save the Category and Subcategory DataFrames as category.csv and subcategory.csv, respectively

# Create the Campaign DataFrame
- Data Extraction and Transformation: Follow the instructions to extract relevant columns from crowdfunding.xlsx, perform necessary data type conversions, and rename columns as specified.
- Exporting DataFrame: Save the Campaign DataFrame as campaign.csv.

# Create the Contacts DataFrame
- Option 1: Using Python dictionary methods to transform contacts.xlsx into the required format.
- Option 2: Using regular expressions for data extraction and transformation.
- Exporting the resulting DataFrame as contacts.csv.

# Create the Crowdfunding Database
- Database Design: Inspecting the CSV files and draft an ERD using QuickDBD.
- Schema Creation: Writing a PostgreSQL schema for the database based on the ERD.
- Database and Table Creation: Creating crowdfunding_db and its tables using the PostgreSQL schema.
- Data Import: Loading data from the CSV files into the corresponding tables in the database.
