# aws-cost-optimization-case-study
RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

# 💰 AWS Cost Optimization Case Study

![AWS](https://img.shields.io/badge/AWS-Cloud-orange?logo=amazonaws)
![Project](https://img.shields.io/badge/project-real--world-blue)
![Focus](https://img.shields.io/badge/focus-finops-success)
![Status](https://img.shields.io/badge/status-completed-brightgreen)
![Level](https://img.shields.io/badge/level-cloud--junior-informational)

---

## 🚀 Overview

This project presents a **cost optimization strategy in AWS**, focusing on reducing infrastructure expenses while maintaining performance and scalability.

* **Company:** Abstergo Industries
* **Author:** Ederson
* **Date:** April 2026

---

## 🎯 Business Problem

The company was facing:

* ❌ Over-provisioned infrastructure
* ❌ High storage costs for cold data
* ❌ Lack of scalability control

---

## 💡 Solution

A 3-step optimization strategy was implemented:

### ⚙️ 1. EC2 Spot Instances

* Replaced on-demand instances for non-critical workloads
* Ideal for batch processing and testing environments
* **Impact:** Significant compute cost reduction

---

### 📦 2. S3 Lifecycle + Glacier

* Automated transition of old data to cheaper storage tiers
* Reduced cost without losing data availability
* **Impact:** Storage optimization

---

### 🔄 3. Auto Scaling

* Dynamic adjustment of compute capacity
* Eliminated idle resources
* **Impact:** Efficient resource usage

---

## 🏗️ Architecture

![AWS Architecture](assets/arquitetura.png)

---

## 📊 Cost Optimization Impact

| Area           | Before         | After            | Impact |
| -------------- | -------------- | ---------------- | ------ |
| Compute        | On-demand only | Spot Instances   | 🔻🔻   |
| Storage        | Standard only  | Tiered (Glacier) | 🔻     |
| Infrastructure | Static         | Auto Scaling     | 🔻     |

💡 **Estimated savings: ~30% monthly cost reduction**

---

## 📄 Documentation

Full report available:
👉 `RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS.pdf`

---

## 📚 Artifacts

* Spot Instances configuration guide
* S3 Lifecycle policies
* Cost analysis spreadsheet

---

## 🧠 Key Learnings

* Cloud cost optimization (**FinOps mindset**)
* Efficient use of Spot Instances
* Storage tiering strategies
* Infrastructure scalability

---

## 🔍 Decision Breakdown

| Service | Problem             | Solution            | Result |
| ------- | ------------------- | ------------------- | ------ |
| EC2     | High fixed cost     | Spot Instances      | -20%   |
| S3      | Expensive cold data | Lifecycle + Glacier | -10%   |
| Infra   | Idle resources      | Auto Scaling        | -5%    |

---

## 👨‍💻 About Me

Cloud-focused professional building hands-on projects in AWS, focusing on:

* Cost optimization
* Cloud architecture
* Infrastructure efficiency

---

## 📈 Next Steps

* Implement AWS Cost Explorer dashboards
* Add monitoring and alerts
* Migrate to serverless architecture
* Automate infrastructure with Terraform

---

## 🌎 Portfolio

More projects coming soon focused on Cloud & DevOps.

---

> 💡 *"In cloud computing, efficiency is not about spending less — it's about spending smart."*
