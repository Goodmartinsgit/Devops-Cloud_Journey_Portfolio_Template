# IAM & Secrets Management

This subdirectory contains configurations, policy templates, and scripts validating cloud-level authorization models and application secrets lifecycle management.

## 📋 Task Checklist & Progress
- [ ] **Task 1: IAM Least-Privilege Policies & Trust Delegation**
  * **Objective**: Configure IAM Roles with least-privilege JSON policy attachments and delegate access using AssumeRole tokens.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-01-iam-trust/](./tasks/task-01-iam-trust/)`
- [ ] **Task 2: Secret Injection with AWS Secrets Manager**
  * **Objective**: Retrieve application API credentials dynamically from AWS Secrets Manager inside a python application script.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-02-secrets-injection/](./tasks/task-02-secrets-injection/)`
- [ ] **Task 3: Local HashiCorp Vault Server Setup**
  * **Objective**: Run a local HashiCorp Vault server, enable KV secret engines, authenticate via AppRole, and retrieve engine variables.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-03-vault-approle/](./tasks/task-03-vault-approle/)`

---
[⬅️ Back to Cloud Engineering Module](../README.md)
