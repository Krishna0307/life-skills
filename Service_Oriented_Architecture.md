# Service Oriented Architecture Report Scaling Issues.

## Introduction

The current project is facing performance and scaling problem. 
After checking the system, the team lead suggested looking into Service Oriented Architecture as a possible solution. This can help improve scalability, performance.

## Problem Statement

* The system becomes slow.
* Scaling the system is a challenge due to its current design.
* A single failure can affect the entire system.
* Changes are slow and risky to update.

## Service Oriented Architecture Overview

* Service Oriented Architecture is a design method.
* The application is divided into small independent services.
* Each service handles a specific business task.
* Services communicate with each other using APIs.
* Services are loosely connected, not tightly linked.
* Each service can be developed separately.

## Benefits of SOA

* The system becomes faster and more scalable.
* Services can be scaled independently based on need.
* A failure in one service does not affect the whole system.

## Proposed System Design

* User Service handles login and user profile details.
* Payment Service manages money transactions.
* Order Service takes care of customer orders.
* Notification Service sends messages and updates.

## Challenges

* Increased system complexity.
* Need for proper service communication design.
* Network latency between services.
* Requirement for monitoring and security mechanisms.

## Conclusion

Service Oriented Architecture is a good way to solve the current performance and scaling problems in the project. It helps improve scalability and maintenance by dividing the system into smaller independent services. 
However, it must be implemented properly and monitored carefully to work well.

## References

* https://aws.amazon.com/what-is/service-oriented-architecture/  
* https://www.ibm.com/topics/soa  
* https://www.geeksforgeeks.org/service-oriented-architecture-soa/  
* https://learn.microsoft.com/en-us/azure/architecture/guide/architecture-styles/soa  