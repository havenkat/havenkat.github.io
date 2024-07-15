#### Micro Services design patterns :


Some of the common patterns:

- API Gateway Pattern: This pattern acts as a traffic cop, handling the traffic over the site. It decides where information should go, checks if you’re allowed to send or get information.

- Aggregator: This pattern is used when a client needs to make a single request and get a composite response from multiple services.

- Chained or Chain of Responsibility: This pattern is used when a client request is processed by a chain of services.

- Asynchronous Messaging: This pattern is used to establish communication between services via message queues to ensure loose coupling.

- Database or Shared Data: This pattern is used when multiple services need to access the same database.

- Event Sourcing: This pattern is used when the state of the business entity is determined by a sequence of events.

- Branch: This pattern is used when a service needs to broadcast an event to multiple listener services.

- Command Query Responsibility Segregator (CQRS): This pattern is used when a service needs to implement a command query responsibility segregation.

- Circuit Breaker: This pattern is used to detect failures and encapsulates the logic of preventing a failure from constantly recurring.

- Decomposition: This pattern is used to break down an application into smaller services by business capability or subdomain.

----
[Home](../../README.md)