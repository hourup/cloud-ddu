# Cloud-DDU 微服务落地基础设施建设

### 概述

这是一个用代码去交流学习微服务的工程，我们始终相信，工程学始终是一门注重实践的学科，只有不断的实践和试错，才能建立起完整的方法论。

Cloud-DDU 致力于用代码的方式去理解微服务，将微服务这个抽象的概念用代码具象化。

组合当前最流行的微服务中间件，实现微服务架构的真正落地。

### 阶段性目标

#### 第一阶段（基础选型与建设阶段）

选取当前业界流行的微服务中间件，整合成微服务落地的基础设施。

| 微服务设施 | 落地中间件                                                   |
| ---------- | ------------------------------------------------------------ |
| 网关       | Spring Cloud Gateway                                         |
| 负载均衡   | Ribbon、Spring Cloud loadbalancer                            |
| 注册中心   | Eureka、Consul、Nacos                                        |
| 配置中心   | Apollo、Nacos                                                |
| 熔断       | RResilience4J、Sentinel                                      |
| 链路追踪   | Zipkin、SkyWalking                                           |
| 分库分表   | sharding-sphere                                              |
| RPC        | feign、dubbo、grpc                                           |
| 监控       | [Prometheus](https://prometheus.io/)、[Grafana](https://grafana.com/)、[Alertmanager](https://prometheus.io/docs/alerting/alertmanager/) |
| 分布式事务 | [Seata](https://github.com/seata/seata)                      |
| 消息队列   | [RocketMQ](http://dubbo.apache.org/)、RabbitMQ、Kafka        |

#### 第二阶段（基础设施落地阶段）

通过对第一阶段各种中间件的整合工作，选择一套高效、稳定的组合方案搭建基础设施，实现剥离业务的承载框架。

#### 第三阶段（假想业务融合阶段）

通过假想业务场景，将业务代码融入第二阶段的基础设施，用业务检验基础设施的可靠性与稳定性，通过不断丰富业务场景，进一步驱动微服务架构的落地工作。

### 模块信息

用来记录各个模块名称和占用的端口

| 模块               | 端口 |
| ------------------ | ---- |
| cloud-nacos-client | 5201 |

### 成员信息

> 按字母先后顺序排列

- [424300370](https://github.com/424300370)

- [changhr2013](https://github.com/changhr2013)

- [itguang](https://github.com/itguang)

- [wangkai19941220](https://github.com/wangkai19941220)