<h1 align="center">Hi, I'm Muhammad Imad 👋</h1>
<h3 align="center">Senior SRE / Platform Engineer · Multi-Cloud (AWS · Azure · GCP) · Kubernetes · GitOps</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Experience-6%2B%20years-0A66C2?style=flat-square" alt="Experience" />
  <img src="https://img.shields.io/badge/Focus-SRE%20%7C%20Platform%20Engineering-2088FF?style=flat-square" alt="Focus" />
  <img src="https://img.shields.io/badge/Open%20to-New%20Opportunities%20%C2%B7%20Remote%20%2F%20Relocation-success?style=flat-square" alt="Open to opportunities" />
</p>

---

### 🚀 About Me

Results-driven **Senior SRE / Platform Engineer** with **6+ years** designing, automating, and operating scalable cloud infrastructure across **AWS, Azure, and GCP**. I build self-service platforms on **Kubernetes**, codify everything with **Terraform / Terragrunt**, ship via **GitOps (ArgoCD)** and **CI/CD pipelines**, and bake in **DevSecOps** and **cloud security** from day one.

- 🏗️ Led architectural redesign of **centralized, multi-region hybrid infrastructure** (on-prem + AWS)
- ☸️ Run **EKS, AKS, GKE, ROSA (OpenShift)** and self-managed (RKE2 / Talos) clusters via GitOps
- 💰 Drove **cost optimization across 50+ AWS accounts** — rightsizing, unused-resource cleanup, cost governance
- 🛡️ Implement **DevSecOps** — Trivy, SonarQube, TFSec, Security Hub, GuardDuty, least-privilege IAM
- 🌍 Architected **multi-region Disaster Recovery** (RTO/RPO-driven, automated failover) during a regional outage

---

### 🛠️ Tech Stack

