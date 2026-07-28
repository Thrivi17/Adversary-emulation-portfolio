# Adversary Emulation & Attack Flow Modeling

A collection of structured threat intelligence artifacts, multi-stage adversary emulation workflows, and machine-readable attack flows mapped to real-world campaigns.

## 📂 Project Structure
- `/flows` - Contains machine-readable `.afb` (Attack Flow Builder) files built using STIX 2.1 standards.
- Emulation notes and technique mappings derived from structured threat intelligence frameworks.

## 🔍 Featured Artifact: MenuPass Campaign Flow
* **File:** `/flows/menupass_attack_flow.afb`
* **Objective:** Modeled a multi-stage intrusion campaign associated with the MenuPass (APT10) threat group to visualize technique sequencing, behavioral transitions, and telemetry dependencies.
* **Key Focus Areas:**
  * Mapping initial access vectors to post-compromise activity.
  * Analyzing operational progression and persistence mechanisms.
  * Translating adversary paths into detection engineering logic.

## 🛠️ Tools & Frameworks
* **Attack Flow Builder** (Center for Threat-Informed Defense)
* **STIX 2.1** Open standards for cyber threat information expression
* **MITRE ATT&CK** Framework mapping
