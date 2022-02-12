# APACHE SNOWFLAKE

## Abstract

Nowadays Software as a Service (SaaS) provides readymade solutions for enterprise-level to the normal user level, which is highly benefited from the cloud platforms where they offer unlimited storage and computing resources on demand this made easy, cost-effective, and flexible. were previously it is so difficult to manage and maintain it. As per the same problem arises and is struggling in data warehousing systems which are designed for fixed resources that lead to unable to scale it and upgrade for newer generation and highly typical to match the dependencies that used in their warehouse all these lead to costlier, inflexibility, high maintenance, and space-time consuming which may lead to slower production, decrease in business sales.
so as same as SaaS the Data warehousing as a service is built. which is an enterprise-ready data warehousing solution for the cloud. where all the data operations are made on the cloud which is flexible, cost-saving, no maintenance, with high-speed computing and fast delivery solutions. hence all these advantages are gained and packed by Snowflake. A fully supported SQL Query and built-in extensions.

## Introduction

Snowflake is a data platform that was built for the cloud and runs on AWS, Azure, and Google Cloud Platform. Snowflake acts as a data warehouse, data lake, database, and secure data exchange. it was founded in July 2012 and was launched publicly in October 2014, which is founded by Benoit Dageville, Thierry Cruanes, Marchin Zukowski. The snowflake data platform is built by a new SQL query engine with an innovative architecture natively designed for the cloud. snowflake provides special features and unique capabilities as a Data Platform as a Cloud Service.

## Research work 

- Snowflake supports ANSI SQL and ACID transactions. Most users can migrate their workloads with little to no changes.
- Snowflake implements Snapshot Isolation (SI) on top of multi-version concurrency control (MVCC).
- Snowflake provides unlimited data operations in single data set 

### Architecture

![](https://docs.snowflake.com/en/_images/architecture-overview.png)



snowflake is a multi-cluster, shared-data architecture which delivers high scale performance, elasticity, and concurrency for as per enterprises requirement.

snowflake is a hybrid of shared-disk and shared-nothing database architecture means it uses a central repository for consistent data from all computational nodes in the platform. whereas each node in the cluster stores a portion of the entire data. this type of architecture is beneficial for high performance, data management, and scale-out. snowflake processes queies using MPP (massively parallel processing).

snowflake's unique architecture consists of three key layers:
* Database storage
* Query processing
* Cloud services

#### Database storage :

Basically, Data is stored by the cloud providers like AWS, Azure, GCP. But, snowflakes take care of all the data aspects like data storing, file size, structure, metadata, statistics, compression, etc. The object stored data is accessible only by the SQL query operations run using snowflake. After post operations or during operations such as cached data and pre processed data all are stored and managed by the cloud service providers

#### Query processing:

Query processing is done under the Virtual Warehouses layer. The 
Virtual Warehouses layer consists of a cluster of compute engines like AWS EC2 instances that make VW are called worker nodes. these are composed of Massively parallel processing (MPP) all are allocated by Snowflake from the cloud providers.each Virtual Warehouse has no impact on the performance of other Virtual Warehouse because they are independent of each other.\
These houses perform DML operations like updating, loading, unloading data to the tables.

#### Cloud Services:

Cloud Services is a layer of collective services like
* Authentication 
* Infrastructure management
* Metadata management
* Query management and optimization
* Access control

All these services combine all of the different components of Snowflake to process the user requests. In this way, all the services coordinate activities across Snowflake. This service also runs on compute instances provide by snowflake from the cloud providers.
 
### Features 

Snowflake offers more than a traditional relational data warehouse like SQL support, ACID transactions, standard interfaces, stability and security, customer support, strong performance, and scalability. Additional  features are 
* Semi-Structured and Schema-Less Data
*  Time Travel and Cloning (by Snapshot Isolation )
*  Security
*  Continuous Availability
*  pure-software-as-a-service experience

## Conclusion

Snowflake as a data warehouse as a service and relational database as a service offers relentlessly unlimited data operations, storage systems, security, sclability, Elasticity  by using the cloud platform.

## Reference 

* https://docs.snowflake.com/en/
* https://resources.snowflake.com/white-paper

