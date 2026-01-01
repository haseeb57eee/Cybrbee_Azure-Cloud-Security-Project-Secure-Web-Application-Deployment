# Azure Cloud Security Project – Secure Web Application Deployment

**Domain:** hasibcybrsecurity.xyz  
**Cloud Platform:** Microsoft Azure  
**Duration:** 3 Days  
**Focus Areas:** Cloud Security, Certificates, WAF, Security Posture Management  

---

## Project Overview
This project demonstrates the design, deployment, and security hardening of a cloud-based web application using Microsoft Azure. The goal was to apply practical cybersecurity concepts in a real cloud environment, including secure application hosting, certificate management, web application firewall configuration, and security posture analysis.

The web application was deployed using Azure App Service with a containerized architecture and connected to a custom domain registered via GoDaddy.

---

## Project Objectives
- Deploy a secure Azure Web App using App Service
- Deploy and manage a containerized web application
- Configure a custom domain for public access
- Implement secure certificate management using Azure Key Vault
- Analyze self-signed and trusted certificates
- Configure and customize Azure Web Application Firewall (WAF)
- Analyze and remediate Azure Security Center recommendations

---

## High-Level Architecture
- GoDaddy Domain (hasibcybrsecurity.xyz)
- Azure App Service (Web App + Container)
- Azure Key Vault (Certificates & Secrets)
- Azure Web Application Firewall (WAF)
- Azure Security Center (Defender for Cloud)

This architecture follows a **defense-in-depth** approach.

---

## Project Timeline & Implementation

### Day 1: Azure Web App & Container Deployment
- Created an Azure Web App using App Service
- Deployed a container image to the web app
- Designed a custom web application using:
  - Bash shell
  - Nano editor
  - Azure terminal / CLI
- Connected the custom domain from GoDaddy

**Outcome:**  
A fully functional web application accessible via `hasibcybrsecurity.xyz`.

-----------------------------------------------------------------------------------------------------------------------------------------

### Day 2: Key Vault & Certificate Management
- Created an Azure Key Vault
- Generated a self-signed certificate
- Stored certificates securely in Key Vault
- Analyzed:
  - Self-signed certificates
  - Trusted (CA-signed) certificates

**Key Insight:**  
Encryption without trust is insufficient for production systems.

-----------------------------------------------------------------------------------------------------------------------------------------

### Day 3: WAF & Security Center Analysis
- Analyzed default Azure WAF rule sets
- Configured custom WAF rules to enhance protection
- Reviewed Azure Security Center recommendations
- Remediated identified security risks and misconfigurations

**Key Insight:**  
Most cloud security risks originate from misconfigurations rather than vulnerabilities.

---

## Security Concepts Applied
- Container security and isolation
- Certificate trust models
- Secure secret storage using Azure Key Vault
- Application-layer protection using WAF
- Continuous security posture monitoring
- Shared responsibility model in cloud security

---

## Tools & Technologies Used
- Microsoft Azure App Service
- Azure Key Vault
- Azure Web Application Firewall (WAF)
- Azure Security Center (Defender for Cloud)
- Docker / Containers
- Bash & Nano
- GoDaddy (Domain Management)

---

## Project Outcome
By the end of this project:
- A secure Azure web application was successfully deployed
- Certificates were created, stored, and analyzed securely
- WAF protections were configured and customized
- Security Center recommendations were reviewed and remediated
- Practical cloud security skills were demonstrated

---

## Future Improvements
- Enable CI/CD pipeline with security scanning
- Implement Azure Monitor & Log Analytics alerts
- Incorporate a load balancer for multiple web application management
- Include Jumphost for more secure accessibility and authorization
- Add DDoS Protection Standard
- Automate security compliance checks

----------------------------------------------------------------------------------------------------

## License
This project is for educational and portfolio purposes.

----------------------------------------------------------------------------------------------------

## 👤 Author
**Md Habibur Rahman**  
Cybersecurity & Cloud Security Enthusiast  
