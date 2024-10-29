# DDoS Containment

## Immediate Actions
- Activate DDoS protection mechanisms, such as traffic filtering and rate limiting, to mitigate the attack.
- Monitor affected services through **Splunk** for signs of ongoing impact.

## Advanced Containment Strategies
### IAM with Okta
- **User Session Management**:
  1. Review active sessions in the **Okta Admin Dashboard**.
  2. Temporarily suspend sessions that appear suspicious or have unusual activity patterns.

### SIEM with Splunk
- **Traffic Analysis**:
  1. Use **Splunk** to monitor incoming traffic and identify patterns typical of DDoS attacks.
  2. Set alerts for spikes in traffic from specific IP addresses or geographical locations.

- **Log Analysis for Incident Response**:
  1. Access the **Search & Reporting** app in **Splunk** to analyze logs for traffic anomalies.
  2. Create dashboards to visualize traffic patterns and identify potential threats in real-time.

## Tools and NIST Recommendations
- Implement Web Application Firewalls (WAF) to filter incoming traffic and protect against application-layer DDoS attacks.
- Regularly update incident response plans to ensure effective responses to DDoS incidents.
