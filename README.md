# Software Engineering Bootcamp Syllabus

*postscript: this document is not AI generated*

The first section consists of multiple chapters built around the [3-tier software architecture](https://en.wikipedia.org/wiki/Multitier_architecture) containing:

0. [Requirements engineering](https://en.wikipedia.org/wiki/Requirements_engineering) and pre-requisites refreshers
1. Service
2. Repository
3. Controller
4. Cross-cutting concerns
5. Testing
6. Security
7. Building & deployment
8. Wrapping things up

There are many overlapping concepts that do not belong to a specific chapter but will be discussed throughout either the instructions themselves or home-projects, including but not limited to:

* 12-factor app principles
* feeling at home with the terminal
* collaboration within software development (Git best practices)
* software engineer tooling (IDEs, linters, formatters, debuggers, profilers)

---

## 0. Requirements Engineering and Problem Description

**Goal:** Understand how to define and structure software problems before writing a single line of code.

**Topics:**

* Fundamentals of requirements engineering: functional vs. non-functional requirements
* Brief overview of stakeholder analysis and user personas
* From use cases to user stories
* Acceptance criteria and Definition of Done
* Software design documentation (SRS, architecture diagrams, sequence diagrams)
* Scoping and prioritization (MoSCoW method, MVP thinking)

**Outcome:**
Participants will define the core problem, document requirements, and design an architecture outline for their end-to-end system.

---

## 1. Service

**Goal:** Understand how to design application logic that is modular, maintainable, and testable.

**Topics:**

* Separation of concerns in business logic
* Service orchestration and transaction management
* Handling domain events and asynchronous workflows
* Working with DTOs and domain models
* Implementing services using clean architecture principles
* Dependency injection and inversion of control
* Error propagation and exception mapping

**Outcome:**
Students will build the service layer for core business use cases, emphasizing reusability and clarity.

---

## 2. Repository

**Goal:** Learn how to design and interact with data persistence layers.

**Topics:**

* Repository pattern fundamentals
* Connecting to relational and non-relational databases
* ORMs (e.g., Sequelize, TypeORM, Hibernate) vs. query builders vs. raw queries
* Pagination, filtering, and sorting patterns
* Data migrations and schema versioning
* Caching strategies (in-memory, Redis)
* Managing transactions and concurrency

**Outcome:**
Students will implement repositories for their domain entities, supporting CRUD operations, pagination, and data transformations.

---

## 3. Controller

**Goal:** Learn how to design and build API endpoints and manage inter-service communication.

**Topics:**

* Introduction to RESTful APIs
* gRPC basics: contracts and message definitions
* Controller responsibilities vs. service responsibilities
* HTTP lifecycle: request parsing, validation, and response formatting
* Routing, middleware, and error handling patterns
* API versioning and backward compatibility
* Input validation and schema definitions (e.g., using JSON Schema or Protocol Buffers)

**Outcome:**
Students will implement a controller layer exposing APIs for the capstone project using REST or gRPC.

---

## 4. Cross-cutting Concerns

**Goal:** Understand system-wide functionalities that apply across layers.

**Topics:**

* **Observability:** logging, tracing, metrics
* Centralized logging (structured logs, correlation IDs)
* Distributed tracing with OpenTelemetry
* Metrics and health checks (Prometheus, Grafana)
* Configuration management (env vars, feature flags)
* Exception handling and resilience (retries, circuit breakers)

**Outcome:**
Students will integrate monitoring, logging, and configuration management into their applications.

---

## 5. Testing

**Goal:** Develop a testing mindset and understand test levels and tooling.

**Topics:**

* TDD and thinking in assertions
* Unit tests, integration tests, E2E tests
* Mocking and stubbing dependencies
* Test coverage and CI integration
* Property-based and snapshot testing
* Test data management and cleanup
* Automated regression testing

**Outcome:**
Students will implement a full suite of automated tests for their project.

---

## 6. Security

**Goal:** Apply security best practices across all layers.

**Topics:**

* Foundations of cybersecurity (CIA triad)
* Authentication & authorization flows
* Session management (stateful) and token-based (stateless) auth (JWT, OAuth2, OpenID Connect)
* Role-based (RBAC), attribute-based (ABAC) and others
* Managing PII (personally identifiable information)
* Secure storage and transmission (hashing, encryption)
* Common vulnerabilities (OWASP Top 10) and mitigations

**Outcome:**
Students will secure their application with proper auth, access control, and basic hardening.

---

## 7. Building & Deployment

**Goal:** Learn how to containerize, automate, and deploy applications.

**Topics:**

* Docker fundamentals and best practices
* Writing efficient Dockerfiles
* Docker Compose for local orchestration
* CI/CD: concepts and pipelines
* Building pipelines with GitHub Actions
* Environment-specific configurations
* Blue-green and zero-downtime deployments
* Infrastructure as Code overview (Terraform, Ansible basics)

**Outcome:**
Students will create CI/CD pipelines and deploy their apps with Docker and GitHub Actions.

---

## 8. Wrapping Things Up

**Goal:** Reflect on the full software development life cycle and career progression.

**Topics:**

* Review and retrospective of what was built
* Software Development Life Cycle (SDLC) overview
* Agile vs. Waterfall vs. DevOps culture
* Writing documentation and maintaining codebases
* Engineering communication and peer review etiquette
* Next steps: scaling systems, design patterns, cloud computing, and microservices

**Outcome:**
Students consolidate their knowledge, polish documentation, and present their capstone projects.

---

## Where to Go From Here?
