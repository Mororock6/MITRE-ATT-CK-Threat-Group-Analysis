# MITRE-ATT-CK-Threat-Group-Analysis
## Overview

This repository contains a defensive-focused analysis of real-world threat actors using the MITRE ATT&CK framework. The project compares two high-impact adversary groups with very different motivations and tradecraft:

* **Scattered Spider (G1015)** – financially motivated, ransomware-driven, heavy social engineering
* **APT29 (G0016)** – state-sponsored espionage, stealthy, long-term persistence

The goal of this project is to demonstrate practical blue team understanding by mapping adversary behavior to techniques, tooling, and mitigations.

---

## Why This Project

This repo was created to:

* Apply MITRE ATT&CK in a real-world context
* Practice threat actor profiling and comparative analysis
* Highlight defensive controls and mitigations
* Showcase blue team–oriented security research

This project is intended for SOC analysts, blue teamers, and security students.

---
## Key Topics Covered

### Scattered Spider (G1015)

* Social engineering & identity compromise
* MFA fatigue & help-desk impersonation
* Use of **BlackCat (ALPHV)** ransomware
* Abuse of **T1047 – Windows Management Instrumentation (WMI)**

### APT29 (G0016)

* State-sponsored cyber espionage
* Long-term stealth operations
* **SUNBURST / SolarWinds** supply chain attack
* **T1195.002 – Compromise Software Supply Chain**

---

## Defensive Focus

Each technique includes:

* Description of attacker behavior
* Why the technique is effective
* Detection considerations
* MITRE-aligned mitigations
* Blue team visibility gaps

---

## Skills Demonstrated

* MITRE ATT&CK mapping
* Threat intelligence analysis
* Blue team mindset & defensive strategy
* Technical writing & documentation

---

## Disclaimer

This project is for educational and defensive research purposes only.
