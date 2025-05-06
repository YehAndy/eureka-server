# 使用 Eclipse Temurin Java 21 JDK 基底映像
FROM eclipse-temurin:21-jdk-alpine

# 建立工作目錄
WORKDIR /app

# 複製 jar 檔案到容器中
COPY target/eureka-server-0.0.1-SNAPSHOT.jar app.jar

# 容器啟動指令
ENTRYPOINT ["java", "-jar", "app.jar"]
