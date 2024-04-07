# Podcasts-Pipeline
This Project was done using Apache Airflow to build a pipeline for downloading podcast episodes, the episodes are stored in a SQLite Database.

Pros of using Airflow:
- The project runs daily, downloading the new episodes everyday.
- Each task runs independently, and we get error logs.
- Each task can be run in an order and can also parallelize.
- This project can be extened eaily using Airflow.
