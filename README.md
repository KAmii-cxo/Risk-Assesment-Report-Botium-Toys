# Risk Assesment Report Botium Toys

# **Table of contents**
1. [Scope, Goals And Risk Assessment Report](#scope-goals-and-risk-assessment-report)
2. [Action plan to address identified gaps and improve security posture](#action-plan-to-address-botium-toys-identified-gaps-and-improve-their-security-posture)
3. [Steps to Improve Security Posture : Step 1 Tool Selection](#step-1-tool-selection)
4. [Steps to Improve Security Posture : Step 2 Policy Creation ](#step-2-policy-creation)
5. [Steps to Improve Security Posture : Step 3 Employee Training Materials](#step-3-employee-training-materials)
6. [Steps to Improve Security Posture : Step 4 Implimenting NIST CSF](#step-4-implimenting-nist-csf)
7. [Steps to Improve Security Posture : Step 5 Testing Stretegies](#step-5-testing-strategies) 

## **Scope, Goals And Risk Assessment Report**

## **Scope and Goals of the Audit**

## **Scope:**
The scope of this audit includes the entire security program at Botium Toys. This encompasses their assets like employee equipment and devices, internal network, and systems. The audit will focus on reviewing the assets Botium Toys has and the controls and compliance practices they have in place.

### **Goals:**
- **Primary Goal:** Assess existing assets and complete the controls and compliance checklist to determine which controls and compliance best practices need to be implemented to improve Botium Toys’ security posture.

---

## **Current Assets Overview**

- **Assets Managed by the IT Department:**
  - On-premises equipment for in-office business needs.
  - Employee equipment: desktops, laptops, smartphones, remote workstations, peripherals (headsets, cables, keyboards, mice, docking stations), surveillance cameras, etc.
  - Retail products available for sale, stored in the company’s adjoining warehouse.
  - Systems, software, and services for accounting, telecommunication, database, security, e-commerce, and inventory management.
  - Internet access, internal network, and data retention/storage systems.
  - Legacy systems requiring human monitoring for maintenance.

---

## **Risk Assessment**

### **Risk Description:**
Currently, there is inadequate management of assets. Additionally, Botium Toys does not have all of the proper controls in place and may not be fully compliant with U.S. and international regulations and standards.

### **Control Best Practices:**
- The first of the five functions of the [NIST CSF](https://www.nist.gov/cyberframework) is Identify. Botium Toys needs to dedicate resources to identify assets and manage them appropriately.
- They will need to classify existing assets and assess the potential impact of asset loss, particularly critical systems, on business continuity.

---

## **Additional Comments:**
- **Potential Impact from Asset Loss:** Medium
  - The IT department lacks clarity on which assets could be at risk.
  
- **Risk to Assets or Fines from Governing Bodies:** High
  - Botium Toys does not have all of the necessary controls in place and is not fully adhering to best practices related to compliance regulations for keeping critical data private and secure.

---

## **Specific Findings:**

- **Access to Data:**
  - All employees currently have access to internal data and may be able to access cardholder data and customers' PII/SPII.
  
- **Encryption:**
  - No encryption is in use for the confidentiality of customers' credit card information stored and processed in the internal database.

- **Access Controls:**
  - Least privilege and separation of duties access controls have not been implemented.

- **IT Department Controls:**
  - The IT department has ensured the availability and data integrity of systems.
  - A firewall is in place that blocks traffic based on an appropriately defined set of security rules.
  - Antivirus software is installed and regularly monitored by the IT department.
  
- **Intrusion Detection System (IDS):**
  - The IT department has not installed an IDS.

- **Disaster Recovery:**
  - No disaster recovery plans or data backups are in place for critical data.

- **Breach Notification:**
  - A breach notification plan is in place for E.U. customers, with notification within 72 hours.
  - Privacy policies, procedures, and processes have been developed and enforced for data documentation and maintenance.

- **Password Policy:**
  - The password policy exists but is not in line with current minimum complexity requirements (e.g., at least eight characters, a combination of letters, numbers, and special characters).
  - There is no centralized password management system to enforce the policy, leading to occasional productivity issues when employees/vendors need password resets.

- **Legacy System Maintenance:**
  - Legacy systems are monitored, but there is no defined schedule or intervention methods.

- **Physical Security:**
  - The physical location of the company's main office, storefront, and warehouse has sufficient locks, up-to-date CCTV surveillance, and functional fire detection and prevention systems.

---

## **Conclusion:**

Botium Toys faces considerable risks due to the lack of appropriate security controls and non-adherence to privacy regulations. By implementing the necessary controls and following the compliance best practices outlined above, Botium Toys can improve its security posture and reduce risks associated with data loss, breaches, and regulatory fines.

---

## Action Plan to Address Botium Toys' Identified Gaps and Improve Their Security Posture:

### Priority 1: Immediate Risk Mitigation (0–3 Months)

1. **Implement Role-Based Access Control (RBAC):**
   - **Steps:**
     - Audit current access privileges across systems.
     - Assign roles with specific access permissions based on job functions.
     - Apply the principle of least privilege to ensure minimum necessary access.
   - **Outcome:** Employees will only access data and systems required for their role.

2. **Encrypt Customer Data:**
   - **Steps:**
     - Implement encryption for credit card and sensitive customer data (both in transit and at rest).
     - Use encryption protocols like TLS for data transmission and AES for storage.
   - **Outcome:** Ensures confidentiality and protection of sensitive customer information.

3. **Deploy an Intrusion Detection System (IDS):**
   - **Steps:**
     - Choose an IDS solution (e.g., Snort, Suricata, or a commercial option).
     - Integrate the IDS with the internal network to monitor traffic and detect anomalies.
   - **Outcome:** Real-time detection of potential threats and network intrusions.

4. **Strengthen Password Policies and Implement Centralized Management:**
   - **Steps:**
     - Update password complexity requirements (e.g., 12+ characters, mixed case, numbers, and symbols).
     - Deploy a centralized password management system like LastPass or KeePass.
     - Train employees on the new system.
   - **Outcome:** Stronger password protection and reduced IT burden for resets.

### Priority 2: Medium-Term Enhancements (3–6 Months)

5. **Develop a Disaster Recovery Plan (DRP):**
   - **Steps:**
     - Identify critical systems and data.
     - Implement a regular backup schedule, with both onsite and offsite storage.
     - Test recovery procedures to ensure readiness during incidents.
   - **Outcome:** Quick recovery from data loss or outages, minimizing business disruption.

6. **Classify and Catalog Assets:**
   - **Steps:**
     - Inventory all assets, including hardware, software, and data.
     - Classify assets based on criticality (e.g., high, medium, low impact).
     - Use an asset management system to track and maintain asset status.
   - **Outcome:** Clear visibility into assets and their importance to business operations.

7. **Schedule Regular Maintenance for Legacy Systems:**
   - **Steps:**
     - Develop a maintenance schedule for monitoring and patching legacy systems.
     - Plan for eventual retirement or replacement of outdated systems.
   - **Outcome:** Reduced vulnerabilities from unsupported systems.

### Priority 3: Long-Term Strategic Goals (6–12 Months)

8. **Conduct Comprehensive Compliance Review:**
   - **Steps:**
     - Evaluate compliance requirements (e.g., PCI DSS, GDPR, or U.S. data protection laws).
     - Align policies and controls with regulatory standards.
     - Perform a gap analysis to identify any additional compliance issues.
   - **Outcome:** Full compliance with industry standards and regulations.

9. **Regularly Update Security Awareness Training:**
   - **Steps:**
     - Provide mandatory training on phishing, social engineering, and data handling.
     - Include updates on new policies like RBAC, encryption, and password management.
   - **Outcome:** Employees become the first line of defense against cyber threats.

10. **Expand Monitoring Capabilities:**
    - **Steps:**
      - Add Security Information and Event Management (SIEM) tools to centralize log collection and analysis.
      - Automate alerts for unusual behavior or potential threats.
    - **Outcome:** Improved visibility and proactive threat response.

## Implementation Timeline

| Action                                | Timeline      | Priority |
|---------------------------------------|---------------|----------|
| Role-Based Access Control             | 0–1 month     | High     |
| Data Encryption                       | 0–2 months    | High     |
| Intrusion Detection System (IDS)      | 1–3 months    | High     |
| Centralized Password Management       | 1–3 months    | High     |
| Disaster Recovery Plan               | 3–5 months    | Medium   |
| Asset Classification                 | 3–6 months    | Medium   |
| Legacy System Maintenance Schedule    | 4–6 months    | Medium   |
| Compliance Review                    | 6–9 months    | Low      |
| Security Awareness Training          | 6–9 months    | Low      |
| Expand Monitoring (SIEM)             | 9–12 months   | Low      |

---
# Steps to Improve Security Posture

## Step 1: Tool Selection

### 1. **Encryption Tools**
   **Goal:** Secure sensitive customer data in transit and at rest.
   - **For Data at Rest:**
     - **VeraCrypt:** Open-source encryption software for files and drives.
     - **BitLocker (Windows):** Built-in encryption for Windows systems.
     - **FileVault (macOS):** Encryption for macOS devices.
   - **For Data in Transit:**
     - **TLS Certificates:** Implement SSL/TLS using tools like Let’s Encrypt or commercial CAs.
     - **VPN:** Secure internal communications with solutions like OpenVPN or WireGuard.

### 2. **Intrusion Detection System (IDS)**
   **Goal:** Monitor network traffic for suspicious activity.
   - **Options:**
     - **Snort:** Open-source IDS with robust community support.
     - **Suricata:** Advanced IDS/IPS with high performance.
     - **Zeek:** Focused on network analysis and anomaly detection.

### 3. **Centralized Password Management Tools**
   **Goal:** Enforce strong password policies and manage credentials.
   - **Options:**
     - **LastPass Enterprise:** Cloud-based solution with policy enforcement and auditing.
     - **Dashlane Business:** Secure credential management with admin controls.
     - **KeePassXC:** Open-source, self-hosted option for secure storage.

### 4. **Asset Management Tools**
   **Goal:** Catalog and classify assets for better management and visibility.
   - **Options:**
     - **Spiceworks Inventory:** Free tool for network and asset management.
     - **Manage Engine Asset Explorer:** Comprehensive IT asset management solution.
     - **Open-AudIT:** Open-source tool for automated asset discovery.

### 5. **Backup Solutions**
   **Goal:** Ensure disaster recovery and data availability.
   - **Options:**
     - **Veeam Backup & Replication:** Enterprise-grade backup for physical, virtual, and cloud environments.
     - **Acronis Cyber Protect:** Combines backup with security features.
     - **Duplicati:** Open-source tool for encrypted backups to multiple destinations.
---

# Step 2: Policy Creation

## 1. **Role-Based Access Control (RBAC) Policy**

### **Policy Objective:**
Define access permissions based on roles to ensure employees have only the access necessary for their job.

### **Sample RBAC Policy Structure:**
**Policy Title:** Role-Based Access Control Policy

**Purpose:**  
To enforce the principle of least privilege and minimize unauthorized access to sensitive systems and data.

**Scope:**  
Applies to all employees, contractors, and third-party vendors accessing Botium Toys’ systems and data.

**Policy:**  
1. **Role Definitions:**  
   - Define roles based on department and job function (e.g., IT Admin, Sales Rep, Customer Support).
2. **Access Levels:**  
   - Assign access levels (e.g., read-only, write, execute) for each role to specific systems and data.
3. **Access Requests:**  
   - Require approval from department heads for access to higher-level systems.
4. **Periodic Reviews:**  
   - Conduct quarterly audits to review and update access permissions.
5. **Separation of Duties:**  
   - Ensure critical tasks are divided among multiple roles to prevent misuse.
6. **Revocation:**  
   - Revoke access immediately upon termination or role change.

**Non-Compliance:**  
Failure to comply with this policy may result in disciplinary action up to and including termination.

---

## 2. **Password Policy**

### **Policy Objective:**
Define standards for password creation, usage, and management to prevent unauthorized access.

### **Sample Password Policy Structure:**
**Policy Title:** Password Management Policy

**Purpose:**  
To establish minimum requirements for creating and maintaining strong passwords.

**Scope:**  
Applies to all users accessing Botium Toys’ systems and data.

**Policy:**  
1. **Complexity Requirements:**  
   - Minimum 12 characters.  
   - Must include upper/lowercase letters, numbers, and special characters.
2. **Expiration and Updates:**  
   - Change passwords every 90 days.  
   - Prohibit reuse of the last 5 passwords.
3. **Account Lockout:**  
   - Lock accounts after 5 failed login attempts.
4. **Password Storage:**  
   - Use only approved password management tools for storage.
5. **Prohibited Actions:**  
   - Sharing passwords with others.  
   - Writing passwords down in unsecured locations.

**Non-Compliance:**  
Violations will result in restricted access and potential disciplinary actions.

---

## 3. **Disaster Recovery Policy (DRP)**

### **Policy Objective:**
Define procedures for recovering critical systems and data in the event of a disaster.

### **Sample DRP Structure:**
**Policy Title:** Disaster Recovery Plan

**Purpose:**  
To ensure business continuity by recovering critical systems and data promptly after a disaster.

**Scope:**  
Applies to all critical systems and data managed by Botium Toys.

**Policy:**  
1. **Critical Systems Identification:**  
   - List critical systems (e.g., e-commerce platform, internal database).
2. **Backup Procedures:**  
   - Daily backups stored offsite and verified weekly.
3. **Recovery Time Objectives (RTO):**  
   - Define acceptable downtime for each system (e.g., 2 hours for e-commerce).
4. **Testing and Maintenance:**  
   - Conduct semi-annual DRP drills.  
   - Update the plan after each test or major system change.
5. **Incident Response Team:**  
   - Assign roles and responsibilities for disaster recovery tasks.

**Non-Compliance:**  
Failure to follow DRP procedures during an incident may result in disciplinary actions.

---

# Step 3: Employee Training Materials

## 1. **Security Awareness Training (Phishing and Social Engineering)**

### **Training Objective:**
Educate employees on identifying phishing emails, social engineering tactics, and safe online behavior.

### **Training Outline:**

#### **Understanding Phishing:**
- **Examples of phishing emails:**  
  - Fake login requests.
  - Urgent payment demands.
- **How to spot red flags:**  
  - Suspicious sender addresses.  
  - Generic greetings (e.g., “Dear User”).  
  - Grammatical errors.  
  - Unexpected links or attachments.

#### **Response to Phishing Attempts:**
- Never click suspicious links or download unexpected attachments.
- Report suspicious emails to the IT department immediately.

#### **Social Engineering Awareness:**
- **Common tactics:**  
  - Pretexting.  
  - Baiting.  
  - Impersonation.
- **Importance of verifying requests:**  
  - Call back known contacts for verification.

#### **Interactive Training:**
- Provide simulated phishing exercises.
- Test employees’ knowledge with short quizzes.

---

## 2. **Training Guides for New Tools (e.g., Password Manager)**

### **Training Objective:**
Ensure employees can efficiently use the password management system while adhering to the password policy.

### **Training Outline:**

#### **Introduction to the Tool:**
- Overview of features (e.g., password storage, autofill, secure sharing).

#### **Setup and Usage:**
- Guide to installing and setting up the tool.
- How to create and store strong passwords.
- How to generate random passwords using the tool.

#### **Best Practices:**
- Regularly review stored credentials.
- Use multifactor authentication (MFA) with the password manager.

#### **Hands-On Activity:**
- Simulate setting up an account and storing credentials.
- Practice retrieving and using stored passwords.

---

## 3. **Compliance and Data Protection Training**

### **Training Objective:**
Familiarize employees with compliance standards and the importance of protecting sensitive data.

### **Training Outline:**

#### **Compliance Overview:**
- Explain relevant regulations (e.g., GDPR, PCI DSS).
- Highlight potential penalties for non-compliance.

#### **Handling Sensitive Data:**
- Define PII/SPII and cardholder data.
- How to encrypt sensitive files.

#### **Data Access and Sharing:**
- Importance of adhering to access control policies.
- Guidelines for secure data sharing (e.g., encrypted email or secure portals).

#### **Interactive Scenarios:**
- Role-play handling customer data requests securely.
- Simulate recognizing and reporting a compliance violation.

---

# Step 4: Implementing NIST CSF

The [NIST Cybersecurity Framework (CSF)](https://www.nist.gov/cyberframework) provides a structured approach to improving cybersecurity. Below is a plan tailored to Botium Toys:

## 1. **Identify (Asset Management and Risk Assessment)**

### **Objective:** 
Create an inventory of assets and classify them by criticality.

### **Steps:**

#### **Asset Inventory:**
- Use tools like Spiceworks or Open-AudIT to document all hardware, software, and data assets.
- Classify assets based on their importance (e.g., critical, high, medium, low).

#### **Risk Assessment:**
- Evaluate risks to critical assets, such as legacy systems or unencrypted databases.
- Document potential impacts (e.g., financial loss, regulatory fines).

#### **Gap Analysis:**
- Compare current controls to NIST best practices.
- Prioritize missing controls (e.g., encryption, access controls).

---

## 2. **Protect (Implement Security Controls)**

### **Objective:** 
Safeguard assets through proper controls and training.

### **Steps:**

#### **Access Controls:**
- Enforce role-based access (RBAC) and least privilege.
- Implement MFA for all systems handling sensitive data.

#### **Encryption:**
- Use TLS for data in transit.
- Encrypt databases with tools like BitLocker or VeraCrypt.

#### **Endpoint Security:**
- Regularly update antivirus and firewalls.
- Deploy device management policies for remote workstations.

#### **Employee Awareness:**
- Conduct security training on phishing, password hygiene, and compliance.

---

## 3. **Detect (Monitoring and Alerts)**

### **Objective:** 
Identify anomalies and potential threats in real-time.

### **Steps:**

#### **Deploy IDS/IPS:**
- Use Snort or Suricata to monitor network traffic.

#### **Log Management:**
- Implement a SIEM solution like Splunk or ELK stack for centralized log analysis.

#### **Incident Reporting:**
- Define procedures for reporting and escalating suspicious activity.

---

## 4. **Respond (Incident Response Plan)**

### **Objective:** 
Minimize damage during a security incident.

### **Steps:**

#### **Incident Response Team:**
- Assign roles (e.g., incident coordinator, technical analyst).

#### **Documented Procedures:**
- Create playbooks for common scenarios (e.g., malware detection, data breaches).

#### **Communication Plan:**
- Notify customers and authorities within required timeframes (e.g., GDPR 72-hour rule).

---

## 5. **Recover (Disaster Recovery and Business Continuity)**

### **Objective:** 
Restore operations and minimize downtime after an incident.

### **Steps:**

#### **Backups:**
- Use automated backups with offsite/cloud storage.
- Test backup restorations regularly.

#### **Disaster Recovery Drills:**
- Simulate scenarios (e.g., ransomware attack) to test response readiness.

#### **Post-Incident Reviews:**
- Analyze incidents to identify gaps and improve controls.

---

# Step 5: Testing Strategies

## 1. **Disaster Recovery Testing**

### **Objective:** 
Ensure the organization can restore operations effectively after an incident.

### **Steps for Testing:**

#### **Tabletop Exercises:**
- Simulate a disaster scenario (e.g., ransomware attack).
- Walk through the disaster recovery plan with key stakeholders to identify gaps.

#### **Backup Restoration Tests:**
- Retrieve backup data and restore critical systems in a test environment.
- Verify data integrity and system functionality post-restoration.

#### **Failover Drills:**
- Simulate a server failure and test failover to backup servers.
- Measure the Recovery Time Objective (RTO) and Recovery Point Objective (RPO) compliance.

#### **Communication Tests:**
- Test the incident communication plan, including notifying employees and customers.
- Ensure the contact details and escalation paths are up to date.

---

## 2. **Compliance Testing**

### **Objective:** 
Verify adherence to industry regulations (e.g., GDPR, PCI DSS).

### **Steps for Testing:**

#### **Internal Audits:**
- Use a compliance checklist to review data handling practices, encryption, and access controls.
- Confirm that privacy notices and breach notification procedures align with legal requirements.

#### **Penetration Testing:**
- Test the security of systems handling sensitive data using tools like Metasploit or Burp Suite.
- Ensure cardholder data is encrypted and access is restricted.

#### **Third-Party Assessments:**
- Engage external auditors to evaluate compliance with standards like GDPR and PCI DSS.

#### **Policy Reviews:**
- Verify that policies (e.g., RBAC, password management) are enforced and up to date.
- Conduct employee interviews to ensure training comprehension.

---

## 3. **Security Control Testing**

### **Objective:** 
Validate the effectiveness of implemented security measures.

### **Steps for Testing:**

#### **Vulnerability Scanning:**
- Regularly scan for vulnerabilities in systems and networks using tools like Nessus or Qualys.

#### **Simulated Attacks:**
- Conduct red team exercises to test defenses against real-world attack scenarios.
- Evaluate detection and response capabilities (e.g., IDS/IPS).

#### **Access Control Testing:**
- Attempt to access restricted systems or data to ensure RBAC and least privilege policies are enforced.

#### **Patch Management:**
- Verify that critical updates are applied promptly and documented.

---

## 4. **Employee Awareness Testing**

### **Objective:** 
Assess the effectiveness of security training programs.

### **Steps for Testing:**

#### **Phishing Simulations:**
- Send fake phishing emails to employees and track response rates.
- Provide additional training for those who fall for the simulation.

#### **Quizzes and Surveys:**
- Test employees on key concepts, such as spotting phishing emails and using the password manager.

#### **Incident Reporting Drills:**
- Simulate a security incident and observe employees’ adherence to reporting procedures.

---

## 5. **Legacy System Management Testing**

### **Objective:** 
Ensure legacy systems are secure and monitored.

### **Steps for Testing:**

#### **Regular Maintenance Checks:**
- Test scheduled updates and interventions.
- Verify that monitoring tools alert for unusual activity.

#### **Compatibility Tests:**
- Ensure legacy systems integrate securely with newer systems.

#### **Decommissioning Plans:**
- Test the secure removal of data and systems nearing end-of-life.

