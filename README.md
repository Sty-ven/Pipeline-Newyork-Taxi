# Pipeline-Newyork-Taxi

### The aim of the project is to build a pipeline for the data of different taxis- Yellow and Green taxi in Newyork city. The processes taken are highlighted below:

* Inspected data from the source (Newyork taxi website). Data was found to be in parquet format (ideal for data processing)
* Created a service account on google cloud console.
* Created a python script that downloaded data from the source
* Orchestrated all of the above using airflow to schedule downloading the data, uploading to google cloud storage (GCS)
* Wrote queries in Bigquery that created tables from the data collected in GCS
* Transformed that data in the tables created using DBT by creating models.
* Visualized the table locally using metabase hosted with Docker
