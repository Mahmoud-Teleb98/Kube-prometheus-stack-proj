# 🚀 Kubernetes Monitoring using Prometheus & Grafana

This project demonstrates monitoring a Kubernetes cluster using:

- Prometheus for metrics collection  
- Grafana for visualization and dashboards  
- Helm for automated deployment  

---

## 📌 Overview

The monitoring stack was deployed using Helm charts to provide:

- Cluster monitoring  
- Pod and node metrics  
- Resource usage visualization  
- Centralized observability for Kubernetes workloads  

---

## 🏗️ Architecture Diagram

```mermaid
flowchart LR
    A[Kubernetes Cluster] --> B[Prometheus]
    B --> C[Grafana Dashboards]
    C --> D[Monitoring & Visualization]
