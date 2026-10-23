# Abdul Rahman Sesay
### Aspiring SOC Analyst | Security Monitoring | Log Analysis

I am building practical cybersecurity experience through home labs and simulated investigations, focusing on Splunk SIEM, Windows and Linux authentication analysis, Suricata network telemetry, phishing triage and evidence-based reporting. I am seeking a Tier 1 Security Operations Centre role.

[LinkedIn](https://www.linkedin.com/in/abdul-rahman-sesay-064ba0377) · [GitHub](https://github.com/Cyberrah)

## Reviewer guide

[Start with the portfolio reviewer guide](REVIEWER_GUIDE.md) for a short route through the strongest evidence and the status of each project.

## Featured investigation: Splunk and Suricata telemetry pipeline

A three-VM VirtualBox lab using the fictional **Kestrel Logistics Group** case study. The published investigation documents Windows and Ubuntu log collection, Suricata EVE JSON ingestion, a scheduled Windows failed-logon detection, and SSH correlation across host and network records.

- Validated a five-failures-in-ten-minutes detection using six controlled Windows logon failures.
- Verified the Suricata collection path with three controlled ICMP alerts.
- Correlated failed and accepted SSH passwords with two network connections using timestamps, IP addresses and source ports.
- Published the final SOC report, source inventory, eight evidence screenshots, SPL searches and configuration examples.

**[Explore the project](https://github.com/Cyberrah/Log-Analysis-Pipeline-Ingesting-and-Analysing-Security-Telemetry-with-Splunk-Enterprise-and-Suricata)** · **[Read the SOC report](https://github.com/Cyberrah/Log-Analysis-Pipeline-Ingesting-and-Analysing-Security-Telemetry-with-Splunk-Enterprise-and-Suricata/blob/main/reports/Kestrel_SOC_Investigation_Report.pdf)** · **[Review the SSH timeline](https://github.com/Cyberrah/Log-Analysis-Pipeline-Ingesting-and-Analysing-Security-Telemetry-with-Splunk-Enterprise-and-Suricata/blob/main/docs/ssh-investigation.md)**

These results demonstrate controlled lab validation. No malicious compromise or production incident response is claimed.

## Project portfolio

| Project | Focus | Published material and status |
|---|---|---|
| [Splunk and Suricata Telemetry Pipeline](https://github.com/Cyberrah/Log-Analysis-Pipeline-Ingesting-and-Analysing-Security-Telemetry-with-Splunk-Enterprise-and-Suricata) | Endpoint and network monitoring; cross-source authentication investigation | Completed lab report, source inventory, eight screenshots, validated alert settings and investigation searches |
| [Splunk SOC Home Lab](https://github.com/Cyberrah/Splunk-SOC-Home-Lab) | Windows event collection and reusable detection examples | Six SPL examples, forwarder configurations, dashboard XML and deployment/testing guides; each example requires its own validation |
| [Phishing Email Analysis](https://github.com/Cyberrah/Phishing-Email-Analysis) | Simulated phishing triage and response recommendations | Simulated email sample, IOC CSV, ATT&CK mapping, illustrative walkthrough images, PDF and Word reports |

The Windows-focused Splunk lab provides starter assets. The separate telemetry pipeline contains the documented three-VM investigation and its observed results.

## Skills and evidence

| Area | Published evidence |
|---|---|
| SIEM configuration and log ingestion | [Configuration examples](https://github.com/Cyberrah/Log-Analysis-Pipeline-Ingesting-and-Analysing-Security-Telemetry-with-Splunk-Enterprise-and-Suricata/tree/main/configs) and [source inventory](https://github.com/Cyberrah/Log-Analysis-Pipeline-Ingesting-and-Analysing-Security-Telemetry-with-Splunk-Enterprise-and-Suricata/blob/main/inventory/Kestrel_Log_Source_Inventory.xlsx) |
| SPL and Windows authentication detection | [Detection searches and validated alert settings](https://github.com/Cyberrah/Log-Analysis-Pipeline-Ingesting-and-Analysing-Security-Telemetry-with-Splunk-Enterprise-and-Suricata/tree/main/detections) |
| Network telemetry analysis | [Suricata ICMP validation](https://github.com/Cyberrah/Log-Analysis-Pipeline-Ingesting-and-Analysing-Security-Telemetry-with-Splunk-Enterprise-and-Suricata/blob/main/screenshots/icmp-validation.png) and [SSH correlation](https://github.com/Cyberrah/Log-Analysis-Pipeline-Ingesting-and-Analysing-Security-Telemetry-with-Splunk-Enterprise-and-Suricata/blob/main/docs/ssh-investigation.md) |
| Security dashboards | [Kestrel dashboard evidence](https://github.com/Cyberrah/Log-Analysis-Pipeline-Ingesting-and-Analysing-Security-Telemetry-with-Splunk-Enterprise-and-Suricata/blob/main/screenshots/soc-dashboard.png) and [separate Windows dashboard template](https://github.com/Cyberrah/Splunk-SOC-Home-Lab/blob/main/splunk-soc-home-lab/dashboards/windows_auth_overview.xml) |
| Phishing triage and IOC documentation | [Simulated phishing investigation](https://github.com/Cyberrah/Phishing-Email-Analysis/tree/main/Phishing_Email_Analysis_Portfolio) |
| Investigation reporting and evidence handling | [SOC report](https://github.com/Cyberrah/Log-Analysis-Pipeline-Ingesting-and-Analysing-Security-Telemetry-with-Splunk-Enterprise-and-Suricata/blob/main/reports/Kestrel_SOC_Investigation_Report.pdf) and [evidence register](https://github.com/Cyberrah/Log-Analysis-Pipeline-Ingesting-and-Analysing-Security-Telemetry-with-Splunk-Enterprise-and-Suricata/blob/main/docs/evidence-register.md) |

## Tools and technologies

Splunk Enterprise · Splunk Universal Forwarder · SPL · Suricata · EVE JSON · Windows Event Logs · Ubuntu · OpenSSH · Kali Linux · VirtualBox · MITRE ATT&CK

## Next development priorities

- Validate the remaining Windows detection examples and record expected versus observed results.
- Test alert throttling to reduce repeat notifications from overlapping search windows.
- Export the Kestrel dashboard definition for reproducible deployment.
- Document sensor visibility across additional VM traffic paths and validate time synchronisation.

## About this portfolio

These projects represent educational lab work and simulated investigations. Detection searches and configuration examples need validation and tuning in the target environment. The phishing walkthrough images are illustrative, not live threat-intelligence evidence. Findings and limitations are documented alongside each project's results.
