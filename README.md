# ITAuditGuide

This aims to be a guide to IT Audit-Best Practices. It is aimed at a company size of SME (Less than 250 people)

Ressources and standards used within:  

-ISA 315 (Revised 2019)

-ISO27001

-NIST CSF 2.0 (Cybersecurity Framework) 

-NIST 800-53 Special Publication 

-NIST 800-63 Special Publication 

## General Process

Before you jump right into the audit with the checklist, there are some key-things you need to be aware of. I'll try to list these below together with a rough outline of the audit timeline: From Start -> Finish. 

### Audit Planning
- **Scope Definition**: Clearly define what will be covered in the audit, including systems, processes, and locations.
- **Objective Setting**: Outline the audit's objectives, which could include assessing risks, evaluating controls, or verifying compliance.
- **Resource Allocation**: Determine the resources needed, including team members, tools, time, and most important budget available. 
- **Risk Assessment**: Identify potential risks that could impact the audit process.

### Execution of the Audit
- **Data Collection**: Gather evidence through interviews, observations, screenshots and document reviews.
- **Testing**: Perform tests on IT controls to assess their effectiveness (Keywords: ITGC, ITAC).
- **Analysis**: Analyze the data collected to identify any issues or areas for improvement.

### Reporting
- **Findings**: Document the audit findings, including any weaknesses or non-compliance issues.
- **Recommendations**: Provide recommendations for addressing the findings.
- **Action Plan**: Develop an action plan with timelines for implementing the recommendations.

### Follow-Up
- **Implementation Review**: Check whether the recommendations have been implemented effectively.
- **Post-Implementation Audit**: If possible/necessaty conduct a follow-up audit to ensure that the changes have resulted in the desired improvements.

### Continuous Improvement
- **Feedback Loop**: Establish a mechanism for ongoing feedback and continuous improvement of the audit process.
- **Update Audit Procedures**: Regularly update the audit procedures to reflect changes in technology, regulations, and business processes -> IT-moves at lightspeed ;).


> [!IMPORTANT]  
> Never underestimate good Audit Planning! Always keep in regular contact with the Lead-Auditor for important information.  

As such the rough timeline can be descriped as: 

```
1. Kick-off internal (Audit Lead and IT-Auditor) 
2. Kick off external (IT Auditor and client)
3. Audit Process and Document Review
4. Finalize and communicate results to client / review possibility 
5. Finalize and communicate results to Audit Lead
```


# Guide 

Below is a guide that aims to provide **concise** walkthrough for needed documentation/proof during the audit. 

> [!NOTE]  
> Guide incomplete...to be finalized


### IT Operation

#### IT Environment / IT Strategy / IT Security Concept / IT Organization

- [ ] Describe the current IT environment.
- [ ] Outline the IT strategy.
- [ ] Provide the IT security concept.
- [ ] Detail the IT organization structure.

#### Hardware / Networks

- [ ] Inventory of all hardware.
- [ ] Network diagrams and configurations.
- [ ] Maintenance schedules and logs.

#### Physical Security

- [ ] Physical security measures in place.
- [ ] Access control systems.
- [ ] Surveillance and monitoring systems.

#### Data Backup and Outsourcing Procedures

- [ ] Data backup policies and procedures.
- [ ] Outsourcing agreements and policies.

#### Measures for Orderly Regular Operation and to Ensure Operational Readiness

- [ ] Standard operating procedures (SOPs).
- [ ] Disaster recovery plans.
- [ ] Business continuity plans.

#### Job Scheduling

- [ ] Job scheduling policies.
- [ ] Automated job scheduling systems.

#### Job Monitoring

- [ ] Monitoring tools and processes.
- [ ] Incident management logs.

#### Intrusion Detection

- [ ] Intrusion detection systems (IDS) in place.
- [ ] Logs and reports from IDS.

#### IT Outsourcing

- [ ] Outsourcing agreements.
- [ ] Service Level Agreements (SLAs).

#### Data Protection Organization

- [ ] Data protection policies.
- [ ] Data protection officer (DPO) contact details.

### Access Management

#### Authentication

- [ ] Authentication mechanisms (e.g., 2FA, SSO).
- [ ] User access review logs.

#### User Application Process

- [ ] User application process documentation.
- [ ] User provisioning and de-provisioning logs.

#### Password & Account Lockout Policies (Parameter Settings)

- [ ] Password policies.
- [ ] Account lockout policies.

#### Authorization Concept

- [ ] Authorization concept (e.g., need-to-know principle, separation of functions).
- [ ] Role-based access control (RBAC) documentation.

#### Administrative Rights, Privileged Users

