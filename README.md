# SpringMicroservicesTemplate

this repo is a template that creates 3 essential project to for a microservices architecture with the following techs: 
 - Spring Boot
 - Spring Webflux 
 - Spring Cloud Gateway
 - Netflix Eureka Discovery Service
 - Keycloak as an identity provider
 - Mongodb as a db for Spring Webflux app
 - Postgresql as a db for Keycloak

<H2>How to use it:</H2>
 - just hit: docker-compose up -d on terminal

<H3>IMPORTANT:</h3>
 - you need to change properties either on the app side or pass'em directly on docker-compose.yml file.
 - if you're willing to test keycloak roles make sure you add <127.0.0.1 keycloak> to your /etc/hosts file so that you don't get missmatch token issuer issues.
 - more tips and infos are included in the docker-compose file.
