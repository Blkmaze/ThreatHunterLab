# ThreatHunt# 🛡️ 

A hands-on cybersecurity lab built by [blkmaze](https://github.com/blkmaze) to simulate real-world threat hunting workflows using ZincSearch, PowerShell automation, and structured queries.

---

## 🎯 Objective

This project helps SOC analysts and cybersecurity students practice:

- Ingesting and indexing logs
- Querying for threat patterns
- Automating detections
- Visualizing alerts with Grafana (optional)

---

## 🧩 Components

| Folder             | Purpose                                      |
|--------------------|----------------------------------------------|
| `logs/`            | Contains raw log files in NDJSON format      |
| `queries/`         | Saved JSON threat queries for ZincSearch     |
| `automation/`      | PowerShell scripts for scheduled threat hunts|
| `reports/`         | Optional report outputs from hunting scripts |

---

## 🔍 Threat Detection Queries

Sample saved queries in `queries/` include:

- `powershell.json`: Detects suspicious PowerShell usage
- `failed-logins.json`: Detects brute force login attempts
- `escalation.json`: Detects privilege escalation activity

---

## 🧪 Automating Threat Hunts

Run the hunt script manually:
```powershell
./automation/hunt-threats.ps1
erLab
