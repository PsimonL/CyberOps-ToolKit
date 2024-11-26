# General Cybersecurity Concepts

## CIA Triad
- Confidentiality - preserving authorized restrictions on information access and disclosure, including means for protecting personal privacy and proprietary information.
- Integrity - guarding against improper information modification or destruction and ensuring information non-repudiation and authenticity.
- Availability - ensuring timely and reliable access to and use of information.

https://www.nccoe.nist.gov/publication/1800-26/VolA/index.html

## Principle of least privilege (PLP)
Concept which states that user or entity should only have enough priviliges to access specific data, resources
and apps to execute given task. 
It significantly reduces attack surface and risk of malware spread. 

https://www.paloaltonetworks.com/cyberpedia/what-is-the-principle-of-least-privilege
https://en.wikipedia.org/wiki/Principle_of_least_privilege

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


It can be analogically applied for instance to vulnerability scanning.

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

https://owasp.org/www-project-top-ten/

## Most common attacks
- Phising
- Man-in-the-Middle
- DDoS
- Spoofing
- OWASP TOP 10 vulnerabilities
- Malware (Viruses, Worms, Trojans, Ransomware, Spyware, Adware, RootKit, Botnets, Keyloggers)
- RootKit

## Types of Penetration Testing methodologies:
- Network Pen Testing 
- Web Application Pen Testing
- Physical Pen Testing
- Wireless Pen Testing
- Mobile Pen Testing
- Social Engineering Pen Testing

![HTB_Pen_Testings](/xyz_resources_n_images/HackTheBoxPentests.jpg)
https://www.hackthebox.com/blog/an-aspiring-hackers-web-application-penetration-testing-guide-for-2024