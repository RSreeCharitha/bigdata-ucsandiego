# HDFS Architecture

1.HDFS is strictly POSIX compliant.

- False

2.Following issues may be caused by lot of small files in HDFS

- NameNode memory usage increases significantly
- Number of map tasks need to process the same amount of data will be larger.

3.You are writing a 10GB file to a HDFS filesystem with a default block size of 128MB. How many blocks will the file be broken into?
- 80

4.You are writing a 10GB file into HDFS with a replication of 2 and block size of 64MB. How much total disk space will this file use?
- 20GB

5.What is the first step in a write process from a HDFS client?

- Start locally caching the data that needs to be written and then contact NameNode


6.HDFS NameNode is not rack aware when it places the replica blocks.

- False
