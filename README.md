# micro-services-seed

The project was generated using the JHipster code generation tool, resulting in a gateway project and two additional microservice projects:

1. **Gateway**: Acts as the central point for routing and handling requests across the microservices. It serves as the entry point for client applications and manages authentication, load balancing, and other cross-cutting concerns. [View the code here](https://github.com/savi-technologies/gateway).

2. **Bizservice1**: A microservice responsible for handling a specific set of business functionalities within the application. It can communicate with the gateway and other services as needed. [View the code here](https://github.com/savi-technologies/biz-service1).

3. **Bizservice2**: Another microservice in the application, responsible for a different set of business functionalities. Like bizservice1, it communicates with the gateway and other services to fulfill its role. [View the code here](https://github.com/savi-technologies/biz-service2).

These three projects work together to form a comprehensive microservices architecture, providing the foundation for building scalable, distributed systems.
