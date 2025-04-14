# ctec345-genex-project

# 🛡️ Genex Services – Secure Network Architecture & Cybersecurity Strategy

**Author:** Aniyah Hall  
**Course:** CTEC 345 – Foundations of Computer and Network Securit
**Instructor:** Professor Latson  
**Institution:** Bowie State University  
**Project Status:** ✅ Completed  
**Phases Covered:** 1–3  
**Date Completed:** March 2024

---

## 📌 Project Overview

This project outlines a full-scale network security and infrastructure plan for **Genex Services LLC**, a leading provider of managed care solutions in the workers' compensation industry. The project follows a structured, three-phase approach to design, implement, and evaluate layered cybersecurity protections, with a focus on resilience, HIPAA compliance, and the NIST Cybersecurity Framework.

---

## 📂 Contents

- [Phase 1: Company Analysis & Infrastructure Design](#phase-1-company-analysis--infrastructure-design)
- [Phase 2: Security Implementation & Policies](#phase-2-security-implementation--policies)
- [Phase 3: Monitoring, Risk Management & Final Evaluation](#phase-3-monitoring-risk-management--final-evaluation)

---

## 📊 Phase 1: Company Analysis & Infrastructure Design

### 🔹 Company Overview
Genex Services specializes in medical case management, telehealth, provider networks, and data analytics to reduce insurance costs and improve injured worker outcomes. It operates 38 U.S. locations with over 2,075 employees.

### 🔹 Services Provided
- Case Management  
- Utilization Review  
- Telehealth Services  
- Medical Provider Network  
- Data Analytics

### 🔹 Security by OSI Layers

| OSI Layer | Threat | Defense |
|----------|--------|---------|
| Physical | Sniffing | Endpoint security, NAC, audits |
| Data Link | Spoofing | MFA, digital signatures, DNSSEC |
| Network | MITM | VPN, HTTPS, 2FA, secure Wi-Fi |
| Transport | DoS, Recon | IDS, audits, load balancing |
| Session | Hijacking | Session timeouts, secure cookies |
| Presentation | Phishing | URL rewriting, user training |
| Application | Exploits | WAFs, secure coding, monitoring |

### 🔹 Why NIST?
NIST provides a flexible, risk-based framework that ensures Genex’s network adheres to HIPAA and GDPR regulations through continuous monitoring and improvement across five core functions: Identify, Protect, Detect, Respond, and Recover.

### 🔹 Network Infrastructure
- **Network Type:** WAN  
- **Topologies Used:**
  - Logical: Mesh, VPN, PPP
  - Physical: Star, Ethernet  
- **Benefits:** Redundancy, scalability, centralized control, secure remote access

---

## 🔐 Phase 2: Security Implementation & Policies

### 🔹 Authentication Methods
- Complex passwords (12+ characters, symbols, upper/lowercase)
- Multi-Factor Authentication (MFA)
- Biometric verification (fingerprint scanning)
- Account lockout & session timeout rules
- Secure credential storage and transmission

### 🔹 Tools Used
- **Nessus Vulnerability Scanner** for regular system scanning  
- **Penetration Testing** to expose and understand vulnerabilities

### 🔹 Access Control Strategies
- Role-Based Access Control (RBAC)
- Least Privilege enforcement
- Secure onboarding/offboarding procedures
- Periodic access reviews and activity monitoring

### 🔹 Network & Connection Security
- VPNs, TLS, and IPSec encryption
- IDS/IPS systems
- Web Application Firewalls (WAFs)
- Endpoint protection (anti-virus, EDR)

---

## 📡 Phase 3: Monitoring, Risk Management & Final Evaluation

### 🔹 Organizational Security
- Emphasis on **confidentiality**, **integrity**, and **availability (CIA Triad)**
- Regular vulnerability scanning and testing
- Business continuity and disaster recovery planning
- Employee awareness and training programs

### 🔹 Policy Implementation
- **Acceptable Use Policy (AUP)**
- **Data Classification Policy**
- **Incident Response Plan**
- **Password Policy**
- **Remote Access Policy**

### 🔹 Physical Security
- External: fencing, surveillance, lighting, keycard access
- Internal: locked areas, visitor management, emergency procedures

### 🔹 Continuity & Recovery
- Daily backups to off-site servers
- DR plan with recovery point and time objectives (RPO & RTO)
- Emergency communications and evacuation plans
- Regular DR drills and plan updates

---

## ✅ Final Summary

This project delivers a full cybersecurity and network infrastructure strategy tailored to Genex Services. Through layered defense, policy development, monitoring tools, and compliance frameworks like NIST and HIPAA, the solution ensures a scalable and secure environment for over 2,000 employees across 38 locations.

---

## 📁 File Structure Suggestion

```bash
genex-security-project/
│
├── README.md
├── phase1/
│   └── Phase 1.pdf
├── phase2/
│   └── Phase 2 documentation.docx
├── phase3/
│   └── Phase 3 final.docx (optional or combined with Phase 2)
└── assets/
    └── diagrams, images, or reports