**Cloud**
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=FF9900)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![GCP](https://img.shields.io/badge/Google%20Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)

**Containers & Orchestration**
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![OpenShift](https://img.shields.io/badge/OpenShift%20(ROSA)-EE0000?style=for-the-badge&logo=redhatopenshift&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white)
![Rancher](https://img.shields.io/badge/Rancher-0075A8?style=for-the-badge&logo=rancher&logoColor=white)

**IaC & Config**
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![Terragrunt](https://img.shields.io/badge/Terragrunt-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white)
![Packer](https://img.shields.io/badge/Packer-02A8EF?style=for-the-badge&logo=packer&logoColor=white)

**GitOps & CI/CD**
![ArgoCD](https://img.shields.io/badge/Argo%20CD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Azure Pipelines](https://img.shields.io/badge/Azure%20Pipelines-2560E0?style=for-the-badge&logo=azuredevops&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)

**Observability & Security**
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![ELK](https://img.shields.io/badge/ELK%20Stack-005571?style=for-the-badge&logo=elasticstack&logoColor=white)
![SonarQube](https://img.shields.io/badge/SonarQube-4E9BCD?style=for-the-badge&logo=sonarqube&logoColor=white)
![Trivy](https://img.shields.io/badge/Trivy-1904DA?style=for-the-badge&logo=aquasecurity&logoColor=white)
![tfsec](https://img.shields.io/badge/tfsec-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)

**Languages**
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white)
![YAML](https://img.shields.io/badge/YAML-CB171E?style=for-the-badge&logo=yaml&logoColor=white)

---

### 🗺️ Platform Architecture — How My Work Fits Together

> Each box is one of my real projects (links in the table below) — rendered live by GitHub on every visit.

```mermaid
flowchart TB
    DEV(["👩‍💻 Developers / Git"]):::entry

    subgraph GOV["☁️ Cloud Foundation & Governance"]
        direction LR
        LZ["🏛️ AWS Landing Zone<br/><i>multi-account · SCPs · audit</i>"]:::aws
        AZ["⚙️ Azure IaC + CI/CD<br/><i>App Service · AKS · Front Door</i>"]:::azure
    end

    subgraph IAC["🧱 Infrastructure as Code"]
        direction LR
        TG["🧱 Terragrunt Platform<br/><i>DRY · VPC / EKS / CloudFront</i>"]:::aws
        PK["🛡️ Golden Images (CIS)<br/><i>Packer · hardened AMIs</i>"]:::sec
    end

    subgraph PLAT["☸️ Kubernetes & GitOps Platform"]
        direction LR
        AR["☸️ ArgoCD GitOps<br/><i>app-of-apps · multi-cluster</i>"]:::k8s
        HC["⛵ Helm Charts Library<br/><i>reusable · auto-release</i>"]:::k8s
        GHA["🔁 Reusable GitHub Actions<br/><i>CI → scan/push → GitOps deploy</i>"]:::cicd
    end

    subgraph APPSEC["🔐 App Security & 💰 FinOps"]
        direction LR
        CG["🔐 Cognito Passwordless<br/><i>CUSTOM_AUTH · Lambda</i>"]:::sec
        CO["💰 Cost Optimizer<br/><i>rightsizing · waste cleanup</i>"]:::fin
    end

    DEV --> GOV
    GOV --> IAC
    IAC --> PLAT
    PLAT --> APPSEC
    CO -. "cost governance" .-> GOV

    click LZ href "https://github.com/Muhammad-Imad/terraform-aws-landing-zone" _blank
    click AZ href "https://github.com/Muhammad-Imad/azure-devops-iac-pipelines" _blank
    click TG href "https://github.com/Muhammad-Imad/terragrunt-aws-platform" _blank
    click PK href "https://github.com/Muhammad-Imad/packer-golden-images-cis" _blank
    click AR href "https://github.com/Muhammad-Imad/argocd-gitops-platform" _blank
    click HC href "https://github.com/Muhammad-Imad/helm-charts-library" _blank
    click CG href "https://github.com/Muhammad-Imad/terraform-aws-cognito-passwordless" _blank
    click CO href "https://github.com/Muhammad-Imad/aws-cost-optimizer" _blank
    click GHA href "https://github.com/Muhammad-Imad/reusable-github-actions" _blank

    classDef entry fill:#0A66C2,stroke:#fff,stroke-width:1px,color:#fff;
    classDef aws fill:#232F3E,stroke:#FF9900,stroke-width:1px,color:#fff;
    classDef azure fill:#0078D4,stroke:#fff,stroke-width:1px,color:#fff;
    classDef k8s fill:#326CE5,stroke:#fff,stroke-width:1px,color:#fff;
    classDef sec fill:#7B1FA2,stroke:#fff,stroke-width:1px,color:#fff;
    classDef fin fill:#2E7D32,stroke:#fff,stroke-width:1px,color:#fff;
    classDef cicd fill:#2088FF,stroke:#fff,stroke-width:1px,color:#fff;
```

---

### 📌 Featured Projects

| Project | What it demonstrates |
|---|---|
| 🏛️ **[terraform-aws-landing-zone](https://github.com/Muhammad-Imad/terraform-aws-landing-zone)** | Multi-account AWS Landing Zone — org / network / identity / log-archive / audit hubs, SCPs, centralized logging |
| 🧱 **[terragrunt-aws-platform](https://github.com/Muhammad-Imad/terragrunt-aws-platform)** | DRY multi-account AWS platform with Terragrunt — `_envcommon` pattern, dependency-ordered VPC / EKS / S3+CloudFront modules |
| ☸️ **[argocd-gitops-platform](https://github.com/Muhammad-Imad/argocd-gitops-platform)** | App-of-apps GitOps across multiple K8s clusters & regions (ArgoCD + Helm + Kustomize) |
| ⛵ **[helm-charts-library](https://github.com/Muhammad-Imad/helm-charts-library)** | Reusable Helm charts — shared library chart + web-service & worker app charts, schema-validated, auto-released |
| 🔁 **[reusable-github-actions](https://github.com/Muhammad-Imad/reusable-github-actions)** | Reusable Actions workflows + composite actions — standardized CI → Trivy-gated build/push → GitOps deploy |
| 🔐 **[terraform-aws-cognito-passwordless](https://github.com/Muhammad-Imad/terraform-aws-cognito-passwordless)** | Reusable, DRY module — passwordless auth (email magic-link + phone OTP) on Cognito CUSTOM_AUTH + Lambda triggers |
| 🛡️ **[packer-golden-images-cis](https://github.com/Muhammad-Imad/packer-golden-images-cis)** | CIS-hardened golden AMIs (Ubuntu / RHEL / Amazon Linux / Windows) with automated builds |
| 💰 **[aws-cost-optimizer](https://github.com/Muhammad-Imad/aws-cost-optimizer)** | Python tool — multi-account cost analysis, rightsizing & unused-resource reports |
| ⚙️ **[azure-devops-iac-pipelines](https://github.com/Muhammad-Imad/azure-devops-iac-pipelines)** | Azure IaC + YAML build/release pipelines for microservices (App Services, AKS, Key Vault, Front Door) |

> 📖 Detailed engineering case studies (architecture, decisions, impact) live in each repo's README.

---

### 🎓 Certifications

<p><i>👆 Click any badge to view the certificate.</i></p>

<p>
  <a href="https://github.com/Muhammad-Imad/Muhammad-Imad/blob/main/certs/aws-devops-engineer-professional.pdf"><img src="https://img.shields.io/badge/AWS%20Certified-DevOps%20Engineer%20Professional-FF9900?style=flat-square&logo=amazonwebservices&logoColor=white" alt="AWS DevOps Pro" /></a>
  <a href="https://github.com/Muhammad-Imad/Muhammad-Imad/blob/main/certs/cka.jpg"><img src="https://img.shields.io/badge/CNCF-Certified%20Kubernetes%20Administrator%20(CKA)-326CE5?style=flat-square&logo=kubernetes&logoColor=white" alt="CKA" /></a>
  <a href="https://github.com/Muhammad-Imad/Muhammad-Imad/blob/main/certs/aws-solutions-architect-associate.png"><img src="https://img.shields.io/badge/AWS%20Certified-Solutions%20Architect%20Associate-FF9900?style=flat-square&logo=amazonwebservices&logoColor=white" alt="AWS SAA" /></a>
  <br/>
  <a href="https://github.com/Muhammad-Imad/Muhammad-Imad/blob/main/certs/az-104-administrator.jpg"><img src="https://img.shields.io/badge/Microsoft-AZ--104%20Azure%20Administrator-0078D4?style=flat-square&logo=microsoftazure&logoColor=white" alt="AZ-104" /></a>
  <a href="https://github.com/Muhammad-Imad/Muhammad-Imad/blob/main/certs/azure-network-engineer.jpg"><img src="https://img.shields.io/badge/Microsoft-Azure%20Network%20Engineer-0078D4?style=flat-square&logo=microsoftazure&logoColor=white" alt="Azure Network Engineer" /></a>
</p>

---

### 📊 GitHub Stats

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=Muhammad-Imad&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&hide=contribs&hide_rank=true" alt="GitHub Stats" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Muhammad-Imad&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Top Languages" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Muhammad-Imad&theme=tokyonight&hide_border=true" alt="GitHub Streak" />
</p>

---

### 📫 Let's Connect

<p>
  <a href="https://www.linkedin.com/in/muhammad-immad-6b0276182"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:muhammad.imad96885@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

<p align="center"><i>📍 Based in Karachi, Pakistan · Open to Remote / Relocation Worldwide · SRE · Platform Engineering · DevOps</i></p>
