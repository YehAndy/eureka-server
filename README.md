# Eureka Server 多節點範例

這是一個簡單的 Eureka Server Spring Boot 專案，可支援多節點部署（非 Kubernetes）。

## 使用方式

1. 使用不同的 `EUREKA_INSTANCE_HOSTNAME` 和 `EUREKA_PEERS` 啟動兩個實例。
2. 可使用 Docker 容器啟動並設置對應環境變數。

例如：

```
docker-compose up --build
```
