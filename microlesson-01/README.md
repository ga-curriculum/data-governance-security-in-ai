<h1>
  <span class="headline">[ Data Security, Privacy, and Bias Considerations in AI]</span>
  <span class="subhead">tktk Microlesson 01</span>
</h1>

**Learning objective:** By the end of this lesson, students will be able to tktk
#  Data Security, Privacy, and Bias Considerations in AI

**Components of the Data Governance Framework**

| **Organizational Bodies and Policies** | **Standards and Processes**                            | **Data Governance Technology**           |
|----------------------------------------|-------------------------------------------------------|------------------------------------------|
| Governance Structure                   | Data Definition and Standard (Metadata Management)    | Metadata Repository                      |
| Data Custodianship                     | Third-Party Data Extract                              | Data Profiling Tool                      |
| User Group Charter                     | Metrics Development and Monitoring                   | Data Cleansing Tool                      |
| Decision Rights                        | Data Profiling                                        |                                          |
| Issue Escalation Process               | Data Cleansing                                        |                                          |
[ Components of the Data Governance Framework Source ](https://www.researchgate.net/publication/228966685_The_need_for_data_governance_A_case_study)

## **1. AI Data Security**

Throughout the AI lifecycle, data security aims to shield data from misuse, breaches, and illegal access.

### **Crucial Elements:**
1. **Protecting Training Data for AI:**
   - **Encryption:** To protect sensitive data, encrypt data while it's in transit and at rest.  
   - **Access Control:** Give datasets and AI systems multi-factor authentication (MFA) and role-based access control (RBAC).  

2. **Safeguarding AI Models:**
   - **Adversarial Defence:** Protect models against attacks such as model inversion, data poisoning, and evasion.  

3. **Authentication and Data Integrity:**
   - **Verify Integrity:** Verify the integrity of the data sources.  
   - **Provenance Tracking:** Track the provenance of data using blockchain.  

4. **Incident Response and Monitoring:**
   - **Monitoring:** Keep an eye out for odd activities in AI pipelines.  
   - **Incident Plan:** Create a strong incident response plan for security risks unique to AI.

 **AI Enhancements in Data Privacy and Security**

| **Aspect**           | **Description**                                                                 | **Example Use Cases**                                        |
|-----------------------|---------------------------------------------------------------------------------|-------------------------------------------------------------|
| **Data Anonymization** | AI algorithms help in anonymizing data by removing personally identifiable information. | Creating datasets for research without compromising individual privacy. |
| **Intrusion Detection** | AI systems can learn to detect unusual patterns indicating a breach.            | Monitoring network traffic to alert for potential threats.   |
| **Encryption**         | AI can improve encryption methods and manage encryption keys more efficiently. | Securely encrypting data for safe communication.            |
| **Fraud Detection**    | AI is used to identify and predict fraudulent activity by analyzing patterns.   | Detecting unusual transactions in banking or credit card use. |
| **Access Control**     | AI enhances security by determining who should have access to what data.        | Biometric systems that use facial recognition or fingerprints for secure access. |
| **Risk Assessment**    | AI evaluates the potential risks associated with data breaches or security threats. | Assessing and prioritizing risks in cyber security management. |

[AI Enhancements in Data Privacy and Security Source 2](https://www.researchgate.net/publication/378288596_AI_in_Data_Privacy_and_Security)

## **2. AI Data Privacy**

AI privacy considerations include safeguarding user data and making sure privacy laws like the CCPA, GDPR, and HIPAA are followed.

### **Important Procedures:**
1. **Data Anonymisation and Masking:**
   - To stop people from being re-identified, remove or obfuscate identifiable information from datasets.  

2. **Differential Privacy:**
   - To guarantee that individual data points cannot be reverse-engineered, add controlled noise to datasets.  

3. **Federated Learning:**
   - Develop AI models on dispersed datasets without moving private information to a central location.  

4. **Limitation of Purpose:**
   - Only gather and handle the information needed for a particular AI application.  
   - Verify adherence to the principles of data minimisation.  

5. **Management of Consent:**
   - Get the user's express consent before using their data.  
   - Offer unambiguous opt-in and opt-out procedures.  

---

## **3. AI's Bias Considerations**

AI bias must be identified and mitigated since it can produce unfair or biased results.

### **Sources of Prejudice:**
1. **Data Bias:**
   - Model predictions are skewed when datasets are skewed or under-represented.  

2. **Algorithmic Bias:**
   - Data biases may be amplified by model design or training procedures.  

3. **Human Bias:**
   - Prejudices or presumptions made when developing models or datasets.  

### **Strategies for Mitigation:**
1. **Diverse and Representative Datasets:**
   - Make sure the datasets cover a range of circumstances, contexts, and demographic groups.  

2. **Bias Auditing and Testing:**
   - Check AI models for equity among various groups on a regular basis.  
   - For bias detection, use tools such as Google's What-If Tool or IBM's AI Fairness 360.  

3. **Algorithm Design:**
   - Use algorithms that consider fairness and balance results for all groups.  
   - To lessen bias, use strategies like re-weighting or re-sampling.  

4. **Explainability and Transparency:**
   - To comprehend decision-making procedures, apply interpretable models or frameworks.  
   - Clearly record the model assumptions, data sources, and modifications.  

5. **Ethical AI Governance:**
   - Create governance structures to monitor moral AI behaviour.  
   - Establish committees or ethical officers to oversee the advancement and application of AI.  

---

## **4. Key Interdependencies**
- **Security and Privacy:**  
  - Strong data security measures (e.g., encryption) reinforce privacy by preventing unauthorized access to sensitive information.  

- **Bias and Privacy:**  
  - Privacy-preserving methods (e.g., differential privacy) must not compromise fairness or model accuracy.  

- **Security and Bias:**  
  - Security protocols must ensure that model updates and training data integrity are not compromised, as altered data can introduce bias.  

--- 

[Source](https://www2.deloitte.com/content/dam/Deloitte/us/Documents/deloitte-analytics/us-ai-institute-trustworthy-ai-in-practice.pdf)
