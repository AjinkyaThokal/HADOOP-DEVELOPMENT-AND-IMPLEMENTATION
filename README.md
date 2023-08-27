# HADOOP DEVELOPMENT AND IMPLEMENTATION

Welcome to the GitHub repository showcasing a powerful and versatile data ingestion and processing pipeline. This project highlights the seamless integration of Sqoop, Hive, Parquet/ORC file formats, and HBase, enabling efficient data movement, transformation, and storage within a Hadoop ecosystem

# Project Overview
In today's data-driven landscape, creating a reliable and efficient pipeline for data integration and processing is crucial. Our project exemplifies this by outlining the following key steps:

**Data Extraction with Sqoop:** We kickstart the pipeline by employing Sqoop, an essential tool for extracting data from various relational databases, including MySQL. This allows us to efficiently transport data from MySQL to Hadoop HDFS.

**Data Transformation and Upsert Logic with Hive:** After arriving in HDFS, we guide the data into Hive, where we organize it into a table. We've added a smart feature called "upsert logic" to help maintain historical records while also keeping the latest data up-to-date.

**Efficient Storage in Parquet and ORC:** To make the data storage efficient and fast, we save the processed data in two formats: Parquet and ORC. These formats minimize space and speed up data analysis.

**Insertion into HBase with Bulk Load:** Our final destination is HBase. The processed data is inserted here using bulk loading, which is efficient for large-scale data storage and retrieval.

# Repository Structure

**Load_Table.hql:** This script contains the code for creating tables and dropping tables in Hive along with Upsert Logic.

**driving_script:** This is the final script which contains Sqoop queries along with Bulk Load Command for HBase.  

