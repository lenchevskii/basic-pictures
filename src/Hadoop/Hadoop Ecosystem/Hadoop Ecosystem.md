#### Oozie

```
It is a workflow scheduler system to manage Apache Hadoop jobs. It connects many
jobs sequentially into one consistent piece of work. Oozie framework is fully
integrated with Apache Hadoop stack and Yarn as an architectural center. In
addition, it supports Hadoop jobs for such platforms as Apache Sqoop, Mapreduce,
Hive and Pig. Oozie is scalable and very much flexible. Therefore, it is easy to
start, stop, suspend and return jobs as well as return failed workflows. It
allows for skipping a specific failure node. There are two basic types of Oozie
jobs. First is Oozie workflow — it stores and draws the workflows composed of
Hadoop jobs. Second is Oozie coordinator — it transports workflow jobs based on
predefined schedules and availability of data.
```

#### HCatalog

```
It is a table and storage management layer on top of Apache Hadoop. Hcatalog is
a main component of Hive. Hence, it enables users to store their data in any
format and any structure. It also supports different Hadoop components to easily
read and write from the cluster. The advantages of the Hcatalog are the following.
It provides visibility for data cleaning and archiving tools. Furthermore, with a
table abstraction, HCatalog freezes the user from the overhead of data storage.
It enables notifications of data availability. HCatalog is an open source tool
allowing for data exchange services and data serialization for Hadoop. Using
serialization, service programs can serialize data into files or messages. Also,
it stores data and its definitions together in one message or file. Consequently,
this makes it easy for programs to dynamically understand information stored in
every file or a message.
```

#### Hive

```
Apache Hive is an open source data warehouse system used for querying and analyzing
large data sets stored in Hadoop files. In Hadoop, it is responsible for processing
structured and semi-structured data. Hive also supports the analysis of large data
sets stored in HDFS and an Amazon S3 file system. Hive uses the language called HiveQL,
which is similar to SQL. HiveQL automatically translates SQL queries into MapReduce
jobs. It is a high-level language platform created to perform queries on enormous
datasets that are held in Hadoop HDFS.
```

#### Pig

```
Pig Latin is a language used in Pig, which is very similar to SQL. Pig loads the data,
applies the required filters and dumps the data in the required format. Pig also
converts all the information into map and reduced tasks that are effectively processed
on Hadoop. Currently, it's mostly deprecated.
```

#### Mahout

```
It is an open source framework used for creating a scalable machine learning
algorithm. As soon as data is kept in HDFS, Mahout gives the data science tools
to detect important patterns in those large data sets automatically.
```

#### Drill

```
Drill is used for large scale data processing. Its main goal is to scale to
several thousands of nodes and query petabytes of data. Actually, Drill is a low
latency, distributed, open source, query engine for big-scale sets of data.
It is also the first distributed SQL query engine that has a schema-free model.
```

#### Avro

```
AVRO provides a container file to store persistence data. Remote procedure call
(RPC) reaches data structures. It's compact, fast, binary data format. AVRO
a provides container file to start persistent data, remote procedure call, reach
data structures and call back binary data format fast. Apache Thrift is a software
framework that allows for scalable cross-language service development.
Thrift is also used for RPC communication. Apache Hadoop does a lot of RPC calls.
Therefore, there is a possibility of using Thrift for performance.
```

#### Thrift

```
Apache Thrift serves for developing scalable cross-language services. It unites a
software stack with a code generation engine to create services that run
seamlessly and effectively between various programming languages, such as, Python,
C++, Java, PHP, Erlang, Ruby, Perl, C#, Haskell, JavaScript, Cocoa, Node.js,
Smalltalk, Delphi and OCaml.
```

#### Hbase

```
It is a no SQL database that runs on top of Hadoop. It is a database that stores
structured data in tables that could have billions of rows and millions of columns.
H-Base also provides Real-Time access to read or write data in HDFS. The components
of Hbase are H-Base Master, Region server, AV master, which is not part of the actual
data storage, but it just performs administration like interface for creating,
updating and deleting tables. The region server is the worker node — it handles reads,
writes, updates and deletes requests from clients region server. Also, the process
works on all nodes in the Hadoop cluster.
```

#### Sqoop

```
It is manually used for importing and exporting data. Specifically, it can import
data from external sources into related Hadoop components like HDFS, Hbase or Hive,
and export data from Hadoop to other external sources. Sqoop supports such relational
databases as Oracle, Netezza and MySQL.
```

#### Flume

```
The system efficiently collects, aggregates and moves a large amount of data from its
origin and then sends it back to HDFS. Flume's architecture is extremely flexible and
simple and rests on streaming data flows. It is complex and also a reliable mechanism.
Flume enables data to flow from the source into the Hadoop environment. Additionally,
it uses a simple extensible data model that allows for the online analytic application.
Hence, utilizing Flume, it becomes possible to extract the data from many servers and
deliver it immediately to Hadoop.
```

#### Zookeeper

```
Hadoop infrastructure is very complex and consists of multiple servers and even
clusters. Zookeeper is used for a cluster node configuration. It is a centralized
service in Hadoop, which maintains configuration information, naming as provide
distributed synchronization. Additionally, it provides group services, manages and
coordinates a large cluster of machines. Zookeeper is fast thanks to the fact that
workloads where reads data are more common than writes. The ideal read-write ratio
is ten to one, it's also ordered. Zookeeper supports a record of all transactions,
which can be used for a high level.
```

#### Apache Ambari

```
It is an open source management platform for provisioning, managing, monitoring and
securing Apache Hadoop cluster. Hadoop management gets simpler because Ambari provides
a consistent and secure platform for operational control.
```

#### MapReduce

```
It is a batch processing engine, which is Mapreduce. It is currently deprecated and
replaced with Spark. We will briefly go through the Mapreduce in this course but the
general message is that whenever you need batch processing, don’t use MapReduce. Better
consider using some other technologies like Spark, Link.
```

#### Yarn

```
Hadoop provides resources and costs a management layer via YARN.
```

#### HDFS

```
Hadoop provides a storage layer via HDFS.
```