- [ ] List of users with administrative rights.
- [ ] Policies for managing privileged accounts.

#### Critical Operating System Level Permissions

- [ ] List of critical OS level permissions.
- [ ] Review logs of permissions changes.

#### Access Databases

- [ ] Access control policies for databases.
- [ ] Database access logs.

#### Access Network

- [ ] Network access control policies.
- [ ] Network access logs.

### Change Management

#### Concept / Process Documentation for Change Management

- [ ] Change management policies.
- [ ] Documentation of change management process.

#### Changes Beyond the Regular Updates

- [ ] List of changes beyond regular updates.
- [ ] Documentation of change approvals.

#### Approval Process for Changes

- [ ] Change approval workflow.
- [ ] Logs of change approvals.

#### Testing Process and System

- [ ] Testing procedures.
- [ ] Test environment documentation.

#### Customizing

- [ ] Documentation of system customizations.
- [ ] Approval logs for customizations.

#### Parameterization

- [ ] Parameterization policies.
- [ ] Parameter changes logs.

#### Effectiveness of the Change Management Process

- [ ] Metrics for assessing change management effectiveness.
- [ ] Review reports of change management process.

#### Data Conversions

- [ ] Documentation of data conversion processes.
- [ ] Logs of data conversion activities.

### Interfaces / APIs

#### Overview of the Data Flows

- [ ] Data flow diagrams.
- [ ] Documentation of data flows between systems.

#### What Data is Transferred?

- [ ] List of data types transferred between systems.
- [ ] Security measures for data transfers.

#### Documentation for Checks / Reconciliation Checks Regarding the (Automatic and Manual) Data Transfers

- [ ] Reconciliation check procedures.
- [ ] Logs of reconciliation checks.

#### Automatic Interfaces

- [ ] Documentation of automatic interfaces.
- [ ] Logs of interface operations.

#### Semi-Automated Interfaces

- [ ] Documentation of semi-automated interfaces.
- [ ] Logs of semi-automated interface operations.

#### Manual Interfaces

- [ ] Documentation of manual interfaces.
- [ ] Logs of manual interface operations.

#### Identification of Faulty Batch Runs

- [ ] Procedures for identifying faulty batch runs.
- [ ] Logs of batch run errors and resolutions.




# Glossary

Goal: Standardize all used Terms here. / Explain them short and brief. List To be completed. 

**Access Control List (ACL)**: A table that tells a computer operating system which access rights each user has to a particular system object, like a file directory or individual file.

**Advanced Persistent Threat (APT)**: A stealthy threat actor, typically a nation-state or state-sponsored group, which gains unauthorized access to a computer network and remains undetected for an extended period.

**Baseline Security**: The minimum level of security that a system, network, or program must adhere to in order to be considered secure.

**Cryptanalysis**: The study of analyzing information systems in order to study the hidden aspects of the systems.

**Data Leakage Prevention (DLP)**: A strategy for making sure that end users do not send sensitive or critical information outside the corporate network.

**Encryption Algorithm**: A method by which plaintext or any other type of data is converted from a readable form to an encoded version that can only be decoded by another entity if they have access to a decryption key.

**Firewall**: A network security system that monitors and controls incoming and outgoing network traffic based on predetermined security rules.

**Hash Function**: A function that converts an input (or 'message') into a fixed-size string of bytes, which is typically a digest that is unique to each unique input.

**Intrusion Detection System (IDS)**: A device or software application that monitors a network or systems for malicious activity or policy violations.

**Key Management**: The process of managing cryptographic keys in a cryptosystem, which includes the generation, exchange, storage, use, crypto-shredding (destruction), and replacement of keys.

**Malware Analysis**: The process of studying or analyzing the functionality, origin, and potential impact of a given malware sample.

**Network Sniffing**: The use of a software tool to capture and analyze the packets sent and received over a digital network.

**Obfuscation**: The deliberate act of creating source or machine code that is difficult for humans to understand.

**Penetration Testing**: A simulated cyber attack against your computer system to check for exploitable vulnerabilities.

**Quantum Cryptography**: The use of quantum-mechanical properties to perform cryptographic tasks.

**Risk Assessment**: The process of identifying, quantifying, and prioritizing (or ranking) the risks against criteria for risk acceptance and objectives relevant to the organization.

**Security Information and Event Management (SIEM)**: A set of tools and services offering a holistic view of an organization’s information security.

**Tokenization**: The process of substituting a sensitive data element with a non-sensitive equivalent, referred to as a token, that has no extrinsic or exploitable meaning or value.

**Vulnerability Scanning**: The automated process of proactively identifying security vulnerabilities of computing systems in a network in order to determine if and where a system can be exploited and/or threatened.

