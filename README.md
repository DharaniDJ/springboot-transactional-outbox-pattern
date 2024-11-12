# springboot-transactional-outbox-pattern
This repository illustrates the Transactional Outbox Pattern in microservices, ensuring reliable messaging and data consistency. The Order Service logs events to an outbox table in the same transaction as business data. The Order Poller service then reads and publishes these events to Kafka, maintaining atomicity.
