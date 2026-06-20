<div align="center">

# Oussama El Gourjt

**Cybersecurity Student · DevSecOps & Security Automation**

Rabat, Morocco — [oussamaelgourjt1@gmail.com](mailto:oussamaelgourjt1@gmail.com)

</div>

<br>

I build the systems that catch problems before they ship, and I break things on purpose to find out where they'd fail in production. Most of what's here came out of one self-built lab: a CI/CD pipeline wired directly into a real SOC stack, so a failed security scan doesn't just sit in a log — it becomes an alert, gets triaged, and shows up on a dashboard.

I'm still a student. Everything below is hands-on work — labs, an internship, personal builds — not polished production software. I'd rather show real work with rough edges than a portfolio that oversells.

<br>

## What I've built

**Secure-by-Design CI/CD Pipeline with Integrated SOC Automation**
A self-hosted GitHub Actions runner with automated SAST (Semgrep) and secret scanning (Gitleaks) enforcing quality gates on every run. Failures don't just fail the build — they auto-create enriched alerts in TheHive via Cortex analyzers, and every pipeline run is visible on a live Kibana dashboard fed by Filebeat. Three-VM lab, fully wired end to end.

**Security Monitoring & Attack Simulation**
Wazuh SIEM deployed across Linux and Windows endpoints, tested against real attack chains simulated with MITRE CALDERA — built to see what actually gets detected, not just what's configured.

**Intrusion Detection — Snort**
Network-level threat detection, paired with simulated attacks to validate what the ruleset actually catches.

<br>

## Internship — IFGICT (March–April 2026)

Full OWASP-based security audit on a simulated banking application, covering the complete offensive and defensive cycle:

- Exploited Stored XSS, SQL Injection, Broken Access Control, and CSRF — each with a documented proof of concept
- Diagnosed session management and authentication flaws, then wrote remediation roadmaps: parameterized queries, RBAC models, ModSecurity rules
- Ran a full security headers audit (HSTS, CSP, X-Frame-Options) and flagged outdated dependencies with concrete fixes

<br>

## Stack

| | |
|---|---|
| **Security** | OWASP ZAP, Metasploit, Nmap, Snort |
| **SIEM / SOC** | Wazuh, ELK Stack, TheHive, Cortex, MISP, Splunk fundamentals |
| **Languages** | Python, Bash |
| **Infra** | Docker, GitHub Actions, Hypervisor (Type 1/2) |
| **OS** | Linux, Windows |

<br>

## Certifications

IBM — Cybersecurity Fundamentals · Cisco NetAcad — Introduction to Cybersecurity, Python Essentials 1 · TryHackMe — Pre-Security

<br>

<div align="center">

<sub>Always building the next lab. Open to internships, junior roles, and collaboration.</sub>

</div>