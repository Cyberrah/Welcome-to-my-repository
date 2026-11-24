# Portfolio reviewer guide

**Abdul Rahman Sesay — aspiring SOC Tier 1 analyst**

## Suggested review route

| Review step | Evidence | What to assess |
|---|---|---|
| 1. Understand the lab and outcome | [Kestrel project](https://github.com/Cyberrah/Log-Analysis-Pipeline-Ingesting-and-Analysing-Security-Telemetry-with-Splunk-Enterprise-and-Suricata) | Scope, telemetry and conclusions |
| 2. Examine an investigation | [SSH timeline](https://github.com/Cyberrah/Log-Analysis-Pipeline-Ingesting-and-Analysing-Security-Telemetry-with-Splunk-Enterprise-and-Suricata/blob/main/docs/ssh-investigation.md) | Timestamp normalisation, source-port matching and interpretation of encrypted traffic |
| 3. Review a detection | [Windows alert search](https://github.com/Cyberrah/Log-Analysis-Pipeline-Ingesting-and-Analysing-Security-Telemetry-with-Splunk-Enterprise-and-Suricata/blob/main/detections/windows-five-failures.spl) and [settings](https://github.com/Cyberrah/Log-Analysis-Pipeline-Ingesting-and-Analysing-Security-Telemetry-with-Splunk-Enterprise-and-Suricata/blob/main/detections/README.md) | Threshold, extraction assumptions and repeat-alert limitations |
| 4. Inspect reporting | [SOC report](https://github.com/Cyberrah/Log-Analysis-Pipeline-Ingesting-and-Analysing-Security-Telemetry-with-Splunk-Enterprise-and-Suricata/blob/main/reports/Kestrel_SOC_Investigation_Report.pdf) | Evidence, findings and coverage limits |
| 5. Review phishing triage | [MediSure analyst handoff](https://github.com/Cyberrah/Strengthening-Cyber-Resilience-through-Phishing-Email-Investigation-and-Response-in-Healthcare-#7-report-and-hand-off) | Email authentication, link and attachment findings, impact gaps and escalation |
| 6. Verify remediation | [Meridian vulnerability register](https://github.com/Cyberrah/Vulnerability-Management-Lifecycle-Scanning-Documenting-and-Remediating-with-Greenbone-OpenVAS/blob/main/reports/vulnerability-register.csv) and [final scan](https://github.com/Cyberrah/Vulnerability-Management-Lifecycle-Scanning-Documenting-and-Remediating-with-Greenbone-OpenVAS/blob/main/evidence/scans/06-post-ssb-mitigation.pdf) | Finding-level closure and remaining scanner results |

## Evidence maturity

- **Observed lab results:** Kestrel collection, Windows alert validation, controlled ICMP alerts and SSH correlation, supported by the published report and screenshots.
- **Verified remediation:** Meridian authenticated rescans support closure of four targeted findings. The repository labels the published Ansible playbooks as reconstructions.
- **Educational simulation:** Phishing sample, indicators, walkthrough and report.
- **Proposed work:** New validation cases and reproduction checklists. These are plans, not additional completed investigations.

The portfolio demonstrates home-lab and simulated investigation experience. It does not claim production SOC employment, live malware analysis or automated incident containment.

[Return to portfolio](README.md)
