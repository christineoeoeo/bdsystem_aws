# Built Big Data System for E-Commerce using AWS services

### Description

* Developed Order History funciton that help further analyze by using data generated on EC2 instance and publish using Kinesis datas stream into AWS function.
* Implement Items Recommendation online based on aggregating customer's purchasing data (publish data thru EC2 into data lake hosted on s3 and spin up EMR cluster to produce recom model using Apache Spark.
* Create Purchasing system that alert us when unexpected rate of orders comes in. This has to be real time as someone needs to handle it immediately.
* Analyze near Real Time server log data using Kinesis Firehose to pump Apache log data into Elastic Search so we can easily query data for dashboards use.
* Data Warehousing and Visualisation by using AWS Glue , Athena, Redshift , Quicksight on top of S3 Datalake.
