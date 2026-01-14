# SDV Security and Privacy  Elicitation Questionnaire

This document reports the full list of questions used in the expert elicitation.
The elicitation targets **industry practitioners** and collects perceptions on SDV definition, threats, mitigations, OTA security, and privacy.
All questions were answered anonymously and analyzed in aggregate. The complete questionnaire, exactly as administered to practitioners, is as follows:

#########################################################################

Our work reviews the security and privacy challenges associated with
**Software-Defined Vehicles (SDVs)**, offering insights from both academic
literature and industry perspectives, and identifying potential threats,
mitigations, and areas for future research.

In this survey, you will be asked to answer multiple-choice questions in six main sections. These sections include an introductory section for statistical purposes, a section on the definition and the main features of SDV, a section on possible security threats, a section on mitigation, questions on Over The Air (OTA) security, and finally a section on privacy.

*The first section of the questionnaire is intentionally more detailed, as it
covers the core features that define the SDV paradigm. Understanding and
assessing these foundational elements is crucial to accurately capturing the
essence and scope of SDVs.*

Please provide your answers based on your experience and personal opinion.
The survey should take approximately **20/30 minutes** to complete.
We thank you in advance for participating and highly value your feedback.
All responses will remain **anonymous**.

# 1. Introduction questions
   
These answers are for statistical purposes only. They are anonymous and will be processed in aggregate form.

**Q1. Organization type**

My organization is considered as:

OEM

Tier 1

Tier 2

Tier 3

Other

**Q2. Job title**

Open text field.

# 2. SDV Definition
   
Please answer the following questions by rating each item on the scale provided.

(Scale: 1 = not relevant, 5 = highly relevant)

**Q3. Decoupling of Hardware and Software**

The shift towards vehicles becoming software-centric, where hardware and software are increasingly independent, with software taking a central role

**Q4. Hardware as a Shared Resource**

Hardware functions as a resource that software can access and utilize as needed.

**Q5. Hardware Abstraction**

The use of standardized interfaces to abstract underlying hardware functions and application services, enabling more flexible and efficient software development.

**Q6. Hardware and Vendor Agnosticism**

Software services and interfaces should be independent of specific hardware, enabling seamless interaction with various systems and applications.

**Q7. Generic Software**

Applications can be developed independently and tailored to specific functions or services, rather than being tied to particular vehicle types.

**Q8. Continuous OTA Updates**

All vehicle components should support over-the-air (OTA) software updates, allowing for ongoing upgrades and management of vehicle functions and capabilities throughout the vehicle’s lifecycle.

**Q9. Enhanced Software Reuse**

The ability to reuse software components across various systems and platforms, promoting efficiency and consistency.

**Q10. Cross-Domain Applications**

The ability to gather and integrate information from multiple domains to deliver improved and more comprehensive services.

**Q11. Advanced Data Collection and Data-Driven Vehicle Intelligence**

SDVs stand apart from traditional vehicles by collecting and sharing data with various entities, fully harnessing this data to enhance vehicle intelligence through effective utilization. 

**Q12. Customer-Centric Development**

Continuously monitor customer usage of features, learn from their interactions, and optimize features based on those insights.

**Q13. Ecosystem Shift**

The vehicle is no longer the central focus but becomes just another device within a broader digital ecosystem, similar to a smartphone.

**Q14. Need for Automotive Industry Transformation**

Transform the automotive industry by introducing new vehicular technologies, as current vehicle setups are not equipped for this transition.

**Q15. Shift to Centralized Control**

Shifting network topology from domain-centric to zonal-centric E/E (Electrical/Electronic) architecture.

**Q16. Strategic Importance of On-Board Operating Systems**

The on-board operating system becomes a crucial strategic component to managing complex vehicle functions.

**Q17. Cloud-Native Design Adoption**

Implementing cloud-native design principles across hardware platforms, from cloud infrastructure to vehicle edge, within an automotive DevOps framework.

**Q18. Scalable In-Vehicle Architecture**

