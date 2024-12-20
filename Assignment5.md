### **Assignment 5: Advanced Kafka and Microservices Communication**

1. **Kafka Producer-Consumer Performance Tuning**
   - Explain how to configure Kafka for optimal performance. Configure your Kafka producer and consumer with appropriate settings for message batching, compression, and retries.

2. **Implementing Event-Driven Microservices**
   - Create two Spring Boot microservices where one service produces events (e.g., customer account created), and another service consumes the events to perform business logic (e.g., trigger a fraud detection check).

3. **Transactional Messaging in Kafka**
   - Implement transactional messaging with Kafka to ensure that messages are delivered exactly once. Set up the producer to send messages as part of a transaction and ensure the consumer processes them correctly.

4. **Kafka Streams for Real-Time Processing**
   - Implement a simple real-time processing system using Kafka Streams in a Spring Boot application. For example, process transaction data to calculate the total transaction amount per customer in real-time.

5. **Kafka Consumer Offset Management**
   - Explain how Kafka manages consumer offsets. Implement a consumer that manually commits offsets, ensuring that messages are processed in order and not lost in case of failure.

6. **Implementing Idempotency in Kafka Consumers**
   - Implement idempotency in Kafka consumers to ensure that processing a message multiple times does not have unintended side effects, such as multiple bank account transactions.
