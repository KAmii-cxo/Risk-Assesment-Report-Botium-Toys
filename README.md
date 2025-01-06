# Risk-Assesment-Report-Botium-Toys

# **Table of contents**
1. [Scope, Goals And Risk Assessment Report](#scope-goals-and-risk-assessment-report)
2. [Action plan to address Botium Toys' identified gaps and improve their security posture](#action-plan-to-address-botium-toys-identified-gaps-and-improve-their-security-posture)

# **Scope, Goals And Risk Assessment Report**

## **Scope and Goals of the Audit**

### **Scope:**
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

### **Risk Score:**
- On a scale of 1 to 10, the risk score is **8**, which is fairly high. This is due to a lack of controls and adherence to compliance best practices.

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
