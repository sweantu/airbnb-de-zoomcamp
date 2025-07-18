Plan: 
    4 weeks: 
    week 1: review knowledge + test function
        - [Github](https://github.com/DataTalksClub/data-engineering-zoomcamp)
        - [Youtube](https://www.youtube.com/playlist?list=PL3MmuxUbc_hJed7dXYoJw8DoCuVHhGEQb)
    week 2: plan the project + test function
    week 3-4: do the project
    week 5: review and optimize the project
Logs:
    week1:
        Summary:
            Terraform to create GCP resources
            Ingesting data pineline: use Kestra (Python, dlt) to ingest raw data to GCS
            Loading data pineline: use Kestra (Python, Bigquery, GCS) to load data from GCS to Bigquery
            Modeling or transforming data pineline: use Kestra (dbt, Spark) to transform data from Bigquery to Bigquery
        Preview:
            Extract / Ingest: python
            Transform: pandas, dbt, spark
            Load: ???


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

