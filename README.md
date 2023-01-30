# Big-Data-101

**What is big data?** 
<br/>
Big data refers to datasets that are so large and complex that they become difficult to process using traditional data processing tools and techniques. These datasets often come from a variety of sources, such as social media, sensors, and transactional data, and may contain a variety of data types, including text, images, and video. Big data has the potential to provide insights and drive innovation, but it also presents a number of challenges, such as how to store, process, and analyze the data efficiently.
<br/>
<br/>

**How it is different from Data mining?** 
<br/>
Data mining is a process that involves analyzing large datasets to identify patterns and trends. It is often used to discover hidden insights in data and can be used to make predictions or recommendations.

Big data is a term that is often used in the context of data mining, as it refers to the large datasets that are often mined for insights. However, the term "big data" can also refer more broadly to the challenges and opportunities associated with working with large and complex datasets.

One key difference between big data and data mining is that big data often refers to the raw data itself, while data mining refers to the process of analyzing and extracting insights from that data. Another difference is that big data often involves working with unstructured data, such as text and images, while data mining is more often used with structured data, such as records in a database.
<br/>
<br/>

**Main topics in big data:**
<br/>

**1-Data storage:** One of the main challenges of big data is finding ways to store and manage large datasets. This may involve using distributed storage systems, such as **Hadoop** or **NoSQL** databases.
<br/>

**2-Data processing:** Processing and analyzing big data often requires the use of specialized tools and techniques, such as distributed processing frameworks like **MapReduce** or **Apache Spark**.
<br/>

**3-Data visualization:** Visualizing big data can help make it easier to understand and extract insights from the data. There are a variety of tools and techniques for visualizing big data, including dashboards and data visualization software.
<br/>

**4-Machine learning:** Big data often involves the use of machine learning algorithms to identify patterns and trends in the data.
<br/>

**5-Privacy and security:** Working with large datasets can raise concerns around privacy and security, as it may be possible to identify individuals from the data. It is important to consider these issues and take appropriate measures to protect the privacy of individuals.
<br/>

**6-Ethical considerations:** Working with big data can raise a number of ethical considerations, such as bias in data and the use of data for unintended purposes. It is important to consider these issues and take steps to ensure that big data is used ethically.
<br/>
<br/>

---

**1- Data 5V's concept:** 

It refers to the five characteristics that define big data: Volume, Velocity, Variety, Veracity, and Value.

1. Volume: refers to the large amount of data that is generated and stored.
2. Velocity: refers to the speed at which the data is generated and processed.
3. Variety: refers to the different types of data, such as structured, unstructured, and semi-structured, that are part of big data.
4. Veracity: refers to the uncertainty, ambiguity, and incompleteness of the data.
5. Value: refers to the potential insights and benefits that can be derived from the data.

**2- Framework:** 

A framework refers to a set of tools and technologies that are used to 1-collect, 2-store, 3-process, and 4-analyze large amounts of data. There are several different big data frameworks available, each with their own strengths and weaknesses. Some of the most popular big data frameworks include:

Hadoop: an open-source framework that allows for distributed storage and processing of large data sets using a cluster of commodity hardware.<br/>

Spark: an open-source, in-memory big data processing framework that can be used for batch processing, real-time processing, and interactive SQL.<br/>

Storm: a distributed, real-time big data processing framework that can process large numbers of streaming data records.<br/>

Flink: a real-time big data processing framework that is designed to handle both batch and streaming data.<br/>

Kafka: a distributed streaming platform that can handle real-time data feeds.<br/>

Hive: a data warehousing and SQL-like query language for big data stored in HDFS.<br/>

Pig: a high-level platform for creating MapReduce programs used with Hadoop.<br/>

Samza: a distributed stream processing framework that is built on top of Apache Kafka.<br/>

These are just a few examples and many more are available in the market, the choice of a framework depends on the use case, the size, the type of data, and the requirement of the organization. <br/>


**Hadoop and Spark in better detail:**

**Hadoop:** 

It is an open-source framework that allows for distributed storage and processing of large data sets using a cluster of commodity hardware. It is built on top of the Hadoop Distributed File System (HDFS), which is a distributed file system that allows for the storage of large data sets across multiple machines. Hadoop also includes a processing engine called MapReduce, which allows for the parallel processing of large data sets across a cluster of machines.

Hadoop is well suited for batch processing of large data sets, and it is often used in big data scenarios where data is stored in HDFS, and processed using MapReduce. Hadoop also provides a rich ecosystem of tools and technologies, such as Pig, Hive, and HBase, that can be used for data processing, analysis, and storage.
<br/>
<br/>

**Spark:**

It is an open-source, in-memory big data processing framework that can be used for batch processing, real-time processing, and interactive SQL. It was designed to overcome the limitations of Hadoop's MapReduce model by providing an in-memory computing model, which allows for faster processing of big data. Spark also provides a rich set of libraries, including Spark SQL, Spark Streaming, and MLlib, that can be used for data processing, analysis, and machine learning.

Spark is a general-purpose big data processing framework and can be used for a wide range of use cases, including ETL, streaming, SQL, and machine learning. It is also faster than Hadoop's MapReduce in terms of iterative and interactive computations, which makes it a great choice for certain type of workloads.

Both Hadoop and Spark can be used together, where Hadoop can be used for storage and batch processing, while Spark can be used for in-memory processing and iterative algorithms.

<br/>
<br/>

