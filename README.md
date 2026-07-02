# SOC Homelab — Threat Detection with Wazuh (Blue Team)

Blue Team / SOC homelab: deploying Wazuh (SIEM) on Ubuntu, enrolling an agent, and investigating a simulated privilege-escalation attempt end to end — the detection workflow a SOC analyst runs daily.

**Full write-up (architecture, deployment, troubleshooting log, case study, MITRE ATT&CK mapping, screenshots):**

👉 [Read the complete Wazuh SIEM lab documentation](wazuh/README.md)

## Highlights

- Deployed a multi-component SIEM (Wazuh Manager + Indexer + Dashboard) with Docker and got it healthy.
- Diagnosed real deployment failures (package format, agent enrollment, time filters) instead of assuming the tool was broken.
- Enrolled an endpoint agent and confirmed live telemetry.
- Investigated a failed sudo / brute-force attempt, reading the alert chain and mapping it to MITRE ATT&CK (T1110, T1548.003).
- Separated actionable security events from compliance/configuration noise.

---

*Part of my IT Support / Cybersecurity portfolio.*
