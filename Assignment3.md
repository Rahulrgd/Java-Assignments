### **Assignment 3: Microservices with Spring Boot**

1. **Microservices Architecture Overview**
   - Briefly explain microservices architecture and its advantages over monolithic applications. Discuss scenarios where microservices would be beneficial.

2. **Building a Simple Microservice**
   - Create a simple Spring Boot microservice that exposes a RESTful API to manage customer information (e.g., customer ID, name, email). Use an embedded database for storage.

3. **Communication Between Microservices**
   - Implement a second microservice for handling orders and show how it can communicate with the customer service microservice via REST API (using `RestTemplate` or `WebClient`).

4. **Spring Cloud Config Server**
   - Set up a Spring Cloud Config Server to manage configurations for multiple microservices. Make sure one of the microservices fetches its configuration from this server.

5. **Service Discovery with Eureka**
   - Implement Service Discovery using Eureka Server and Eureka Clients. Show how two microservices can register and discover each other through Eureka.

6. **API Gateway with Spring Cloud Gateway**
   - Set up a Spring Cloud Gateway to act as an API Gateway for routing requests to your microservices.

7. **Handling Failures with Circuit Breaker**
   - Implement a Circuit Breaker using Spring Cloud Circuit Breaker (Hystrix) to handle failures in one of the microservices.
