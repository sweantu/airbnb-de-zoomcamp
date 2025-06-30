Plan: 
    6 weeks (30/6 - 11/8): 
    week 1 (30/6 - 6/7): review knowledge
        - [Github](https://github.com/DataTalksClub/data-engineering-zoomcamp)
        - [Youtube](https://www.youtube.com/playlist?list=PL3MmuxUbc_hJed7dXYoJw8DoCuVHhGEQb)
    week 2: plan the project
    week 3-5: do the project
    week 6: review and optimize the project
Logs:
    week1: 10 hours
        Terraform to create GCP resources
        Ingesting data pineline: use Kestra (Python, dlt) to ingest raw data to GCS
        Modeling data pineline: use Kestra (Python, Bigquery, GCS) to model data from GCS to Bigquery
        Transforming data pineline: use Kestra (dbt, Spark) to transform data from Bigquery to Bigquery
        - 30/6: overview
        - 1/7:  Bigquery, dbt
        - 3/7: Spark
        - 5/7: Kestra, dlt


Summary
    Goal
        Create a dashboard to display 2 charts. One chart is distributed by category, the other chart is presented by timeline.
    Requirements
        1. Describe the problem
        2. Develop in the cloud using IaC
        3. Ingest raw data into a data lake using workflow orchestration
        4. Model data and insert it into a data warehouse using workflow orchestration
        5. Transform data using dbt, Spark
        6. Visualize data in a dashboard
        7. Document the project

