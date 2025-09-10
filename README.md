# SOC-Analyst-Lab
The SOC Analyst lab project aimed to establish a controlled environment for simulating and detecting cyber attacks.  Using the "So You Want to be a SOC Analyst?" Hands-on Lab by Eric Capuano, I was able to take a deep dive into SOC operations, attack detection, and hands-on threat hunting.  This lab provided real-world experience, from setting up attack simulations to writing detection rules that can actively block threats.  This hands-on experience was designed to deepen understanding of network security, attack patterns, and defensive strategies.

⚠️ Disclaimer: This project was conducted in a controlled lab environment for educational purposes only. 
Do not attempt to replicate outside of an isolated test environment.


### Skills Learned

- Deployed and configured LimaCharlie EDR for endpoint monitoring and telemetry collection.
- Enabled and applied Sigma detection rules to enhance threat visibility.
- Established and managed Sliver C2 sessions to simulate adversary techniques.
- Performed credential dumping detection by monitoring sensitive process access (lsass.exe).
- Built and tested custom Detection & Response (D&R) rules to detect and block attacks.
- Conducted threat hunting by analyzing process trees, network connections, and file hashes.
- Applied YARA rules for malware detection, scanning, and automation.
- Validated indicators of compromise (IOCs) with VirusTotal and cross-referenced telemetry.
- Practiced incident triage and forensic analysis using process, network, and timeline data.
-Strengthened ability to map detections to the MITRE ATT&CK framework for SOC workflows

### Tools Used

- LimaCharlie EDR for endpoint telemetry, detection, and response.
- Windows Sysmon for event and log collection.
- Sigma Ruleset for detection rule enrichment.
- Sliver C2 Framework for command-and-control attack simulation.
- Windows Defender for endpoint protection alerts.
- ProcDump for credential dumping from lsass.exe.
- VirusTotal for malware hash reputation analysis.
- YARA for custom malware detection and automated scanning.

## 📊 Results
- Successfully established and monitored a live C2 session.
- Created detection rules to identify credential dumping attempts.
- Built response rules to block destructive attacker actions.
- Implemented automated YARA scanning for proactive hunting.

## 🚀 Lessons Learned
- How attackers establish persistence and dump credentials.
- How defenders can leverage EDR telemetry to create **custom detections**.
- The power of Sigma and YARA rules in proactive defense.
- End-to-end visibility: from implant execution → telemetry → detection → response.

## Walkthrough
[![PDF](https://img.shields.io/badge/-View%20Full%20Writeup-red?style=for-the-badge&logo=adobeacrobatreader)](writeup/SYWTBAS_Lab_Writeup.pdf)