**(O) In-memory processing:** is a method of computing where data is temporarily stored and processed in the computer's RAM (Random Access Memory) rather than on disk. This allows for faster processing speeds, as data can be quickly accessed and manipulated without the need to read and write to disk.

In-memory processing is particularly useful for big data scenarios where large amounts of data need to be processed quickly. It is also useful for real-time and interactive applications that require low-latency response times.

In-memory processing can be contrasted with disk-based processing, in which data is stored on disk and must be read and written to disk for each processing step, which is slower and more time-consuming.

Spark is an example of a framework that uses in-memory processing, where it stores the data in RAM and performs the processing on it, this way it can handle large data sets at a much faster speed than traditional disk-based approaches.


<br/>
<br/>

**(O) Cache reference:** Cache reference refers to the act of looking up data in a cache memory, a high-speed memory storage that temporarily holds frequently accessed data for quick access. The cache reference process helps to speed up data retrieval by reducing the number of memory accesses required to access the data.

<br/>
<br/>


**Distributed File Systems:**

1. NFS (Network File System): NFS is a network file system protocol that allows a user on a client computer to access files over a network as if they were stored on their local computer. NFS is simple to set up and use and is widely supported across many operating systems.

Pros:

Easy to set up and use

Widely supported across many operating systems

Cons:

Not designed for large scale data storage and retrieval

Poor performance with large data sets

Limited security and reliability features

2. AFS (Andrew File System): AFS is a distributed file system developed at Carnegie Mellon University that provides a transparent and scalable way to store and access files over a network. AFS uses a distributed architecture to ensure high availability and scalability.

Pros:

Distributed architecture for high availability and scalability
Supports large data sets
Supports file sharing and collaboration

Cons:

Complex to set up and manage

Limited support for newer operating systems

3. Coda: Coda is a distributed file system that provides a high-performance and scalable way to store and access files over a network. Coda is designed for use in mobile and wireless environments, where the network may be unreliable.

Pros:

Designed for use in mobile and wireless environments
High-performance and scalable

Cons:

Complex to set up and manage

Limited support and development

**MapReduce:**

1. Google MapReduce: MapReduce is a programming model developed by Google for processing large data sets in a parallel and distributed manner. Google MapReduce was the first implementation of the MapReduce programming model and has been widely adopted and imitated by other systems.

Pros:

Simplifies the process of writing parallel and distributed data processing applications

Can handle very large data sets

Well-documented and widely used

Cons:

Limited to batch processing of data

Not suitable for real-time data processing

2. Hadoop MapReduce: Hadoop MapReduce is an open-source implementation of the MapReduce programming model that is part of the Hadoop ecosystem. Hadoop MapReduce allows for the processing of large data sets in a parallel and distributed manner.

Pros:

Open-source and widely adopted

Part of a larger ecosystem of big data tools and technologies

Can handle very large data sets

Cons:

Limited to batch processing of data

Can be slow and resource-intensive for certain types of workloads

**Google BigTable vs HBase vs Pig:**

1. Google BigTable: BigTable is a distributed NoSQL database developed by Google that provides a high-performance and scalable way to store and access large amounts of structured data. BigTable is designed to handle very large data sets and provides a flexible schema-less data model.

Pros:

High-performance and scalable

Designed to handle very large data sets

Flexible schema-less data model

Cons:

Proprietary technology developed by Google

Limited support for data processing and analysis outside of Google's ecosystem

2. HBase: HBase is an open-source, NoSQL database that is part of the Hadoop ecosystem. HBase provides a distributed and scalable way to store and access large amounts of structured data. HBase is designed to be compatible with the Hadoop Distributed File System (HDFS) and can be used in conjunction with other Hadoop tools and technologies.

Pros:

Open-source and widely adopted

Part of a larger ecosystem of big data tools and technologies

Distributed and scalable

Cons:

Can have performance issues with large data sets and complex queries

Steep learning curve and complex configuration

3. Pig: Pig is a high-level platform for creating MapReduce programs used with Hadoop. Pig provides a higher-level data processing language that abstracts away much of the complexity of writing MapReduce programs.

Pros:

High-level data processing language that abstracts away much of the complexity of MapReduce programming

Integrates well with the Hadoop ecosystem

Cons:

Performance can be slow for certain types of workloads

Steep learning curve for those unfamiliar with the Pig Latin language

**HIVE:**

Hive is a data warehousing and SQL-like query language for Hadoop that provides a high-level, flexible and scalable way to perform data analysis on large data sets. Hive provides an interface for querying data stored in the Hadoop Distributed File System (HDFS) and can also be used in conjunction with other Hadoop tools and technologies.

Pros:

Provides a high-level, flexible, and scalable way to perform data analysis on large data sets

Integrates well with the Hadoop ecosystem

Supports SQL-like query language

Cons:

Performance can be slow for certain types of workloads

Steep learning curve for those unfamiliar with HiveQL language

**YARN:**

YARN (Yet Another Resource Negotiator) is a resource management system for Hadoop that provides a centralized platform for managing and allocating computing resources in a Hadoop cluster. YARN allows multiple data processing frameworks, such as MapReduce, Spark, and others, to run on the same cluster, improving resource utilization and enabling a more flexible and scalable big data processing environment.

Pros:

Centralized platform for managing and allocating computing resources in a Hadoop cluster

Allows multiple data processing frameworks to run on the same cluster

Improves resource utilization and enables a more flexible and scalable big data processing environment

Cons:

Complex to set up and manage

Overhead for resource management can impact performance for certain types of workloads
