# system-design
Patterns in System Design

1) Use Distributed Queues (Kafka) to aggregate data eg collect events from multiple machines in a monitoring system
2) Distributed systems imply exactly once semantics are very hard to achieve. eg events in Kafka, or jobs in dist. job scheduler have to be idempotent
3) Use Dead Letter Queue when calling an unreliable service or a database. 
 
