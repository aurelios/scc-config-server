# scc-config-server
This project shows how to use the **Spring Cloud Configuration Server** to centralize and manage the configuration of microservices
from multiple different environments.



## 🚀 How to run ?

1 - Specify your git url of your repository where you has store your microservices configurations on  `spring.cloud.config.server.git.uri` of the file **[application.properties](src/main/resources/application.properties)**

2 - Run the application

```shell script
./mvnw spring-boot:run
```
3 - Check the multiple enviroments configuration of scc-limits-service microservice

http://localhost:8888/scc-limits-service/prod

http://localhost:8888/scc-limits-service/qa

http://localhost:8888/scc-limits-service/dev

