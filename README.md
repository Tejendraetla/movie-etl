# Movies-ETL (Extract, Transform, Load) Practice

The Extract, Transform, and Load (ETL) process is used to create data pipelines in this module. The ETL process creates data pipelines that transform data as it travels from one location to another. In order to perform analysis, one must first set up a pipeline of data that can be used for analysis. As a result, the ability to perform data analysis without the use of ETL is extremely limited.

## Project Overview
To find out which low-budget films will go viral, Amazing Prime, a streaming service, is hosting a hackathon in which participants must guess which ones will be the most successful. Predictive models can only be built with an ETL pipeline. The goal of this project is to create an ETL pipeline that can be refactored to process large datasets into a SQL database.

## Project Deliverables
    - Deliverable 1: Write an ETL Function to Read Three Data Files
    - Deliverable 2: Extract and Transform the Wikipedia Data
    - Deliverable 3: Extract and Transform the Kaggle Data
    - Deliverable 4: Create the Movie Database

Movies ETL (Extract, Transform, Load) Project
Overview
This project demonstrates the full ETL (Extract, Transform, Load) process to support data analysis and predictive modeling. The goal was to create a robust, reusable ETL pipeline that processes large datasets and stores the cleaned, structured data in a relational SQL database. The project was developed as part of a hackathon challenge by Amazing Prime, a streaming platform seeking to identify which low-budget films are likely to go viral.

Project Objective
Build a refactorable ETL pipeline to ingest, clean, and load movie-related data from various sources into a SQL database, laying the foundation for future machine learning models to predict film success.

Project Deliverables
Deliverable 1: Develop an ETL function to read and ingest data from three distinct data files.

Deliverable 2: Extract and transform movie metadata from Wikipedia (JSON format).

Deliverable 3: Extract and transform movie ratings and metadata from Kaggle datasets (CSV format).

Deliverable 4: Load the cleaned and combined dataset into a SQL database structured into appropriate relational tables.

ETL Phases
Extract Phase

Data was ingested from multiple file types (CSV and JSON) using Pandas in the Python environment.

Transform Phase

Cleaned and standardized datasets by addressing missing values, removing corrupted records, and reformatting columns.

Combined datasets into a cohesive structure, ensuring consistency in naming conventions, keys, and formats for database loading.

Load Phase

Established a SQL database connection in Python using SQLAlchemy.

Loaded the final processed dataset into two SQL tables designed for efficient querying and future analysis.

### Image 1 - `movies` Table Query.  This table contains `6,052` rows of movies metadata
![Image1](https://github.com/Peteresis/Movies-ETL/blob/b781ede023d1b623984cdec41033abea5e99c83e/Images/movies_query.png)<br/>

### Image 2 - `ratings` Table Query.  This table contains `24,024,289` rows of ratings data
![Image2](https://github.com/Peteresis/Movies-ETL/blob/7b9abe8a28c5a7084835b42e62560e5b63605c7a/Images/ratings_query.png)<br/>
