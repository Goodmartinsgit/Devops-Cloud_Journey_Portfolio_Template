# Terraform & Infrastructure as Code

This subdirectory contains Terraform files (`.tf`), state files configurations, modular resource files, and plans.

## 📋 Task Checklist & Progress
- [ ] **Task 1: S3 Backend with DynamoDB State Locking**
  * **Objective**: Configure a remote state backend using an S3 Bucket and enable collaborative state locking via a DynamoDB table.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-01-remote-backend/](./tasks/task-01-remote-backend/)`
- [ ] **Task 2: Modular Infrastructure Reusability**
  * **Objective**: Build a reusable networking Module (VPC, Subnets, Gateways) and instantiate it across `dev` and `prod` workspaces.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-02-tf-modules/](./tasks/task-02-tf-modules/)`
- [ ] **Task 3: Dynamic Provisioning using Variables & Loop Expressions**
  * **Objective**: Use `for_each` and local lists variables to map out multiple subnets, maps configs, and tag formats dynamically.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-03-loops-variables/](./tasks/task-03-loops-variables/)`

---
[⬅️ Back to Cloud Engineering Module](../README.md)
