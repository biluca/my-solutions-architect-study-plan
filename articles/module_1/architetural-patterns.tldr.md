# Architectural Patterns

Architectural patterns provide reusable solutions to common problems in software architecture. They address issues like hardware performance, high availability, and business value optimization. The two main categories are Monolithic and Distributed architectures:

## Monolithic Architectures:

- Layered (N-Tier): Divides application into layers (e.g., presentation, business logic).
- Microkernel: Core system with extensible plug-ins.
- Hexagonal (Ports and Adapters): Decoupled design using interfaces and implementations.
- CQRS: Separates read/write operations for performance and scalability.

## Distributed Architectures:

- Microservices: Collection of loosely coupled services.
- Event-Driven: Uses events for communication between services.
- Service-Oriented (SOA): Services communicate over a network using standard protocols.
- Serverless: Third-party manages server infrastructure.
- Event Sourcing: State changes captured as a sequence of events.
- Broker: Mediates communication between components.
- Client-Server: System divided into clients and servers.