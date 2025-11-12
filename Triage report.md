# Triage Report: Failed Login Investigation

## 🕵️ Alert Summary
- **Alert Name:** Excessive Failed Logins
- **Source:** Splunk (EventCode 4625)
- **Triggered On:** 2025-11-12 09:42 IST
- **Severity:** Medium

## 📊 Investigation Details
- **Account Involved:** shreyash.malekar
- **Source IP:** 192.168.1.101
- **Failed Attempts:** 27 within 1 hour
- **Logon Type:** 3 (Network)
- **Failure Reason:** Unknown user name or bad password

## 🔍 SPL Query Used
index=windows EventCode=4625
| stats count by Account_Name, Source_Network_Address
| sort - count
