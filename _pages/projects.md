---
title: "Projects"
permalink: /projects/
---

## AWS EKS Kubernetes Platform
**Problem:** Teams shipped services inconsistently, leading to reliability gaps and rising cloud spend.  
**Solution:** Designed an EKS platform with multi-AZ node groups, IAM-based access, autoscaling, and cost-aware policies for workloads. Standardized deployments through GitHub Actions.  
**Technologies:** AWS, EKS, Terraform, CloudFormation, GitHub Actions, CloudWatch, Grafana.  
**Impact:** Faster, safer releases and reduced idle compute through right-sized capacity and autoscaling.

## GCP GKE Autopilot Platform
**Problem:** Needed a managed Kubernetes option with minimal ops overhead for new services.  
**Solution:** Built GKE Autopilot environments with namespace isolation, workload identity, and GitLab-driven deployments. Added logging and metrics pipelines into ELK and Prometheus for visibility.  
**Technologies:** GCP, GKE Autopilot, GitLab CI, Prometheus, ELK, Grafana.  
**Impact:** Reduced cluster management toil while keeping security and observability consistent across teams.

## CI/CD Automation (GitHub Actions + GitLab)
**Problem:** Manual deployments slowed delivery and introduced configuration drift.  
**Solution:** Authored reusable pipelines covering build, test, security checks, and multi-env rollouts for frontend and backend services. Integrated artifact versioning and environment promotions.  
**Technologies:** GitHub Actions, GitLab CI, Docker, AWS, GCP.  
**Impact:** Shortened deployment cycles and increased confidence through automated gates and repeatable releases.

## Infrastructure as Code (Terraform + CloudFormation)
**Problem:** Environments were hand-built and difficult to audit or replicate.  
**Solution:** Codified AWS and GCP stacks with Terraform modules and CloudFormation templates, embedding guardrails for IAM, networking, and cost controls.  
**Technologies:** Terraform, CloudFormation, AWS, GCP.  
**Impact:** Provisioning became predictable, reviewable, and aligned with compliance requirements.

## Observability Stack
**Problem:** Fragmented monitoring delayed incident detection and troubleshooting.  
**Solution:** Consolidated metrics, logs, and traces using CloudWatch, ELK, Prometheus, and Grafana with service-level dashboards and alert policies.  
**Technologies:** CloudWatch, ELK, Prometheus, Grafana, Kubernetes.  
**Impact:** Improved MTTR with actionable alerts and shared visibility across platform and application teams.

## Security & Compliance Platform
**Problem:** Security controls and SOC 2 needs were bolted on late in delivery.  
**Solution:** Integrated IAM hardening, secrets management, and compliance checks into pipelines and infrastructure code. Added audit-friendly logging and access patterns across AWS and GCP.  
**Technologies:** IAM, Terraform, CloudFormation, GitHub Actions, GitLab CI, CloudWatch.  
**Impact:** Reduced security risk and simplified audits through built-in guardrails and traceability.