**Whitelisting**: A security process in which a list of permitted entities is created and maintained, and any entity not on the list is denied access.

**XSS (Cross-Site Scripting)**: A security vulnerability typically found in web applications, which enables attackers to inject client-side scripts into web pages viewed by other users.

**Zero-Day Attack**: An attack that exploits a potentially serious software security weakness that the vendor or developer may be unaware of.

**Audit Trail**: A step-by-step record by which data can be traced to its source.

**Business Continuity Planning (BCP)**: The process involved in creating a system of prevention and recovery from potential threats to a company.

**Cyber Forensics**: The process of extracting information and data from computer storage media and guaranteeing its accuracy and reliability.

**Demilitarized Zone (DMZ)**: A physical or logical subnetwork that contains and exposes an organization's external-facing services to an untrusted network, usually a larger network such as the internet.

**Endpoint Security**: The methodology of protecting the corporate network when accessed via remote devices such as laptops or other wireless and mobile devices.

**Forensic Analysis**: The process of gathering and examining data in a way that preserves the integrity of the data and maintains a strict chain of custody for the data.

**Governance, Risk Management, and Compliance (GRC)**: The umbrella term covering an organization's approach across these three areas.

**Identity and Access Management (IAM)**: A framework for business processes that facilitates the management of electronic identities.

**General Data Protection Regulation (GDPR)**: A regulation in EU law on data protection and privacy in the European Union and the European Economic Area, which also addresses the transfer of personal data outside the EU and EEA areas.

**Swiss Federal Data Protection Act (FADP)**: The Swiss law that governs the processing of personal data by private individuals and federal government agencies, ensuring the protection of privacy and fundamental rights when personal data is processed.

**Service Level Agreement (SLA)**: A commitment between a service provider and a client that outlines the service standards the provider is obligated to meet, including the quality, availability, and responsibilities.

**Segregation of Duties (SoD)**: A key internal control that prevents conflict of interest, error, and fraud by ensuring that no single individual has control over all aspects of a financial transaction.

**Recovery Time Objective (RTO)**: The targeted duration of time within which a business process must be restored after a disaster or disruption in order to avoid unacceptable consequences associated with a break in business continuity.

**Recovery Point Objective (RPO)**: The maximum tolerable period in which data might be lost due to a major incident before the incident poses a significant risk to business operations and the achievement of a business's objectives.

**Information Security Management System (ISMS)**: A systematic approach to managing sensitive company information so that it remains secure, including people, processes, and IT systems.

**Change Management**: The systematic approach to dealing with the transition or transformation of an organization's goals, processes, or technologies.

**Data Sovereignty**: The concept that information which has been converted and stored in binary digital form is subject to the laws of the country in which it is located.

**Encryption Key**: A random string of bits created specifically for scrambling and unscrambling data.

**Incident Response Plan (IRP)**: A set of instructions to help IT staff detect, respond to, and recover from network security incidents.

**Logical Access Controls**: The tools and protocols used to limit access to systems and ensure that only authorized users can perform certain actions.

**Multi-Factor Authentication (MFA)**: A security system that requires more than one method of authentication from independent categories of credentials to verify the user's identity for a login or other transaction.

**Network Segmentation**: The practice of splitting a computer network into subnetworks, each being a network segment or network layer.

**Operational Level Agreement (OLA)**: An agreement between an IT service provider and another part of the same organization that assists with the provision of services.

**Patch Management**: The process of distributing and applying updates to software. These patches are often necessary to correct errors (known as "bugs") in the software.

**Phishing**: The fraudulent attempt to obtain sensitive information such as usernames, passwords, and credit card details by disguising oneself as a trustworthy entity in an electronic communication.

**Red Team Assessment**: An exercise where a security team assesses the security of an organization by emulating the behaviors and techniques of likely attackers in the most realistic way possible.

**Social Engineering**: The art of manipulating people so they give up confidential information, which includes a wide range of malicious activities accomplished through human interactions.

**Threat Intelligence**: Evidence-based knowledge, including context, mechanisms, indicators, implications, and actionable advice, about an existing or emerging menace or hazard to assets.

**Unified Threat Management (UTM)**: A single security solution, and the security policies associated with managing a set of security services, to protect against multiple threat types.

**Virtual Private Network (VPN)**: A service that allows you to connect to the Internet via an encrypted tunnel to ensure your online privacy and protect your sensitive data.

**Zero Trust Security Model**: A security concept centered on the belief that organizations should not automatically trust anything inside or outside its perimeters and instead must verify anything and everything trying to connect to its systems before granting access.







