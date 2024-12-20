### **Assignment 9: Advanced Java and Spring Boot**

1. **Java Concurrency and Multithreading**
   - Implement a thread-safe cache using `ConcurrentHashMap` or `Synchronized` blocks. Then, create a multi-threaded test where multiple threads read and write to this cache simultaneously, ensuring thread safety.
   - Describe how you would handle race conditions and deadlocks in a multi-threaded environment. Provide examples and explain how Java concurrency utilities like `ExecutorService` or `CountDownLatch` can help mitigate these issues.

2. **Memory Management and Performance Optimization**
   - Write a Java program to create and manage a large object graph. Then, explain how the JVM's garbage collection mechanism works (including the roles of minor and major GC). Optimize the program to avoid excessive memory usage and reduce GC pauses.
   - Explain how to analyze memory leaks and how tools like VisualVM, JProfiler, or YourKit can be used to profile a Java application. Share your approach to optimize performance in a large-scale application.

3. **Spring Boot Advanced Topics**
   - Implement an asynchronous service in Spring Boot using `@Async` annotation and an `Executor` bean. Test the performance improvement by simulating long-running operations (e.g., sending emails or processing large datasets).
   - Configure Spring Boot to use multiple data sources (e.g., MySQL for transactional data and MongoDB for logging data). Ensure that the application reads and writes data from both sources effectively.

4. **Spring Boot Actuator and Monitoring**
   - Implement a custom health check endpoint using Spring Boot Actuator to monitor the health of external APIs integrated into your application. Ensure it can handle different failure scenarios (e.g., API is down, slow response, etc.).
   - Set up metrics collection for your Spring Boot application using Micrometer and expose them through Prometheus. Create a Grafana dashboard to visualize important application metrics such as response time, memory usage, and request count.

5. **Spring Boot and Reactive Programming**
   - Convert an existing blocking API to a non-blocking API using Spring WebFlux. Implement a service that uses reactive streams (e.g., `Mono`, `Flux`) to handle requests concurrently and asynchronously.
   - Discuss the advantages and disadvantages of using reactive programming in Spring Boot. When would you choose WebFlux over the traditional Spring MVC?

6. **Unit Testing with Mockito and Spring Boot**
   - Write unit tests for a service class in Spring Boot using Mockito. Use the `@MockBean` annotation to mock external services like REST APIs and databases. Ensure that the unit tests properly handle exceptions and edge cases.
