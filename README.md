# Nextcloud DevOps Infra

This repository contains the **Infrastructure as Code (IaC)** and automation scripts to deploy a **Nextcloud cloud storage solution** on **Microsoft Azure**.  

The project was developed as part of a 2-month internship to demonstrate **DevOps practices** and cloud deployment automation.

## Features
- **Terraform**: Creates Azure infrastructure (VM, VNet, NSG, Public IP).  
- **Ansible**: Configures VM and installs Nextcloud stack with Docker.  
- **Jenkins CI/CD**: Automates deployment and integrates monitoring & alerting.  
- **Security**: Firewall rules, HTTPS, automatic updates, fail2ban.  
- **Monitoring**: Disk usage checks, alerts, and future integration with Prometheus/Grafana.  

## Objective
Provide a **scalable, secure, and automated Nextcloud environment** to practice and showcase **DevOps skills** using cloud platforms and modern tools.

---
