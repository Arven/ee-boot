# Flare Boot
Boot-Alike for Containerless Java EE Applications

This project is a Boot provider which can be used to start up a quick Java EE project. It is annotation-driven like Spring Boot, but is entirely unrelated to Spring and does not use any of the Spring technologies. It uses Weld and its service provider interface to provide extra dependency injection features.

The following features are available:
- JPA persistence injection
- JTA transaction services
- EJB 3.1 bean injection
- CDI bean injection
