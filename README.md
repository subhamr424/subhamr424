# SUBHAM RATHORE

### DevOps & Cloud Engineer · Kubernetes · Platform Engineering

<p align="left">
  <a href="https://github.com/subhamr424">
    <img src="https://img.shields.io/badge/GitHub-subhamr424-111111?style=flat-square&logo=github&logoColor=white"/>
  </a>
  <img src="https://img.shields.io/badge/Experience-3%2B%20Years-111111?style=flat-square"/>
  <img src="https://img.shields.io/badge/AWS-Certified-FF9900?style=flat-square&logo=amazonaws&logoColor=white"/>
  <img src="https://img.shields.io/badge/AWS-Cloud-232F3E?style=flat-square&logo=amazonaws&logoColor=white"/>
  <img src="https://img.shields.io/badge/Azure-Cloud-0078D4?style=flat-square&logo=microsoftazure&logoColor=white"/>
</p>

---

## ENGINEERING PROFILE

I engineer **cloud infrastructure, deployment platforms, and production systems** with a focus on reliability, automation, scalability, and operational simplicity.

My work spans the complete infrastructure lifecycle:

**Infrastructure → Containers → Kubernetes → CI/CD → GitOps → Observability → Production**

Currently working across **AWS, Azure, Kubernetes, infrastructure automation, cloud-native deployments, and platform engineering**.

```text
                     ┌───────────────────────────┐
                     │        APPLICATIONS        │
                     └─────────────┬─────────────┘
                                   │
                              CI/CD / GitOps
                                   │
                     ┌─────────────▼─────────────┐
                     │      PLATFORM LAYER       │
                     │ Kubernetes · Helm · Istio  │
                     └─────────────┬─────────────┘
                                   │
                     ┌─────────────▼─────────────┐
                     │    CLOUD INFRASTRUCTURE   │
                     │       AWS · Azure         │
                     └─────────────┬─────────────┘
                                   │
                     ┌─────────────▼─────────────┐
                     │     AUTOMATION / IaC      │
                     │ Terraform · Ansible · Git │
                     └─────────────┬─────────────┘
                                   │
                     ┌─────────────▼─────────────┐
                     │       OBSERVABILITY       │
                     │ Prometheus · Grafana ·    │
                     │ Loki · CloudWatch         │
                     └───────────────────────────┘
```

---

# WHAT I ENGINEER

| Area                 | Focus                                                                |
| -------------------- | -------------------------------------------------------------------- |
| ☁️ **Cloud**         | AWS · Azure · VPC · EC2 · ECS · EKS · ALB · Auto Scaling · RDS       |
| ☸️ **Kubernetes**    | EKS · Kubernetes · Helm · Istio · Ingress · Microservices            |
| 🚀 **Delivery**      | Jenkins · GitHub Actions · GitLab CI · AWS CodePipeline · CodeDeploy |
| 🔄 **GitOps**        | Argo CD · Helm · ECR · Kubernetes                                    |
| 🏗️ **IaC**          | Terraform · CloudFormation · Ansible                                 |
| 🐳 **Containers**    | Docker · Amazon ECR · ECS · Kubernetes                               |
| 📊 **Observability** | Prometheus · Grafana · Loki · CloudWatch · Azure Monitor             |
| 🐘 **Database HA**   | PostgreSQL · Patroni · ETCD · Streaming Replication                  |
| 🐧 **Systems**       | Linux · NGINX · Apache · Gunicorn · Bash                             |
| 🔐 **Security**      | IAM · Security Groups · UFW · SSL/TLS · Private Networking           |

---

# SELECTED WORK

## 01 — AWS EKS · Microservices · DevOps

**Repository:** `aws-eks-microservices-devops`

A Kubernetes-focused microservices platform built around **Amazon EKS**, containerized workloads and automated application delivery.

**Architecture**

```text
Developer
   │
   ▼
Git Repository
   │
   ▼
CI/CD Pipeline
   │
   ├── Build
   ├── Test
   └── Container Image
            │
            ▼
         Amazon ECR
            │
            ▼
        Amazon EKS
       ┌────┴────┐
       │         │
   Frontend   Backend
       │         │
       └────┬────┘
            ▼
       Load Balancer
```

**Stack**

`AWS` `EKS` `Kubernetes` `Docker` `Helm` `CI/CD`

