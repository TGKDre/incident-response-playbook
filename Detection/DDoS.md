# DDoS Detection

## Indicators of DDoS Attacks
- Sudden spikes in network traffic from a single or multiple IP addresses.
- Slow response times from web applications and services due to overwhelming traffic.
- Unavailability of services or applications that are usually accessible.

## Tools and Procedures
### IAM with Okta
- **User Access Monitoring**:
  1. Monitor for any unauthorized access attempts to critical systems during DDoS events.
  2. Review user access patterns to identify potential insider threats during high traffic periods.

### SIEM with Splunk
- **Traffic Analysis**:
  1. Configure **Splunk** to collect and analyze network traffic data in real-time.
  2. Create alerts for unusual traffic patterns that exceed normal thresholds.
  
- **Anomaly Detection**:
  1. Utilize **Splunk’s Machine Learning Toolkit** to build models that recognize baseline traffic patterns.
  2. Trigger alerts when current traffic deviates significantly from established norms.

## NIST Recommendations
- Implement traffic shaping and rate limiting on network devices to mitigate the impact of DDoS attacks.
- Regularly review and update incident response plans to ensure a quick and effective response to DDoS threats.
