# Swiss Data Protection Law (DSG) Guide

This Guide is an attempt at a clear and concise guide for SME and the **Swiss** Data protection law (DSG). 

Main Questions that always come up: 

1. What is it?

2. What do we need to do? (at a minimum)

3. What are things to watch out for? 

Legal ressources are: 

**1. Datenschutzgesetz (DSG) / Official English Translation: Federal Act on Data Protection (FADP)** 

This is the actual law itself. 
You can browse this in english on the following link https://www.fedlex.admin.ch/eli/cc/2022/491/en)

**2. Datenschutzverordnung (DSV) / *Inofficial* English Translation: Data Protection Regulation (DPR)** 

This Regulation goes in depth on some topcis such as technical measures and other details. 
You can browse this in german, french and italian on the following link https://www.fedlex.admin.ch/eli/oc/2022/568/de


>[!WARNING]
> Always note that English is not an official language of the Swiss Confederation. Even translations provided by the state are marked as *"for information purposes only without legal force."*


# Basic Compliance Checklist

Use this checklist as a starting point. **Note: Chapters are sorted by importance.**

### 1. Record of Data Processing Activities

- [ ] Maintain a record of all activities involving personal data (e.g., customer management, accounting, HR, online shops).
  - [ ] Include purposes, categories of data subjects, data types, recipients, and retention periods as required by Art. 12 revDSG.
  - [ ] Ensure this record is kept if you have 250+ employees, process sensitive data on a large scale, or conduct high-risk profiling.

### 2. Privacy Policy

- [ ] Create a privacy policy for any systematic, legally unnecessary collection of personal data.
  - [ ] Inform individuals about the policy via terms and conditions, forms, apps, etc.
  - [ ] Make the policy accessible on your website.
  - [ ] Include: who you are (with contact details), purposes of data collection, data types, recipients (names not necessary), possible countries or regions the data might be transferred to, and the legal basis for processing.

### 3. Data Processor Contracts

- [ ] Establish a Data Processing Agreement (DPA) if outsourcing data processing to an IT provider or another third party.
  - [ ] Ensure the DPA includes security measures (TOMs) and allows for audits.
  - [ ] Ensure the DPA complies with Art. 28 GDPR if it references DSG.
  - [ ] Verify existing and new DPAs for compliance.

### 4. Security Measures and Reporting

- [ ] Implement technical measures:
  - [ ] Access control
  - [ ] MFA for external access
  - [ ] Audit trails (required for sensitive data, keep for 1 year)
  - [ ] Pseudonymization
  - [ ] Firewalls
  - [ ] Anti-malware software
  - [ ] Offline backups
- [ ] Implement organizational measures:
  - [ ] Policies and instructions
  - [ ] Staff training
  - [ ] Log reviews
  - [ ] Processing regulations for sensitive data
- [ ] Reporting Obligations:
  - [ ] Notify the Federal Data Protection and Information Commissioner (FDPIC/EDÖB)  if data confidentiality, integrity, or availability is compromised and poses significant risk.
  - [ ] Document the incident for two years.
  - [ ] Inform affected individuals if they need to take protective measures.

### 5. Transfer of Personal Data Abroad

- [ ] Ensure compliant data transfers within the EEA, UK, and adequate countries.
- [ ] For other countries:
  - [ ] Ensure the transfer is necessary for contract execution with or for the data subject.
  - [ ] Obtain explicit waiver of protection from the data subject.
  - [ ] Implement Standard Contractual Clauses (SCCs) with Swiss adaptations and assess the risk of governmental access (perform a TIA).

### 6. Handling Data Subject Rights

- [ ] Verify the identity of individuals requesting access to their data.
- [ ] Provide data (not documents) free of charge within 30 days.
- [ ] Ensure accuracy to avoid incomplete or false information.
- [ ] Allow data correction requests, and note disputes.
- [ ] Respect requests to delete or stop processing data unless there are compelling reasons to continue.
- [ ] Notify individuals of automated decisions with significant impact and offer human review.
- [ ] Provide data in a reusable format upon request.

### 7. Privacy by Default

- [ ] Ensure default settings in apps, websites, etc., are privacy-friendly.
- [ ] Developers should prioritize privacy settings.

### 8. Data Protection Impact Assessment (DPIA)

- [ ] Conduct a DPIA for high-risk data processing projects.
  - [ ] Document the project and protection measures.
  - [ ] Assess residual risks and seek help if high risks remain.
  - [ ] Keep records of the DPIA.

### 9. Contact Points

- [ ] Designate a contact point for:
  - [ ] Data subject requests
  - [ ] New projects involving personal data
  - [ ] Data breach notifications
