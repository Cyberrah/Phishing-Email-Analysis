# Evidence assessment and investigation limits

**Case type: educational simulation.** This guide distinguishes the supplied sample from conclusions that would require additional evidence.

## Claim-to-evidence review

| Observation | Published source | Supported conclusion | Not established |
|---|---|---|---|
| Sender display name impersonates Microsoft Account Support; domain uses micr0soft spelling | [Simulated email](../email_sample/simulated_phishing_email.txt) | Brand impersonation is part of the scenario | Ownership or reputation of real infrastructure |
| Message threatens suspension and requests account verification | [Simulated email](../email_sample/simulated_phishing_email.txt) | Urgency and a credential-verification lure | A recipient clicked or disclosed credentials |
| Authentication-Results contains fail values | [Simulated email](../email_sample/simulated_phishing_email.txt) | The exercise supplies simulated authentication failures | Independently verified DNS checks or trusted gateway authentication results |
| Account_Update.zip is named in the message | [Simulated email](../email_sample/simulated_phishing_email.txt) | An unexpected attachment is described | Attachment contents, execution, malware family or a computed file hash |
| IOC CSV includes LAB-SIMULATED-HASH-NOT-A-REAL-FILE | [IOC inventory](../IOC/indicators_of_compromise.csv) | This is a placeholder | A usable SHA-256 indicator |
| Walkthrough graphics show analysis stages | [Illustrative screenshots](../screenshots/) | Visual explanation of the workflow | Live reputation results or tool execution |

## Assessment

The scenario is classified as malicious within the exercise because it combines impersonation, urgency and an account-verification lure. The assigned severity is a training judgement. No real user impact, credential theft, endpoint execution or production containment is demonstrated.

The IOC list is training data. Do not deploy its documentation domains, IP address or placeholder hash as a production blocklist. The supplied text is not a complete original message with an attached archive.

## Evidence needed for a real investigation

- Original message with complete headers and trusted mail-gateway records.
- URL redirect and destination evidence collected in an approved analysis environment.
- Original attachment bytes and a computed hash before making attachment conclusions.
- Mail delivery, click, identity and endpoint telemetry to establish exposure and impact.
- A timeline with source, timezone, confidence and evidence reference for each event.
- Recorded actions, authorisation and outcomes for any containment.

## Decision record template

| Decision | Analyst record |
|---|---|
| Case ID / analyst / UTC time | To complete for a new case |
| Source and authenticity of message | To complete |
| Observed facts and evidence references | To complete |
| Hypotheses and missing evidence | To complete |
| Recipient exposure / account or endpoint impact | Unknown until supported |
| Verdict / severity / rationale | To complete |
| Escalation owner / recommended action | To complete |
| Actions actually performed and outcome | None implied by this template |

[Project overview](../README.md) · [ATT&CK mapping](../mitre/mitre_attack_mapping.md)
