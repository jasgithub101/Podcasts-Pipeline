# Podcasts-Pipeline
This Project was done using Apache Airflow to build a pipeline for downloading podcast episodes, the episodes are stored in a SQLite Database.

Pros of using Airflow:
- The project runs daily, downloading the new episodes everyday.
- Each task runs independently, and logs can be monitored.
- Each task can be run in an order and can also parallelize.
- This project can be extened eaily using Airflow.

This is the DAG(Directed Acyclic Graph) that shows how the tasks are ordered in the pipeline:
![image](https://github.com/jasgithub101/Podcasts-Pipeline/assets/93384756/53932603-7b14-4fa9-b009-908ceade3ef1)

The data is taken from this [xml file](https://www.marketplace.org/feed/podcast/marketplace/).
