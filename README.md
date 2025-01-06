# Risk-Assesment-Report-Botium-Toys

# **Botium Toys: Security Audit Report**

## **Scope of Audit**

- **Assets Managed by the IT Department:**
  - On-premises equipment for in-office business operations.
  - Employee equipment: desktops, laptops, smartphones, remote workstations, peripherals (headsets, cables, keyboards, mice, docking stations), and surveillance cameras.
  - Retail products for sale, stored in the warehouse.
  - Systems, software, and services: accounting, telecommunication, database, security, e-commerce, and inventory management.
  - Internet access, internal network, data retention and storage.
  - Legacy systems maintenance (end-of-life systems requiring manual monitoring).

---

## **Goals of the Audit**

- **Primary Goal:** Assess existing assets and determine necessary controls and compliance best practices for improving Botium Toys’ security posture.
- **Action Items:** 
  - Review assets, controls, and compliance practices.
  - Complete a checklist for assessing the status of the current security program.
  - Identify gaps in asset management and compliance.

---

## **Current Asset Overview**

- On-premises equipment and end-user devices are used for business operations.
- Retail products are stored both on-site and in a warehouse.
- Key systems and services include accounting, e-commerce, and inventory management.
- There is a legacy system maintenance process in place for end-of-life systems.

---

## **Risk Assessment**

### **Risk Description**

Botium Toys is currently facing inadequate asset management and missing controls required for full compliance with U.S. and international regulations. The company may not be fully prepared to handle data security or business continuity issues.

---

### **Control Best Practices**

- **First NIST CSF Function: Identify** - Focus on identifying assets and appropriately managing them.
  - Classify and prioritize assets.
  - Determine the impact of asset loss, particularly business-critical systems.

---

### **Risk Score**: 8/10

- **Justification**: The company lacks proper controls and is not adhering to compliance best practices.

---

### **Potential Impact from Asset Loss**

- **Rating**: Medium
- **Reason**: IT department is unaware of which assets are at risk.

---

### **Risk from Regulatory Non-Compliance**

- **Rating**: High
- **Reason**: Lack of proper security controls and non-adherence to compliance regulations for data protection and privacy.

---

## **Security Findings**

1. **Access Controls**
   - All employees have access to internal data, including customer PII and cardholder data.
   - Access controls and least privilege policies have not been fully implemented.

2. **Data Encryption**
   - No encryption for sensitive customer data (e.g., credit card information) stored and transmitted internally.

3. **Intrusion Detection**
   - No intrusion detection system (IDS) has been installed.

4. **Disaster Recovery & Data Backups**
   - No disaster recovery plan or backups for critical data in place.

5. **Compliance with Privacy Policies**
   - Privacy policies for E.U. customers are in place, including breach notification within 72 hours.
   - Data handling procedures have been documented and enforced by the IT department.

6. **Password Policy**
   - Password policy exists but does not align with current best practices (e.g., complexity and length requirements).
   - No centralized password management system to enforce policy.

7. **Legacy System Maintenance**
   - While legacy systems are monitored, there is no clear schedule or intervention process for maintaining them.

8. **Physical Security**
   - Adequate physical security (locks, CCTV, fire prevention systems) is in place for the company’s storefront and warehouse.

---

## **Recommendations**

1. **Asset Management**
   - Implement a comprehensive asset management process to properly identify, classify, and manage all company assets.

2. **Encryption**
   - Implement encryption to secure sensitive data, such as credit card information and PII.

3. **Access Controls**
   - Enforce least privilege access and separation of duties to reduce risks of unauthorized access to sensitive data.

4. **Intrusion Detection System (IDS)**
   - Install an IDS to detect and respond to potential network threats.

5. **Disaster Recovery Plan**
   - Establish a disaster recovery plan, including regular backups for critical systems and data.

6. **Password Policy & Management**
   - Update the password policy to align with current best practices.
   - Implement a centralized password management system to enforce the policy and improve productivity.

7. **Regular Legacy System Maintenance**
   - Develop and implement a maintenance schedule for legacy systems to ensure they are securely monitored and updated.

8. **Compliance & Privacy**
   - Ensure full adherence to compliance regulations and data protection standards, especially concerning customer privacy.

---

## **Conclusion**

Botium Toys faces significant risks due to a lack of appropriate security controls and compliance with privacy regulations. By implementing the above recommendations, the company can reduce its security risk and improve its security posture, ensuring better protection of sensitive data and assets.
