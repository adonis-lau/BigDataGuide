## 目录

- [Hadoop](#[Hadoop](docs/Hadoop))
    - [HDFS架构](#[HDFS架构](docs/Hadoop/HDFS架构.md))
    - [Yarn架构](#[Yarn架构](docs/Hadoop/Yarn架构.md))
    - [MapReduce过程](#[MapReduce过程](docs/Hadoop/MapReduce过程.md))
    - [Yarn调度MapReduce过程](#[Yarn调度MapReduce过程](docs/Hadoop/Yarn调度MapReduce过程.md))
    - [HDFS写流程](#[HDFS写流程](docs/Hadoop/HDFS写流程.md))
    - [HDFS读流程](#[HDFS读流程](docs/Hadoop/HDFS读流程.md))
    - [HDFS创建一个文件的流程读流程](#[HDFS创建一个文件的流程](docs/Hadoop/HDFS创建一个文件的流程.md))
    - [Hadoop1.x 和Hadoop 2.x 的区别](#[Hadoop1.x 和Hadoop 2.x 的区别](docs/Hadoop/Hadoop1.x 和Hadoop 2.x 的区别.md))
    - [Hadoop1.x的缺点](#[Hadoop1.x的缺点](docs/Hadoop/Hadoop1.x的缺点.md))
    - [Hadoop HA介绍的缺点](#[Hadoop HA介绍](docs/Hadoop/Hadoop HA介绍.md))
    - [Hadoop的常用配置文件有哪些](#[Hadoop的常用配置文件有哪些](docs/Hadoop/Hadoop的常用配置文件有哪些.md))
    - [小文件过多会有什么危害,如何避免?](#[小文件过多会有什么危害,如何避免?](docs/Hadoop/小文件过多会有什么危害,如何避免?.md))
    - [启动Hadoop集群会分别启动哪些进程,各自的作用](#[启动Hadoop集群会分别启动哪些进程,各自的作用](docs/Hadoop/启动Hadoop集群会分别启动哪些进程,各自的作用.md))
- [Hive](#[Hive](docs/Hive))
    - [Hive内部表和外部表的区别](#[Hive内部表和外部表的区别](docs/Hive/Hive内部表和外部表的区别.md))
    - [Hive四种排序方式的区别](#[Hive四种排序方式的区别](docs/Hive/Hive四种排序方式的区别.md))
    - [Hive的metastore的三种模式](#[Hive的metastore的三种模式](docs/Hive/Hive的metastore的三种模式.md))
    - [Hive中join都有哪些](#[Hive中join都有哪些](docs/Hive/Hive中join都有哪些.md))
    - [Impala 和 Hive 的查询有哪些区别](#[Impala 和 Hive 的查询有哪些区别](docs/Hive/Impala 和 Hive 的查询有哪些区别.md))
    - [Hive中大表JOIN小表的优化方法](#[Hive中大表JOIN小表的优化方法](docs/Hive/Hive中大表JOIN小表的优化方法.md))
    - [Hive SQL 是怎样解析成MR JOB的?](#[Hive SQL 是怎样解析成MR JOB的?](docs/Hive/Hive SQL 是怎样解析成MR JOB的?.md))
    - [Hive UDF简单介绍](#[Hive UDF简单介绍](docs/Hive/Hive UDF简单介绍.md))
    - [Hive SQL : 按照学生科目取每个科目的TopN](#[Hive SQL : 按照学生科目取每个科目的TopN](docs/Hive/Hive SQL : 按照学生科目取每个科目的TopN.md))
- [Hbase](#Hbase)
    - [Hbase的架构](#[Hbase的架构](docs/HBase/Hbase的架构.md))
    - [Hbase 如何设计RowKey](#[Hbase 如何设计RowKey](docs/HBase/Hbase 如何设计RowKey.md))
    - [Hbase的存储结构及优缺点](#[Hbase的存储结构及优缺点](docs/HBase/Hbase的存储结构及优缺点.md))
    - [Hbase的HA实现,Zookeeper在其中的作用](#[Hbase的HA实现,Zookeeper在其中的作用](docs/HBase/Hbase的HA实现,Zookeeper在其中的作用.md))
    - [HMaster宕机的时候,哪些操作还能正常工作](#[HMaster宕机的时候,哪些操作还能正常工作](docs/HBase/HMaster宕机的时候,哪些操作还能正常工作.md))
    - [Hbase写数据的流程](#[Hbase写数据的流程](docs/HBase/Hbase写数据的流程.md))
    - [Hbase读数据的流程](#[Hbase读数据的流程](docs/HBase/Hbase读数据的流程.md))
    - WAL(Write-Ahead-Log)
    - Phoenix
- [面试指南](#面试指南)
    - [备战面试](#备战面试)
    - [常见面试题总结](#常见面试题总结)
    - [面经](#面经)
- [工具](#工具)
    - [Git](#git)
    - [Docker](#Docker)
- [说明](#说明)

## [Hadoop](docs/Hadoop)

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

## 面试指南

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

