## tinycache

#### 项目介绍

这是一款轻量级的分布式缓存系统，模仿自 groupcache 设计。该项目具有以下特点：

- 最近最少访问(Least Recently Used, LRU) 缓存策略
- 单机缓存和基于 HTTP 的分布式缓存
- 多种 Go 锁机制防止缓存击穿
- 基于一致性哈希选择节点，实现负载均衡
- 使用 protobuf 优化节点间二进制通信

#### 使用方法

欢迎通过 go module 机制将其作为您项目的一部分，请参考 run.sh 的使用方法。

