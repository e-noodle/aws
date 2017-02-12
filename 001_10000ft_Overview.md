# AWS Infrastructure
#### 10,000 Foot Overview 

```
+-----------------+----------------+--------------------+
|   GAME          |   ARTIFICIAL   |     MESSAGING      |
|   DEVELOPMENT   |   INTELLIGENCE |                    |
+-------------------------------------------------------+
|   BUSINESS      |      IOT       | DESKTOP STREAMING  |
|   PRODUCTIVITY  |                |                    |
+-------------------------------------------------------+
|   APPLICATION   |  MOBILE        | DEVELOPER          |
|   SERVICES      |  SERVICES      | TOOLS              |
+-------------------------------------------------------+
|                 |   SECURITY &   |                    |
|    ANALYTICS    |   IDENTITY     | MANAGEMENT TOOLS   |
+-------------------------------------------------------+
|    MIGRATION    |    STORAGE     |     DATABASES      |
|                 |                |                    |
+-----------------+----------+-----+--------------------+
| NETWORK & CONTENT DELIVERY |           COMPUTE        |
+----------------------------+--------------------------+
|               AWS GLOBAL INFRASTRUCTURE               |
+-------------------------------------------------------+
```


## Storage

#### [S3] - Simple Storage Service
* Virtual disk in the cloud
* Object based storage
* Stores files, movies, pictures etc.

#### [Glacier] - Archive Storage

* Stores files for archiving
* Low cost
* Good for compliance

#### [EFS] - Elasic File Service
* Block based storage.
* Can be shared
* Install Applications, Databases (can also use EBS)
* Can share across multiple machines

#### Storage Gateway

* Way of connecting up S3 to on premise datacenters
* Virtual appliance installed on premise



## Databases

 Fundamental to all exams

#### RDS

* Oracle Server
* SQL Server
* Arora (MySQL, PostgreSQL)

#### DynamoDB - Non relational DB
> Developer Cert

#### Redshift - Replicate primary DBs to redshift
* Useful for running reports

#### Elasticache
* Caches data in the cloud
* Useful for caching common queries and to improve performance



## Migration

#### Snowball

Way of transferring data from on premise to AWS. Allow you to mover TB of data into the cloud.  
Hardware Appliance (1RU) with internal storage

> SA
> A

* New Product - Snowball Edge - Amazon on Premise hardware

#### DMS - Allow you to migrate databases within Amazon.
Allows you to migrate data automatically and resolves issues with traditional migrations e.g. licensing issues with oracle

#### SMS - Server Migration Service

Allows you to migrate Virtual Machines (e.g 50 machines at a time) directly to the cloud (simiar to DMS migration)



## Analytics

#### Athena
Allows you to run SQL queries on S3.  e.g search flat files or json files using SQL.

#### EMR - Elastic Map Reduce
* Reduce large amounts of data - e.g logs reports etc.  Uses Hadooop, Apache preso, spark 
* Useful in BigData

#### Cloud Search
* Allow you to add search features to your site

#### Elastic Serach (open source)
* Allow you to add search capabilities to your website
* Also worth looking at angolia (non AWS)

#### Kinesis
Processing large amounts of data - TB/hour
* Anaalise social media feeds
* run realtime analysis

#### Data Pipeline
Move data from S3 into DynamoDB or viaversa

#### QuickSight 
* Business analytics tool
* Create rich dashboards
* Analyse data from DynamoDB, Redshift



## Security & Identity

#### IAM
* How to manage users
* Privleges



## Management Tools

#### Inspector
Agent that you install on the virtual machines and does security reporting

#### Certificate Manager
Provides you with free SSL certificates for webservices



## Application Services

#### Directory Service
Allows you to connect Active Directory to AWS

#### WAF 
Traditionally firewalls protect you at tht network layer. 
WAF allows you to apply Application Level protection to your website.

* SQL injection
* cross site sripting
* Way of connecting up S3 to on premise datacenters

#### AWS Artifact
* Compliance Documentation
* ISO 900 Certification
* PCI Certification

#### Cloud Watch
Used to monitor performance of your AWS environment
* Disk util
* RAM, CPU etc 

#### Cloud Formation (Infrastructre as Code)
A way of turning your physical infrastructure into code.  Its a document which describes your AWS environment which become templates which can be used to deploy infrastructure.

#### Cloud Trail
Used for auditing changes in your environment

#### Opsworks
Integration with Chef for automated deployment

#### Config
Alerts can be created to advise when configurations change

#### Trust Advisor
Automated way of scanning the environemnt and optimising resources.

#### Step Functions
Way to understand the interaction of application components and micro services

#### SWF - Simple Workflow
Allows you to coordinate and manage tasks and workflows.

#### API Gateway
Create publish and monitor APIs at scale.
Allow applications to access backend services e.g lambda or  backend systems to access business data or logic.

#### AppStream
Allows applications to be streamed to users

#### Elasic Transcoder
Alows media content to be transcoded dynamically into different formats (e.g. ipad, iphone etc)


# Developer Tools

#### CodeCommit
Allow you to store code in the cloud

#### CodeBuild
Allows you to build code (pay per min)

#### CodeDeploy 
Deploy code

#### Code Pipeline 
Allows Pipelines to be managed



# Mobile Services

#### Mobile Hub
Console for managing mobile apps

#### Cognito
Users can sign into application using Social media providerss (e.g gmail, facebook)

#### Device Farm
Enables you to improve the quiality of IOS, Android devices (physical)

#### Mobile Analytics - Allows you to analyse app data

#### PinPoint
Engage with your users and understand behaviour of how users use application (like Google Analytics but for apps)

#### WorkDocs
Uses S3 with security to allow you to manage business documents in the cloud

#### Workmail
Exchange for AWS


# IOT
Allow you to manage IOT devices 
Provides services such as IOT gatway


# Desktop and App Streaming

#### Workspaces
A way of having a desktop in the client.

#### AppStream 2.0
A way of streaming desktop applications to users


# Artificial Intelligence

Elon Musk - Warning us against the dangers of artification intelligence
Superintelligenece = Nick Bostrom
