## Summary ##
Externailized Configuration Management (ECM) application is an Angular plus Spring Boot microservices implementation to retrieve configuration parameters in the form of key-value (KV) pairs from Google Cloud Firestore. Angular provides the front-end while Spring Boot provides the service endpoints using REST API interface. Firestore is a managed NoSQL cloud database from Google that is used as the data store by the ECM application.

Configuration parameters managed by the application can be broadly grouped into two categories:  
1. application boot/startup parameters and
2. runtime application parameters

It should be noted, however, that any KV pair can be managed by the application and it is up to the consumer applications on how to make use of those KV pairs.

## High-level flow diagram ##
