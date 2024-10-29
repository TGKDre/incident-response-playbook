# Phishing Detection

## Indicators of Phishing
- Suspicious sender email addresses or domains that do not match expected patterns.
- Requests for sensitive information accompanied by urgency or fear tactics.
- Links that reveal URLs inconsistent with legitimate sources when hovered over.

## Tools and Procedures
### IAM with Okta
- **Multi-Factor Authentication (MFA)**: 
  1. Enable MFA in the **Okta Admin Dashboard** under **Security > Multifactor**.
  2. Configure required factors (e.g., SMS, authenticator app).
  3. Enforce MFA for all users, especially during login attempts from new devices or locations.
  
- **User Activity Monitoring**:
  1. Access the **Reports** section in the **Okta Admin Dashboard**.
  2. Generate a report for **User Logins** to identify unusual login patterns.
  3. Set up alerts for login attempts from suspicious IP addresses.

### SIEM with Splunk
- **Email Logging**:
  1. Configure email servers to forward logs to **Splunk** using the **Universal Forwarder**.
  2. In **Splunk**, create a data input to ingest email logs.
  3. Build a dashboard to visualize email traffic and flag anomalies.

- **Alerts and Dashboards**:
  1. Use the **Search & Reporting** app in **Splunk** to create searches for phishing indicators.
  2. Save the search as an alert to notify the security team when specific thresholds are met (e.g., multiple failed logins).

## NIST Recommendations
- Implement centralized logging in **Splunk** to track user activities related to email access and set up alerts for potential phishing attempts.
- Conduct regular **Security Awareness Training** for users to help them recognize and respond to phishing threats.
