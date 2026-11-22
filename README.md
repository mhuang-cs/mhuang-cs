专注高并发交易链路、海量数据存储架构与线上稳定性治理的资深 Java 后端工程师（已授权发明专利核心发明人）。

### 🛠 核心架构沉淀与工程实战

| 项目名称                                                     | 核心架构设计与实测指标                                       | 涉及技术栈                                                   |
| :----------------------------------------------------------- | :----------------------------------------------------------- | :----------------------------------------------------------- |
| **[flash&#8209;trade&#8209;core](https://github.com/mhuang-cs/flash-trade-core)**<br> | **高并发核心交易与异步清结算参考架构**<br>• 通用状态机引擎驱动订单生命周期，支持分布式异步对账防漏单<br>• `Redis + Lua` 防重幂等、乐观锁防覆盖、MQ 削峰与死信补偿<br>• 集成 `K8s` 部署与 `SkyWalking + Prometheus` 监控大盘（单节点压测 P99 < 35ms） | `Spring Cloud Alibaba`<br>`Redis Lua` · `Kafka/RabbitMQ`<br>`K8s` · `SkyWalking` |
| **[heterogeneous&#8209;data&#8209;arch](https://github.com/mhuang-cs/heterogeneous-data-arch)**<br> | **千万级数据治理与多模异构存储实战**<br>• 千万级大表深分页延迟关联优化（**4.2s → 0.03s**）、InnoDB 死锁与慢 SQL 调优<br>• 基于 `Canal` 订阅 Binlog 实现 `MySQL → ES / MongoDB` 准实时异构同步与数据一致性巡检 | `MySQL 8.4` · `InnoDB`<br>`MongoDB` · `Elasticsearch`<br>`Canal` |
| **[jvm&#8209;ops&#8209;playbook](https://github.com/mhuang-cs/jvm-ops-playbook)**<br> | **生产级 JVM 调优与线上故障诊断实录**<br>• 容器内存限额（Cgroups）下的 G1 / ZGC 参数调优与压测对比<br>• Heap/Metaspace OOM 复现、MAT 堆栈分析、CPU 飙升与死锁 `Arthas` 终端排查全流程 | `JVM` · `Arthas` · `MAT`<br>`Docker` · `Linux`               |
| **[llm&#8209;resilient&#8209;gateway](https://github.com/mhuang-cs/llm-resilient-gateway)**<br> | **大模型企业级接入网关与稳定性治理**<br>• 解决 LLM 调用慢、易超时痛点：Token 令牌桶精细化限流、多模型熔断降级与路由<br>• SSE 流式响应背压控制及结构化输出（JSON Schema）自动重试兜底 | `Spring Boot 3` · `Spring AI`<br>`Sentinel` · `Redis`        |

### 📜 已授权发明专利

- [《多媒体数据处理装置》](./assets/CN109862402B-多媒体数据处理装置.pdf)（`CN109862402B`）— 基于节点 CPU 算力负载的分布式并行分片调度与宕机故障自动转移
- [《提升景观照明云控平台文件传输效率的处理系统及方法》](./assets/CN109618011B-提升景观照明云控平台文件传输效率的处理系统及方法.pdf)（`CN109618011B`）— 元信息状态追踪、分块并发分发与高并发中心源站削峰

---

📍 Base: 深圳 | 📫 Contact: `huang.min@163.com`
