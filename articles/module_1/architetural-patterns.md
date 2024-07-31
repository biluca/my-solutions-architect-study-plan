# Architectural Patterns

An architectural pattern is a general, reusable resolution to a commonly (but not exclusive) occurring problem in software architecture within a given context. The architectural patterns address various issues in software engineering, such as computer hardware performance limitations, high availability, minimization of a business risk and optimization of business value.

There are two main categories of architectural patterns: Monolithic and Distributed. Both patterns have their strengths and weaknesses, and the choice between them depends on the specific needs of the application, the size of the development team, and the scalability requirements. While monolithic architectures may suffice for smaller applications or projects with less complexity, distributed architectures offer greater flexibility and scalability for larger, more complex systems. The transition from monolithic to distributed architectures is a common path as applications grow and evolve.

## Monolithic Architectures

### Layered (N-Tier) Architecture

- Description: Divides the application into distinct layers (e.g., presentation, business logic, data access, database).
- Use Case: Traditional enterprise applications where separation of concerns and maintainability are important.

### Microkernel Architecture

- Description: Consists of a core system providing minimal functionality and extensible plug-ins for additional features.
- Use Case: Product-based applications needing a stable core with varying functionalities (e.g., IDEs, e-commerce platforms).

### Hexagonal Architecture (Ports and Adapters)

- Description: Emphasizes a decoupled design using interfaces (ports) and implementations (adapters) for external systems.
- Use Case: Applications needing high flexibility and maintainability, especially with external service interactions.

### CQRS (Command Query Responsibility Segregation)

- Description: Separates read and write operations into different models to optimize performance, scalability, and security.
- Use Case: Systems with complex business logic requiring distinct read and write paths (e.g., financial services).

## Distributed Architectures

### Microservices Architecture

- Description: Composes an application as a collection of loosely coupled services, each implementing a specific business capability.
- Use Case: Large-scale applications needing flexibility, scalability, and independent deployment.

### Event-Driven Architecture

- Description: Utilizes events to trigger and communicate between decoupled services.
- Use Case: Applications needing to respond to high volumes of asynchronous events (e.g., real-time data processing).

### Service-Oriented Architecture (SOA)

- Description: Structures an application as a collection of services communicating over a network using standardized protocols.
- Use Case: Enterprise systems integrating various services across different platforms and technologies.

### Serverless Architecture

- Description: Relies on third-party services to manage server infrastructure, focusing solely on code.
- Use Case: Applications with varying workloads needing cost efficiency and rapid development.

### Event Sourcing

- Description: Captures all changes to the application state as a sequence of events.
- Use Case: Systems where auditability and traceability of changes are critical (e.g., financial and legal applications).

### Broker Architecture

- Description: Uses a broker component to mediate communication and coordination between different components or services.
- Use Case: Distributed systems integrating disparate components or systems (e.g., message-oriented middleware).

### Client-Server Architecture

- Description: Divides the system into clients (request services) and servers (provide services).
- Use Case: Traditional web applications and networked systems.
