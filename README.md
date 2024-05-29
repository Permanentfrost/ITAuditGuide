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


## IT Operations

### IT Environment / IT Strategy / IT Security Concept / IT Organization

- [ ] **IT Strategy Documentation**
  - [ ] **Existence**: An IT strategy is documented and in alignment with the corporate strategy.
  - [ ] **Risk Awareness**: The strategy includes an awareness of possible risks from the use of IT.
  - [ ] **Periodic Review**: The IT strategy is reviewed and updated periodically to adapt to changing business and technological landscapes.

- [ ] **IT Security Concept**
  - [ ] **ISMS Implementation**: An Information Security Management System (ISMS) is in place and operational.
  - [ ] **Security Measures**: Specific security measures such as virus protection, firewalls, DMZ (Demilitarized Zone), and intrusion detection systems are implemented and maintained.
  - [ ] **Incident Response Plan**: There is a documented and tested incident response plan.

- [ ] **IT Organization**
  - [ ] **Skill and Capacity**: The required skills and capacities to produce and maintain IT services are available within the organization.
  - [ ] **Training Programs**: Employees undergo regular training to keep their skills up-to-date.
  - [ ] **Reporting Channels**: Clear reporting channels are established.
  - [ ] **Functional Separation**: The principle of functional separation is implemented to prevent conflicts of interest and reduce risk.

### Hardware / Networks

- [ ] **Inventory Management**
  - [ ] **Inventory Records**: The IT infrastructure, including hardware, networks, and operating systems, is fully and accurately inventoried.
  - [ ] **Update Frequency**: The inventory is regularly updated to reflect any changes.
  - [ ] **Ownership and Accountability**: Each piece of hardware is assigned an owner responsible for its maintenance and security.

### Physical Security

- [ ] **Physical Protective Measures**
  - [ ] **Premises Security**: Physical protective measures against burglary, theft, and vandalism are implemented.
  - [ ] **Access Control**: Access to the premises is restricted to authorized personnel and access logs are maintained.
  - [ ] **Monitoring and Testing**: Security measures are continuously monitored and regularly tested for effectiveness.

- [ ] **Environmental Controls**
  - [ ] **Fire Protection**: Systems are in place to protect against fire, including alarms, extinguishers, and suppression systems.
  - [ ] **Water and Temperature Control**: Measures to protect against water damage and to maintain appropriate temperature levels are in place.
  - [ ] **Power Management**: Uninterruptible Power Supply (UPS) systems and redundant power sources are implemented to ensure continuous operation.

### Data Backup and Outsourcing Procedures

- [ ] **Data Security Measures**
  - [ ] **Backup Policies**: Data backup policies are documented and implemented.
  - [ ] **Backup Frequency**: Regular backups are performed, and the frequency is aligned with business needs.
  - [ ] **Monitoring**: Backup processes are logged and monitored for successful completion.
  - [ ] **Restoration Testing**: Periodic tests of data restoration processes are conducted to ensure backups can be successfully restored.

- [ ] **Outsourcing Procedures**
  - [ ] **Vendor Selection**: Procedures for selecting outsourcing vendors are documented and include risk assessments.
  - [ ] **Contract Management**: Contracts with outsourcing vendors include clear SLAs (Service Level Agreements) and security requirements.
  - [ ] **Monitoring and Review**: Performance and security measures of outsourcing vendors are regularly monitored and reviewed.

### Measures for Orderly Regular Operation and to Ensure Operational Readiness

- [ ] **Operational Measures**
  - [ ] **Emergency Operations**: Procedures for emergency operations supplement regular operations with organizational regulations and technical procedures to restore IT after failures.
  - [ ] **Incident Management**: An incident management system is in place to log, classify, and process incidents promptly.
  - [ ] **Problem Management**: Problem management processes are established to identify and resolve the root causes of incidents.

- [ ] **Operational Integrity and Availability**
  - [ ] **Integrity Measures**: Measures to ensure the integrity of IT systems are implemented.
  - [ ] **Availability Measures**: Measures to ensure the availability of IT systems, such as redundancy and failover mechanisms, are in place.

### Job Scheduling

- [ ] **Access Controls for Job Scheduling**
  - [ ] **Access Regulation**: Controls to regulate access to job controls or applications/tools that may interfere with financial reporting are established and effective.
  - [ ] **Logging and Monitoring**: Access to job scheduling systems is logged and monitored for unauthorized access or changes.

### Job Monitoring

- [ ] **Monitoring Controls**
  - [ ] **Job Processing Oversight**: Controls to oversee jobs processing financial reporting data are established and effective.
  - [ ] **Alerting Mechanisms**: Alerting mechanisms are in place to notify relevant personnel of job processing issues.
  - [ ] **Performance Metrics**: Job performance metrics are collected and analyzed to ensure efficient processing.

### Intrusion Detection

- [ ] **Intrusion Detection Systems**
  - [ ] **Implementation**: Intrusion detection systems (IDS) are implemented to monitor the IT environment for vulnerabilities and intrusions.
  - [ ] **Response Plan**: A response plan for detected intrusions is documented and tested.
  - [ ] **Regular Updates**: IDS signatures and rules are regularly updated to recognize new threats.

### IT Outsourcing

