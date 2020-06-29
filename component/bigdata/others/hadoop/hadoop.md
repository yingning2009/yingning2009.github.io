###Hadoop
####简介
Hadoop主要是指由MapReduce和Hdfs组成的分布式基础架构，而在广义上一般指Hadoop生态圈，它起源于Apache Nutch项目，在Google公开了部分GFS和MapReduce思想后，Doug Cutting为了提升Nutch性能，完成了其实现，并在Nutch 0.8版本之后，剥离出Hadoop。
Hadoop目前主要有三大发行版本，分别为Apache、Cloudera和Hortonworks，其中我们学习一般使用Apache版本，而Cloudera在企业中的应用则更为广泛。
####组成

如图，在Hadoop1.x时代，它主要是由MapReduce和HDFS组成，而在Hadoop2.x时代则增加了负责资源调度的Yarn来解耦两者的耦合性。