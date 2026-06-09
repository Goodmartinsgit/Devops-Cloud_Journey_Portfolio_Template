# Disaster Recovery & Business Continuity

This subdirectory documents failover steps, backup retention schedules, and verification tests logs.

## 📋 Task Checklist & Progress
- [ ] **Task 1: Cross-Region Database Backups Copy**
  * **Objective**: Write an automated script taking daily database snapshots and copying them to an isolated S3 bucket in a separate AWS region.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-01-crossregion-backup/](./tasks/task-01-crossregion-backup/)`
- [ ] **Task 2: Active-Passive Multi-Region DNS Failover**
  * **Objective**: Set up Route 53 health checks and active-passive routing policy redirecting requests to backup regions upon primary failures.
  * **Status**: ⏳ Planned
  * **Task Folder**: `[task-02-dns-failover/](./tasks/task-02-dns-failover/)`

---
[⬅️ Back to Advanced Architecture Module](../README.md)
