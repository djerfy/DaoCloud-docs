# 基本概念

本页的词汇表定义了 MySQL 背后的核心概念，以帮助您构建 MySQL 工作原理的思维模型，并了解文档在使用某些术语时所指代的内容。

- ACID 合规

    ACID 合规性是 Atomiciy、Consistency、Isolation 和 Durability 这 4 个单词的首字母缩写，是一组由原子性、一致性、隔离性和持久性组成的数据库特性，可确保高效完成数据库事务。

- ACL

    访问控制列表或 ACL 是控制对系统资源访问的用户权限列表。

- Connection Status Metric（连接状态指标）

    连接状态指标是衡量创建、连接和运行的线程数与数据库连接限制相关的指标。

- DBaaS（数据库即服务）
  
    数据库即服务、托管数据库服务，简称为 DBaaS，这是一种云服务，允许用户在订阅的基础上访问云数据库系统，而无需拥有个人云数据系统。

- E2EE

    英文全称为 End-to-end encryption，即端到端加密，或简称为 E2EE，是一种通信系统，它为所有人加密消息和消息服务，但接收消息的用户和发送消息的用户除外。

- Failover（故障转移）

    故障转移是一种高可用性 (HA) 机制，可监控服务器的故障并在主服务器发生故障时将流量或操作重新路由到备用服务器。

- High Availability（高可用性）

    高可用性 (HA) 是一种基础架构设计方法，专注于减少停机时间和消除单点故障。

- Hot Standby（热备）

    热备用是侦听主节点何时发生故障以便备用节点取代其位置的行为。

- Index vs. Sequential Reads Metric（索引与顺序读取指标）

    索引与顺序读取指标图显示了使用索引的读取占主服务器上所有数据库（模式）的读取总数的比例。

- LUKS Disk Encryption（LUKS 磁盘加密）

    Linux 统一密钥设置磁盘加密 (LUKS) 是 Linux 存储设备的开源磁盘加密规范。

- Machine Type（机器类型）

    机器类型是用于虚拟机 (VM) 实例的一组虚拟化硬件资源。

- Node Plan（节点计划）

    节点计划、数据库或集群配置是节点规格的硬件计划。

- Operations Throughput Metric（运营吞吐量指标）

    操作吞吐量指标是对服务器上所有数据库的获取、插入、更新和删除操作的吞吐量的度量。

- Point-In-Time-Recovery（恢复时间点）

    恢复时间点（简称 PITR）确保进行自动备份，以便恢复在服务器先前状态下创建的数据。

- Port（端口）

    端口是网络连接的通信端点。使用每个传输协议所用的端口号来标识一个端口。

- Read-Only Node（只读节点）

    只读节点是集群主节点的副本。

- SQL Mode（SQL 模式）

    SQL 模式或 sql_mode 是一个 MySQL 系统变量，用于配置 MySQL 服务器的操作特性。

- SSL Certificate（SSL 证书）

    SSL 证书是描述网站身份的数字凭证。

- Standby Node（备用节点）

    备用节点是在热备模式时设为空闲待用的节点。

- Tag（标记）

    标记是与资源相关联的关键字，有助于管理资源所有权并组织对资源的查找和操作。