# Required for microservices

**lombok**

**Exception Handling**

**Service discovery** is the technology to automatically detect services and devices on a computer network. It is how applications and microservices locate different components on a network. A service discovery protocol is a network protocol that implements this technology and reduces manual configuration tasks on the part of both the administrators and the users.

**Service registry** is a key component of service discovery. It is a database containing the locations of all available service instances. Thus, it must be updated and regularly maintained.

**Load Balancer** is a network device that sits between a set of backend servers and clients. It distributes the incoming traffic to multiple servers to reduce the load. Load Balancers typically use various algorithms, such as round-robin to determine which server to send incoming traffic to. In Spring, if you want to use Load Balancer then Spring Cloud provides us with some already developed ready-made Load Balancer. By using this you don’t need to write any Load Balancer or create your own, you can just use the tool very easily by importing some dependencies and writing minimal code.

**OpenFeign** is often used in microservices and cloud-native applications to simplify communication between different services. It is a part of the Spring Cloud ecosystem and designed to work smoothly with other Spring Cloud components to create microservices-based applications. In simple words, it simplifies the process of writing web service clients.

**ErrorDecoder** to handle Exceptions using feign

**Zipkin** is an open-source project that provides mechanisms for sending, receiving, storing, and visualizing traces. This allows us to correlate activity between servers and get a much clearer picture of exactly what is happening in our services.

**Sleuth** is a distributed tracing solution for Spring Cloud. It helps understand the latency issues in the microservice architecture by adding tracing information to the logs. While Sleuth helps to generate trace information, visualizing and storing it is a job for a tool like Zipkin.

**API Gateway** is a server that summarizes the internal system architecture of the application. The API gateway has responsibilities to provide the application client with API, perform request routing, provide authentication, load balancing, monitoring, composition, and protocol translation. When a client makes a request, the request transmits to the API gateway, and further, it routes to appropriate microservices.

**Circuit Breaker** is to prevent calls to microservice when it’s known the call may fail or time out. This is done so that clients don’t waste their valuable resources handling requests that are likely to fail.

**Spring Security** is a framework that focuses on providing both authentication and authorization to Java applications.

**Unit Test Cases**

**Docker** is an open source platform that enables developers to build, deploy, run, update and manage containers—standardized, executable components that combine application source code with the operating system (OS) libraries and dependencies required to run that code in any environment.

**Kubernetes** is a portable, extensible, open source platform for managing containerized workloads and services, that facilitates both declarative configuration and automation.

**Jenkins** is a Java-based open-source automation platform with plugins designed for continuous integration. It is used to continually create and test software projects, making it easier for developers and DevOps engineers to integrate changes to the project and for consumers to get a new build.

**SonarQube** is a Code Quality Assurance tool that collects and analyzes source code, and provides reports for the code quality of your project. It combines static and dynamic analysis tools and enables quality to be measured continually over time.
