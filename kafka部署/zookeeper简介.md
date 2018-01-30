#kafka部署
---
一、kafka特性

（1）高吞吐量：每秒处理几十万条数据，它的延迟最低只有几毫秒。
（2）可拓展性：kafka集群支持热拓展
（3）持久性、可靠性：消息可以被持久化到本地磁盘

二、基本概念
http://blog.csdn.net/hmsiwtv/article/details/46960053

![kafka关系](http://www.aboutyun.com/data/attachment/forum/201505/02/225851j2s4eq67aq9llaol.png "这是CSDN的图标")



#kafka名词解释
后面大家会看到一些关于kafka的名词，比如topic、producer、consumer、broker，我这边来简单说明一下。



producer：生产者，就是它来生产“鸡蛋”的。

consumer：消费者，生出的“鸡蛋”它来消费。

topic：你把它理解为标签，生产者每生产出来一个鸡蛋就贴上一个标签（topic），消费者可不是谁生产的“鸡蛋”都吃的，这样不同的生产者生产出来的“鸡蛋”，消费者就可以选择性的“吃”了。

broker：就是篮子了。

大家一定要学会抽象的去思考，上面只是属于业务的角度，如果从技术角度，topic标签实际就是队列，生产者把所有“鸡蛋（消息）”都放到对应的队列里了，消费者到指定的队列里取

#kafka官方文档
http://ifeve.com/kafka-1/


