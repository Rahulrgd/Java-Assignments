### **Assignment 4: Kafka Basics and Integration with Spring Boot**

1. **Kafka Overview**
   - Explain the key components of Kafka (Producer, Consumer, Broker, Topic, Partition). Describe how Kafka ensures fault tolerance and scalability.

2. **Setting Up Kafka in Spring Boot**
   - Create a Spring Boot application and configure it to use Kafka. Write a simple producer that sends a message to a Kafka topic.
   
3. **Kafka Consumer in Spring Boot**
   - Implement a Kafka consumer in the Spring Boot application that listens to messages from the Kafka topic and processes them.

4. **Handling Kafka Message Serialization**
   - Implement a producer and consumer using custom message objects (e.g., `Order` or `Transaction`) and configure message serialization/deserialization using Avro or JSON.

5. **Error Handling with Kafka Consumers**
   - Implement error handling for your Kafka consumers. For example, set up a Dead Letter Queue (DLQ) for messages that cannot be processed.

6. **Message Acknowledgment**
   - Explain how Kafka message acknowledgment works in Spring Boot. Implement manual acknowledgment in a Kafka consumer using Spring Kafka.

7. **Producer-Consumer Group Configuration**
   - Configure the Kafka producer and consumer in such a way that the consumer is part of a consumer group and is able to process messages in parallel from multiple instances.
