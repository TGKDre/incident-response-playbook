# Ransomware Containment

## Immediate Actions
- Disconnect affected systems from the network to prevent further spread of the ransomware.
- Identify and isolate infected endpoints through **Okta** to restrict access to sensitive data.

## Advanced Containment Strategies
### IAM with Okta
- **User Account Management**:
  1. Log into the **Okta Admin Dashboard**.
  2. Navigate to **Directory > Users**.
  3. Temporarily suspend the accounts of affected users to prevent further access.
  
- **Access Control**:
  1. Review and modify access policies for sensitive resources.
  2. Restrict access to critical systems until the incident is fully investigated.

### SIEM with Splunk
- **Traffic Monitoring**:
  1. Use **Splunk** to analyze network traffic and identify communication with known malicious IPs.
  2. Set up alerts for unusual outgoing connections from infected systems.

- **Log Analysis**:
  1. Access the **Search & Reporting** app in **Splunk**.
  2. Create queries to review logs for file changes or deletions that may indicate ransomware activity.

## Tools and NIST Recommendations
- **Endpoint Detection and Response (EDR)**:
  1. Deploy solutions like **CrowdStrike Falcon** to monitor endpoint activity.
  2. Use the console to isolate infected endpoints and remediate threats.

- Implement incident response protocols to contain ransomware incidents and prevent data loss.
