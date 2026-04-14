# Syed Misbah Uddin
### Security Analyst & Threat Hunter | Offensive Automation Engineer

I bridge red team tooling with enterprise defense by engineering Python-based reconnaissance pipelines, executing large-scale EASM triage, and manipulating raw network traffic to evaluate infrastructure. 

My core engineering focus lies at the intersection of **stateful execution guardrails**, **adversarial machine learning**, and **testing network egress boundaries**. I do not just run automated scans; I build the autonomous frameworks that execute them.

---

### ⚙️ Core Architecture & Tooling

#### [KESTREL](https://github.com/SyedMisbahGit/Kestrel) | *Autonomous EASM & ML Intelligence Grid*
A zero-cost, fully autonomous External Attack Surface Management framework designed to operate continuously without physical infrastructure. 
* **Autonomous Execution:** Orchestrated via GitHub Actions and SQLite Write-Ahead Logging (WAL) for state persistence.
* **Adversarial ML:** Utilizes a Shannon Entropy Engine for cryptographic secret extraction, integrated with a custom Random Forest Classifier to autonomously score findings and eliminate false positives.
* **Contextual Risk Engine:** Maps vulnerabilities to network topology, dynamically elevating threat severity based on Lateral Pivot Risk (e.g., origin IPs unmasked behind WAFs).

#### [HYBRID-IDS](https://github.com/SyedMisbahGit/HYBRID-IDS-MCP) | *Evasive Threat Detection Pipeline*
A hybrid threat detection pipeline bridging traditional signature-based matching with Machine Learning to operate in high-noise environments.
* **PCAP Telemetry:** Trained Random Forest classification models directly on complex, PCAP-derived network features.
* **Evasion Mitigation:** Engineered specifically through deep statistical analysis of ICMP and TCP anomalies to optimize precision against evasive, application-layer network threats.

#### [AndroNet](https://github.com/SyedMisbahGit/AndroNet) | *Mobile Packet Analyzer (ISEA Hackathon Runner-Up)*
A custom network telemetry tool and native Deep Packet Inspection (DPI) engine.
* **Dynamic Flow Analysis:** Utilizes the Python Scapy library to capture and parse complex, multi-layered TCP/IP sessions.
* **C2 Detection:** Features custom-programmed traffic analyzers designed to isolate and identify anomalous Command & Control (C2) beaconing patterns on mobile networks.

---

### 🔬 Research & Development (Upcoming)

#### SpecterDNS | *Steganographic DoH Exfiltration Engine*
*(Currently in Active Development)*
Architecting a covert data exfiltration channel designed to test enterprise egress boundaries. SpecterDNS encapsulates AES-encrypted payloads within standard HTTPS GET requests directed at public DNS-over-HTTPS (DoH) resolvers. By implementing a steganographic dictionary-based translation algorithm, it spoofs encrypted data chunks as legitimate API subdomains, systematically blinding standard Deep Packet Inspection (DPI) and stateless egress firewalls.

---

### 📫 Secure Comms
* **LinkedIn:** [linkedin.com/in/bytesyed](https://linkedin.com/in/bytesyed)
* **Vulnerability Research:** Active on HackerOne and enterprise VDPs.
