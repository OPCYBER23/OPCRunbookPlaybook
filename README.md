# Security Attack & Incident Response Simulation Runbooks

## Overview

This project contains a set of structured attack simulation runbooks and corresponding incident response playbooks developed in a controlled virtual lab environment.

The purpose of this project is to demonstrate practical understanding of both offensive security techniques and defensive incident response workflows, aligned with common enterprise security operations practices.

The simulations cover denial-of-service attacks and phishing-based credential harvesting, along with structured response procedures for detection, containment, and recovery.

---

## Project Objectives

* Simulate common cyber attack vectors in a controlled environment
* Practice structured attack execution and documentation
* Develop incident response playbooks aligned with security operations workflows
* Demonstrate defensive controls including firewall rules, MFA, and monitoring
* Improve understanding of attacker vs defender perspectives

---

## Lab Environment

All activities were performed in an isolated virtual lab environment.

**Systems used:**

* Kali Linux (attack simulation machine)
* Windows Server (target system)
* WordPress test environment
* Virtual network (host-only / private subnet)

---

## Attack Simulations Included

### 1. Denial of Service (DoS) Simulation

* ICMP flood-based traffic generation using Kali Linux tools
* Network impact monitoring using system tools and packet capture
* Firewall-based mitigation and traffic blocking
* Performance analysis before and after containment

### 2. Phishing Attack Simulation

* Credential harvesting simulation using cloned login page techniques
* Social engineering attack workflow using SET toolkit
* Credential capture and analysis
* Multi-factor authentication (MFA) implementation and testing

---

## Defensive Controls Demonstrated

* Windows Defender Firewall rule configuration
* IP-based traffic blocking
* Network traffic monitoring and analysis
* Multi-Factor Authentication (MFA) using authenticator applications
* User session management and password reset procedures
* Security awareness and detection techniques

---

## Incident Response Coverage

Each attack simulation is paired with a structured response playbook covering:

* Preparation and baseline monitoring
* Detection and analysis of attack activity
* Containment and eradication strategies
* System recovery procedures
* Post-incident review and lessons learned

---

## Key Skills Demonstrated

* Network traffic analysis
* Basic penetration testing methodology
* Security operations workflow understanding
* Incident response documentation
* Defensive configuration of host-based security controls
* Phishing awareness and credential protection concepts

---

## Disclaimer

All activities documented in this repository were performed in a controlled, isolated lab environment using intentionally configured test systems. No real-world systems, networks, or users were targeted.

---

## Author

Cyber Security Student (Certificate IV – TAFE)
