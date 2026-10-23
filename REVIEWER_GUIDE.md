# Portfolio reviewer guide

**Abdul Rahman Sesay — aspiring SOC Tier 1 analyst**

## Suggested review route

| Review step | Evidence | What to assess |
|---|---|---|
| 1. Understand the lab and outcome | [Kestrel project](https://github.com/Cyberrah/Log-Analysis-Pipeline-Ingesting-and-Analysing-Security-Telemetry-with-Splunk-Enterprise-and-Suricata) | Scope, telemetry and conclusions |
| 2. Examine an investigation | [SSH timeline](https://github.com/Cyberrah/Log-Analysis-Pipeline-Ingesting-and-Analysing-Security-Telemetry-with-Splunk-Enterprise-and-Suricata/blob/main/docs/ssh-investigation.md) | Timestamp normalisation, source-port matching and interpretation of encrypted traffic |
| 3. Review a detection | [Windows alert search](https://github.com/Cyberrah/Log-Analysis-Pipeline-Ingesting-and-Analysing-Security-Telemetry-with-Splunk-Enterprise-and-Suricata/blob/main/detections/windows-five-failures.spl) and [settings](https://github.com/Cyberrah/Log-Analysis-Pipeline-Ingesting-and-Analysing-Security-Telemetry-with-Splunk-Enterprise-and-Suricata/blob/main/detections/README.md) | Threshold, extraction assumptions and repeat-alert limitations |
| 4. Inspect reporting | [SOC report](https://github.com/Cyberrah/Log-Analysis-Pipeline-Ingesting-and-Analysing-Security-Telemetry-with-Splunk-Enterprise-and-Suricata/blob/main/reports/Kestrel_SOC_Investigation_Report.pdf) | Evidence, findings and coverage limits |
| 5. Review validation planning | [Six-detection test matrix](https://github.com/Cyberrah/Splunk-SOC-Home-Lab/blob/main/splunk-soc-home-lab/docs/detection-validation-matrix.md) | Positive/negative cases, boundaries and test provenance |
| 6. Review phishing judgement | [Phishing evidence assessment](https://github.com/Cyberrah/Phishing-Email-Analysis/blob/main/Phishing_Email_Analysis_Portfolio/docs/evidence-assessment.md) | Facts versus hypotheses and investigation gaps |

## Evidence maturity

- **Observed lab results:** Kestrel collection, Windows alert validation, controlled ICMP alerts and SSH correlation, supported by the published report and screenshots.
- **Reusable examples:** The separate Windows lab's six SPL searches and dashboard template; complete per-search execution records are still pending.
- **Educational simulation:** Phishing sample, indicators, walkthrough and report.
- **Proposed work:** New validation cases and reproduction checklists. These are plans, not additional completed investigations.

The portfolio demonstrates home-lab and simulated investigation experience. It does not claim production SOC employment, live malware analysis or automated incident containment.

[Return to portfolio](README.md)
