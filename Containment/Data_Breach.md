# Data Breach Containment

## Immediate Actions
- Identify and isolate compromised systems to prevent further data loss.
- Reset passwords for affected accounts through **Okta** to secure access.

## Advanced Containment Strategies
### IAM with Okta
- **User Account Suspension**:
  1. Access the **Okta Admin Dashboard**.
  2. Navigate to **Directory > Users** and suspend any accounts showing signs of compromise.
  
- **Access Control Review**:
  1. Review access logs to identify any unauthorized access attempts.
  2. Modify policies to restrict access to sensitive information until the breach is contained.

### SIEM with Splunk
- **Anomaly Detection**:
  1. Use **Splunk** to analyze user behavior and identify anomalies indicating unauthorized access.
  2. Set alerts for any abnormal patterns of access to sensitive data.

- **Threat Intelligence Correlation**:
  1. Integrate threat intelligence feeds to identify known compromised accounts.
  2. Cross-reference user activity logs with threat data in **Splunk**.

## Tools and NIST Recommendations
- Utilize **Splunk** for continuous monitoring and real-time alerts on data access.
- Regularly conduct security audits to ensure proper access controls are in place and effective.
