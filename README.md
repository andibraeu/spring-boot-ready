Spring Example Project
====

Prerequisites
----
* jdk installed
* docker installed

About
----
This is an example Spring-Boot application that is already configured 
to support a lot of tools and plugins i like to use in my daily business.

Things that are configured already:
* [Actuator](https://docs.spring.io/spring-boot/docs/current/reference/htmlsingle/#production-ready)
	* adds health check, jms, metrics, loggers, dependencies, ... endpoints
* [Spring-Boot Admin UI](https://github.com/codecentric/spring-boot-admin/blob/master/README.md)
	* really nice UI on top of Actuator to monitor spring boot applications. for instance can set different log 
	levels at runtime, see health status of dependencies (e.g. database, hystrix, messaging queues), metrics, etc.
* [SwaggerUI](https://swagger.io/swagger-ui/)
	* adds a nice generated documentation of your api endpoints, with "try out" functionality to make actual requests 

