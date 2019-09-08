### 项目介绍：
此为spring cloud的demo项目，包含了zuul网关、服务提供者、消费者、feign调用。

项目的调用流程：下单 -> 扣库存  -> 仓库发货  -> 增加积分

### 启动项目
1. 启动mysql数据库，执行一下zuul-gateway模块下的sql语句，主要用来动态路由和灰度发布功能
2. 顺序启动eureka-server、服务提供者、网关等等