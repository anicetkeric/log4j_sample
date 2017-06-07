# log4j_sample
 Apache Log4j2 with Spring Boot
 
 # Apache Log4j 2
Apache Log4j 2 est une mise à niveau vers Log4j qui fournit des améliorations significatives par rapport à son prédécesseur, Log4j 1.x, et fournit plusieurs améliorations disponibles dans Logback tout en réparant certains problèmes inhérents à l'architecture de Logback. [ Read more ](https://logging.apache.org/log4j/2.0/index.html).
  
 # Log4J 2 Spring Boot Dependencies

 Exclude logback from default log dependency of Spring Boot
```xml
<dependency>
	<groupId>org.springframework.boot</groupId>
	<artifactId>spring-boot-starter</artifactId>
	<exclusions>
		<exclusion>
			<groupId>org.springframework.boot</groupId>
			<artifactId>spring-boot-starter-logging</artifactId>
		</exclusion>
	</exclusions>
</dependency>
```
– Add Log4j2 dependency

```xml
<dependency>
	<groupId>org.springframework.boot</groupId>
	<artifactId>spring-boot-starter-log4j2</artifactId>
</dependency>
```
