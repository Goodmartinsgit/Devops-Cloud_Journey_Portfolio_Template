# Microservices & Event-Driven Architecture

This subdirectory houses message broker manifests, API Gateway configurations, and logs validating microservices communication.

## 📋 Task Checklist & Progress

- [ ] **Task 1: Decompose Your Business Management App into 5 Microservices**
  * **Objective**: **Scenario:** You have a business management application that currently handles: user registration/login, product catalogue management, order processing, payment handling, and email/SMS notifications. This is a monolith. Your job is to decompose it into 5 microservices with clearly defined boundaries.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-01-decompose-your-business-management-app-into/](./tasks/task-01-decompose-your-business-management-app-into/)`
- [ ] **Task 2: Implement gRPC Communication Between 2 Services — Auto-Generate Client from .proto File**
  * **Objective**: **Scenario:** Implement gRPC communication between your Order Service and Product Catalogue Service. The Order Service needs to call the Product Catalogue to verify a product exists and check its stock before creating an order.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-02-implement-grpc-communication-between-2-services/](./tasks/task-02-implement-grpc-communication-between-2-services/)`
- [ ] **Task 3: Build an Event Sourcing Store — Events as Source of Truth, Rebuild State from Event Log**
  * **Objective**: **Scenario:** Implement a simple Event Sourcing store for the Order aggregate. Orders exist as event logs; current state is derived by replaying events.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-03-build-an-event-sourcing-store-events/](./tasks/task-03-build-an-event-sourcing-store-events/)`
- [ ] **Task 4: Set Up Apache Kafka on K8s Using Strimzi — Produce and Consume Events Between Services**
  * **Objective**: **Scenario:** Deploy Kafka to your Kubernetes cluster using Strimzi and implement event-driven communication between your Order Service (producer) and Payment Service (consumer).
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-04-set-up-apache-kafka-on-k8s/](./tasks/task-04-set-up-apache-kafka-on-k8s/)`
- [ ] **Task 5: Deploy Istio Traffic Management — Weighted Routing, Circuit Breaking, Fault Injection for Testing**
  * **Objective**: **Step 1: Deploy two versions of Product Service**
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-05-deploy-istio-traffic-management-weighted-routing/](./tasks/task-05-deploy-istio-traffic-management-weighted-routing/)`
- [ ] **Task 6: Write AsyncAPI Documentation for Your Event-Driven Services**
  * **Objective**: Create a complete AsyncAPI specification documenting all five services from Task 1.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-06-write-asyncapi-documentation-for-your-event/](./tasks/task-06-write-asyncapi-documentation-for-your-event/)`
- [ ] **Task 7: Implement the Saga Pattern for a Multi-Service Transaction**
  * **Objective**: **Scenario:** Implement a saga for the flow: order creation → payment → inventory reservation. Use the orchestration approach with persistent saga state.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-07-implement-the-saga-pattern-for-a/](./tasks/task-07-implement-the-saga-pattern-for-a/)`
- [ ] **Task 8: Set Up an API Gateway (Kong) — Auth, Rate Limiting, Transformations**
  * **Objective**: **Step 1: Install Kong with Helm**
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-08-set-up-an-api-gateway-kong/](./tasks/task-08-set-up-an-api-gateway-kong/)`
- [ ] **Task 9: Implement the Outbox Pattern to Ensure Exactly-Once Message Delivery**
  * **Objective**: **Full implementation with PostgreSQL and Kafka:**
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-09-implement-the-outbox-pattern-to-ensure/](./tasks/task-09-implement-the-outbox-pattern-to-ensure/)`
- [ ] **Task 10: Run Chaos Tests Against Your Microservices — Kill One Service, Do Others Degrade Gracefully?**
  * **Objective**: **Scenario:** Use chaos engineering to verify your system degrades gracefully when services fail.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-10-run-chaos-tests-against-your-microservices/](./tasks/task-10-run-chaos-tests-against-your-microservices/)`
- [ ] **Task 11: Chapter 12 + Task 10 Summary**
  * **Objective**: Service discovery and chaos engineering are two sides of the same coin: discovery ensures services can find each other; chaos tests that they survive when those connections fail. Both are essential for building resilient production systems.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-11-chapter-12-task-10-summary/](./tasks/task-11-chapter-12-task-10-summary/)`
- [ ] **Task 12: Set Up an API Gateway (Kong or AWS API Gateway) — Auth, Rate Limiting, Transformations**
  * **Objective**: **Full Kong setup with auth, rate limiting, and request transformation:**
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-12-set-up-an-api-gateway-kong/](./tasks/task-12-set-up-an-api-gateway-kong/)`
- [ ] **Task 13: Implement the Outbox Pattern to Ensure Exactly-Once Message Delivery**
  * **Objective**: **Complete outbox implementation with Kubernetes deployment:**
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-13-implement-the-outbox-pattern-to-ensure/](./tasks/task-13-implement-the-outbox-pattern-to-ensure/)`
- [ ] **Task 14: Run Chaos Tests Against Your Microservices — Kill One Service, Do Others Degrade Gracefully?**
  * **Objective**: **Chaos engineering** is the practice of intentionally introducing failures in production (or production-like) environments to build confidence that your system handles them gracefully.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-14-run-chaos-tests-against-your-microservices/](./tasks/task-14-run-chaos-tests-against-your-microservices/)`

---
[⬅️ Back to Advanced Architecture Module](../README.md)
