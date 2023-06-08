1. redis 内存快满了会怎么样
2. . 缓存雪崩，击穿，穿透
3. 单线程模式
4. 分布式锁
5. 怎么做数据备份，aof,rdb
6. 集群方案
7. 为什么高性能
8. redis内部结构(zset常问),常用数据结构
		![[img20230417145114.png]] 
		![[img20230417144351.png]]
9. 与memcache什么区别
	*  Redis 支持的数据类型更丰富（String、Hash、List、Set、ZSet），而 Memcached 只支持最简单的 key-value 数据类型；
	-   Redis 支持数据的持久化，可以将内存中的数据保持在磁盘中，重启的时候可以再次加载进行使用，而 Memcached 没有持久化功能，数据全部存在内存之中，Memcached 重启或者挂掉后，数据就没了；
	-   Redis 原生支持集群模式，Memcached 没有原生的集群模式，需要依靠客户端来实现往集群中分片写入数据；
	-   Redis 支持发布订阅模型、Lua 脚本、事务等功能，而 Memcached 不支持；
	-   Redis 支持发布订阅模型、Lua 脚本、事务等功能，而 Memcached 不支持；
	  
	* 基于内存的数据库，多用做缓存，都有过期策略，性能都很高
10. 与mongo有什么区别
11. redis是单线程吗