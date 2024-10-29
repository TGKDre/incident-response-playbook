# Data Breach Detection

## Indicators of a Data Breach
- Unusual outbound traffic patterns indicating unauthorized data exfiltration.
- Alerts from security tools regarding access to sensitive data by unauthorized users.
- Notifications of failed login attempts followed by a sudden successful login.

## Tools and Procedures
### IAM with Okta
- **User Activity Monitoring**:
  1. Use **Okta** to generate reports on user activity, focusing on unusual access to sensitive applications and data.
  2. Set alerts for multiple failed login attempts followed by successful logins from the same user.

- **Access Control Policies**:
  1. Regularly review and adjust access controls based on user roles to minimize data exposure.
  2. Implement **Okta**’s policy framework to enforce role-based access control (RBAC).

### SIEM with Splunk
- **Data Loss Prevention (DLP)**:
  1. Integrate DLP solutions with **Splunk** to monitor for sensitive data moving outside the organization.
  2. Create alerts for any unauthorized access attempts to sensitive information.

- **Behavioral Analytics**:
  1. Utilize machine learning capabilities in **Splunk** to identify anomalies in user behavior.
  2. Configure alerts for deviations from typical access patterns, such as accessing large amounts of data in a short time.

## NIST Recommendations
- Conduct regular audits of user accounts and permissions to identify and remediate any anomalies.
- Utilize encryption to protect sensitive data both at rest and in transit to mitigate the impact of potential breaches.
