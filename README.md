# 面试题

## Go 语言

GMP 调度模型

Context 的用法

Go 的垃圾回收

Go 的逃逸分析


## 操作系统&计算机网络
select 和 epoll

进程的调度

HTTP 和 HTTPS 的区别。

TCP 拥塞控制。

HTTPS 的加密过程，需要几次通信

三次握手和四次挥手，说一下 time_wait。

用过哪些锁，自旋锁和互斥锁有什么区别。（同学们锁一定好好复习，也是必考点之一）

用过哪些分布式锁。答了 mysql，redis， zookeeper 分别聊了一下优缺点。

redis setnx + expire 有什么缺点，如何优化。因为之前自己用过，所以答上来了，但是好像不是面试官想要的最优解。

打开一个 URL 的过程。（这个也是必考点，基本上每个人都会，所以尽量说点其他人不知道的，一定要有自己的思考，让面试官眼前一亮，而不是觉得你在背书）


## 数据库

Mysql 用的是什么数据结构

大库 DDL 怎么做比较好

Mysql 的幻读是怎么个情况，Mysql 是如何避免的。

B 树 和 B+ 树的区别，为什么 mysql 要用 B+ 树，mongodb 要用 B 树。

redis 的跳表知道吗，为什么不用红黑树。我回答了因为红黑树实现比跳表复杂。但是面试官不是很满意，后来查了一下是有这部分原因的。

redis 集群是怎么实现的，说一下一致性 hash。

Mysql 集群如何保证数据的一致性




## 中间件

rabbitmq 的工作原理

kafka 的工作原理

## 架构

设计一个海量的评论系统

设计一个微信朋友圈系统，列出主要的表结构，只需要实现一些基础的功能，比如聊天列表等。写出一些数据结构，然后和面试官讨论了一下，很快就过了。

类似于设计一个长链接转短链接，不过需要考虑高并发，回答了分库分表。

mysql 集群在保证强一致性的情况下，如何保证高并发。聊了好多种方法，但是面试官都不是很满意，中间磕磕绊绊的。最后问可不可以用缓存，我前面提到了使用 redis 中间做一层，但是面试官说用 memcache。。。

 设计一个海量日志写入系统

 
