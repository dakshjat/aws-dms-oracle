# AWS DMS Oracle
## Migrate Oracle Databases to Amazon RDS for Oracle Using AWS DMS

This AWS CloudFormation template to migrate Oracle databases to Amazon RDS for Oracle using AWS DMS.


![Architecture Diagrams](https://user-images.githubusercontent.com/47545538/185991758-1d07209e-9198-49df-a5dc-9f9c53150bc7.jpg)
The source Oracle database runs on an on-premises environment, and the target database runs on Amazon RDS for Oracle. AWS DMS is utilized to migrate existing data using the full-load migration type and replicate ongoing changes using the CDC migration type. 

___
It covered the creation of the following AWS DMS resources:
* AWS DMS Source Endpoint
* AWS DMS Target Endpoint
* AWS DMS Subnet Group
* AWS DMS Replication Instance
* AWS DMS Database Migration Tasks
* AWS DMS Event Subscriptions

For more information on the migration blog, visit [Strategy to Migrate Oracle Databases to Amazon RDS for Oracle Using AWS DMS Effectively](https://medium.com/@dakshjat/strategy-to-migrate-oracle-databases-to-amazon-rds-for-oracle-using-aws-dms-effectively-da677853c646)
