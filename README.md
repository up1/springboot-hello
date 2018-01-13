# Hello service with Spring Boot

Step to run

```
// Testing
$mvn clean test

// Run with spring boot
$mvn spring-boot:run

// Packaging JAR file + Create image
$mvn clean package docker:build

// Start service with Docker compose
$docker-compose -f docker/docker-compose.yml down
```

### References
* [Spotify Docker Plugin](https://github.com/spotify/docker-maven-plugin)
