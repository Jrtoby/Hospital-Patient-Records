![](Intro_image.jpg)
# Hospital-Patient-Records
Data from Massachussets General Hospital from 2011 - 2022.

## Data Source
![](Data_source.png)
Dataset from **_MAVEN ANALYTICS_**, imported into power BI for analysis containing multiple tables of data structure, **_75,592_** of records and **_55_** of fields.

## Introduction
This project analyzes Hospital Patient Records from Massachusetts General Hospital, containing synthetic data of approximately 1,000 patients from 2011 to 2022. The dataset includes information on patient demographics, insurance coverage, medical encounters, and procedures. The objective is to uncover insights into patient admissions, hospital stays, medical costs, and insurance coverage through data exploration and visualization.

## Problem Statement
1. How many patients have been admitted or readmitted over time?
2. How long are patients staying in the hospital, on average?
3. How much is the average cost per visit?
4. How many procedures are covered by insurance?

## Concept Execution
The following Power Bi features were incoperated;

- Data sources,
- Data cleaning,
- Power Query,
- Data modeling,
- Caculated Columns and Measures using Dax,
- Data Visualization,
- Filters,
- Dashboard Building and
- Reporting.

## Data Cleaning
The "Remove Duplicate" operation was used on the neccessary columns, confirming no duplicate existed, null and empty rows in REASONDESCRIPTION was replaced with "Not reported" and that of numerical columns replaced to 0. Column data types were appropriately validated such as formatting the cost columns to display currency.
