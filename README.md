# DevSecOps

## What is DevSecOps?

DevSecOps means integrating security controls throughout the software development life cycle (SDLC) instead of treating security as a final manual stage. 

The main goal is to detect issues early, automate security checks, enforce policies in CI/CD, and continuously monitor production.

---

## What DevSecOps Does in Daily Work

* Integrates security into development
* Performs SAST (Static Application Security Testing)
* Performs SCA (Software Composition Analysis)
* Scans for secret leakage
* Secure IaC (Infrastructure as Code)
* Scans container images
* Performs DAST (Dynamic Application Security Testing)
* Automate security checks in CI/CD
* Enforce security gates
* Monitor application and infrastructure
* Manage vulnerabilities
* Implement security as a shared responsibility
* Code quality checks
* Code smells checks
* CI/CD scanning

---

## Tools and Tech Used by DevSecOps

* **Secure Code:** SonarQube, Checkmarx
* **Scan Dependencies and Libraries:** OWASP Dependency-Check, Snyk
* **Detect Secrets:** Gitleaks, GitGuardian
* **Scan IaC:** Trivy, Checkov
* **Test Running Application:** OWASP ZAP, Burp Suite
* **Automate Security Checks:** GitHub Actions, GitLab CI/CD, Jenkins
* **Scan Container Images:** Trivy, Grype
* **Block Insecure Deployments:** SonarQube Quality Gates, OPA (Open Policy Agent)
* **Manage Vulnerabilities:** Snyk, DefectDojo

**Main Tools:** SonarQube, Trivy, OWASP, Gitleaks, Falco

---

## Core Concepts

* Shift-left security
* Shift-right security
* Defense in depth
* Least privilege
* Zero Trust
* Security gates
* Risk Management
* Threat Modeling
* Attack surface
* **CIA:** Confidentiality, Integrity, Availability