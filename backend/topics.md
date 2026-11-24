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

## 未覆盖
- Go：逃逸分析、sync.Pool 与 WaitGroup/Once
- Java：类加载机制、G1/ZGC 等垃圾回收器
- Java：ConcurrentHashMap、CAS 与原子类、ThreadLocal
- MySQL：锁类型（行锁、间隙锁、临键锁）与死锁排查
- MySQL：主从复制与分库分表
- Redis：主从复制与哨兵、Cluster 分片
- Redis：分布式锁实现细节（Redlock 争议）
- 网络：HTTP/1.1 与 HTTP/2、拥塞控制、DNS
- 操作系统：进程与线程切换开销、虚拟内存与页表、内存管理