→ [Explore Repository](https://github.com/subhamr424/aws-eks-microservices-devops)

---

## 02 — AWS · 3-Tier Production Architecture

**Repository:** `aws-3tier-architecture-devops`

Designed around the principles of **network isolation, high availability, scalability and secure application delivery**.

```text
                    INTERNET
                       │
                       ▼
                  Route 53 / DNS
                       │
                       ▼
                    ALB
                       │
          ┌────────────┴────────────┐
          │                         │
     Public Layer             Application Layer
          │                         │
      NAT Gateway              Private EC2
                                    │
                                    ▼
                               Database Layer
                                    │
                                   RDS
```

**Stack**

`AWS` `VPC` `ALB` `EC2` `Auto Scaling` `RDS` `Route 53` `IAM`

→ [Explore Repository](https://github.com/subhamr424/aws-3tier-architecture-devops)

---

## 03 — AI DevOps · Kubernetes Operations

**Repository:** `AI-DevOps-Kubernetes-Agent`

Exploring the intersection of **AI and infrastructure operations**, with the goal of making Kubernetes troubleshooting and operational workflows more intelligent and automated.

**Stack**

`AI` `Kubernetes` `DevOps` `Automation` `Python`

→ [Explore Repository](https://github.com/subhamr424/AI-DevOps-Kubernetes-Agent)

---

## 04 — Intelligent DevOps Platform

**Repository:** `intelligent-devops-platform`

A platform-oriented project focused on bringing together **automation, Kubernetes operations and intelligent DevOps workflows**.

**Stack**

`Kubernetes` `DevOps` `Automation` `Cloud Native`

→ [Explore Repository](https://github.com/subhamr424/intelligent-devops-platform)

---

## 05 — E-Commerce · Microservices · Istio

**Repository:** `ecommerce-microservices-istio`

A cloud-native e-commerce architecture using **microservices, Kubernetes and Istio** to explore service-to-service communication, traffic management and platform observability.

```text
                    Ingress
                       │
                       ▼
                 Istio Gateway
                       │
          ┌────────────┼────────────┐
          ▼            ▼            ▼
       Service A    Service B    Service C
          │            │            │
          └────────────┼────────────┘
                       │
                 Observability
                       │
              Prometheus / Grafana
```

**Stack**

`Kubernetes` `Docker` `Istio` `Microservices` `Observability`

→ [Explore Repository](https://github.com/subhamr424/ecommerce-microservices-istio)

---

## 06 — DevOps Platform

**Repository:** `devops-platform`

Infrastructure and automation components built around reusable **DevOps and platform engineering patterns**.

**Stack**

`DevOps` `Kubernetes` `Terraform` `CI/CD` `Automation`

→ [Explore Repository](https://github.com/subhamr424/devops-platform)

---

# PRODUCTION EXPERIENCE

Beyond personal projects, my professional work includes:

* Production AWS infrastructure across **EC2, ECS and EKS**
* Highly available **3-tier AWS architectures**
* Blue/Green, Rolling and Zero-Downtime deployments
* End-to-end CI/CD using Jenkins, GitHub Actions, GitLab CI and AWS deployment services
* GitOps deployments using **Argo CD + Helm + EKS**
* Infrastructure provisioning with **Terraform and CloudFormation**
* Container platforms using **Docker, ECS, ECR and Kubernetes**
* PostgreSQL HA using **Patroni + ETCD**
* Production monitoring with **Prometheus, Grafana, CloudWatch and Azure Monitor**
* Linux infrastructure administration, hardening and troubleshooting
* Production migrations, performance tuning and AWS cost optimization
* Root Cause Analysis of infrastructure, Kubernetes, networking and deployment incidents

---

# CLOUD ARCHITECTURE

### AWS

`EC2` `VPC` `ALB` `NAT Gateway` `Route 53` `ACM` `IAM` `S3` `ECR` `ECS` `EKS` `RDS` `Auto Scaling` `CloudWatch`

### Azure

`Virtual Machines` `VNet` `Azure Load Balancer` `VMSS` `Azure AD` `ACR` `AKS` `Azure Monitor`

---

# DELIVERY MODEL

```text
       CODE
        │
        ▼
     GIT PUSH
        │
        ▼
   ┌───────────┐
   │   BUILD   │
   │   TEST    │
   └─────┬─────┘
         │
         ▼
   CONTAINER IMAGE
         │
         ▼
      REGISTRY
         │
         ▼
      GITOPS
      Argo CD
         │
         ▼
    KUBERNETES
         │
         ▼
   OBSERVE / ALERT
         │
         ▼
   IMPROVE / SCALE
```

The goal is simple:

> **Every deployment should be repeatable. Every change should be traceable. Every production system should be observable.**

---

# TOOLBOX

<p align="center">
<img src="https://skillicons.dev/icons?i=aws,azure,kubernetes,docker,terraform,ansible,jenkins,git,github,linux,bash"/>
</p>

<p align="center">
<img src="https://skillicons.dev/icons?i=prometheus,grafana,postgresql,redis,mongodb,python"/>
</p>

**Platform:** Kubernetes · EKS · Helm · Istio · Argo CD
**CI/CD:** Jenkins · GitHub Actions · GitLab CI · AWS CodePipeline · CodeDeploy
**Infrastructure:** Terraform · CloudFormation · Ansible
**Observability:** Prometheus · Grafana · Loki · CloudWatch · Azure Monitor

---

# CERTIFICATION

### AWS Certified Solutions Architect – Associate

**SAA-C03 · April 2026**

---

# GITHUB

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=subhamr424&show_icons=true&hide_border=true&count_private=true&rank_icon=github" height="170"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=subhamr424&layout=compact&hide_border=true" height="170"/>
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=subhamr424&hide_border=true" height="170"/>
</p>

---

# CURRENTLY ENGINEERING

```text
Cloud Infrastructure
Kubernetes Platforms
GitOps & Continuous Delivery
Infrastructure as Code
Observability & Reliability
AI-assisted DevOps
Platform Engineering
```

I’m particularly interested in building platforms where **developers can ship faster without infrastructure becoming a bottleneck**.

---

# CONNECT

<p align="center">

<a href="https://github.com/subhamr424">
<img src="https://img.shields.io/badge/GitHub-subhamr424-111111?style=for-the-badge&logo=github&logoColor=white"/>
</a>

<a href="https://linkedin.com/subham-rathore-055a94256">
<img src="https://img.shields.io/badge/LinkedIn-Subham%20Rathore-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

</p>

---

<p align="center">

### BUILD → AUTOMATE → DEPLOY → OBSERVE → SCALE

**Engineering reliable infrastructure, one system at a time.**

</p>
