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
- Go GMP 调度器与抢占（backend-20261124-01）
- Go GC 三色标记与混合写屏障（backend-20261124-02）
- Go sync.Mutex 正常/饥饿模式（backend-20261124-03）
- Java ThreadPoolExecutor 参数与流程（backend-20261124-04）
- Java AQS 与 ReentrantLock（backend-20261124-05）
- MySQL redo/undo/binlog 与两阶段提交（backend-20261124-06）
- MySQL EXPLAIN 与慢查询优化（backend-20261124-07）
- Redis 底层编码与 ZSet 跳表（backend-20261124-08）
- TLS 握手与 1.3 改进（backend-20261124-09）
- 零拷贝 sendfile/mmap（backend-20261124-10）
- Go：逃逸分析与栈/堆分配（backend-20261125-01）
- Go：sync.Pool 实现与注意事项（backend-20261125-02）
- Java：类加载过程与双亲委派（backend-20261125-03）
- Java：G1 与 ZGC 垃圾回收（backend-20261125-04）
- Java：ConcurrentHashMap(JDK8) 原理（backend-20261125-05）
- MySQL：间隙锁/临键锁与死锁排查（backend-20261125-06）
- Redis：分布式锁与 Redlock 争议（backend-20261125-07）
- 网络：HTTP/1.1、HTTP/2、HTTP/3 对比（backend-20261125-08）
- 操作系统：虚拟内存、页表与缺页中断（backend-20261125-09）
- Redis：Cluster 哈希槽与 MOVED/ASK（backend-20261125-10）

## 未覆盖
- Go：WaitGroup/Once/RWMutex、map 实现与并发安全
- Java：CAS 与原子类（LongAdder）、ThreadLocal、JMM happens-before
- MySQL：主从复制与分库分表、MVCC ReadView 细节、大表 DDL
- Redis：主从复制与哨兵、过期与淘汰策略、大 Key/热 Key
- 网络：TCP 拥塞控制与滑动窗口、DNS 解析、三次握手与 SYN 洪泛
- 操作系统：进程调度算法、死锁、页面置换、IO 模型 (BIO/NIO/AIO)
