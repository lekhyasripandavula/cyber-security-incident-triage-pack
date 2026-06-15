# Cyber Security Incident Triage Pack - Healthcare Phishing Scenario

## 1. Mock Incident Report Log

 Field - Details 
 Incident ID - INC-001 
 Date/Time Reported - 15 June 2026, 09:10 
 Reported By - Service Desk Analyst 
 Incident Type - Phishing / Credential Compromise 
 Affected User/Team - Finance Department 
 Description | A staff member clicked a phishing email posing as a Microsoft 365 password reset and entered login credentials. Suspicious login attempts were then observed from an overseas IP address.
 Initial Impact - Possible compromised staff account and risk of unauthorised access to email and internal systems.
 Severity - High 
 Status - Under Investigation 
 Actions Taken - Password reset requested, sessions revoked, MFA checked, incident logged, analyst informed.
 Escalated To - Security Analyst / Incident Manager 

## 2. Triage and Escalation Note

This incident involves a suspected phishing attack against a staff member in the Finance Department. The user received an email that appeared to be a Microsoft 365 password reset request. After clicking the link, the user entered their login credentials. Shortly afterwards, suspicious login attempts were identified from an overseas IP address, suggesting the account may have been compromised.

This incident should be treated as high priority because compromised credentials can allow unauthorised access to email, internal documents, and other connected systems. In a healthcare environment, this creates risk to sensitive information, operational continuity, and public trust.

The first response step would be to confirm the facts with the reporting user and log the incident clearly. The second step would be to secure the account by forcing a password reset and revoking active sessions. The third step would be to review available logs for unusual sign-in activity, mailbox rule changes, failed logins, and any evidence of further suspicious behaviour. The fourth step would be to escalate the matter to a security analyst or incident manager if the activity suggests broader compromise or ongoing malicious access. The fifth step would be to document all actions taken and provide clear updates to relevant internal stakeholders.

This case shows the importance of timely triage, escalation, and accurate incident records. Even a single compromised account can create wider risks if not handled quickly and carefully.

## 3. Common Cyber Threats Facing NHS Organisations

### Phishing and Credential Theft

Phishing is when attackers send fake emails or messages designed to trick users into clicking malicious links or giving away usernames and passwords. Healthcare organisations are often targeted because staff are busy, work across many systems, and handle sensitive information. If credentials are stolen, attackers may gain access to email, records, or internal systems. One basic defence is staff awareness training combined with multi-factor authentication.

### Ransomware

Ransomware is malicious software that can lock files or systems until a payment is made. This is especially serious in healthcare because it can disrupt appointments, records access, communications, and patient care. Even short outages can cause major operational problems. One important defence is keeping systems patched and maintaining secure offline backups.

### Third-Party or Supply Chain Compromise

A third-party or supply chain compromise happens when attackers gain access through an external supplier, contractor, or software provider. Healthcare organisations rely on many shared services and digital suppliers, so weaknesses in one organisation can affect others. This can lead to data exposure, service disruption, or wider network risk. One basic defence is carrying out supplier security checks and limiting unnecessary access.

## Conclusion

This project shows a basic understanding of cyber incident logging, triage, escalation, and common threats affecting healthcare organisations. It also demonstrates the importance of clear communication, accurate documentation, and early response during suspected cyber incidents.
