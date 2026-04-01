## Data Engineering
- Data engineering is the process of designing, building, and maintaining the infrastructure necessary to collect, store, process and analyze data. It involves developing and implementing software, tools, and frameworks to enable the acquisition, transformation, storage and retrieval of data.

## Data Pipeline
- A data pipeline is a series of interconnected systems and processes that enable the flow of data from its source to its destination in an optimal and usable way.


COLLECTION > INGESTION > PREPARATION > COMPUTATION > PRESENTATION. |
-------------------------------------------------------------------| 

## Modern Data Pipelines
- Ingesting data from a souce system
- Transforming and cleaning data
- Storing this data in a persistent medium
- GOAL: Ensure data is in a format that can be analyzed

## Orchestration
- Orchestration is the pricess of coordinating the various stages and components of a data pipeline to ensure that data is processed efficiently and accurately.

### Tools for Orchestration
- Open Source: Apache Airflow, Apache NiFi, Prefect, Dagster, Airbyte
- Proprietary: AWS Step Functions, Google Cloud Composer, Amazon MWAA

## ETL
- The ETL process involves extracting data from a source system, transforming it into a format that is suitable for analysis, and loading it into a target system, such as a data warehouse or a database.

### Task:
- A task in a data pipeline represents a discrete unit of work that needs to be performed, such as reading data from a file, applying a transformation, or writing data to a database.

### DAG (Directed Acyclic Graph)
- A DAG is a data structure that represents the dependencies between tasks in a data pipeline.

### Dependencies
- Dependencies represent the relationships between the tasks in a DAG. A task may have one or mpore dependencies, meaning that it relies on the successful completion of one or more other tasks before it can start.

### List of steps 
1. Install Airflow
2. Initialize DB
3. Add user
4. Configure Airflow
5. Disable CSRF (for our purposes in codespaces)

