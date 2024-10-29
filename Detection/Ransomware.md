# Ransomware Detection

## Indicators of Ransomware
- Unusual file encryption activity on endpoints, often indicated by the addition of file extensions.
- Sudden spike in CPU or disk usage, especially on file servers.
- Alerts from antivirus or endpoint detection tools regarding potential ransomware signatures.

## Tools and Procedures
### IAM with Okta
- **User Access Monitoring**:
  1. Utilize **Okta** to track user access patterns for sensitive files and directories.
  2. Set alerts for unusual access attempts or activities during non-business hours.
  
- **Multi-Factor Authentication (MFA)**:
  1. Enforce MFA for all administrative accounts to reduce unauthorized access risks.
  2. Regularly review and update MFA methods to ensure effectiveness.

### SIEM with Splunk
- **Log Analysis**:
  1. Configure **Splunk** to ingest logs from endpoints and servers.
  2. Create a search to detect anomalies, such as mass file modifications or encryption events.
  
- **Threat Intelligence Integration**:
  1. Integrate threat intelligence feeds to correlate observed activities with known ransomware indicators.
  2. Use **Splunk** to visualize data and identify patterns that may suggest a ransomware attack.

## NIST Recommendations
- Implement continuous monitoring and logging for all critical systems to detect potential ransomware activity early.
- Regularly conduct security awareness training to ensure users recognize ransomware tactics, such as phishing emails.
