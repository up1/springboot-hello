# Hello service with Spring Boot

Step to run

```
// 1. Testing
$mvn clean test

// 2. Packaging JAR file + Create image
$mvn clean package docker:build

// 3. Start service with Docker compose
$docker-compose -f docker/docker-compose.yml down
```

### References
* [Spotify Docker Plugin](https://github.com/spotify/docker-maven-plugin)