The in-vehicle architecture must be designed for scalability to accommodate future upgrades and expansions.

**Q19. Hierarchical and Containerized Software Architecture**

Moving from tightly coupled software and hardware to a hierarchical, containerized architecture.

**Q20. Collaborative Communication Architecture**

Designing communication systems to facilitate interaction between vehicles, edge devices, and cloud services.

**Q21. Automotive Ethernet as a Key Enabler**

Automotive Ethernet can play a crucial role in enabling the functionalities of SDVs.

**Q22. Other (Open-ended)**

Please suggest any additional features and try to rate each one.

# 3. Security Threats
   
Please answer the following questions by rating each item on the scale provided.

(Scale: 1 = low criticality, 5 = high criticality unless otherwise specified)

**Q23. In-Vehicle Network Attacks**

Attacks targeting in-vehicle networks, including CAN bus vulnerabilities and Service-Oriented Architecture (SOA) exploits, carried over from existing automotive systems.

**Q24. V2X / VANET Attacks**

Security threats associated with Vehicle-to-Everything (V2X) and Vehicular Ad Hoc Networks (VANETs), inherited from current automotive systems.

**Q25. AI System Threats**

Risks related to AI systems involved in perception and planning, which may also affect smart sensors such as cameras, LiDAR, etc.

**Q26. Connectivity and API Attacks**

Security threats targeting connectivity and APIs in both in-vehicle systems and cloud environments.

**Q27. Malware from Third-Party Applications**

Introduction of malware through third-party applications integrated with the vehicle’s infotainment or operational systems, potentially leading to data breaches or system failures.

**Q28. Mixed-Criticality Attacks**

Exploits that take advantage of the dynamic nature of SDVs, where both low- and high-criticality tasks coexist on the same platform. 

**Q29. Task Migration Attacks**

Exploiting vulnerabilities during the offloading of tasks to different zonal computers for load distribution, which can pose security risks at the ECU or network level.

**Q30. Hardware Supply Chain Risks**

How critical do you perceive the risks associated with the hardware supply chain for SDV components?

**Q31. Supply Chain Code Injection**

Compromising the software supply chain by injecting malicious code during development or distribution, which can impact multiple vehicles from the manufacturer.

**Q32. Ransomware Criticality**

How critical do you believe the threat of ransomware is in your sector?

**Q33. Ransomware-Company**

How much of a priority is it for your company to avoid or circumvent ransomware?

**Q34. IP Ownership vs Security**

Do you find IP ownership and security in conflict?

# 4. Wireless Attack Vectors
   
How critical do you consider the risks posed by the following wireless attack vectors?

(Scale: 1 = not relevant, 5 = highly relevant)

**Q35. Criticality of the following wireless vectors (rate each one):**

DSRC

Telematics

TPMS

Wi-Fi

Bluetooth

Remote Keyless Entry (RKE)

5. Possible Attackers
   
List of possible attackers to worry about

(Scale: 1 = not relevant, 5 = highly relevant)

**Q36. Concern level for the following attackers (rate each one):**

Criminals

Hacktivists

Nation states

Competitors

Others (open-ended)

**Q37. Other threats (Open-ended)**

Please indicate other possible threats and try to rate each one of them.

# 6. Security Mitigations
   
(Scale: 1 = low priority, 5 = high priority)

**Q38. Secure Vehicle Software Engineering (SVSE) Lifecycle**

Incorporate security-by-design principles, secure coding practices, thorough testing (static, dynamic, fuzz), and continuous monitoring throughout the software development lifecycle.

**Q39. Safety and Security Risk Assessments**

Use integrated risk assessment methods (e.g., STRIDE, EVITA) and automate testing from TARA using attack trees, with added focus on Common Attack Patterns and Testing Automation Frameworks (TAF) to improve efficiency.

**Q40. Securing the CAN Bus**

Implement message filtering, network isolation, and separation of critical and non-critical system components to protect the CAN bus.

**Q41. Improving Automotive Ethernet Security**

Apply security extensions like MACsec or TLS to enhance Automotive Ethernet protection.

