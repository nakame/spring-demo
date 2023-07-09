## Spring 'hello, world'

Simple Spring Boot 'hello, world' application for testing CI configuration.

### Build

Default build
```shell
mvn clean package
```

Native Image (GraalVM)

```shell
mvn -Pnative spring-boot:build-image
```

Docs: https://docs.spring.io/spring-boot/docs/current/reference/html/native-image.html

### Test

```shell
curl -v localhost:8080/hello
```