- [ ] Ensure all staff report data issues to this contact point promptly.

### 10. Good Practice: Reliance on Consent

- [ ] Avoid relying on consent for data processing where possible.
- [ ] If necessary, ensure consent is informed and voluntary, and explicit for sensitive data and high-risk profiling.


# Deep Dive


>[!IMPORTANT]
> Deep Dive section to be expanded/completed. 


### Record of Data Processing Activities

According to Article 12 FADP, the company maintains a record of all data processing activities. Companies with more than 250 employees or those that process particularly sensitive personal data on a large scale or conduct profiling with a high risk are obliged to do so. However, it is strongly suggested to build up such an inventory nonetheless to have a certain level of overview.  

### Risk Assessment and Data Protection Impact Assessment

For data processing activities that are relevant to data protection and pose a high risk to data subjects, a data protection impact assessment must be carried out according to Article 22 FADP.

### Profiling

If profiling with a high risk is carried out, i.e., the linking of personal data from which personality traits of a person can be derived, the explicit consent of the data subjects must be obtained.

### Transfer of Personal Data Abroad

The lawful transfer of personal data to third countries may only take place in compliance with appropriate data protection standards or other legal bases. Article 16 paragraph 2 FADP regulates the conditions for transfers to third countries not listed in the list issued by the state.

### Processing of Personal Data Abroad

If a company has personal data processed by third parties, it is responsible for ensuring that the data processing complies with applicable data protection regulations. A data processing agreement is generally concluded for such processing.

### Technical and Organizational Measures

According to Article 8 FADP, suitable technical protection mechanisms and organizational processes (TOMS) must be established to minimize data protection risks and protect personal data.

These TOMS are (similar to the CIA-Triad) divided into the categories of confidentiality, availiabilty, integrity and traceability. 

>[!TIP]
>The **CIA** triad relates to **C**onfidentiality (restricting access to authorized individuals), **I**ntegrity (preventing unauthorized modifications), and **A**vailability (ensuring reliable access when needed).

This is further detailed in Art. 3 of the DPR: 

1. Confidentiality

    a. Authorized persons only have access to the personal data they need to perform their tasks (access control);
    b. Only authorized persons have access to the premises and facilities where personal data is processed (entry control);
    c. Unauthorized persons cannot use automated data processing systems via data transmission facilities (user control).

2. Availability and integrity

    a. Unauthorized persons cannot read, copy, alter, move, delete, or destroy data carriers (data carrier control);
    b. Unauthorized persons cannot store, read, modify, delete, or destroy personal data in the storage system (storage control);
    c. Unauthorized persons cannot read, copy, alter, delete, or destroy personal data during the disclosure of personal data or the transport of data carriers (transport control);
    d. The availability of personal data and access to it can be quickly restored in the event of a physical or technical incident (restoration);
    e. All functions of the automated data processing system are available (availability), malfunctions are reported (reliability), and stored personal data cannot be damaged by system malfunctions (data integrity);
    f. Operating systems and application software are always kept up to date with the latest security standards and known critical vulnerabilities are closed (system security).

3. Traceability

    a. It can be verified which personal data was entered or modified in the automated data processing system, at what time, and by whom (input control);
    b. It can be verified to whom personal data was disclosed using data transmission facilities (disclosure control);
    c. Data security breaches are quickly detected (detection) and measures are taken to mitigate or eliminate the consequences (elimination).


### Privacy by Default and Privacy by Design

When designing, developing, and upgrading IT systems, the principles of data protection and IT security must be integratively taken into account according to Article 7 FADP.

### Employee Training

Employees must be trained at appropriate intervals on data protection and data protection processes.

### Information Obligations

The company ensures that data subjects can obtain all relevant information about data processing according to Article 19 FADP. If a website is operated, the information obligation is usually fulfilled by a privacy policy published on the website.

### Right to Information/Data Disclosure

Data subjects can demand information and disclosure of their data according to Article 25 FADP. The company has an obligation to provide information, which also applies to contract data processing.

### Employees' Right to Information

Employees also have the right to information about the processing of their data in the company (information, correction, objection).

### Data Breaches

Employees must report violations of data protection to the responsible authority in the company as soon as possible. In the case of violations with expected high risk, immediate notification to the Federal Data Protection and Information Commissioner (FDPIC) must be made, indicating the nature of the violation, its impact, and the measures taken or planned.



# Data Protection Glossary


