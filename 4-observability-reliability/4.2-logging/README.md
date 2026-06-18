# Logging & Log Management

This subdirectory houses logs shipper configs and search dashboards validating log management pipelines.

## 📋 Task Checklist & Progress

- [ ] **Task 1: Deploy ELK Stack on K8s with Helm**
  * **Objective**: Deploy a working ELK stack on a Kubernetes cluster, ship nginx and application logs, and configure 30-day ILM.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-01-deploy-elk-stack-on-k8s-with/](./tasks/task-01-deploy-elk-stack-on-k8s-with/)`
- [ ] **Task 2: Write LogQL Queries in Grafana**
  * **Objective**: Write LogQL queries to extract insights from application logs in Loki.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-02-write-logql-queries-in-grafana/](./tasks/task-02-write-logql-queries-in-grafana/)`
- [ ] **Task 3: Add Fluent Bit DaemonSet — Route App Logs to Loki, System Logs to OpenSearch**
  * **Objective**: Deploy Fluent Bit as a DaemonSet, with routing rules that send application logs to Loki and system logs to OpenSearch.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-03-add-fluent-bit-daemonset-route-app/](./tasks/task-03-add-fluent-bit-daemonset-route-app/)`
- [ ] **Task 4: Set Up S3-Based Log Archival**
  * **Objective**: Configure Fluent Bit to ship logs older than 30 days to S3, with Glacier transition, and verify retrieval.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-04-set-up-s3-based-log-archival/](./tasks/task-04-set-up-s3-based-log-archival/)`
- [ ] **Task 5: CloudWatch Logs Insights — Identify Top 10 Slowest API Endpoints**
  * **Objective**: Use CloudWatch Logs Insights to analyse access logs and identify the slowest API endpoints.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-05-cloudwatch-logs-insights-identify-top-10/](./tasks/task-05-cloudwatch-logs-insights-identify-top-10/)`
- [ ] **Task 6: Update Node.js App to Use Pino**
  * **Objective**: Refactor a Node.js application to use pino for structured JSON logging with correlation IDs.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-06-update-nodejs-app-to-use-pino/](./tasks/task-06-update-nodejs-app-to-use-pino/)`
- [ ] **Task 7: Implement Log-Based Alerting — Loki Ruler Error Rate Alert**
  * **Objective**: Configure the Loki Ruler to fire an alert when error rate exceeds 5% for 5 minutes.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-07-implement-log-based-alerting-loki-ruler/](./tasks/task-07-implement-log-based-alerting-loki-ruler/)`
- [ ] **Task 8: Set Up Audit Logging with CloudTrail**
  * **Objective**: Configure CloudTrail to capture all AWS API calls, ship to CloudWatch Logs, and alert on root login or IAM changes.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-08-set-up-audit-logging-with-cloudtrail/](./tasks/task-08-set-up-audit-logging-with-cloudtrail/)`
- [ ] **Task 9: Build a Log Correlation Tool**
  * **Objective**: Given a trace ID (correlation ID), pull logs from all services for that request.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-09-build-a-log-correlation-tool/](./tasks/task-09-build-a-log-correlation-tool/)`

---
[⬅️ Back to Observability Module](../README.md)
