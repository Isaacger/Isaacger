# 🛡️ SOC Analyst Portfolio

Hands-on blue-team investigations, detections and automation, documented the way a SOC analyst would report them.

**Focus areas:** alert triage · incident investigation · network forensics · Windows/AD logs · malware analysis · SIEM detection (KQL / SPL) · SOAR automation

---

## 📋 Index
 **Status key:** ✅ Complete · 🟡 In progress · 🔲 Not started

| # | Area | Investigation | Tools | Status |
|---|---|---|---|---|
| 01 | Alert Triage | [SOC101 – Phishing](01-alert-triage/letsdefend-SOC101-phishing/) | LetsDefend, VirusTotal | 🔲 |
| 01 | Alert Triage | [SOC102 – Brute Force](01-alert-triage/letsdefend-SOC102-bruteforce/) | LetsDefend, AbuseIPDB | 🔲 |
| 02 | Incident Investigation | [SSH Brute-Force](02-incident-investigations/ssh-bruteforce/) | auth.log, Wazuh | 🔲 |
| 02 | Incident Investigation | [Phishing Email](02-incident-investigations/phishing-email/) | Email headers, PhishTool | 🔲 |
| 02 | Incident Investigation | [Suspicious Login](02-incident-investigations/suspicious-login/) | Entra ID, Sentinel | 🔲 |
| 03 | Network Traffic | [Wireshark DNS/HTTP PCAP](03-network-traffic-analysis/wireshark-dns-http-pcap/) | Wireshark, Zeek | 🔲 |
| 04 | Endpoint & Windows | [Windows Event Logs](04-endpoint-and-windows/windows-event-logs/) | Sysmon, Chainsaw | 🔲 |
| 04 | Endpoint & Windows | [Active Directory Auth](04-endpoint-and-windows/active-directory-auth/) | Event IDs 4624/4625/4769 | 🔲 |
| 05 | Malware Analysis | [Static Analysis – Sample 01](05-malware-analysis/static-analysis-sample-01/) | PEStudio, CAPA, YARA | 🔲 |
| 06 | SIEM Detection | [Sentinel KQL](06-siem-detection/sentinel-kql/) | Microsoft Sentinel | 🔲 |
| 06 | SIEM Detection | [Splunk SPL](06-siem-detection/splunk-spl/) | Splunk | 🔲 |
| 07 | Automation | [PowerShell Scripts](07-automation-and-scripting/powershell-scripts/) | PowerShell | 🔲 |
| 07 | Automation | [SOAR – Shuffle + Wazuh + TheHive](07-automation-and-scripting/soar-shuffle-wazuh-thehive/) | Shuffle, Wazuh, TheHive | 🔲 |

---

## 🗂️ Repository Structure

```
soc-analyst-portfolio/
├── 01-alert-triage/
├── 02-incident-investigations/
├── 03-network-traffic-analysis/
├── 04-endpoint-and-windows/
├── 05-malware-analysis/
├── 06-siem-detection/
├── 07-automation-and-scripting/
└── templates/investigation-report-template.md
```

Each investigation folder contains:
- `README.md` – the full report (summary, steps, IOCs, timeline, verdict, MITRE mapping)
- `screenshots/` – annotated evidence images
- `evidence/` – sanitized logs, query output, exported artefacts

## 🧰 Skills & Tools
SIEM: Splunk, Microsoft Sentinel, Wazuh · Network: Wireshark, Zeek · Endpoint: Sysmon, Event Viewer, Chainsaw · Malware: PEStudio, CAPA, YARA · Automation: PowerShell, Shuffle, TheHive · Frameworks: MITRE ATT&CK, Cyber Kill Chain, NIST 800-61

## ⚠️ Disclaimer
All work was performed in lab/training environments. IOCs are defanged. No live malware, real customer data or employer data is stored in this repository.

## 📫 Contact
<p>
  <a href="https://www.linkedin.com/in/isaacdearcosalcedo/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
</p>
