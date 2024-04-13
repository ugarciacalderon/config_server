# CONFIG SERVER
Provides support for externalized configuration in a distributed system

The configuration is make in application.yml and config of development environment, qa environment and
prod environment get from this repository [config_server](git@github.com:ugarciacalderon/config.git)

Additional the configurations can be defined in the:
- classpath: /resources/config
- specific directory
- reposiitory git

The repository properties can be encrypted so as not to expose sensitive information, Spring Cloud Config Server
will decrypt them internally.

Available endpoints
- http://localhost:8071/encrypt
- http://localhost:8071/decrypt


Official Documentation

[Spring Framework Config](https://docs.spring.io/spring-cloud-config/docs/current/reference/html/)

![img.png](img.png)
