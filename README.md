# Alfonso Rodríguez

**Senior Platform Engineer** · Hong Kong 🇭🇰 · Mexican 🇲🇽

10+ years building payments, logistics, and SaaS platforms. I work at the
boundary between backend services and the infrastructure they run on —
Kubernetes, Terraform, event-driven systems, and the operational practices
that keep them reliable under real traffic.

Go, Kubernetes, Terraform, Kafka, PostgreSQL, AWS.

---

## What I'm building

### Platform & infrastructure

**[k3s-cluster](https://github.com/beabys/k3s-cluster)** — Two-phase self-hosted
Kubernetes platform on Proxmox. Ansible bootstraps the cluster (external HAProxy +
MariaDB + K3s nodes); Terraform deploys the platform services — Traefik, MetalLB,
Longhorn, Prometheus, Loki, ArgoCD, Fission, and External Secrets Operator.

**[proxmox-terraform](https://github.com/beabys/proxmox-terraform)** — Reusable
Terraform modules for provisioning VMs and LXC containers on Proxmox, with
multi-instance definitions and parameterized machine shapes. The infrastructure
foundation the cluster above runs on.

### Developer tooling

**[mydevstack](https://github.com/my-devstack/mydevstack)** — Web interface for
managing 18+ AWS services running locally against LocalStack, FloCi, or MiniStack.
Real-time status, CRUD operations, and code examples for every service.
TypeScript, Vue, Go, Docker.

**[ilnamiqui](https://github.com/beabys/ilnamiqui)** — Long-term memory for AI
coding assistants. Persists project context — decisions, fixes, architecture
choices — across chat sessions. Local, private, zero telemetry.

### Libraries

**[ayotl](https://github.com/beabys/ayotl)** — Lightweight, zero-interface Go
configuration library supporting JSON, YAML, and INI with environment variable
substitution. Named after the Nahuatl word for "turtle shell."

---

## Background

Over the past decade I've designed high-throughput payment systems, led
cross-regional engineering teams, and migrated monolithic platforms to
microservices. I care about clean code, pragmatic architecture, and mentoring
the people I work with.

Selected experience:

- **Alchemy Global Solutions** — Senior Backend/Platform Engineer. Redesigned
  inventory import for an event-driven architecture; built KYC services; migrated
  monolith to microservices on Kubernetes; designed gRPC server/client systems.
- **Caton Technology** — Lead Platform Engineer. Docker + GitLab CI/CD pipelines;
  led engineering teams across Hong Kong and Singapore; ran on-premises white-label
  SaaS platforms on bare-metal infrastructure.
- **Lalamove** — Senior Software Engineer. High-performance microservices for
  real-time logistics; high-availability systems under peak load; driver
  registration flow.
- **Yedpay** — Senior Backend/Platform Engineer. Payment gateway APIs for Alipay,
  UnionPay, BestPay, and Visa (CyberSource) under PCI-DSS; transactional
  notifications (SMS, email, push).

---

## Find me

- Website — [alfonsorodriguez.xyz](https://alfonsorodriguez.xyz)
- LinkedIn — [in/beabys](https://www.linkedin.com/in/beabys/)
- Email — [contact@alfonsorodriguez.xyz](mailto:contact@alfonsorodriguez.xyz)
