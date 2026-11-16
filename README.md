专注高并发交易链路、OMS 订单系统架构与线上稳定性治理的 Java 后端工程师。  
本主页用于沉淀日常技术实验、千万级数据调优基准测试与故障排查复盘。

**核心技术栈**：`Java` · `Spring Boot / Cloud Alibaba` · `MySQL 8.0` · `Redis` · `Kafka / RabbitMQ` · `JVM / Arthas` · `Linux`

## 🛠️ 核心工程实验室与架构沉淀

| 项目名称 | 核心内容与实测数据 | 涉及技术栈 |
| :--- | :--- | :--- |
| **[java-troubleshooting-labs](https://github.com/mhuang-cs/java-troubleshooting-labs)** | Heap/Metaspace OOM 本地复现、CPU 飙升与线程死锁终端诊断实录 | `JVM` / `Arthas` / `MAT` / `Linux` |
| **[oms-high-concurrency-core](https://github.com/mhuang-cs/oms-high-concurrency-core)** | 下单接口高并发防重幂等、订单状态机乐观锁、MQ 削峰与死信补偿机制 | `Spring Boot` / `Redis Lua` / `RabbitMQ` |
| **[mysql-10m-tuning-lab](https://github.com/mhuang-cs/mysql-10m-tuning-lab)** | 1000 万级订单表深分页查询（4.2s → 0.03s）与 InnoDB 死锁日志拆解 | `MySQL 8.0` / `EXPLAIN` / `InnoDB` |
| **[oms-architecture-blueprint](https://github.com/mhuang-cs/oms-architecture-blueprint)** | 订单中心核心状态流转、分布式对账防漏单与大促限流降级架构设计 | `System Design` / `Mermaid` |

---
📍 Base：深圳 ｜ 📫 Contact：`huang.min@163.com`
