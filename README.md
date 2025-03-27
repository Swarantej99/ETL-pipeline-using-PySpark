# ETL-pipeline-using-PySpark

An ETL (Extract, Transform, and Load) pipeline extracts data from sources, transforms it, and loads it into a storage system. It helps create clean, usable data formats for analysis. PySpark is ideal for building ETL pipelines for large-scale data processing. It offers distributed computing, high performance, and handles structured and unstructured data efficiently.

The dataset we will be using for building an ETL Pipeline contains temperature-related data for various countries from 1961 to 2022. The columns include identifiers like ObjectId, Country, ISO2, and ISO3, along with year-wise temperature data such as F1961, F1962, etc., as floating-point values. Some columns contain missing values.

We’ll develop an ETL Pipeline using PySpark to process this dataset to handle the following tasks:

-Extract: Load the dataset from the CSV file.
-Transform: Clean the data, handle missing values, and pivot year-wise temperature data for analysis.
-Load: Save the processed data into a new storage format (e.g., Parquet or a database).

The next steps like Extract – Load the Dataset, Transform – Clean and Process the Data, Save the Processed Data was clearly mentioned in the attached  Jupyter code file clealry 
