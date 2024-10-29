# Phishing Containment

## Immediate Actions
- Identify and block malicious emails that have been reported by users.
- Inform users not to click on links or provide personal information in response to suspicious emails.

## Advanced Containment Strategies
### IAM with Okta
- **User Account Management**:
  1. Access the **Okta Admin Dashboard**.
  2. Review user accounts for signs of compromise (e.g., unusual login locations).
  3. Temporarily suspend accounts suspected of being affected by phishing.

- **Password Reset**:
  1. Initiate password resets for affected accounts.
  2. Ensure that multi-factor authentication (MFA) is enforced for all users to enhance security.

### SIEM with Splunk
- **Log Analysis**:
  1. Use **Splunk** to analyze logs for any unauthorized access or suspicious activity stemming from phishing attempts.
  2. Create alerts for any logins from unusual locations or devices.

- **Phishing Simulation Data**:
  1. Monitor results from phishing simulation exercises if conducted.
  2. Use **Splunk** to analyze user engagement with simulated phishing attacks and track the effectiveness of training.

## Tools and NIST Recommendations
- **Email Filtering Solutions**:
  1. Implement solutions like **Proofpoint** or **Mimecast** to filter out malicious emails.
  2. Regularly update filtering rules based on emerging phishing trends.

- Regularly conduct security awareness training to educate employees about recognizing phishing attempts and reporting them.
