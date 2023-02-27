---
title: "Introduction to Distributed Computing"
date: "2019-06-18"
categories: 
  - "analytics"
  - "big-data"
  - "cloud"
tags: 
  - "azure"
  - "big-data"
  - "concurrency"
  - "databricks"
  - "spark"
cover:
    image: "images/img-1.jpg"


---

Distributed computing technology enables the compute load to be spread, or _distributed_, across multiple nodes (computers) connected via a network. The networked machines connected to each other share the same goal and share the compute load to effectively collaborate and provide the resources to obtain the goal. The early examples of distributed architecture was (famous or infamous) Napster where multiple computers will serve the common goal of a request to download a file. While there are various examples of distributed computing (biggest being the internet itself), the need of distributed computing in Modern Machine Leaning application is driven because of few reasons. 1) need to process ever growing volume of data 2) problem with scaling-up the computers/resources by adding more memory processors 3) need to create fault tolerance applications.

Presently, Apache Spark is the gold standard framework for distributed, in-memory, general-purpose cluster-computing, which efficiently partitions (or shards) a given dataset for data transformation or statistical modeling. Readers who are unfamiliar with this approach to handling compute are encouraged to read [https://docs.microsoft.com/en-us/azure/hdinsight/spark/apache-spark-overview](https://docs.microsoft.com/en-us/azure/hdinsight/spark/apache-spark-overview), but suffice it to say that it is of definite advantage to use Spark’s framework on top of a distributed compute system, which processes data fragmentations on available compute nodes _in memory_.

There are various ways teams can leverage power of Apache Spark and distributed computing. The most traditional solutions are deployed using Apache Spark on on-premise big data clusters but that involves buying, acquiring, managing, maintaining expensive hardware. Cloud technologies such as Azure has made it easier for users to use Spark and Distributed Computing by deploying Big Data Clusters on cloud, taking away need to buy, acquire, and maintain the clusters. Some of these solutions still require users to manage the clusters in case users wants to add compute nodes and scale the computing needs.

### Introducing Databricks

Databricks is a service, which effectively removes all management burdens that accompany a Spark cluster. Furthermore, it enables streamlined collaboration, operationalization, and custom multi-language programming through its “notebook” interface. Those unfamiliar with Databricks technology are encouraged to dig further (see [https://docs.microsoft.com/en-us/azure/azure-databricks/what-is-azure-databricks](https://docs.microsoft.com/en-us/azure/azure-databricks/what-is-azure-databricks)). Databricks doesn’t necessarily remove the need for domain expertise, but it is not a _new_ domain/technology; it simply runs Spark under the hood providing more frequent feature updates, elasticity and geographic coverage.
