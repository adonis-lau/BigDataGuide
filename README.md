## 目录

## Hadoop

* ##### [Hadoop介绍](docs/Hadoop/Hadoop介绍.md)

* ##### [HDFS架构](docs/Hadoop/HDFS架构.md)

* ##### [Yarn架构](docs/Hadoop/Yarn架构.md)

* ##### [MapReduce过程](docs/Hadoop/MapReduce过程.md)

* ##### [Yarn调度MapReduce过程](docs/Hadoop/Yarn调度MapReduce过程.md)

* ##### [HDFS写流程](docs/Hadoop/HDFS写流程.md)

* ##### [HDFS读流程](docs/Hadoop/HDFS读流程.md)

* ##### [HDFS创建一个文件的流程](docs/Hadoop/HDFS创建一个文件的流程.md)

* ##### [Hadoop1.x 和Hadoop 2.x 的区别](docs/Hadoop/Hadoop1.x 和Hadoop 2.x 的区别.md)

* ##### [Hadoop1.x的缺点](docs/Hadoop/Hadoop1.x的缺点.md)

* ##### [Hadoop HA介绍](docs/Hadoop/Hadoop HA介绍.md)

* ##### [Hadoop的常用配置文件有哪些](docs/Hadoop/Hadoop的常用配置文件有哪些.md)

* ##### [小文件过多会有什么危害,如何避免?](docs/Hadoop/小文件过多会有什么危害,如何避免?.md)

* ##### [启动Hadoop集群会分别启动哪些进程,各自的作用](docs/Hadoop/启动Hadoop集群会分别启动哪些进程,各自的作用.md)

## [Hive](docs/Hive)

* ##### [Hive内部表和外部表的区别](docs/Hive/Hive内部表和外部表的区别.md)

* ##### [Hive四种排序方式的区别](docs/Hive/Hive四种排序方式的区别.md)

* ##### [Hive的metastore的三种模式](docs/Hive/Hive的metastore的三种模式.md)

* ##### [Hive中join都有哪些](docs/Hive/Hive中join都有哪些.md)

* #####  [Impala 和 Hive 的查询有哪些区别](docs/Hive/Impala 和 Hive 的查询有哪些区别.md)

* ##### [Hive中大表JOIN小表的优化方法](docs/Hive/Hive中大表JOIN小表的优化方法.md)

* ##### [Hive SQL 是怎样解析成MR JOB的?](docs/Hive/Hive SQL 是怎样解析成MR JOB的?.md)

* ##### [Hive UDF简单介绍](docs/Hive/Hive UDF简单介绍.md)

* ##### [Hive SQL : 按照学生科目取每个科目的TopN](docs/Hive/Hive SQL : 按照学生科目取每个科目的TopN.md)

## [Hbase](docs/Hbase)

* ##### [Hbase的架构](docs/Hbase/Hbase的架构.md)

* ##### [Hbase 如何设计RowKey](docs/HBase/Hbase 如何设计RowKey.md)

* ##### [Hbase的存储结构及优缺点](docs/HBase/Hbase的存储结构及优缺点.md)

* ##### [Hbase的HA实现,Zookeeper在其中的作用](docs/HBase/Hbase的HA实现,Zookeeper在其中的作用.md)

* ##### [HMaster宕机的时候,哪些操作还能正常工作](docs/HBase/HMaster宕机的时候,哪些操作还能正常工作.md)

* ##### [Hbase写数据的流程](docs/HBase/Hbase写数据的流程.md)

* ##### [Hbase读数据的流程](docs/HBase/Hbase读数据的流程.md)

## [Spark](docs/Spark)

##### [Spark的运行架构](docs/Spark/Spark的运行架构.md)

##### [Spark程序的执行流程](docs/Spark/Spark程序的执行流程.md)

##### [Spark的shuffle介绍](docs/Spark/Spark的shuffle介绍.md)

##### [Spark的 partitioner 都有哪些](docs/Spark/Spark的 partitioner 都有哪些.md)

##### [Spark有哪几种join](docs/Spark/Spark有哪几种join.md)

##### [RDD有哪些特点](docs/Spark/RDD有哪些特点.md)

##### [宽依赖和窄依赖](docs/Spark/宽依赖和窄依赖.md)

##### [Spark中的算子都有哪些](docs/Spark/Spark中的算子都有哪些.md)

##### [RDD的缓存级别都有哪些](docs/Spark/RDD的缓存级别都有哪些.md)

##### [RDD懒加载是什么意思](docs/Spark/RDD懒加载是什么意思.md)

##### [Spark的几种部署方式](docs/Spark/Spark的几种部署方式.md)

##### [SparkOnYarn模式下的Cluster模式和Client模式区别](docs/Spark/SparkOnYarn模式下的Cluster模式和Client模式区别.md)

##### [Spark运行原理,从提交一个jar到最后返回结果,整个过程](docs/Spark/Spark运行原理,从提交一个jar到最后返回结果,整个过程.md)

