# Disaster Recovery & Business Continuity

This subdirectory documents failover steps, backup retention schedules, and verification tests logs.

## 📋 Task Checklist & Progress

- [ ] **Task 1: **
  * **Objective**: **Task:** Define RTO and RPO for a fictional e-commerce application, then design the architecture required to meet those targets.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-01-task/](./tasks/task-01-task/)`
- [ ] **Task 2: Active-Active (Multi-Site)**
  * **Objective**: **What it is:** Two or more fully identical environments run simultaneously, each serving live user traffic. There is no "primary" and "standby" — all regions are primary.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-02-active-active-multi-site/](./tasks/task-02-active-active-multi-site/)`
- [ ] **Task 3: **
  * **Objective**: **Task:** Set up an active-passive DR architecture with a primary environment in us-east-1 and a standby in eu-west-1, with Route 53 failover routing.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-03-task/](./tasks/task-03-task/)`
- [ ] **Task 4: **
  * **Objective**: **Task:** Implement Aurora Global Database across us-east-1 and eu-west-1. Test failover and measure the actual RTO.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-04-task/](./tasks/task-04-task/)`
- [ ] **Task 5: **
  * **Objective**: **Task:** Design a multi-region architecture that prevents split-brain during a network partition.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-05-task/](./tasks/task-05-task/)`
- [ ] **Task 6: **
  * **Objective**: **Task:** Implement immutable backups using S3 Object Lock + Vault Lock, then verify that even administrator-level deletion attempts are blocked.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-06-task/](./tasks/task-06-task/)`
- [ ] **Task 7: **
  * **Objective**: **Task:** Set up AWS Backup to automate daily snapshots of RDS, EBS, and EFS resources, with cross-region copy to eu-west-1.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-07-task/](./tasks/task-07-task/)`
- [ ] **Task 8: **
  * **Objective**: **Task:** Set up an Aurora Global Database, test failover, and measure actual RTO vs target.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-08-task/](./tasks/task-08-task/)`
- [ ] **Task 9: **
  * **Objective**: **Task:** Write and test a full DR runbook — a step-by-step failover to the standby region with measured RTO.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-09-task/](./tasks/task-09-task/)`
- [ ] **Task 10: **
  * **Objective**: **Task:** Conduct a DR fire drill — shut down the primary region simulation, verify standby serves traffic, and measure RTO.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-10-task/](./tasks/task-10-task/)`
- [ ] **Task 11: **
  * **Objective**: **Task:** Build a complete BCP document for ShopFast, including roles, responsibilities, communication templates, and a decision tree.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-11-task/](./tasks/task-11-task/)`

---
[⬅️ Back to Advanced Architecture Module](../README.md)
