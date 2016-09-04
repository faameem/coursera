#Welcome To Big Data#

## Where This Course Fits: An Overview of the Big Data Specialization ##

**Big Data with Splunk**

**SDSC, San Diego Supercomputer Center**

**University of California, San Diego** 

### Course Outline ####
+ Hadoop
+ Big data analytics
+ Machine learning for big data
+ Graph analytics for big data
+ Capstone project in cooperation with Splunk
	- Interview opportunity with Splunk for top performers in the project.

### Faculty ###
+ Natasha Balac
+ Andrea Zonca - *Spark*
+ Mahidhar Tatineni - *Hadoop*
+ Amarnath Gupta - *Machine Learning*
+ Paul Rodriquez - *Graph*

## Introduction to Big Data ##

**Predicting the future to solve tomorrow's challenges.**

Big Data is diverse and complex, such as

- Customers
- Products
- Services
- Others

We can gather, store, manipulate big data to gain access to untapped value through analytics and predictive analytics.

+ Improve business ROI
+ Predict extreme weather conditions
+ Tackle biodiversity concerns
+ Gain insight into customer purchase habits

## How much data is there? Can we manage it? ##

Data growth is mostly being driven by unstructured data.

+ EB*1024=Zettabyte
+ PB*1024=Exabyte
+ TB*1024=Petabyte
+ GB*1024=Terabyte
+ MB*1024=Gigabyte
+ KB*1024=Megabyte
+ B*1024=Kilobyte
+ Byte

## The Emerging Big Data Stack ##

**Big Data Functional Requirements**

+ Collection
+ Integration
+ Analysis *[simple, statistical, predictive analytics]*
+ Actions / Decisions
+ *Example: Recommender systems of Amazon, Netflix.*

**Big Data Stack**

+ Fast data layer 
  - Speed: batch/real-time
  - Scale: MB - PB
  - Hadoop 
+ Big analytics
  - R
  - Python
  - Spark
+ Focused services
  - Fraud detection
  - Travel forecasting

**Hadoop**  

+ Need: Real-time, scalable, high perfomance computing and analytics of large complex data sets.
+ Hadoop brings storage and computational capacity together.
+ The Apache Hadoop project develops open-source software for reliable, scalable, distributed computing. It enables distributed processing of large data sets across clusters of commodity servers.

**Hadoop Features**

+ Low-cost (commodity servers)
+ Scalable (additional nodes can be added easily)
+ Fault tolerant (one node goes down, backup nodes are used until fixed)
+ Flexible (schema free; Can work with structured/unstructured data)

**Hadoop Implementations**

+ Open Source 
	- Apache Hadoop
+ Enterprise Level Service Providers
	- Cloudera
	- Hortonworks
	- MapR
	- Amazon Web Services
	- Intel
	- Pivotal

## Basic Hadoop Components ##
+ Data
	- Hadoop Distributed File System (HDFS)
		+ Distributed file system.
		+ Provides built in redundancy and fault tolerance.
+ Processing
	- Hadoop MapReduce
		+ Programming model for large scale data processing.
		+ Minimize data movement by bringing computation to where the data is.

**Hadoop 1.0**

+ Redundant reliable storage layer
	- HDFS
+ Cluster resource management & data processing layer
	- MapReduce
+ Applications layer
	- Pig (data flow)
	- Hive (sql)
	- Others (cascading)

**Hadoop 2.0**

+ Redundant reliable storage layer
	- HDFS2
+ Cluster resource managment & scheduling layer
	- YARN (not stuck with just map reduce paradigm)
+ Execution engine layer
	- Tez
		+ Applications layer using Tez
			- MapReduce (batch)
			- Pig (data flow)
			- Hive (sql)
			- Others (cascading)
+ Applications layer using YARN
	- RT Stream, Graph (Storm, Giraph)
	- Services (Hbase)

**Apache Hadoop Ecosystem**

+ HDFS
+ YARN Map Reduce v2 (distributed processing framework)
+ Zookeeper (Coordination)
+ Flume (log collector)
+ Sqoop (sql to hadoop data exchange)
+ Oozie (workflow)
+ Pig (scripting)
+ Mahout (machine learning)
+ R connectors (statistics)
+ Hive (SQL query)
+ Hbase (columnar storage)
+ Ambari (Provisioning, managing, and monitoring Hadoop clusters)

