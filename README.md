## tinycache

#### 项目介绍

这是一款轻量级的分布式缓存系统，模仿自 groupcache 设计。该项目具有以下特点：

- 基于最近最少访问算法（Least Recently Used）缓存淘汰策略
- 使用 WaitGroup、RWMutex 等多种 Go 锁机制，防止缓存击穿
- 基于一致性哈希算法在分布式场景下选择结点，实现负载均衡
- 使用轻便高效的 ProtoBuf 优化节点间二进制通信

#### 使用方法

欢迎通过 go module 机制将其作为您项目的一部分，请参考 run.sh 的使用方法。

