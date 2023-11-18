#### NameNode

```
NameNode is a master server that exists in the HDFS cluster. It manages the file system namespace by executing an operation like the opening, renaming and closing files. Also, it simplifies the architecture of the system. A NameNode handles the file system namespace and regulates access to files by clients. Client applications communicate to the NameNode at any time they need to locate a file, or when the file should be added, copied, moved or deleted. The NameNode responds back with the successful requests by returning a list of relevant DataNode servers where the data lives.
```

#### DataNode

```
DataNode represents the second layer of Hadoop architecture. A DataNode manages the state of an HDFS node and interacts with the blocks. It can perform jobs like semantic and language analysis, statistics and machine learning tasks, and also jobs like clustering, data import, data export, search, decompression and indexing. On startup, every DataNode connects to the NameNode and performs a handshake to verify the namespace ID and the software version of the DataNode. The DataNode verifies the block replicas in its ownership by sending a block report to the NameNode. The DataNode sends a heartbeat to the NameNode every 3 seconds to confirm that the DataNode is operating and the block replicas it hosts are available.
```

#### YARN

```
YARN is currently known as a large-scale distributed operating system used for Big Data processing. Also, YARN allows different data processing methods like graph processing, interactive processing, stream processing as well as batch processing to run and process data stored in HDFS. Thereby, the YARN component opens the Apache Hadoop software library to different distributed applications beyond MapReduce. Moreover, in addition to resource management, Yarn performs the scheduling function.
```

#### Metastore

```
Metastore is the component whose main function is to store all the structure data of different tables and partitions in a warehouse including serializers and deserializers required to write and read data, columns and column type information, and relevant HDFS files which store the data. Metastore is the component that keeps all the structure data of the different partitions and tables in a data warehouse including column and column type information, the serializers and deserializers required to read and write data and the appropriate HDFS files where the data is stored. Also, Metastore offers two critical but frequently neglected features of the data warehouse: data discovery and data abstraction.

Without the data abstractions, a user has to provide information about data formats, extractors and loaders along with the query. At the same time, data discovery enables users to discover and explore relevant and specific data in the warehouse.
```

#### Hadoop Structure

```
Hadoop Architecture comprises three major layers: HDFS (Hadoop Distributed File System), Yarn and MapReduce. HDFS provides for data storage of Hadoop; MapReduce is the data processing layer of Hadoop; and YARN or Yet Another Resource Negotiator is the resource management layer of Hadoop. In Hadoop architecture, one masternode and multiple datanodes are available. As was already mentioned, masternode’s function is to assign a task to various datanodes and manage resources. The datanodes do actual computing. They store the real data whereas on master we have metadata. This means it stores data about data.
```

#### HDFS

```
The primary objective of HDFS is to store data reliably even in the presence of failures including NameNode failures, DataNode failures and network partitions. HDFS architecture includes NameNode, multiple Datanodes and blocks.

DataNode and NameNode are pieces of software created for running on commodity computers. Commonly, the user data is held in the HDFS files. The file in a file system will be split into one or more segments and/or stored in separate datanodes. These segments of a file are also known as blocks. That is to say, the smallest volume of data that HDFS can write or read is named a Block. The default size of one block is 128 MB.
```

#### Parallel Computing

```
Parallel computing is computing architecture where many independent operations are executed simultaneously in any order. Parallel processing allows for making quick work on a big data set because instead of having one processor doing all the work, you split up the task amongst many processors. Hadoop’s technology enables parallel processing, which enables parallel searching, metadata management, parallel analysis (with MapReduce) and the establishment of workflow system analysis. In particular, MapReduce provides a specific programming “template” for parallel analysis of large-scale data sets. Thus, a MapReduce job can be executed in parallel across thousands of nodes in a cluster.
```

#### Hadoop Difference

```
An RDBMS works well with structured data while the Hadoop software framework provides opportunities for effective analysis of non-structured, semi-structured or structured data. Hadoop can manage and analyze bigger amounts of data than RDBMS. RDBMS works better when the volume of data is low (in Gigabytes). However, when the data size is evaluated Petabytes, Hadoop is the best solution. What is more, Hadoop has higher throughput. RDBMS provides vertical scalability, which is also called "Scaling Up" a machine, which means you can add more resources or hardware, such as memory or CPU, to a machine in the computer cluster. While Hadoop provides horizontal scalability, which is known as "Scaling Out" a machine and means adding more machines to the existing computer clusters as a result of which Hadoop becomes a fault-tolerant.
```
