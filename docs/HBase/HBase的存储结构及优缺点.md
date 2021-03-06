## Hbase的存储结构及优缺点

![](../../pictures/hbase逻辑结构.png)

**Hbase的优点及应用场景**:

1. 半结构化或非结构化数据: 
   对于数据结构字段不够确定或杂乱无章非常难按一个概念去进行抽取的数据适合用HBase，因为HBase支持动态添加列。
2. 记录很稀疏： 
   RDBMS的行有多少列是固定的。为null的列浪费了存储空间。HBase为null的Column不会被存储，这样既节省了空间又提高了读性能。
3. 多版本号数据： 
   依据Row key和Column key定位到的Value能够有随意数量的版本号值，因此对于须要存储变动历史记录的数据，用HBase是很方便的。比方某个用户的Address变更，用户的Address变更记录也许也是具有研究意义的。
4. 仅要求最终一致性： 
   对于数据存储事务的要求不像金融行业和财务系统这么高，只要保证最终一致性就行。（比如HBase+elasticsearch时，可能出现数据不一致）
5. 高可用和海量数据以及很大的瞬间写入量： 
   WAL解决高可用，支持PB级数据，put性能高
   适用于插入比查询操作更频繁的情况。比如，对于历史记录表和日志文件。（HBase的写操作更加高效）
6. 业务场景简单： 
   不需要太多的关系型数据库特性，列入交叉列，交叉表，事务，连接等。

**Hbase的缺点：**

1. 单一RowKey固有的局限性决定了它不可能有效地支持多条件查询
2. 不适合于大范围扫描查询
3. 不直接支持 SQL 的语句查询



[参考文章1](<https://www.iteye.com/blog/forlan-2364661>)

[参考文章2](<https://blog.csdn.net/liaynling/article/details/81199238>)

[参考文章3](<https://juejin.im/post/5c31cf486fb9a04a102f6f89#heading-2>)