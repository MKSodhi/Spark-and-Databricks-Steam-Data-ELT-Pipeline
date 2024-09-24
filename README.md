# Steam Games Data Integration and Processing Project

## Project Description

This project was developed for study purposes in **Apache Spark** and **Databricks Community Edition**. The main objective is to demonstrate the process of ingesting and loading video game data obtained from external sources into multiple CSV files in the Bronze Layer, due to the complexity of the JSON structure.

## Objectives

1. **Data Ingestion**:
   - Ingest data from external JSON files containing information about Steam games.
   - The data includes various attributes like game names, release dates, developers, publishers, prices, categories, and PEGI ratings.

2. **Data Extraction and Loading**:
   - **Extract** data from the JSON files and **load** it into multiple CSV files in the **Bronze Layer**.
   - This step focuses solely on handling the complexity of the JSON structure by creating separate CSVs for different aspects of the data.

## Project Steps

### 1. Importing Libraries and Reading Data

- Use Python libraries like `pyspark.sql` to load and process the JSON files.
- Read the raw JSON data into Spark DataFrames.

### 2. Data Extraction and Loading

- Extract relevant columns from the JSON data.
- Due to the complexity of the structure, create multiple DataFrames to separate game info, categories, and PEGI ratings.
- Store each DataFrame as a CSV file in the Bronze Layer.

### 3. Storage and Organization

- Save the raw data as separate CSV files in the Bronze Layer for further analysis and processing in future stages.

## Project Structure

- **Databricks Notebook**: Contains code for data ingestion and loading using Spark.
- **Data**:
  - **Bronze Layer**: Multiple raw CSV files containing different aspects of the JSON data.

## Notebook Screenshot

Here is a screenshot of the Databricks notebook used for this project:

![Databricks Notebook](images/Print_Databricks.png)

## Conclusion

This project was carried out to deepen my studies in Databricks and Apache Spark.