##### [Spark的stage是如何划分的](docs/Spark/Spark的stage是如何划分的.md)

##### [Spark2.0为什么放弃了akka而用netty](docs/Spark/Spark2.0为什么放弃了akka而用netty.md)

##### [Spark的各种HA,master、worker、executor的HA](docs/Spark/Spark的各种HA,master、worker、executor的HA.md)

##### [Spark的内存管理机制](docs/Spark/Spark的内存管理机制.md)

##### [Spark中的广播变量](docs/Spark/Spark中的广播变量.md)

##### [什么是数据倾斜,怎样去处理数据倾斜](docs/Spark/什么是数据倾斜,怎样去处理数据倾斜.md)

##### [Spark代码中哪些部分在Driver端执行,哪些部分在Worker端执行](docs/Spark/Spark代码中哪些部分在Driver端执行,哪些部分在Worker端执行.md)

## [Flink](docs/Flink)

##### [Flink的运行架构](docs/Flink/Flink的运行架构.md)

##### [Flink的作业执行流程](docs/Flink/Flink的作业执行流程.md)

##### [Flink具体是如何实现exactly-once语义](docs/Flink/Flink具体是如何实现exactly-once语义.md)

##### [Flink的window实现机制](docs/Flink/Flink的window实现机制.md)

##### [Flink的window分类](docs/Flink/Flink的window分类.md)

##### [Flink的state是存储在哪里的](docs/Flink/Flink的state是存储在哪里的.md)

##### [Flink是如何实现反压的](docs/Flink/Flink是如何实现反压的.md)

##### [Flink的部署模式都有哪些](docs/Flink/Flink的部署模式都有哪些.md)

##### [Flink-on-yarn的部署](docs/Flink/Flink-on-yarn的部署.md)

##### [Flink中的时间概念，eventTime和processTime的区别](docs/Flink/Flink中的时间概念，eventTime和processTime的区别.md)

##### [Flink中的sessionWindow怎样使用](docs/Flink/Flink中的sessionWindow怎样使用.md)

## [Kafka](docs/Kafka)

##### [Kafka的架构](docs/Kafka/Kafka的架构.md)

##### [Kafka与其他消息组件对比](docs/Kafka/Kafka与其他消息组件对比.md)

##### [Kafka实现高吞吐的原理](docs/Kafka/Kafka实现高吞吐的原理.md)

##### [Kafka怎样保证不重复消费](docs/Kafka/Kafka怎样保证不重复消费.md)

##### [Kafka怎样保证不丢失消息](docs/Kafka/Kafka怎样保证不丢失消息.md)

##### [Kafka与sparkStreaming集成,如何保证exactly-once语义](docs/Kafka/Kafka与sparkStreaming集成,如何保证exactly-once语义.md)

##### [Ack有哪几种,生产中怎样选择](docs/Kafka/Ack有哪几种,生产中怎样选择.md)

##### [如何通过offset寻找数据](docs/Kafka/如何通过offset寻找数据.md)

##### [如何清理过期数据](docs/Kafka/如何清理过期数据.md)

##### [1条message中包含哪些信息](docs/Kafka/1条message中包含哪些信息.md)

##### [Zookeeper在Kafka中的作用](docs/Kafka/Zookeeper在Kafka中的作用.md)

##### [Kafka可以脱离zookeeper单独使用吗](docs/Kafka/Kafka可以脱离zookeeper单独使用吗.md)

##### [Kafka有几种数据保留策略](docs/Kafka/Kafka有几种数据保留策略.md)

##### [Kafka同时设置了7天和10G清除数据,到第5天的时候消息到达了10G,这个时候kafka如何处理?](docs/Kafka/Kafka同时设置了7天和10G清除数据,到第5天的时候消息到达了10G,这个时候kafka如何处理?.md)

## [Zookeeper](docs/Zookeeper)

##### [Zookeeper是什么,有什么功能](docs/Zookeeper/Zookeeper是什么,有什么功能.md)

##### [ZK的几种部署模式](docs/Zookeeper/ZK的几种部署模式.md)

##### [ZK是怎样保证主从节点的状态同步](docs/Zookeeper/ZK是怎样保证主从节点的状态同步.md)

##### [ZK的通知机制](docs/Zookeeper/ZK的通知机制.md)

##### [ZK的分布式锁实现方式](docs/Zookeeper/ZK的分布式锁实现方式.md)

##### [ZK采用的哪种分布式一致性协议?还有哪些分布式一致性协议](docs/Zookeeper/ZK采用的哪种分布式一致性协议?还有哪些分布式一致性协议.md)

##### [leader选举过程](docs/Zookeeper/leader选举过程.md)

### 备战面试

