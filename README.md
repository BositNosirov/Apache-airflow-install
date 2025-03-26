# Apache-airflow-install
Apache Airflow Installation via Docker on Windows 10


Prerequisites
 - Docker Desktop for Windows with WSL 2 enabled
 - (Optional) Git for Windows


Steps

 - Clone repository
   git clone https://github.com/apache/airflow


  - Download official example file
   curl 'https://airflow.apache.org/docs/apache-airflow/2.8.1/docker-compose.yaml'


  - Initialize Airflow
    docker-compose up airflow-init

  - Start Airflow services
    docker-compose up


After a few moments, the Airflow web UI will be available at:
http://localhost:8080

Username: airflow
Password: airflow

Documentation
https://airflow.apache.org/docs/apache-airflow/stable/start/docker.html
