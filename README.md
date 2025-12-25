# DefSOC – Defensive Security Operations Center Lab

DefSOC is a hands-on **Defensive Security Operations Center (SOC) lab project**
focused on building, securing, and monitoring a Linux-based environment using
**Wazuh SIEM**.

This project simulates a real-world blue team setup where security events are
collected, analyzed, and visualized to detect suspicious or malicious activity.

---

## 🎯 Project Objective

The objective of DefSOC is to:
- Build a realistic SOC-style monitoring environment
- Gain hands-on experience with SIEM deployment
- Understand log collection, alerting, and threat detection
- Practice Linux server administration and access control
- Simulate attacks and observe how they are detected

---

## 🏗️ Architecture Overview

Kali Linux (Attacker / Wazuh Agent)
|
| Logs, Events, Attack Traffic
|
Ubuntu Server (DefSOC Core)

    Wazuh Manager

    Wazuh Indexer (OpenSearch)

    Wazuh Dashboard


---

## 🧭 Project Phases

### ✅ Phase 1 – Server Foundation
- Ubuntu Server installation
- VirtualBox networking (Bridged)
- SSH access configuration
- Initial system verification

### ✅ Phase 2 – Access Control & System Readiness
- Multi-user configuration
- Sudo privilege management
- Secure SSH access
- Network stability verification

## Phase 3 – Agent Enrollment & Validation

- Enrolled Ubuntu Server as a Wazuh agent using authenticated enrollment
- Established secure communication between agent and manager
- Validated agent health via CLI and Wazuh Dashboard
- Enabled SOC monitoring modules (FIM, SCA, Rootcheck, Syscollector)
- Hardened setup by disabling agent enrollment port after completion

📸 Evidence: `screenshots/phase3/`

---

## 🛠️ Tools & Technologies

- Ubuntu Server 22.04 LTS
- Kali Linux
- VirtualBox
- Wazuh SIEM
- OpenSearch
- Linux (SSH, users, permissions)
- Git & GitHub

---

## 📌 Why DefSOC?

DefSOC focuses on **practical defensive security skills**, not just theory.
It demonstrates:
- Blue team fundamentals
- SOC workflows
- System-level security understanding

This project is suitable for **learning, demonstrations, and security portfolios**.