**Q42. Data Protection in VANETs**

Use encryption, Multi-Factor Authentication (MFA), and anonymization techniques to protect data in Vehicular Ad Hoc Networks (VANETs).

**Q43. Secure Ad-Hoc Communication Protocols**

Develop new protocols for secure communication both within vehicles and with external interfaces.

**Q44. Securing Telematics Systems**

Reduce attack surfaces and improve ECU re-flashing and diagnostics with dynamic challenges and stronger authentication mechanisms.

**Q45. Network Security Solutions**

Utilize signature-based and anomaly-based intrusion detection systems, Host-based Integrity Verification Systems (HIVS), Network-based Intrusion Detection Systems (NIDS), and Challenge-based Intrusion Prevention Systems (CIPS).

**Q46. Gateway Firewalls**

Implement firewalls to control and monitor traffic between different network segments, ensuring authorized communications and blocking potential threats.

**Q47. Compliance with Standards**

Applying only the ISO 21434 and UNECE R155/156 standards to address security threats may be sufficient.

**Q48. Adopting Industry-Standard Operating Systems**

Using industry-wide "gold-standard" operating systems such as AUTOSAR and Android Automotive instead of custom solutions.

**Q49. Adequacy of Current Testing Methods**

How would you prioritize the adequacy of current testing methods in ensuring the security and reliability of SDVs?

**Q50. Insurance as a Countermeasure**

Do you see insurance as an important countermeasure?

**Q51. Insurance Importance for Organization**

To what extent do you rely on insurance?

**Q52. Other mitigations (Open-ended)**

 please indicate other mitigations and try to rate each one of them.
 
# 7. OTA Security
   
Please answer the following questions by rating each item on the scale provided.

(Scale: 1 = low criticality, 5 = high criticality)

**Q53. OTA Update Risks**

What are the potential security risks associated with OTA updates, such as disruptions, rollbacks, or the installation of malicious firmware?

**Q54. Non-Functional Properties for OTA Security**

What are the key non-functional properties required to ensure the security of OTA updates (rate each one)?

Security

Trust

Privacy

Security & Trust

Security & Privacy

Trust & Privacy

**Q55. Impact of SDV Features on OTA Security**

Which features of SDVs most significantly impact on the security of OTA updates (rate each one)?

Connectivity

Data Integrity

Authentication

Authorization

Encryption

Fail-safe mechanisms

Update mechanisms

**Q56. Optimal Architectural Model for OTA Updates**

What architectural model is most effective for managing OTA updates securely (rate each one)?

AUTOSAR Adaptive

PKI (Public Key Infrastructure)

Blockchain

Decentralized (Edge or Fog)

Centralized (Cloud)

**Q57. Other (Open-ended)**

Please indicate other relevant features and try to rate each one of them.

# 8. Privacy
   
Please answer the following questions by rating each item on the scale provided.

(Scale: 1 = low criticality, 5 = high criticality)

**Q58. Sufficiency of Existing Privacy Mechanisms** 

The current privacy mechanisms in most infotainment systems (e.g., Android Automotive) are sufficient for protecting driver privacy.

**Q59. Opt-Out Rights for Data Collection** 

Drivers should be given the right to completely opt out of data collection, even for OEM services, and still being able to use their infotainment system.

**Q60. GDPR as the Privacy Standard**

Every stakeholder should design privacy according to GDPR as it is the "gold standard".

**Q61. OEM Control over Third-Party Apps**

OEMs should be allowed to choose which third-party apps to allow on their platform.

**Q62. OEM Data Collection Rights**

OEMs should have the right to collect any data they want for their own purposes as long as they do not sell it to third parties.

**Q63. OEM Responsibility for Data Sanitization**

OEMs are responsible to sanitize collected data upon sharing it with third parties since they are data controllers according to GDPR.

**Q64. Privacy vs. Security**

Privacy is considered an afterthought compared to security.

**Q65. Other (Open-ended)** 

Please indicate other relevant features and try to rate each one of them.

