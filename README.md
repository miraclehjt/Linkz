## Linkz
**Linkz**是搭建Java分布式架构的解决方案，结合Dubbox，Thrift等RPC框架，可快速搭建互联网应用的后端平台。**Linkz**关注的重点是整合。

## Linkz当前的主要功能

* **基于Netty的高并发HTTP容器**：基于Netty特性实现的支持高并发、快速开发的HTTP容器。

* **基于zookeeper的分布式配置管理**：基于zookeeper实现的分布式配置管理，支持文本配置和数据表配置，并可自由扩展。

* **Resource Proxy**：资源代理层，支持各种资源（DB、Redis、Mongodb等）的分库分表、资源定位等，路由协议可自行扩展。

* **敏感词组件**：自己实现的敏感词组件，可自行选择是否使用。

* **丰富的工具类**：较丰富的工具类。

* **其他**：还有很多，如各种序列化协议的支持（ProtocolBuffer、Kryo、Json等）、OAuth2.0的简易支持、重写的Redis Client API、基于Redis的配额校验组件等，可以自行探索。

## TODO
Linkz还在不断完善中，后续会补充使用文档。