# Phishing Incident Response & Analysis Lab

## Overview
This project demonstrates a real-world SOC phishing investigation workflow. A documented phishing email was analyzed to determine legitimacy, assess business risk, extract indicators of compromise, and produce a formal incident report.

The focus of this lab is analyst triage, investigation, and documentation — not phishing delivery or exploitation.

---

## Incident Scenario
A user reported a suspicious email claiming to contain a confidential termination agreement requiring immediate review via DocuSign.

The email impersonated a trusted service and used urgency to prompt immediate user interaction.

---

## Investigation Summary
The phishing email was investigated using a structured SOC methodology:

- Reviewed sender and subject metadata
- Identified brand impersonation and domain mismatch
- Assessed social engineering techniques
- Evaluated potential impact of credential compromise
- Documented findings in a formal incident report

---

## Incident Report
 **Phishing Alert – Fake DocuSign Termination Email**  
Location: `INCIDENT-REPORTS/phishing-alert-1.md`

The incident report includes:
- Email metadata analysis
- Social engineering indicators
- MITRE ATT&CK mapping
- Risk assessment and analyst verdict
- Screenshot evidence from a real phishing campaign

---

## Evidence
Screenshots supporting this investigation are stored in the `screenshots/` directory and include:

- Original phishing email source (UC Berkeley phishing archive)
- Impersonated DocuSign termination lure

---

## Skills Demonstrated
- SOC phishing alert triage
- Email threat analysis
- Social engineering detection
- Incident documentation
- Risk-based decision making
- MITRE ATT&CK alignment

---

## Disclaimer
This project analyzes a publicly documented phishing email for educational and defensive security purposes only. No malicious interaction or exploitation was performed.

