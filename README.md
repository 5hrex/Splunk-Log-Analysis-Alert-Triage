# Splunk Log Analysis & Alert Triage Project

## 🛡️ Overview
This project simulates a SOC analyst workflow using Splunk to ingest Windows security logs, detect suspicious login behavior, and triage alerts. It demonstrates core SIEM skills including SPL query writing, dashboard analysis, and incident documentation.

## 🧰 Tools & Technologies
- Splunk Enterprise (Free Trial or Cloud)
- Windows Event Logs (EventCodes 4624, 4625)
- SPL (Search Processing Language)

## 🔍 Key Activities
- Ingested Windows security logs into Splunk
- Used SPL to detect:
  - Failed login attempts (EventCode 4625)
  - Successful logins (EventCode 4624)
  - Brute-force login patterns
  - Unusual processes and DNS anomalies
- Created dashboards for login trends and alert triage
- Documented investigation steps and flagged suspicious activity
