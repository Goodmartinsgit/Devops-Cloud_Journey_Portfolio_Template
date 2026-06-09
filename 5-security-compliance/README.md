# 🔒 Module 5: Security & Compliance

This module documents secure system design practices, vulnerability scanning integrations, Kubernetes role bindings, and zero-trust proxy configurations.

## 🧭 Chapters Index

| Chapter | Focus | Core Domain / Tooling | Status |
| :--- | :--- | :--- | :---: |
| 📂 **[5.1 DevSecOps & Supply Chain Security](./5.1-devsecops/)** | DevSecOps | Trivy scanning, Gitleaks secrets audit, SAST checks, secure base images. | ⏳ Planned |
| 📂 **[5.2 Kubernetes Security](./5.2-k8s-security/)** | K8s Security | RBAC policies, NetworkPolicies, PodSecurityStandards, secrets encrypt. | ⏳ Planned |
| 📂 **[5.3 Zero Trust & Network Security](./5.3-zero-trust/)** | Zero Trust | TLS/SSL certificate authority (Let's Encrypt), VPN access tunnels. | ⏳ Planned |

---

## 🛠️ Key Security Skills
* **Vulnerability Scanning**: Setting up automated container scanning using Trivy to detect packages CVEs and base image flaws.
* **Kubernetes Hardening**: Creating RBAC files limiting system access, and writing NetworkPolicies blocking non-essential namespace communications.
* **Secrets Audits**: Integrating Gitleaks checks inside pipeline jobs to block committing passwords/keys.
* **Network Encryptions**: Setting up dynamic certificate managers automating SSL renewal sequences for web nodes.

---
[⬅️ Back to Main Portfolio](../README.md)
