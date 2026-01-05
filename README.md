# Penetration Testing Project Repository

This repository documents a complete five-phase penetration testing workflow, implemented using an organized Git branching model. Each key phase of the assessment is isolated into its own branch to ensure clean versioning, repeatability, and professional documentation standards.

## Repository Structure

- **main** – Project overview, methodology, scope, documentation.
- **reconnaissance** – Host discovery, network mapping, and passive information gathering.
- **scanning** – Port scanning, service enumeration, network profiling.
- **vulnerability-assessment** – Vulnerability identification, analysis, and validation.
- **exploitation** – Controlled exploitation, privilege escalation, persistence checks.
- **reporting** – Final technical and executive reporting with evidence.

## Purpose

The purpose of this repository is to simulate and document a full penetration testing lifecycle while maintaining strong operational structure, clarity, and professional reporting standards.

## Usage

Switch to each phase branch to follow the documented workflow and maintain separate commits for:
- Recon activities
- Scanning results
- Vulnerability triage

# Phase Guide: Five-Stage Penetration Testing Methodology

This document provides a high-level overview of the five phases used in this project.

---

## 1. Reconnaissance
Purpose: Gather preliminary information about the target environment.

Activities:
- Lab verification
- ARP discovery
- Ping sweeps
- Passive OSINT and DNS review

---

## 2. Scanning
Purpose: Identify live hosts, services, and potential entry points.

Activities:
- Port scanning (TCP/UDP)
- Version detection
- Service enumeration
- Scripted scanning

---

## 3. Vulnerability Assessment
Purpose: Validate potential weaknesses and map them to known CVEs.

Activities:
- Manual review of services
- Vulnerability mapping and triage
- Automated scanning integration
- Risk scoring using CVSS

---

## 4. Exploitation
Purpose: Validate real-world impact of identified vulnerabilities.

Activities:
- Exploit selection and execution
- Privilege escalation
- Post-exploitation enumeration

---

## 5. Reporting
Purpose: Document results, risks, and remediation recommendations.

Artifacts:
- Executive summary
- Technical analysis
- Evidence repository
- Final PDF report

---

# Project Scope

This penetration testing project focuses on a controlled virtual lab environment.  
The assessment is strictly limited to predefined IP ranges and systems.

## In-Scope Targets

- VirtualBox Host Network: `192.168.56.0/24`
- Specific target machine(s): Defined in the reconnaissance branch.

## Out-of-Scope

- Any public network
- Systems outside the target subnet
- Denial-of-Service attacks
- Attacks impacting system stability without explicit testing justification

## Engagement Rules

- Only document and validate findings; avoid destructive exploitation.
- Maintain logs of all executed commands and observed outputs.
- Follow ethical penetration testing standards throughout engagement.



This phase guide is used 
