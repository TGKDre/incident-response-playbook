# DDoS Eradication

## Steps for Eradication
1. **Identify Attack Vector**:
   - Use **Splunk** to analyze incoming traffic and determine the nature of the DDoS attack (e.g., volumetric, application layer).

2. **Deploy DDoS Mitigation Services**:
   - Activate DDoS protection services (e.g., **Cloudflare**, **Akamai**) to filter malicious traffic and restore service availability.

3. **Implement Rate Limiting**:
   - Configure rate limiting on network devices to control the flow of traffic and minimize the impact of ongoing attacks.

4. **Post-Incident Review**:
   - Analyze logs in **Splunk** to understand the attack's origin and devise strategies to prevent future occurrences.

## Tools and NIST Recommendations
- **Web Application Firewall (WAF)**:
  - Utilize a WAF to block malicious traffic and protect web applications from DDoS attacks.

- Conduct regular DDoS drills to ensure preparedness and refine response strategies.