| **Term**                     | **Description**                                                                                                                                                      |
|------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Data Protection Act (DPA)** | The Swiss federal law regulating the processing of personal data, aiming to protect the privacy and rights of individuals.                                            |
| **Federal Act on Data Protection (FADP)** | Official English translation of the Swiss Data Protection Act.                                                                                              |
| **Data Protection Regulation (DPR)** | Regulation detailing specific technical measures and other data protection requirements.                                                                         |
| **Personal Data**            | Any information relating to an identified or identifiable person.                                                                                                    |
| **Processing**               | Any operation performed on personal data, such as collection, storage, use, modification, or deletion.                                                                |
| **Data Controller**          | The person or organization that determines the purposes and means of processing personal data.                                                                        |
| **Data Processor**           | The person or organization that processes personal data on behalf of the data controller.                                                                             |
| **Data Subject**             | The individual whose personal data is being processed.                                                                                                               |
| **Consent**                  | A data subject's freely given, specific, informed, and unambiguous indication of agreement to the processing of their personal data.                                  |
| **Data Breach**              | A security incident resulting in the accidental or unlawful destruction, loss, alteration, unauthorized disclosure of, or access to personal data.                   |
| **Privacy by Design**        | An approach to projects that promotes privacy and data protection compliance from the start.                                                                          |
| **Privacy Impact Assessment (PIA)** | A process to evaluate and mitigate the data protection risks of a project.                                                                                           |
| **Anonymization**            | The process of removing identifying information from data so that it can no longer be linked to an individual.                                                        |
| **Pseudonymization**         | The process of replacing identifying information with pseudonyms to protect individuals' identities while retaining data utility.                                      |
| **Data Portability**         | The right of a data subject to receive their personal data in a structured, commonly used format and to transfer it to another controller.                             |
| **Data Retention**           | The practice of storing data for a specified period and ensuring its timely and secure deletion.                                                                      |
| **Cross-Border Data Transfer**| The transfer of personal data to countries outside Switzerland, subject to specific legal requirements to ensure data protection.                                      |
| **Right to Access**          | The right of individuals to obtain information about the processing of their personal data and to access that data.                                                    |
| **Right to Rectification**   | The right of individuals to correct inaccurate or incomplete personal data.                                                                                          |
| **Right to Erasure (Right to be Forgotten)** | The right of individuals to have their personal data deleted under certain circumstances.                                                                  |
| **Right to Restriction of Processing** | The right of individuals to limit the processing of their personal data under specific conditions.                                                               |
| **Right to Object**          | The right of individuals to object to the processing of their personal data for specific purposes, such as direct marketing.                                           |
| **Supervisory Authority**    | The independent public authority responsible for overseeing the application of data protection laws and ensuring compliance.                                           |
| **Data Protection Officer (DPO)** | A person appointed to oversee data protection strategy and compliance within an organization.                                                                        |
| **Binding Corporate Rules (BCRs)** | Internal rules adopted by multinational companies to ensure personal data transfers within the organization comply with data protection laws.                           |
| **Standard Contractual Clauses (SCCs)** | Contractual terms established by data protection authorities to ensure adequate safeguards for personal data transferred outside Switzerland.                       |
| **Code of Conduct**          | Guidelines developed by industry bodies or associations to help ensure compliance with data protection laws.                                                          |
| **Certification Mechanism**  | A process that certifies an organization's data processing operations comply with data protection standards.                                                           |
| **Technical and Organizational Measures (TOMs)** | Measures implemented to ensure data security, including access controls, pseudonymization, and staff training.                                                     |
| **Risk Assessment**          | The process of identifying and evaluating data protection risks to implement appropriate measures.                                                                    |
| **Data Processing Agreement (DPA)** | A contract between a data controller and a data processor outlining the processing of personal data and compliance requirements.                                      |
| **Profiling**                | The automated processing of personal data to evaluate certain personal aspects, often requiring explicit consent if high risk.                                          |
| **Record of Data Processing Activities** | Documentation of all processing activities, including purposes, data types, and retention periods, mandatory for certain organizations.                                |
| **Data Subject Rights**      | The rights granted to individuals under data protection laws, including access, rectification, erasure, and objection.                                                 |
| **Data Protection Impact Assessment (DPIA)** | An evaluation of the impact of data processing activities on the protection of personal data, required for high-risk processing.                                   |
| **FDPIC (Federal Data Protection and Information Commissioner)** | The Swiss authority responsible for enforcing data protection laws and overseeing compliance.                                          |
| **Privacy by Default**       | The principle that systems and processes should be designed to automatically provide the highest level of privacy protection.                                          |
| **Employee Training**        | Regular training for employees on data protection principles and practices.                                                                                           |
| **Information Obligations**  | The duty to inform data subjects about the processing of their personal data, typically through a privacy policy.                                                      |
| **Data Transfer Impact Assessment (TIA)** | An assessment required to evaluate the risks associated with transferring personal data to countries with different data protection standards.                     |






