### **Assignment 6: Microservices Advanced Topics for Banking Sector**

1. **Microservice Security with OAuth2**
   - Set up OAuth2 authentication for your microservices using Spring Security. Secure an API endpoint and explain the flow of authentication between the resource server and authorization server.

2. **Rate Limiting in Microservices**
   - Implement rate limiting in your microservices to avoid overloading. Use a library such as `Bucket4j` or `Resilience4j` to limit the number of requests per minute for sensitive endpoints like account balance inquiries.

3. **Distributed Tracing with Spring Cloud Sleuth**
   - Implement distributed tracing in your microservices using Spring Cloud Sleuth and Zipkin. Track a request as it travels through multiple services to visualize and analyze performance bottlenecks.

4. **Kafka for Transactional Integrity in Microservices**
   - Implement a Saga pattern using Kafka to ensure transactional integrity across microservices (e.g., an order placed in one service and payment in another, both must either succeed or fail together).

5. **Event Sourcing in Banking System**
   - Implement event sourcing for a banking transaction system. Store events as the primary source of truth (e.g., each deposit or withdrawal as a separate event) and reconstruct the state from events.

6. **Implementing CQRS (Command Query Responsibility Segregation)**
   - Implement CQRS in your banking microservices system to handle transaction commands (write operations) separately from query operations. This will improve performance and scalability.

7. **Banking System with Multi-Database Support**
   - Implement a microservice that handles multiple databases (e.g., one for transactions, another for customer information) and ensure data consistency using eventual consistency patterns.

8. **Kafka for Auditing in Banking System**
   - Implement an auditing system for a banking microservice using Kafka to log each transaction (e.g., withdrawal, deposit) to an audit log topic for compliance and auditing purposes.
