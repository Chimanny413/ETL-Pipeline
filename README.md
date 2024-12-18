# Crowdfunding ETL Pipeline Project

## Overview

This project demonstrates the development of an ETL (Extract, Transform, Load) pipeline for processing and storing crowdfunding data. Using Python, Pandas, and PostgreSQL, we extracted data from Excel files, transformed it into clean, structured datasets, and loaded it into a relational database for efficient storage and querying. The project serves as a practical application of data engineering and database management principles.

## Project Goals

-   Extract raw data from Excel files.

-   Transform the data into clean, structured formats.

-   Create and populate a relational database with the transformed data.

-   Demonstrate foundational skills in data engineering, including ETL processes and database schema design.

## Project Deliverables

1. **Category and Subcategory DataFrames**

   -  Extracted unique categories and subcategories from the crowdfunding dataset.

   -  Assigned unique identifiers (e.g., cat1, subcat1) for relational mapping.

   -   Exported the results as category.csv and subcategory.csv.

1. **Campaign DataFrame**

-   Transformed crowdfunding campaign data, including:

-   Renaming and formatting columns (e.g., converting UTC timestamps to readable dates).

-   Converting financial data to numeric formats.

Mapping categories and subcategories using unique IDs.

Exported the result as campaign.csv.

Contacts DataFrame

Extracted and cleaned contact details from the provided dataset using regular expressions.

Split full names into first_name and last_name columns.

Exported the result as contacts.csv.

Relational Database

Designed an ERD (Entity-Relationship Diagram) and implemented a relational database schema.

Created PostgreSQL tables with appropriate primary and foreign keys.

Imported CSV data into the database.

Verified data integrity through SQL queries.

Tools and Technologies

Python: Used for data extraction and transformation.

Libraries: Pandas, NumPy, Regular Expressions

PostgreSQL: Used for designing and implementing the relational database.

Jupyter Notebook: Documented the ETL process for reproducibility.

GitHub: Version control and collaboration.
