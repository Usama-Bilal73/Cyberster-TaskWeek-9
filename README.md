# API Security & Enterprise Risk Management (Purple Team - Week 9)

## Overview
This repository contains the documentation, simulation workflows, and defensive hardening configurations for the Week 9 training module. The assessment shifts focus toward API security vulnerabilities, business logic exploitation using the OWASP Juice Shop platform, and designing zero-trust enterprise risk management frameworks.

## Student & Assessment Details
* **Student Name:** Waleed
* **Instructor:** Muhammad Saad
* **Affiliation:** Cyberster Training Lab
* **Focus Area:** API Discovery, BOLA/IDOR Exploitation, and Defense-in-Depth Engineering

---

## Testing Strategy & Workflow
The laboratory objectives were completed via a structured adversary simulation and defensive engineering lifecycle:
1. **API Discovery & Reconnaissance:** Capturing and inspecting backend API endpoints and routing structures using browser developer tools and proxy traffic interception.
2. **BOLA/IDOR Exploitation:** Simulating Broken Object Level Authorization (BOLA) and Insecure Direct Object References (IDOR) to access or manipulate unauthorized user records and data matrices.
3. **Enterprise Risk Assessment:** Evaluating systemic architectural vulnerabilities and translating technical flaws into high-level business risk metrics.
4. **Defensive Hardening:** Designing comprehensive zero-trust mitigation strategies, endpoint access controls, and multi-tier network segregation.

---

## Core Technical Focus Areas

### 1. API Attack Surface Mapping
* Analyzing RESTful API request/response structures.
* Identifying unprotected parameter routes and hidden object identifiers exposed within client-side scripts.

### 2. Threat & Malware Case Studies
* Researching structural execution lifecycles of advanced historical threat campaigns (e.g., Stuxnet, WannaCry) to evaluate modern endpoint vulnerabilities.

### 3. Defensive Architecture & Zero-Trust
* Designing multi-tier network segmentation models utilizing VLAN boundaries.
* Simulating the positioning of Next-Generation Firewalls (NGFW) to enforce strict access control lists (ACLs) and API traffic filtering.

---

## Remediation & Mitigation Roadmap
* **Object-Level Authorization Enforcement:** Implement robust, server-side context-aware authorization checks validating that the logged-in session explicitly owns the requested resource ID.
* **API Gateway & Rate Limiting:** Position API gateways to enforce strict rate-limiting, schema validation, and centralized authentication tokens (e.g., JWT).
* **Network Segmentation:** Isolate critical application tiers and database components using secure containerized networks and Docker-based firewall layers.
