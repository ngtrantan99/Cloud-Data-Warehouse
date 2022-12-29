1. Title:
Project: Udacity Data Engineering Nanodegree - Data Warehouse

2. Summary:
This project is about song listen log files with song metadata to facilitate analytics. The Python SDK is used to construct a Redshift cluster, and a Python and SQL data pipeline is used to produce a data schema for analytics. JSON data is copied from an S3 bucket to Redshift staging tables before being inserted into a star schema with fact and dimension tables. Analytics queries on the ` songplays` fact table are straightforward, and additional fields can be easily accessed in the four dimension tables `users`, `songs`, `artists`, and `time`.

3. Project files:
- create_tables.py: use to drop and recreate tables
- dwh.cfg: confiure redshift cluster
- elt.py: copy data staging tables and intert into schema and dimension tables
- sql_queries.py: excecute the sql queries