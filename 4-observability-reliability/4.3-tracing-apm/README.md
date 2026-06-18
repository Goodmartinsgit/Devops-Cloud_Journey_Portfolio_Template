# Distributed Tracing & APM

This subdirectory houses traces instrumentation files and APM setups.

## 📋 Task Checklist & Progress

- [ ] **Task 1: Trace a Concept Map**
  * **Objective**: Before writing any code, build your mental model. Draw (on paper or digitally) a trace for the following scenario:
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-01-trace-a-concept-map/](./tasks/task-01-trace-a-concept-map/)`
- [ ] **Task 2: Instrument Your Node.js App**
  * **Objective**: Instrument a Node.js Express application with OpenTelemetry SDK, enabling auto-instrumentation for HTTP and database calls.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-02-instrument-your-nodejs-app/](./tasks/task-02-instrument-your-nodejs-app/)`
- [ ] **Task 3: Deploy the OTel Collector as a Kubernetes DaemonSet**
  * **Objective**: A **DaemonSet** ensures one pod runs on every node in your cluster. For the OTel Collector, this means every node has a local Collector that applications can send spans to, without going over the network to a central Collector.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-03-deploy-the-otel-collector-as-a/](./tasks/task-03-deploy-the-otel-collector-as-a/)`
- [ ] **Task 4: Set Up Adaptive Sampling with Error 100% / Success 1%**
  * **Objective**: Configure Jaeger and an OTel Collector to always capture error traces (100%) while sampling only 1% of successful requests.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-04-set-up-adaptive-sampling-with-error/](./tasks/task-04-set-up-adaptive-sampling-with-error/)`
- [ ] **Task 5: Trace a Complete User Request End-to-End**
  * **Objective**: Instrument a complete request flow from browser → API gateway → auth service → database, and visualise the full trace in Tempo with log correlation.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-05-trace-a-complete-user-request-end/](./tasks/task-05-trace-a-complete-user-request-end/)`
- [ ] **Task 6: Use Datadog APM and Document Differences vs OTel**
  * **Objective**: Instrument one service with Datadog APM, and compare the experience with your existing OTel setup.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-06-use-datadog-apm-and-document-differences/](./tasks/task-06-use-datadog-apm-and-document-differences/)`
- [ ] **Task 7: Deploy Pyroscope and Identify a CPU Hotspot**
  * **Objective**: Deploy Pyroscope for continuous profiling of a Node.js application and identify a CPU hotspot.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-07-deploy-pyroscope-and-identify-a-cpu/](./tasks/task-07-deploy-pyroscope-and-identify-a-cpu/)`
- [ ] **Task 8: Set Up Grafana Faro for RUM and Track Core Web Vitals**
  * **Objective**: Instrument a web application with Grafana Faro to track real user page load times, JavaScript errors, and Core Web Vitals.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-08-set-up-grafana-faro-for-rum/](./tasks/task-08-set-up-grafana-faro-for-rum/)`
- [ ] **Task 9: Build a Service Dependency Map from Trace Data**
  * **Objective**: Using trace data collected from your instrumented services, build a visual service dependency map and identify any circular dependencies.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-09-build-a-service-dependency-map-from/](./tasks/task-09-build-a-service-dependency-map-from/)`
- [ ] **Task 10: Final Chapter Task: Build a Complete Observability System**
  * **Objective**: Build a complete observability system for a three-service application and demonstrate it can detect and diagnose a performance regression.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-10-final-chapter-task-build-a-complete/](./tasks/task-10-final-chapter-task-build-a-complete/)`

---
[⬅️ Back to Observability Module](../README.md)
