# Phishing Email Analysis & Incident Response Lab

A simulated SOC investigation covering email triage, authentication review, IOC documentation, ATT&CK mapping, and response recommendations.

**Project type:** Educational simulation. The walkthrough images are illustrative; their reputation counts and details are examples, not live threat-intelligence findings.

## Investigation overview

The scenario involves a message impersonating Microsoft Account Support, an urgent account-verification request, and an unexpected ZIP attachment. The investigation documents impersonation, simulated authentication failures, the credential lure, and recommended containment steps.

**Lab verdict:** Malicious (simulated), with high severity assigned within the exercise. This is not a production incident assessment.

## Explore the evidence

- [Full investigation overview](Phishing_Email_Analysis_Portfolio/README.md)
- [Simulated email sample](Phishing_Email_Analysis_Portfolio/email_sample/simulated_phishing_email.txt)
- [Indicators of compromise](Phishing_Email_Analysis_Portfolio/IOC/indicators_of_compromise.csv)
- [MITRE ATT&CK mapping](Phishing_Email_Analysis_Portfolio/mitre/mitre_attack_mapping.md)
- [SOC report — PDF](Phishing_Email_Analysis_Portfolio/report/SOC_Phishing_Investigation_Report.pdf)
- [Editable report — Word](Phishing_Email_Analysis_Portfolio/report/SOC_Phishing_Investigation_Report.docx)
- [Illustrative walkthrough images](Phishing_Email_Analysis_Portfolio/screenshots)

## Evidence quality

[Read the evidence assessment](Phishing_Email_Analysis_Portfolio/docs/evidence-assessment.md) for a claim-to-source table, limits of the simulated headers and attachment, and evidence needed to establish real-world impact. The IOC hash placeholder is not an actionable file hash.

## Workflow

1. Triage the reported email and identify social-engineering cues.
2. Review headers, sender alignment, and simulated SPF/DKIM/DMARC results.
3. Examine the URL and attachment indicators within the exercise.
4. Record IOCs and map supported behaviours to ATT&CK.
5. Document the verdict, limitations, and response recommendations.

## Skills demonstrated

Phishing triage · email authentication analysis · IOC documentation · ATT&CK mapping · incident reporting

[Return to cybersecurity portfolio](https://github.com/Cyberrah/Welcome-to-my-repository)
