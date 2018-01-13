# Hello service with Spring Boot

Step to run

```
// 1. Compile + Build + JAR file + Create image
$mvn clean package docker:build

//2. Start service with Docker compose
$docker-compose -f docker/docker-compose.yml down
```