* [【备战面试1】程序员的简历就该这样写](docs/essential-content-for-interview/PreparingForInterview/程序员的简历之道.md)
* [【备战面试2】初出茅庐的程序员该如何准备面试？](docs/essential-content-for-interview/PreparingForInterview/interviewPrepare.md)
* [【备战面试3】7个大部分程序员在面试前很关心的问题](docs/essential-content-for-interview/PreparingForInterview/JavaProgrammerNeedKnow.md)
* [【备战面试4】Github上开源的Java面试/学习相关的仓库推荐](docs/essential-content-for-interview/PreparingForInterview/JavaInterviewLibrary.md)
* [【备战面试5】如果面试官问你“你有什么问题问我吗？”时，你该如何回答](docs/essential-content-for-interview/PreparingForInterview/如果面试官问你“你有什么问题问我吗？”时，你该如何回答.md)
* [【备战面试6】美团面试常见问题总结（附详解答案）](docs/essential-content-for-interview/PreparingForInterview/美团面试常见问题总结.md)

### 常见面试题总结

* [第一周（2018-8-7）](docs/essential-content-for-interview/MostCommonJavaInterviewQuestions/第一周（2018-8-7）.md) (为什么 Java 中只有值传递、==与equals、 hashCode与equals)
* [第二周（2018-8-13）](docs/essential-content-for-interview/MostCommonJavaInterviewQuestions/第二周(2018-8-13).md)(String和StringBuffer、StringBuilder的区别是什么？String为什么是不可变的？、什么是反射机制？反射机制的应用场景有哪些？......)
* [第三周（2018-08-22）](docs/java/collection/Java集合框架常见面试题.md) （Arraylist 与 LinkedList 异同、ArrayList 与 Vector 区别、HashMap的底层实现、HashMap 和 Hashtable 的区别、HashMap 的长度为什么是2的幂次方、HashSet 和 HashMap 区别、ConcurrentHashMap 和 Hashtable 的区别、ConcurrentHashMap线程安全的具体实现方式/底层具体实现、集合框架底层数据结构总结）
* [第四周(2018-8-30).md](docs/essential-content-for-interview/MostCommonJavaInterviewQuestions/第四周(2018-8-30).md) （主要内容是几道面试常问的多线程基础题。）

### 面经

- [5面阿里,终获offer(2018年秋招)](docs/essential-content-for-interview/BATJrealInterviewExperience/5面阿里,终获offer.md)
- [蚂蚁金服2019实习生面经总结(已拿口头offer)](docs/essential-content-for-interview/BATJrealInterviewExperience/蚂蚁金服实习生面经总结(已拿口头offer).md)
- [2019年蚂蚁金服、头条、拼多多的面试总结](docs/essential-content-for-interview/BATJrealInterviewExperience/2019alipay-pinduoduo-toutiao.md)

## 工具

### Git

* [Git入门](docs/tools/Git.md)

### Docker

* [Docker 入门](docs/tools/Docker.md)
* [一文搞懂 Docker 镜像的常用操作！](docs/tools/Docker-Image.md)

## 资料

### 书单

- [大数据程序员必备书单](docs/data/bigdata-recommended-books.md)

### Github榜单

- [大数据项目月榜单](docs/github-trending/BigDataGithubTrending.md)

***

## 说明

### 介绍

*  **对于 大数据 初学者来说：** 本文档倾向于给你提供一个比较详细的学习路径，让你对于Java整体的知识体系有一个初步认识。另外，本文的一些文章
也是你学习和复习 大数据 知识不错的实践；
*  **对于非 大数据 初学者来说：** 本文档更适合回顾知识，准备面试，搞清面试应该把重心放在那些问题上。要搞清楚这个道理：提前知道那些面试常见，不是为了背下来应付面试，而是为了让你可以更有针对的学习重点。

Markdown 格式参考：[Github Markdown格式](https://guides.github.com/features/mastering-markdown/)，表情素材来自：[EMOJI CHEAT SHEET](https://www.webpagefx.com/tools/emoji-cheat-sheet/)。

利用 docsify 生成文档部署在 Github pages: [docsify 官网介绍](https://docsify.js.org/#/)

### 关于转载

如果你需要转载本仓库的一些文章到自己的博客的话，记得注明原文地址就可以了。

### 如何对该开源文档进行贡献

1. 笔记内容大多是手敲，所以难免会有笔误，你可以帮我找错别字。
2. 很多知识点我可能没有涉及到，所以你可以对其他知识点进行补充。
3. 现有的知识点难免存在不完善或者错误，所以你可以对已有知识点的修改/补充。

### 为什么要做这个开源文档？

初始想法源于自己的个人那一段比较迷茫的学习经历。主要目的是为了通过这个开源平台来帮助一些在学习大数据知识或者面试过程中遇到问题的小伙伴。

### Contributor

下面是笔主收集的一些对本仓库提过有价值的pr或者issue的朋友，人数较多，如果你也对本仓库提过不错的pr或者issue的话，你可以加我的微信与我联系。下面的排名不分先后！

<a href="https://github.com/adonis-lau">
    <img src="https://avatars0.githubusercontent.com/u/14901776?s=460&v=4" width="45px"></a>

