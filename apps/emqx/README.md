# EMQX

EMQX 是一款基于 Erlang/OTP 构建的开源 MQTT 消息代理（Broker），专门用于支持 MQTT 协议。它提供了一系列强大的功能，使其成为物联网（IoT）应用程序的理想选择。以下是 EMQX 的主要功能：

## 主要功能：

### MQTT 3.1 和 3.1.1 支持

EMQX 支持 MQTT 协议的 3.1 和 3.1.1 版本，允许设备和应用程序使用 MQTT 进行高效的消息通信。

### MQTT 5.0 支持

EMQX 还支持 MQTT 5.0 协议，该协议引入了更多的功能，如属性、共享订阅、会话过期等，提高了消息传递的灵活性。

### 集群支持

EMQX 具有强大的集群功能，可以横向扩展以处理大规模的消息流量和连接请求。这确保了高可用性和可扩展性。

### 插件系统

EMQX 提供了丰富的插件系统，允许用户根据需要扩展其功能，包括认证、授权、数据存储、消息转发等方面的插件。

### 安全性

EMQX 提供了多层次的安全性，包括基于用户名和密码的认证、TLS/SSL 支持以进行加密通信、ACL（访问控制列表）以及 MQTT 的安全功能。

### 遗愿消息

EMQX 支持 MQTT 遗愿消息，确保消息能够在设备断开连接后得到适当的处理。

### 数据存储

EMQX 支持多种数据存储后端，包括 Mnesia、MySQL、PostgreSQL 和 Redis，以便于灵活地存储消息数据。

### 可视化监控

EMQX 提供了一个用户友好的 Web 界面，用于监控连接、会话、消息发布和订阅等关键指标。

### 负载均衡

EMQX 具备负载均衡功能，可自动将连接和消息均匀分布到集群中的各个节点，以提高性能和稳定性。

### 高可用性

EMQX 支持热备份和故障切换，确保即使在节点故障时也能保持高可用性。