
![alt text](https://media.amazonwebservices.com/blog/2007/big_pbaws_logo_300px.jpg "AWS")

## AWS Infrastructure 
#### 10,000 foot Overview


---

## Services Overview

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


---

## Storage

#### [S3] Simple Storage Service

   - Virtual disk in the cloud
   - Object based storage
   - Stores files, movies, pictures etc.

#### [Glacier] Archive Storage

   - Stores files for archiving
   - Low cost
   - Good for compliance

#### [EFS] Elasic File Service

   - Block based storage.
   - Can be shared
   - Install Applications, Databases (can also use EBS)
   - Can share across multiple machines

#### Storage Gateway

   - Way of connecting up S3 to on premise datacenters
   - Virtual appliance installed on premise




---

## Databases

  > ***Fundamental to all exams***


#### RDS

  - Oracle Server
  - SQL Server
  - Arora (MySQL, PostgreSQL)


#### DynamoDB
  - Non relational DB 
  > ***Exam*** Developer

#### Redshift - Replicate primary DBs to redshift

  - Useful for running reports

#### Elasticache

  - Caches data in the cloud
  - Useful for caching common queries and to improve performance





---

## Migration

#### Snowball

  - Way of transferring data from on premise to AWS. 
  - Allow you to mover TB of data into the cloud.  
  - Hardware Appliance (1RU) with internal storage
  - > `New Product - Snowball Edge - Amazon on Premise hardware`
  
  - > SA, A

#### DMS

  - Migrate databases within Amazon.
  - Migrate data automatically and avoid overhead issues with licensing involved with traditional migrations e.g. oracle

#### SMS (Server Migration Service)
  - Migrate Virtual Machines (e.g 50 machines at a time) directly to the cloud (simiar to DMS migration)




---

## Analytics

#### Athena

  - Run SQL queries on S3
    - e.g search flat files or json files using SQL.


#### EMR - Elastic Map Reduce

  - Reduce large amounts of data (e.g logs reports etc).
  - NoSQL Databases
    - Hadooop
    - Apache Preso
    - Apache Spark 
  - Handles BigData


#### Cloud Search

  - Allow you to add search features to your site


#### Elastic Serach (open source)

  - Add search capabilities to your website
  > Angolia (non AWS solution)

#### Kinesis

  -  Process large amounts of data (TB/h)
  - Anaalise social media feeds
  - run realtime analysis


#### Data Pipeline

  Move data from S3 into DynamoDB or viaversa


#### QuickSight 

  - Business analytics tool
  - Create rich dashboards
  - Analyse data from DynamoDB, Redshift




---

## Security & Identity

#### IAM

  - How to manage users
  - Privleges



## Management Tools

#### Inspector

- Agent installed on the virtual machines and does security reporting


#### Certificate Manager

  - Provides free SSL certificates for web applications and services.




---

## Application Services


#### Directory Service

  - Connect Active Directory to AWS


#### WAF 

  - Traditionally firewalls protect you at the pysical Network layer. 
  - WAF applies Application Level security protection to your application/site.
  - Protects against
     - SQL injection
     - cross site sripting
     - Way of connecting up S3 to on premise datacenters


#### AWS Artifact

  - Compliance Documentation
  - ISO 900 Certification
  - PCI Certification


#### Cloud Watch

  - Used to monitor performance of your AWS environment
     - Disk util
     - RAM
     - CPU etc 


#### Cloud Formation (Infrastructre as Code)

  - A document which describes your AWS environment which become templates which can be used to deploy infrastructure.
  - A way of turning your physical infrastructure into code.


#### Cloud Trail

  - Used for auditing changes in your environment


#### Opsworks

  - Integration with Chef for automated deployment


#### Config

  - Alerts can be created to advise when configurations change


#### Trust Advisor

  - Automated way of scanning the environemnt and optimising resources.


#### Step Functions
  
  - Understand the interaction of application components and micro services


#### SWF - Simple Workflow
  
  - Coordinate and manage tasks and workflows.


#### API Gateway

  - Create publish and monitor APIs at scale.
  - Allow applications to access backend services e.g lambda or  backend systems to access business data or logic.


#### AppStream

  - Allow applications to be streamed to users


#### Elasic Transcoder
  
  - Alows media content to be transcoded dynamically into different formats (e.g. ipad, iphone etc)




---

## Developer Tools

#### CodeCommit

  - Store code in the cloud

#### CodeBuild

  - Build code (pay per min)

#### CodeDeploy

  - Deploys code

#### Code Pipeline 

  - Manage Code pipelines




---

## Mobile Services


#### Mobile Hub

  - Console for managing mobile apps

#### Cognito

  - Users can sign into application using Social media providerss (e.g gmail, facebook)

#### Device Farm

  - Enables you to improve the quiality of IOS, Android devices (physical)

#### Mobile Analytics

  - Analyse app data

#### PinPoint

  - Engage with your users and understand behaviour of how users use application (like Google Analytics but for apps)

#### WorkDocs

  - Uses S3 with security to allow you to manage business documents in the cloud

#### Workmail
  
  - Exchange for AWS



---

## IOT

  - Manage IOT devices 
  - Provides services such as IOT gateway


---

## Desktop and App Streaming

#### Workspaces
  - A way of having a desktop in the client.

#### AppStream 2.0
  - A way of streaming desktop applications to users



---

## Artificial Intelligence

  - Elon Musk *`Warning` us against the dangers of artification intelligence*

  > **Recommended Book**
  > Superintelligenece by Nick Bostrom