- [ ] **Outsourcing Scope and Management**
  - [ ] **Scope Definition**: The scope of IT outsourcing is clearly defined, including data center operations, shared service centers, business processes, and application development.
  - [ ] **Risk Management**: Risks associated with outsourcing are identified, and compensating controls are implemented.
  - [ ] **ICS Compliance**: Outsourced controls within the framework of the Internal Control System (ICS) are appropriate and effective (IDW PS 331 and IDW PS 951).

### Data Protection Organization

- [ ] **Data Protection Compliance**
  - [ ] **Data Protection Officer**: A data protection officer has been appointed in accordance with legal requirements.
  - [ ] **GDPR Compliance**: The organization meets the requirements of the GDPR and the BDSG.
  - [ ] **Incident Response**: Procedures are in place to respond appropriately to data protection incidents.


## Access Management

### Authentication

- [ ] **User Identification**
  - [ ] **Internal Users**: All internal users of the relevant accounting system and their databases are clearly identifiable.
  - [ ] **External Users**: All external users, including contractors and vendors, are properly identified.
  - [ ] **Temporary Users**: Temporary user accounts are managed with clear identification and limited access.

- [ ] **Access Control Policies**
  - [ ] **Role-Based Access**: Access is granted based on clearly defined roles and responsibilities.
  - [ ] **Minimum Access Principle**: Access granted corresponds to the minimum necessary to perform job functions.
  - [ ] **Access Reviews**: Regular reviews of user access rights are conducted to ensure compliance with access control policies.

### User Application Process

- [ ] **Authorization Assignment**
  - [ ] **Formal Process**: The assignment of authorizations (new, change, deactivate, delete) is subject to a formal, documented process.
  - [ ] **Timely Implementation**: Authorizations are implemented promptly to minimize security risks.
  - [ ] **Separation of Functions**: The process respects the separation of functions principle (application, approval, allocation).

- [ ] **User Provisioning**
  - [ ] **Onboarding**: New users are onboarded with appropriate access rights.
  - [ ] **Modification**: Changes to user access are documented and approved.
  - [ ] **Deactivation**: Deactivation of user access is promptly handled when no longer needed.

### Password & Account Lockout Policies (Parameter Settings)

- [ ] **Password Policies**
  - [ ] **Password Complexity**: Clear specifications define the complexity requirements for passwords.
  - [ ] **Password History**: Parameters are set to prevent the reuse of recent passwords.
  - [ ] **Password Expiry**: Passwords are set to expire after a defined period.

- [ ] **Account Lockout Policies**
  - [ ] **Incorrect Login Attempts**: Parameters define the number of incorrect login attempts before account lockout.
  - [ ] **Lockout Duration**: The duration of the account lockout period is defined.
  - [ ] **Unlock Procedures**: Procedures for unlocking accounts are documented and secure.

### Authorization Concept (Need-to-Know Principle, Separation of Functions, etc.)

- [ ] **Authorization Framework**
  - [ ] **Role Concepts**: An authorization concept for all audit-relevant systems ensures the assignment of authorizations via role concepts.
  - [ ] **Need-to-Know Principle**: Access is granted based on the need-to-know principle to enhance security.
  - [ ] **Separation of Functions**: The principle of separation of functions is enforced to prevent conflicts of interest and fraud.

- [ ] **Compliance**
  - [ ] **Data Protection Regulations**: Data protection regulations, such as GDPR, are considered and integrated into the authorization concept.
  - [ ] **Documentation**: The authorization concept is documented and accessible to relevant personnel.

### Administrative Rights, Privileged Users

- [ ] **Scope of Authorization**
  - [ ] **Minimum Privileges**: The scope of authorization for administrators and highly privileged users is limited to a necessary minimum.
  - [ ] **No Collective Users**: There are no collective or shared user accounts.
  - [ ] **No Anonymous Accounts**: Anonymous accounts are prohibited.

- [ ] **Logging and Monitoring**
  - [ ] **Action Logging**: Actions performed by administrators and privileged users are logged.
  - [ ] **Regular Audits**: Regular audits of privileged user activities are conducted to detect and respond to unauthorized actions.

### Critical Operating System Level Permissions

- [ ] **Permission Management**
  - [ ] **Minimal Permissions**: Critical permissions at the operating system level are assigned according to the minimum principle.
  - [ ] **Privileged Access Logging**: Privileged access is logged and regularly reviewed.

- [ ] **Access Reviews**
  - [ ] **Periodic Reviews**: Periodic reviews of critical operating system level permissions are conducted to ensure appropriateness.
  - [ ] **Revocation Procedures**: Procedures for revoking unnecessary permissions are documented and implemented.

### Access Databases

- [ ] **Database Access Control**
  - [ ] **Restricted Access**: Only a few authorized administrators have access to the relevant database content.
  - [ ] **Emergency Access**: There is an emergency user concept in place for critical situations.
  - [ ] **Access Logging**: Access to databases is logged and monitored.

### Access Network

- [ ] **Network Access Control**
  - [ ] **VPN Access**: Network access from outside (e.g., field staff, home office workplaces) is only possible via VPN.
  - [ ] **Hardware Requirements**: Access is restricted to company-approved hardware (e.g., company computer).
  - [ ] **Two-Factor Authentication**: Two-factor authentication (2FA), such as via mobile phone, is required for network access.

- [ ] **Security Monitoring**
  - [ ] **Intrusion Detection**: Network access points are monitored for unauthorized access attempts.
  - [ ] **Access Logs**: Network access logs are maintained and reviewed for suspicious activities.


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







