# General Cybersecurity Concepts

## CIA Triad
- Confidentiality
- Integrity
- Availability

## Principle of least privilege

## Binary classification in Cybersecurity
Given a classification of a specific data set, there are four basic combinations of actual data category and assigned category: true positives TP (correct positive assignments), true negatives TN (correct negative assignments), false positives FP (incorrect positive assignments), and false negatives FN (incorrect negative assignments).

|               | **Test outcome positive**      | **Test outcome negative**      |
| ------------- | ----------------- | ----------------- |
| **Condition positive**| True Positive (TP) | False Negative (FN)|
| **Condition negative**     | False Positive (FP)| True Negative (TN) |


Example based on Threat identification, let's for IDS/IPS.
|               | **Detection Triggered**      | **Behavior Present**      |
| ------------- | ----------------- | ----------------- |
| **True Positive (TP)**    | Yes | Yes|
| **False Positive (FP)**     | Yes | No |
| **False Negative (FN)**    | No | Yes |
| **True Negative (TN)**     | No | No |


It can be analogically applied to for instance vulnerability scanning.

## OWASP TOP 10
For year 2021:
1. A01:2021 - Broken Access Control
2. A02:2021 - Cryptographic Failures
3. A03:2021 - Injection
4. A04:2021 - Insecure Design
5. A05:2021 - Security Misconfiguration
6. A06:2021 - Vulnerable and Outdated Components
7. A07:2021 - Identification and Authentication Failures
8. A08:2021 - Software and Data Integrity Failures
9. A09:2021 - Security Logging and Monitoring Failures 
10. A10:2021 - Server-Side Request Forgery 

For year 2017:
1. A01:2017 - Injection
2. A02:2017 - Broken Authentification
3. A03:2017 - Sensitive Data Exposure
4. A04:2017 - XML External Entities (XXE)
5. A05:2017 - Broken Access Control
6. A06:2017 - Security Misconfiguration
7. A07:2017 - Cross-Site Scripting (XSS)
8. A08:2017 - Insecure Deserialization
9. A09:2017 - Using Components with Known Vulnerabilities
10. A10:2017 - Insufficient Logging & Monitoring


## Most common attacks
- Phising
- Man-in-the-Middle
- DDoS
- Spoofing
- OWASP TOP 10 vulnerabilities
- Malware (Viruses, Worms, Trojans, Ransomware, Spyware, Adware, RootKit, Botnets, Keyloggers)
- RootKit