## Incident Response Plan
### 1. Purpose
The purpose of this Incident Response Plan (IRP) is to establish a structured approach for identifying, containing, eradicating, and recovering from cybersecurity incidents affecting Georgia Peach Title & Law, LLC.

### 2. Scope
This plan applies to:
- Email systems
- Wire transfer communications
- Document management systems
- Employee endpoints
- Client data repositories

### 3. Incident Classification
Incidents are categorized as:
- Low Severity – Minimal operational impact
- Medium Severity – Limited business disruption or financial exposure
- High Severity – Significant financial loss, regulatory impact, or reputational damage

### 4. Incident Response Lifecycle
The organization follows a structured lifecycle aligned with industry best practices:
1. Preparation
2. Identification
3. Containment
4. Eradication
5. Recovery
6. Lessons Learned

### 5. Roles and Responsibilities
- IT Administrator – Initial detection and technical containment
- Partners – Executive decision-making
- Operations Manager – Client communication coordination
- External IT Support – Advanced investigation (if required)
- Employees - First line of defense

## 6. Example Incident: Business Email Compromise (Wire Fraud Attempt)
Scenario:
An attacker sends a phishing email to the Closing Coordinator, requesting a wire transfer for a closing. The email appears to come from a legitimate client.

### Step 1: Identification
- Employee notices the email address doesn't match the corresponding email in the closing software system, and reports suspicious email to IT Administrator as a suspected phishing attemt
- IT reviews and detects email spoofing
- Email flagged in egress 

### Step 2: Containment
- Block sender at email gateway
- Quarantine any attached files
- Disable temporary access to impacted systems (if necessary)

### Step 3: Eradication
- Alert all employees who received the email to remove malicious email from inbox
- Reset any potentially compromised credentials
- Apply security patches or filters to prevent repeat attack

### Step 4: Recovery
- Verify legitimate wire transfer instructions with client via secure channel, over the phone or have them come into the office
- Resume normal operations
- Document incident resolution

### Step 5: Lessons Learned
- Conduct staff refresher training on phishing and BEC and remind of its importance
- Implement multi-factor authentication (MFA) for wire approvals
- Review email gateway filters and security awareness policies
- Update risk register with incident details
