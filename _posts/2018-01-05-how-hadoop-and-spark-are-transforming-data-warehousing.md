---
layout: post
current: post
cover:  assets/images/posts/warehouse.jpg
navigation: True
title: How Hadoop and Spark Are Transforming Data Warehousing
date: 2018-01-05 11:27:10
tags: [Hadoop, Spark, Big Data, Data Warehouse]
class: post-template
subclass: 'post tag-elastic-stack'
logo: assets/images/ghost.png
author: pranav
crosspost_to_medium: false
---

<p>Traditional data warehouses cannot handle big data. Hadoop, Spark, Impala, Parquet and SQL on Hadoop will play big role in data warehouse modernization.</p>

<hr />

<p>The nature of data that enterprises have been dealing with has been changing in the last few years. It is no longer just transactional data. Volume, velocity, and variety of data is increasing steadily. Why should you care? If your organization is not capturing, storing and analyzing new types of data, your organization is potentially losing a competitive edge. Or put it the other way, leveraging this new type of data can give you a competitive edge.  
</p>

<p>
In this and following articles, I am going to cover –
</p>

<ul>
<li>How data warehouses are excellent at dealing with structured data</li>
<li>Rise of unconventional data</li>
<li>Short-comings of traditional data warehouses</li>
<li>How Hadoop ecosystem and Apache Spark can help?</li>
</ul>

<h2>How data warehouses are excellent at dealing with structured data</h2>

<p>
Business Intelligence, analytics, and data warehousing are mature fields that have existed for more than three decades. Business Intelligence softwares are typically powered by an underlying data warehouse and data mart(s). Traditional data warehouses and data marts rely on relational databases like Oracle, Teradata, MySQL and the like following star schema. SQL constructs make slicing, dicing, drill down/up of data possible along different dimensions.  
</p>

<p>
Data warehouses have worked nicely and they continue to serve the purpose. Most of this data has been highly structured data, i.e. transactional data most suitable for relational databases. But what about big data, the new type of unconventional data that is semi-structured or unstructured? What about data coming at very high velocity at thousands or millions of events per second?
</p>

<h2>Rise of unconventional data</h2>

<p>
A lot has been written and said about how data is growing and about the 3 (or 4) V’s (Volume, Velocity, Variety, and Veracity). Sensor data, smart phones, images, social media, and machine logs are new types of unstructured and semi-structured data. They can be effectively used to gain a competitive edge.  
</p>

<p>
Traditional data warehouses cannot handle these new types of data, they can’t handle all the V’s. The associated costs are prohibitive due to licensing and infrastructure costs.
</p>

<h2>Short-comings of traditional data warehouses</h2>

<p>
<strong>Inability to deal with 3 V’s.</strong> Hard to efficiently handle the 3 V’s without breaking the bank. Besides there is no efficient way of handling unstructured and semi-structured data.
</p>
<p>
<strong>Lots of ETL.</strong> Moving data the from source transactional systems (OLTP systems) require a number of ETL jobs to move data around and transform it to the target data mart.
</p>
<p>
<strong>Inability to retain data.</strong> High storage costs means data needs to be archived to tapes and becomes inaccessible forever.
</p>
<h2>How Hadoop ecosystem and Apache Spark can help?</h2>

<p>
Hadoop ecosystem has come a long way since its inception around 2005. It has proven itself in handling the famous 3 V’s. Lots of research has gone into distributed file systems, storage formats, distributed computing, SQL-on-Hadoop engines, security etc.
</p>

<p>
Hadoop’s MapReduce framework was traditionally used to do analysis on the hadoop data. Apache Spark is a distributed computing framework that can run on HDFS, Amazon S3 and perform in-memory fast analytics. Spark is 10x to 100x faster than MapReduce even when all the data cannot fit in the cluster’s memory. 
</p>

<p>
Storage – HDFS, Amazon S3 are two widely used resilient and distributed file systems that can scale from terabytes to petabytes/exabytes. 
</p>

<p>
Storage formats – Special purpose efficient columnar storage formats like Parquet have evolved to enable fast analytics queries. 
</p>

<p>
SQL-on-Hadoop engines – Cloudera’s Impala, Spark-SQL and Apache Drill are distributed query engines providing low latency interactive SQL queries on HDFS files.  
</p>

<p>
The SQL-on-Hadoop engines are getting faster by the day to catch up with the speeds of relational databases. They also support JDBC/ODBC connectivity via third party applications. The availability of JDBC/ODBC connectivity means that existing BI tools like OBIEE, Tableau, Microstrategy, Qlik and others can connect and query the big data.  
</p>

<p>
While traditional data warehouses are here to stay, at least in the near future. Hadoop ecosystem, spark and other NoSQL databases can help in modernizing your BI infrastructure, by providing the ability to store and analyze new types of unstructured, semi structured, high volume, high velocity data.
</p>

<p>
Are you looking to modernize your DW/BI infrastructure?
</p>


<em>Originally published at </em>

<a href="http://brevitaz.com/hadoop-spark-data-warehousing-business-intelligence/" data-href="http://brevitaz.com/hadoop-spark-data-warehousing-business-intelligence/" rel="canonical" target="_blank"><em>http://brevitaz.com/hadoop-spark-data-warehousing-business-intelligence/</em></a>

<em> on May 10, 2016.</em>

