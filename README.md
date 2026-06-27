# Oluwasheyi Olayemi Ojelade

**Cloud Operations & DevOps Engineer**

I build infrastructure to solve actual business problems. My job is to keep production systems online, secure, and easy for developers to use. I close the gap between development teams that want to move quickly and operations teams that need systems to stay stable under heavy load. Coming from a background in Linux systems administration and server hardening, security is built into my architecture from the very first decision.

[![Portfolio](https://img.shields.io/badge/Portfolio-Visit_My_Website-005571?style=for-the-badge&logo=vercel)](https://oluwasheyi-portfolio.virusinferno.xyz)

---

### What I Do
* **Cloud & Orchestration:** Amazon Web Services (EC2, S3, VPC, Route 53, EKS), Kubernetes, Google Cloud Platform, Microsoft Azure.
* **Infrastructure as Code & GitOps:** Terraform with S3 remote backend management, ArgoCD.
* **CI/CD & Containers:** GitHub Actions, Docker, Docker Compose, custom GitHub Runners.
* **Security & Networking:** Trivy container vulnerability scanning, IAM least privilege, UFW, Nginx Ingress Controller, Cert-Manager.
* **Observability & Monitoring:** Prometheus, Grafana, Alertmanager, Helm, Datadog.

---

### Featured Architecture & Deployments
* **AeroBank (Financial Infrastructure):** Served as Tech Lead for a 22 person engineering team to architect a highly available AWS environment using Terraform. Orchestrated a multi stage Docker build into Amazon EKS and automated GitOps pipelines using ArgoCD to achieve zero downtime cluster synchronization.
* **Automated DevSecOps Pipeline:** Built a CI/CD workflow that catches critical CVEs before an image ships. Trivy scanning sits directly inside GitHub Actions and automatically blocks vulnerable images from reaching the AWS ECR registry.
* **Cross Region Serverless Failover:** Architected a serverless backend that fails over automatically with zero downtime. DynamoDB Global Tables replicate data between regions in real time, while Route 53 health checks redirect traffic if a regional failure occurs.
* **Kubernetes Observability Stack:** Deployed a full observability layer on Amazon EKS using Helm, Prometheus, and Grafana. Configured custom dashboards for cluster visibility and set up Alertmanager to route pod failures straight to a Slack channel.

---

### Let's Connect
If you need someone who can look at a system, find where it is losing money or exposing risk, and fix it without breaking what already works, that is exactly what I deliver. Feel free to reach out via my portfolio to discuss cloud architecture, infrastructure roles, or system reliability.
