# Ransomware Eradication

## Steps for Eradication
1. **Complete System Backup**:
   - Ensure that all unaffected systems are backed up before proceeding with eradication.

2. **Malware Removal**:
   - Use endpoint protection tools (e.g., **CrowdStrike**, **Malwarebytes**) to scan and remove ransomware from infected systems.
   - Follow the vendor's guidelines for malware removal to ensure complete eradication.

3. **Reimage Infected Systems**:
   - If ransomware cannot be completely removed, reimage the infected systems using clean backups.
   - Ensure that systems are updated with the latest patches before rejoining the network.

4. **Monitor for Residual Activity**:
   - Use **Splunk** to monitor network and endpoint activity for signs of re-infection or lateral movement by the malware.

## Tools and NIST Recommendations
- **Endpoint Detection and Response (EDR)**:
  - Deploy EDR tools to continuously monitor and respond to threats, ensuring all malicious artifacts are removed.

- Conduct a post-incident review to analyze the response effectiveness and improve future ransomware prevention strategies.
