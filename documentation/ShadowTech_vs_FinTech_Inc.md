# Campaign Documentation: ShadowTech Group vs. FinTech Inc.

## Overview
This document provides a technical breakdown and structured mapping of the campaign executed by the **ShadowTech Group** against **FinTech Inc**. It outlines the adversary's attack flow, initial access vectors, execution methods, and persistence mechanisms based on standardized threat intelligence frameworks.

---

## Campaign Metadata
* **Campaign Name:** ShadowTech Groups Campaign Against FinTech Inc
* **Target Organization:** FinTech Inc
* **Threat Actor:** ShadowTech Group
* **Author:** Thrivikraman Madhavan
* **Creation Date:** July 28, 2026
* **Primary Objective:** Data exfiltration, with potential for disruptive activities such as data encryption for impact

## Attack Flow & Techniques (MITRE ATT&CK Mapping)

* **Phishing (T1566 / TA0001):** The campaign initiated via spear phishing targeting employees at FinTech Inc.
* **Drive-by Compromise (T1189 / TA0001):** An alternative initial access vector exploiting browser-based vulnerabilities.
* **PowerShell (T1059.001 / TA0002):** Utilized for command-line execution and internal script handling once access was established.
* **Scripting (T0853 / TA0104):** Deployed as an alternative execution method in environments where standard command shells are restricted.
* **Scheduled Task/Job (T1053):** Implemented to ensure persistence across system reboots and operational cycles.
* **Exploitation for Privilege Escalation (T1068 / TA0004):** Performed to escalate system-level privileges leveraging known local vulnerabilities.
* **Rootkit (T1014 / TA0005):** Utilized to maintain stealth, hide malicious artifacts, and evade endpoint detection mechanisms.
