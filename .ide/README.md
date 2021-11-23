# 使用SmartIDE开发Boathouse后端项目

```shell
cd src/product-service/api
./mvnw spring-boot:run
```

API http://localhost:8080/api/v1.0/swagger-ui.html
PHPMyAdmin http://localhost:8090/


## Debugging

https://github.com/Microsoft/vscode-java-debug/issues/300cl

```shell
mvn spring-boot:run -Dspring-boot.run.jvmArguments="-Xdebug -Xrunjdwp:transport=dt_socket,server=y,suspend=y,address=8000"
mvn spring-boot:run -Dspring-boot.run.jvmArguments="agentlib:jdwp=transport=dt_socket,server=y,suspend=y,address=8000"
```

记得安装Lombok插件

