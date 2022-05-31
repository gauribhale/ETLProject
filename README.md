# ETL Project

In this project, following tasks are performed-
1. Extracted the transactional data from a given MySQL RDS server to HDFS(EC2) instance using Sqoop.

2. Transformed the transactional data according to the given target schema using PySpark. 

3. This transformed data is loaded to an S3 bucket.

4. Created the Redshift tables according to the given schema.

5. Loaded the data from Amazon S3 to Redshift tables.

6. Performed the analysis queries.
