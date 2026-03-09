# SOC Incident Response Lab: 0x2A Security Investigation

## Project Overview
An end-to-end investigation of a multi-stage attack on the `imreallynotbatman.com` enterprise environment. This project simulates the role of a SOC Analyst identifying a brute-force attack that escalated into a web defacement and malware deployment.

## Technical Skills Demonstrated
* **Traffic Analysis:** Investigated logs to identify a high-severity brute-force attack using the "Hydra" user agent.
* **Threat Mapping:** Correlated attacker behavior to **MITRE ATT&CK** techniques (T1110.001, T1078).
* **OSINT & Forensics:** Analyzed IOCs, including Attacker IP (40.80.148.42) and malicious executable `3791.exe` hashes.
* **NIST CSF Alignment:** Developed a remediation roadmap focused on the "Respond" and "Recover" functions.

## Project Contents
* **[IR Triage Report](./Documentation/IR-Triage-Report-0x2A.pdf):** Executive-level summary of the incident and remediation.
* **[Investigation Notes](./Technical-Forensics/Technical-Investigation-Notes.pdf):** Detailed technical log of the forensic process.
