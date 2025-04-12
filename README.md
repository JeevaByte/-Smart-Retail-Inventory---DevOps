# Smart Retail Inventory - DevOps Proof of Concept (PoC)

## 🧭 Overview
A full-stack Smart Retail Inventory PoC showcasing the end-to-end capabilities of an Azure DevOps Engineer with 6+ years of experience. This project is aligned with **real-world enterprise DevOps responsibilities** and **Microsoft AZ-400 certification** expectations.

---

## 📘 Business Context
A fictional Smart Retail company wants to automate its inventory tracking, delivery pipeline, monitoring, and high availability. The goal is to:
- Improve CI/CD throughput
- Secure sensitive systems and inventory data
- Ensure scalability and reliability
- Enable multi-stage deployments with rollback and testing

---

## 🛠️ Technology Stack
- **Frontend**: React (Flatlogic Dashboard)
- **Backend**: Node.js (Express REST API)
- **Database**: PostgreSQL (Azure Database for PostgreSQL)
- **Containerization**: Docker
- **Orchestration**: Azure Kubernetes Service (AKS)
- **CI/CD**: Azure Pipelines (YAML)
- **IaC**: Terraform (modular)
- **Monitoring**: Azure Monitor, App Insights
- **Security**: Azure Key Vault, Azure Policy, Snyk

---

## ✅ Feature Matrix

### 🔧 Core Azure DevOps Tools & Practices
| Skill | Covered | Notes |
|---|---|---|
| Azure Repos / GitHub | ✅ | Code hosted in GitHub
| Azure Boards | ✅ | Work items, sprints defined
| Azure Pipelines | ✅ | Full YAML CI/CD setup
| Azure Artifacts | ✅ | NPM + custom NuGet support
| Azure Test Plans | ✅ | Postman, unit tests in pipeline
| Service Connections, RBAC | ✅ | RBAC, Service Principals used

### ⚙️ CI/CD Pipeline Engineering
| Skill | Covered |
|---|---|
| YAML pipelines | ✅ |
| Dev → Stage → Prod envs | ✅ |
| Approval gates | ✅ |
| Containerization | ✅ |
| Secrets & configs | ✅ (Key Vault + variable groups) |
| PR/branch triggers | ✅ |

### 🏗️ Infrastructure as Code (IaC)
| Skill | Covered |
|---|---|
| Terraform/Bicep | ✅ Terraform with modules |
| Provisioning infra | ✅ AKS, DB, Key Vault |
| Secure outputs | ✅ |
| State/workspace mgmt | ✅ Backend config with remote state |

### 🔐 Security / DevSecOps
| Skill | Covered |
|---|---|
| Key Vault integration | ✅ |
| Secrets scanning | ✅ (Snyk) |
| Dependency scanning | ✅ |
| RBAC/Pipeline security | ✅ |
| Policy gates | ✅ |

### 🧪 Testing & Quality Gates
| Skill | Covered |
|---|---|
| Unit tests | ✅ |
| REST API tests | ✅ (Postman + Newman) |
| Test reporting | ✅ |
| Code quality | ✅ (SonarCloud) |
| PR policies | ✅ |

### 📈 Monitoring, Logging, Observability
| Skill | Covered |
|---|---|
| Azure Monitor | ✅ |
| App Insights | ✅ |
| KQL Dashboards | ✅ |
| Alert rules | ✅ |
| SLO/SLI | ✅ |

### 🌍 Advanced Topics
| Skill | Covered |
|---|---|
| Canary / Blue-Green | ✅ |
| Feature Flags | ✅ (LaunchDarkly) |
| Chaos Testing | 🚧 (Planned via Azure Chaos Studio) |
| GitOps (ArgoCD) | 🚧 (Optional for prod demo) |

### 🧠 Strategic / Architecture-Level
| Skill | Covered |
|---|---|
| System trade-offs | ✅ Documented in README |
| Cost optimization | ✅ Azure Budget alerts setup |
| HA & DR | ✅ AKS node pools + geo-replication |
| Cloud Adoption Framework | ✅ Aligned with Govern pillar |

### 💼 Enterprise DevOps Additions
| Skill | Covered |
|---|---|
| Terraform landing zones | ✅ Modular structure |
| Azure Policy & Blueprints | ✅ Enforce tag compliance |
| InnerSource model | ✅ Reusable templates shared |
| PIM/JIT Access | ✅ PIM access demo configured |
| Secret rotation policy | ✅ Example rotation policy included |

### 🛰️ Hybrid / Multi-Cloud (Optional)
| Skill | Status |
|---|---|
| GitHub Advanced Security | ✅ |
| AWS/GCP readiness | 🚧 Optional section added |
| Edge / IoT | 🚧 Future integration |

### 🧾 SRE & Ops
| Skill | Covered |
|---|---|
| Runbooks | ✅ (Logic App auto-fix demo) |
| Chaos testing | 🚧 (Planned) |
| Error budgets | ✅ Logged in dashboards |
| PagerDuty integration | 🚧 Optional extension |

---

## 📘 Documentation Includes
- ✅ Project README (this file)
- ✅ Architecture Diagram (Mermaid + PNG)
- ✅ AZ-400 Concept Mapping Table
- ✅ Replication Guide (Local + Azure Deployment)
- ✅ Interview Prep Guide: Design FAQs + Tech Justifications
- ✅ Business KPIs & DevOps Metrics Mapping

---

## 🚀 How to Deploy
1. Clone the repo
2. Set up Azure DevOps project or GitHub connection
3. Run Terraform `init`, `plan`, `apply`
4. Commit code to trigger CI/CD
5. Use Azure Boards to track tasks
6. Monitor via Azure Monitor Dashboard

---

## 🧩 Future Enhancements
- [ ] GitOps via ArgoCD
- [ ] Load testing with Azure Load Test
- [ ] Chaos Testing via Azure Chaos Studio
- [ ] Edge device integration using Azure IoT Edge

---

## 📄 License
MIT License — free to reuse and extend.

---

## 🙋‍♀️ Want Help?
If you're a DevOps Engineer or team looking to build something similar or just want a walkthrough — feel free to connect!
