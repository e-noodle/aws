# 10,000 Foot Overview
# Part 3

# Git Hub Repository
```sh
$ git clone https://github.com/e-noodle/aws
```

## Storage

### [S3] - Simple Storage Service
* Virtual disk in the cloud
* Object based storage
* Stores files, movies, pictures etc.

### [Glacier] - Archive Storage

* Stores files for archiving
* Low cost
* Good for compliance

### [EFS] - Elasic File Service
* Block based storage.
* Can be shared
* Install Applications, Databases (can also use EBS)
* Can share across multiple machines

### Storage Gateway

* Way of connecting up S3 to on premise datacenters
* Virtual appliance installed on premise

## Databases

Fundamental to all exams

### RDS

* Oracle Server
* SQL Server
* Arora (MySQL, PostgreSQL)

### DynamoDB - Non relational DB

```D```

### Redshift - Replicate primary DBs to redshift
* Useful for running reports

### Elasticache
* Caches data in the cloud
* Useful for caching common queries and to improve performance

### Snowball

Way of transferring data from on premise to AWS. Allow you to mover TB of data into the cloud.  
Hardware Appliance (1RU) with internal storage

```SA, A```

* New Product - Snowball Edge - Amazon on Premise hardware

### DMS - Allow you to migrate databases within Amazon.
Allows you to migrate data automatically and resolves issues with traditional migrations e.g. licensing issues with oracle

### SMS - Server Migration Service

Allows you to migrate Virtual Machines (e.g 50 machines at a time) directly to the cloud (simiar to DMS migration)

### Athena

Allows you to run SQL queries on S3.  e.g search flat files or json files using SQL.

### EMR - Elastic Map Reduce
* Reduce large amounts of data - e.g logs reports etc.  Uses Hadooop, Apache preso, spark 
* Useful in BigData

### Cloud Search
* Allow you to add search features to your site

### Elastic Serach (open source)
* Allow you to add search capabilities to your website
* Also worth looking at angolia (non AWS)

### Kinesis

Processing large amounts of data - TB/hour
* Anaalise social media feeds
* run realtime analysis


## Certifications
* [Link to more info] - Professional
 
## References
*  [Concepts and Components](https://acloud.guru/course/aws-certified-solutions-architect-associate/learn/aws-overview/concepts-and-components-2/watch) - aCloudGuru Concepts and Components
[Link to more info]: <https://aws.amazon.com/certification/certified-solutions-architect-professional    />
