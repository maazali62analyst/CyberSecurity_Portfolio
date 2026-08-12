# Cyber Security Portfolio

Welcome to my Cyber Security Portfolio. This repository documents my
hands-on journey toward becoming a SOC Analyst through practical labs,
detections, and incident investigations.

## Featured Project: SOC Home Lab (In Progress)

A self-built home lab simulating a small enterprise environment, used to
practice detection engineering, log analysis, and incident response.

### Architecture
- **Victim Endpoint:** Windows 10 VM with Sysmon (SwiftOnSecurity config)
  for detailed process, network, and registry logging
- **SIEM:** ELK Stack (Elasticsearch + Kibana) for log ingestion,
  dashboards, and detection
- **Attack Simulation:** Atomic Red Team, mapped to MITRE ATT&CK techniques
- **Network:** Isolated internal network (VirtualBox), no exposure to
  host/internet

### What I Did
- Deployed and configured a Windows endpoint with detailed telemetry via
  Sysmon
- Shipped logs to ELK using Winlogbeat
- Built Kibana dashboards for process, logon, and network activity
  monitoring
- Simulated real attack techniques (MITRE ATT&CK mapped) using Atomic
  Red Team
- Detected each simulated attack and wrote up full incident reports
  (see `/incident-reports`)

### Skills Demonstrated
SIEM configuration · Log analysis · Detection engineering · Sysmon ·
MITRE ATT&CK · Incident triage & reporting · Windows fundamentals

### Incident Reports
See `/incident-reports` for detailed write-ups of each simulated attack,
including detection method, IOC, MITRE technique, and remediation steps.

### Screenshots
See `/screenshots` for Kibana dashboards and alert examples.

## Goals
- Build practical, demonstrable cybersecurity skills
- Document projects the way a real analyst documents investigations
- Continue expanding this portfolio with future projects

---
*This lab was built independently as part of hands-on SOC Analyst
preparation.*
