# 功能列表

## 云原生统一管理

**混合存储接入**

统一 CSI 标准化接入，实现多数据访问类型（NFS，块存储，本地存储）接入，满足不同场景需求。

**动态存储管理**

支持动态方式分配存储池资源，无需管理员手动管理、运维数据卷。

**多数据卷创建方式**

可通过存储池动态创建数据卷，以及支持快照创建数据卷。

## 云原生本地存储（Hwameistor）

### 功能

**高性能本地卷**

无需外接存储设备，实现 IO 本地化，无需网络开销，实现高性能本地吞吐，支持 数据库、中间件等对性能有高要求的应用上云。

**多类型数据卷**

支持 LVM 类型、裸磁盘类型数据卷，满足不同磁盘需求场景。

**CSI 标准**

通过标准的 CSI 标准接入 Hwameistor 本地存储，统一使用姿势。

**主备高可用**

实现数据卷多副本冗余机制，保障数据高可用，提高数据读写可靠性。

**数据卷扩容** 

业务无感扩容，支持应用在运行过程中，为挂载的数据卷进行弹性扩容。

### 生产可运维

**无中断升级（不影响业务数据）**

数据平面、控制平面分离，控制平面升级/扩展节点时，业务应用数据读写 0感知。

**换盘**

支持磁盘告警后进行换盘，保障业务应用不受影响，生产可运维。

**一键驱逐节点数据卷**

手动一键式驱逐某一节点数据卷，实现生产可运维。

**自动驱逐节点数据卷**

结合 Kubernetes 驱逐行为自动感知并驱逐节点上的数据卷。

**单磁盘维度（LD）数据迁移**

支持磁盘出现预警时并需要换盘，迁移所有数据，保障业务应用数据不丢失。

**应用负载维度的数据迁移**

支持有状态应用重调度时，以应用为 维度实现数据迁移，保障业务应用 Pod 成功调度以及调度后的数据一致性。

**统一 Dashboard **

统一 DashBoard 展示资源使用率情况及分布 ，存储资源状态，及监控告警。

**丰富 Metrics 指标**

全方位的数据服务监控告警，实现数据盘、存储池及存储驱动的全面监控，全面保障数据安全性。