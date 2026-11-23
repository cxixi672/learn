# backend 主题覆盖

## 已覆盖
- Go：channel 的 nil/关闭语义（backend-20261123-01）
- Go：context 取消传播与 cancel 释放（backend-20261123-02）
- Java：HashMap 数据结构、扩容与树化（backend-20261123-03）
- Java：volatile 与 synchronized、JMM 可见性与原子性（backend-20261123-04）
- MySQL：B+ 树索引、回表、覆盖索引、最左前缀（backend-20261123-05）
- MySQL：REPEATABLE READ 下的快照读、当前读与幻读（backend-20261123-06）
- Redis：缓存穿透、击穿、雪崩（backend-20261123-07）
- Redis：RDB 与 AOF 持久化（backend-20261123-08）
- 网络：TCP 四次挥手、TIME_WAIT、CLOSE_WAIT（backend-20261123-09）
- 操作系统：select/poll/epoll 与 LT/ET（backend-20261123-10）

## 未覆盖
- Go：GC、调度器（GMP）、逃逸分析
- Go：sync 包（Mutex、WaitGroup、Once、Pool）与内存模型
- Java：类加载机制、G1/ZGC 等垃圾回收器、线程池参数
- Java：AQS 与 ReentrantLock
- MySQL：binlog/redo log/undo log、两阶段提交、锁类型
- MySQL：EXPLAIN 执行计划与慢查询优化
- Redis：数据结构底层编码、主从复制与哨兵、Cluster 分片
- Redis：分布式锁实现细节（Redlock 争议）
- 网络：HTTP/1.1 与 HTTP/2、HTTPS 握手、拥塞控制
- 操作系统：进程与线程切换开销、虚拟内存与页表、零拷贝
