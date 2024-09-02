# The GRC Project 

<br />
<p align="center">
<img src="https://dcybersecurity.sa/wp-content/uploads/2021/09/grc-circle-1200x1200.png" height="30%" width="30%" alt="Detection Engineering Logo Team Ghost"/>
</p>

<h2>Description</h2>

In this project, I designed and secured an environment of a cybersecurity consulting firm responsible for managing and protecting Government Controlled Unclassified Information (CUI). The project was guided by the framework set forth in the NIST Special Publication 800-171 (Protecting Controlled Unclassified Information in Nonfederal Systems and Organizations) System Security Plan (SSP) and focused on achieving compliance with the Cybersecurity Maturity Model Certification (CMMC) Level 2 requirements.

To ensure the environment met these stringent requirements, I implemented a comprehensive set of security controls based on NIST Special Publication 800-53 (Security and Privacy Controls for Information Systems and Organizations). These controls were selected and tailored to fulfill the specific requirements outlined in the SSP, ensuring the environment's security posture was robust enough to handle the sensitive nature of CUI.

A key part of this project involved conducting a baseline risk assessment using the NIST Special Publication 800-30 (Guide for Conducting Risk Assessments). This assessment allowed for the identification and prioritization of critical risks within the environment, providing a clear understanding of the overall risk landscape. The results of this assessment were quantified into an overall risk score, highlighting the areas that required immediate attention.

Following the risk assessment, I applied the NIST Special Publication 800-37 (Risk Management Framework for Information Systems and Organizations: A System Life Cycle Approach for Security and Privacy) to manage the identified risks effectively. This process involved creating a detailed Plan of Action and Milestones (POA&M), which outlined the specific steps necessary to implement the required security controls and achieve full compliance with the NIST SP 800-171 SSP.

The culmination of these efforts resulted in a significant improvement in the security posture of the environment, with a calculated 40% reduction in the overall risk score. This reduction effectively lowered the environment's risk level to 'low,' ensuring that the firm is well-positioned to securely manage and protect CUI in alignment with government standards and industry best practices.

<br />
<p align="center">
<img src="https://imgur.com/ysyWGTU.png" height="75%" width="75%" alt="Detection Engineering Logo Team Ghost"/>
</p>

<br />

<h2>Baseline Security Audit and System Security Plan</h2>

#### Overview
The Baseline Security Audit was conducted using the NIST SP 800-171 framework to evaluate the current state of security controls within the organization. The audit aimed to determine which security requirements were fully implemented, which were planned for future implementation, and which were deemed not applicable to the organization’s environment.

During the audit, each security control was reviewed and categorized accordingly:

- **Implemented Controls**: These are the security measures that were fully operational at the time of the audit. Examples include the enforcement of access control mechanisms, the implementation of least privilege, and the monitoring of physical access to critical infrastructure.

- **Planned to be Implemented**: This category includes security controls that were identified as necessary but had not yet been fully implemented. Plans were outlined to ensure that these controls would be established within a specified timeframe. For example, multi-factor authentication for privileged accounts and full implementation of audit logging mechanisms were among the controls planned for future implementation.

- **Not Applicable Controls**: Some security controls were determined to be irrelevant to the organization's operations. These were typically controls related to wireless access, mobile devices, or external connections that were not present in the environment. For instance, controls related to the protection of wireless networks were marked as not applicable due to the absence of wireless devices within the organization.

#### System Security Plan (SSP):
The System Security Plan (SSP) provides a comprehensive overview of the organization’s information system, detailing the security requirements and controls that have been implemented, planned, or are not applicable. The SSP is structured to align with the NIST SP 800-171 guidelines, ensuring that the organization meets the necessary security standards for handling Controlled Unclassified Information (CUI).

**Key sections of the SSP include:**

  **System Identification**: 
   - **System Name/Title**: The system is identified as the "SOHO System."
   - **System Categorization**: It is categorized as Moderate Impact for Confidentiality, indicating the importance of protecting the confidentiality of the information processed by the system.
   - **System Unique Identifier**: The system is uniquely identified by the code [00S51B525].

  **Responsible Organization**: 
   - The organization responsible for the system is LionSec, located at 3823 Fakename Street, Huntsville, AL.
   - Key personnel include Emilia Garcia, the Information Owner, and Felix Aburto, the System Owner and Security Officer, both of whom are tasked with overseeing the security of the system and ensuring compliance with relevant regulations.

  **General Description/Purpose of the System**: 
   - The system’s primary function is to securely manage, process, and store CUI as part of the firm’s core business operations, including conducting security assessments, performing incident response, and managing compliance audits for government contracts.

  **System Environment**:
   - This section provides a detailed description of the network topology, highlighting key components such as routers, firewalls, switches, workstations, and servers. The environment is designed to ensure secure handling of CUI, with clearly defined system boundaries and robust security measures in place to protect against unauthorized access and external threats.

  **Requirements**:
   - The SSP includes a thorough description of how each security requirement is being implemented, planned, or deemed not applicable. Each requirement is documented with its status, the current implementation details, and any scoping guidance that has been applied.


#### Documentation of Implemented Controls:

The Current Implemented Controls document provides a thorough description of the specific security measures in place. For instance, access control measures are well-defined, including account management, role-based access control (RBAC), and the implementation of least privilege principles. These controls are crucial for restricting access to sensitive information and ensuring that only authorized personnel can perform certain functions within the system.
  
More information can be found in the LionSec SSP.docx and the Current Implemented Controls.docx files that I have attached.

<br />
<p align="center">
<img src="https://imgur.com/OkqJ94k.png" height="100%" width="100%" alt="Detection Engineering Logo Team Ghost"/>
</p>

<br />
<p align="center">
<img src="https://imgur.com/S1LtIz6.png" height="100%" width="100%" alt="Detection Engineering Logo Team Ghost"/>
</p>

<br />


<h2>Baseline Risk Assessment and Risk Assessment Report</h2>

#### Overview
The Baseline Risk Assessment was meticulously conducted to evaluate the security posture of the organization by analyzing key controls and their associated risks. This assessment was structured according to the NIST SP 800-30 framework and focused on identifying vulnerabilities, assessing the likelihood and impact of potential threats, and calculating overall risk scores for each control. The findings were documented in an Excel spreadsheet that served as the primary tool for tracking and managing these risks.

#### Key Components of the Assessment

  **Control Identification and Categorization**:
   Each row in the assessment corresponds to a specific security control, identified by a unique control identifier (e.g., PS-4 for Personnel Termination). The controls are derived from NIST SP 800-53, ensuring comprehensive coverage of security requirements. For each control, the assessment details the control name, a description of the control, and the specific threats it addresses.

  **Risk Analysis**:
   - **Threats**: The assessment lists the potential threats associated with each control, such as unauthorized access to Controlled Unclassified Information (CUI), data corruption, or system unavailability due to environmental factors.
   - **Vulnerability Description**: This section provides a brief description of the vulnerabilities related to the threats. For example, "Unauthorized access" might be listed as a vulnerability for controls dealing with account management or cryptographic key management.
   - **Likelihood and Impact Values**: The likelihood of a threat being realized and its potential impact are quantified on a scale from 0 to 10. For instance, a likelihood of 8 suggests that the threat is highly likely to occur, and an impact of 8 indicates that the event could have severe or catastrophic consequences for the organization.

  **Overall Risk Score Calculation**:
   The overall risk score for each control is calculated by multiplying the likelihood by the impact (Overall Risk = Likelihood \* Impact). These scores help in prioritizing which controls require immediate attention based on their risk levels. For example, several controls in the assessment have an overall risk score of 64, indicating high-priority risks that could significantly affect the organization's operations.

  **Disposition of Controls**:
   The spreadsheet categorizes each control based on its current status—whether it is "In Place," "Planned to be Implemented," or "Not In Place." This categorization is crucial for understanding the maturity of the security environment and identifying areas that require further development.

  **Risk Explanation**:
   For each control, the assessment provides a detailed explanation of the risk associated with not fully implementing the control. This explanation helps to contextualize the risk score by explaining the potential consequences in more detail. For example, if cryptographic key management controls are not in place, the risk explanation might discuss the potential for unauthorized access due to compromised or poorly managed keys.

### Risk Assessment Report
Following the Baseline Risk Assessment, a comprehensive Risk Assessment Report was prepared. This report distilled the findings of the assessment into an actionable document, emphasizing the most critical risks that could impact the organization’s security posture.

**Executive Summary**:

The report provided a high-level overview of the most critical risks identified, focusing on those with the highest risk scores. It highlighted 32 high-risk items (with a score of 64) and 20 medium-risk items (with a score of 56), emphasizing the need for immediate or medium-term action to address these vulnerabilities.

**Key Findings**:

The report detailed the specific controls that were assessed as high-risk. For instance, the Personnel Termination control was identified as high-risk due to the potential for unauthorized access to CUI by former employees. Similarly, Vulnerability Monitoring and Scanning was flagged as critical due to the threat of unpatched vulnerabilities being exploited by attackers.

**Recommendations**:

The report provided clear recommendations for mitigating the identified risks. These recommendations were categorized into immediate actions (e.g., implementing additional controls for high-risk areas), medium-term actions (e.g., updating the incident response plan), and long-term actions (e.g., conducting regular vulnerability assessments).
Conclusion:

The report concluded with a call to action, stressing the importance of addressing the identified vulnerabilities to maintain the organization’s security posture. It underscored the necessity of proactive risk management to safeguard the organization’s assets and data against emerging threats.

More information can be found in the files: LionSec Baseline Risk Assessment.xlsx and LionSec Risk Assessment Report.docx


<br />
<p align="center">
<img src="https://imgur.com/YrRRQVp.png" height="100%" width="100%" alt="Detection Engineering Logo Team Ghost"/>
</p>

<br />
<p align="center">
<img src="https://imgur.com/0b40q2H.png" height="100%" width="100%" alt="Detection Engineering Logo Team Ghost"/>
</p>

<br />

<h2>NIST 800-37 Risk Management Framework</h2>

<br />
<p align="center">
<img src="https://media.licdn.com/dms/image/D5612AQH4m0Ud-dCvLw/article-cover_image-shrink_600_2000/0/1678258984629?e=2147483647&v=beta&t=MINQCWtRjcNDIGz1R9uRCYH_P7lq1jWb6l9RkPwz_U4" height="30%" width="30%" alt="Detection Engineering Logo Team Ghost"/>
</p>


After the baseline risk assessment is completed I will next utilize NIST SP 800-37 Risk Management Framework (RMF) to systematically manage and reduce the risks identified during the baseline risk assessment to an acceptable level. The RMF provides a comprehensive approach to integrating risk management into the life cycle of the information system, ensuring that security is continuously maintained.

<br />

### Categorize System:

I categorized the system as having a **Moderate Impact** level for confidentiality, integrity, and availability. This categorization was based on the guidelines provided in NIST SP 800-60, which outline the criteria for determining the impact level of an information system.

**Confidentiality**:
   - The system handles Controlled Unclassified Information (CUI), which, if disclosed without authorization, could have a serious adverse effect on the organization. A breach of confidentiality could lead to unauthorized access to sensitive information, resulting in significant legal, financial, and reputational damage. However, the information does not reach the level of sensitivity that would justify a "High" impact categorization, as the potential consequences, while serious, are not catastrophic.

**Integrity**:
   - The integrity of the system is critical to ensuring that the data it processes remains accurate and unaltered. Any unauthorized modification or destruction of data could disrupt business operations and undermine the trust in the system's output. This could lead to operational failures, financial losses, and damage to the organization's reputation. The impact of such an event would be serious but not severe enough to cause extreme harm, thus warranting a "Moderate" categorization.

**Availability**:
   - The availability of the system is essential for the organization to carry out its core business operations. If the system becomes unavailable, it could significantly impede the organization’s ability to function effectively, leading to delays, missed deadlines, and potential loss of revenue. However, the impact would not be so severe as to justify a "High" impact level, as the organization would still be able to recover and continue operations after a disruption.

By categorizing the system as "Moderate Impact," I determined that while a breach of confidentiality, integrity, or availability could have serious consequences for the organization, these consequences would not be catastrophic. This categorization guided the selection of appropriate security controls to protect the system in line with the organization’s risk tolerance and regulatory requirements.

<br />

### Select Security Controls:

To ensure the secure handling of Controlled Unclassified Information (CUI) within the organization, I carefully selected and implemented security controls that align with the requirements set forth in NIST SP 800-171. This selection process was critical in building a comprehensive System Security Plan (SSP) that not only meets compliance standards but also effectively mitigates the specific risks identified in the organization’s environment.

**Mapping Requirements to Controls**:
   - The first step in selecting the appropriate security controls was to map the requirements outlined in NIST SP 800-171 to relevant controls from NIST SP 800-53. NIST SP 800-171 provides a set of security requirements specifically designed for protecting CUI in non-federal systems, and NIST SP 800-53 offers a comprehensive catalog of controls to meet these requirements. By cross-referencing these documents, I identified which controls were necessary to fulfill each requirement.

**Tailoring Controls to the Environment**:
   - After mapping the requirements, I tailored the selected controls to the specific context of the organization. This involved considering the organization’s operational environment, risk tolerance, and the specific threats identified in the Baseline Risk Assessment. For example, controls related to access management were tailored to enforce stricter permissions and monitoring for users handling CUI, while controls for incident response were enhanced to ensure quick and effective mitigation of security incidents.

**Prioritizing Controls Based on Risk**:
   - The Baseline Risk Assessment played a crucial role in prioritizing which controls to implement first. By assessing the likelihood and impact of various threats, I was able to identify high-risk areas that required immediate attention. For instance, controls addressing vulnerabilities in cryptographic key management and vulnerability scanning were prioritized due to their high-risk scores, ensuring that the most critical risks were mitigated as a priority.

**Documenting Controls in the SSP and Baseline Risk Assessment**:
   - Each selected control was thoroughly documented in both the SSP and the Baseline Risk Assessment. In the SSP, the controls were described in detail, outlining how they would be implemented, the specific NIST SP 800-171 requirements they addressed, and any relevant scoping considerations. In the Baseline Risk Assessment, these controls were linked to specific threats and vulnerabilities, providing a clear rationale for their selection and implementation. This documentation ensured that there was a clear audit trail showing how the organization’s security posture was aligned with NIST SP 800-171 requirements.

<br />

### Implement Security Controls:

As part of the "Implement Security Controls" phase of the NIST Risk Management Framework (RMF), I developed and executed a comprehensive Plan of Action and Milestones (POA&M) for all security controls that had not yet been implemented as specified in the System Security Plan (SSP). This step was crucial for addressing identified weaknesses and ensuring that the system could meet its security requirements.

**Identification of Weaknesses**:
   - Through a detailed security audit and gap analysis, I identified various controls that were either partially implemented or not implemented at all. These weaknesses were carefully documented, including their potential impact on the security posture of the system.

**Development of the POA&M**:
   - For each identified weakness, I developed a detailed POA&M entry that outlined the specific actions needed to mitigate the weakness. This included assigning responsibilities, estimating resources, and setting deadlines for each task. For instance, controls related to information flow enforcement, logging of privileged function executions, and the enforcement of unsuccessful logon attempt limits were prioritized based on their impact on overall system security.

**Resource Allocation and Scheduling**:
   - The POA&M also included a detailed breakdown of resource allocation, specifying whether the resources were funded, unfunded, or reallocated from existing projects. Milestones with interim completion dates were set to ensure that progress could be tracked effectively. For example, the implementation of enhanced logging mechanisms was scheduled with specific dates for assessment, procurement, deployment, and testing.

**Milestones and Interim Completion Dates**:
   - Each control weakness had a series of milestones with interim completion dates. These milestones served as checkpoints to ensure that the implementation of controls was on track. For instance, the milestone for the configuration of system use notification banners included steps for policy development, implementation across access points, and final review.

**Continuous Monitoring and Adjustments**:
   - The POA&M was designed to be a living document, with provisions for updating milestones and schedules as needed. If delays occurred or additional needs were identified during testing, the POA&M was adjusted to reflect these changes. This flexibility was essential for addressing any unforeseen challenges that arose during the implementation phase.

**Completion and Verification**:
   - As each control was implemented, the corresponding POA&M entry was updated to reflect its completion. Testing and verification processes were conducted to ensure that the controls were functioning as intended. Upon successful verification, the control was marked as complete in the POA&M.

By developing and executing the POA&M, I ensured that all necessary security controls were implemented in a structured and timely manner. This approach not only addressed existing weaknesses but also reinforced the overall security posture of the system, paving the way for successful authorization and continuous monitoring.

More information can be found in the file : LionSec POAM.docx

<br />
<p align="center">
<img src="https://imgur.com/BUCHdNh.png" height="100%" width="100%" alt="Detection Engineering Logo Team Ghost"/>
</p>


<br />

### Assess Security Controls:

After implementing the necessary security controls outlined in the System Security Plan (SSP) and documented in the Plan of Action and Milestones (POA&M), I conducted a post-implementation risk assessment to evaluate the effectiveness of these controls. This assessment aimed to determine how the newly implemented controls impacted the overall risk profile of the organization, specifically focusing on the reduction of risks identified in the initial Baseline Risk Assessment.

**Re-evaluation of Implemented Controls**:
   - Each control that was implemented was re-evaluated to determine its effectiveness in mitigating the associated risks. The post-implementation risk assessment involved reassessing the likelihood and impact of each threat now that the controls were in place. For example, controls related to authenticator management (such as IA-5 and IA-5(6)) were reassessed to see how well they protected against unauthorized access.

**Likelihood and Impact Adjustment**:
   - With the controls implemented, the likelihood of various threats occurring was expected to decrease. For instance, the likelihood of password exposure was reduced because of the newly established protections around authenticator management. Similarly, the impact of potential breaches or unauthorized access was also reassessed, with some impacts being mitigated or lessened due to stronger security measures.

**Calculation of New Overall Risk Scores**:
   - After adjusting the likelihood and impact values, the overall risk scores were recalculated for each control. These new risk scores were compared to the initial risk scores to determine the effectiveness of the implemented controls. For instance, controls that previously had an overall risk score of 64 may have seen significant reductions, reflecting the decreased likelihood of successful attacks or breaches.

**Documentation of Risk Reduction**:
   - The post risk assessment showed that the overall risk across the organization’s environment was reduced by approximately 40%. This reduction was calculated by comparing the cumulative risk scores before and after the implementation of controls. The controls that had the most significant impact on risk reduction were those related to boundary protection, authenticator management, and the prevention of unauthorized access.

**Final Risk Profile**:
   - The final risk profile indicated that the organization’s environment was now at a much lower risk level, with many of the previously identified high-risk items being reduced to moderate or low risk. The effectiveness of the implemented controls not only addressed the critical vulnerabilities but also ensured ongoing protection against potential threats.

More information can be found in the file : LionsSec POST Risk Assessment.xlsx

<br />

### Authorize System:

After successfully implementing and assessing the necessary security controls, I proceeded to the "Authorize System" phase of the NIST Risk Management Framework (RMF). This critical phase involved obtaining formal authorization to operate the system, ensuring that all risks had been sufficiently mitigated to an acceptable level.

**Preparation of the Authorization Package**:
   - To initiate the authorization process, I compiled a comprehensive authorization package that included all the necessary documentation. This package contained the System Security Plan (SSP), the results from the Baseline and Post Risk Assessments, the Plan of Action and Milestones (POA&M), The Security Assessment Report (SAR) and the Continuous Monitoring Plan. These documents provided a clear and detailed account of the system’s security posture and the steps taken to address identified risks.

**Submission to the Authorizing Official (CISO)**:
   - The authorization package was submitted to the Chief Information Security Officer (CISO), who serves as the Authorizing Official (AO). The CISO’s role was to review the package, assess the residual risks, and determine whether the system’s security controls were adequate to protect the organization's operations and assets.

**Risk-Based Decision Making**:
   - The CISO conducted a thorough review of the package, focusing on the remaining residual risks documented in the POA&M and the effectiveness of the implemented controls. This review was guided by the risk assessments, which quantified the likelihood and impact of potential threats. The CISO considered whether the risks were within the organization’s acceptable risk tolerance and whether any further actions were necessary.

**Authorization Decision**:
   - After evaluating the residual risks and the overall security posture of the system, the CISO made a risk-based decision to authorize the system to operate. The decision was based on the confidence that the implemented security controls were sufficient to protect the system and the information it processes. The CISO provided formal authorization, granting the system the authority to operate (ATO) within the defined parameters.

**Issuance of the Authorization to Operate (ATO)**:
   - The CISO issued the ATO, officially allowing the system to enter production and operate under the prescribed security controls. The ATO also outlined any conditions or limitations, such as requirements for continuous monitoring or specific areas where additional safeguards might be needed in the future.

**Continuous Monitoring and Reauthorization**:
   - Following the authorization, a continuous monitoring plan was activated to ensure that the system remains compliant with the established security controls. Regular assessments and updates will be conducted to maintain the system's security posture and to address any new risks that emerge over time. The CISO will review the system periodically to determine if reauthorization is necessary, especially if significant changes occur in the system’s environment or operational context.

The files for the Authorization Package have been attached as well.

<br />
<p align="center">
<img src="https://imgur.com/khd2QgM.png" height="100%" width="100%" alt="Detection Engineering Logo Team Ghost"/>
</p>

<br />
<p align="center">
<img src="https://imgur.com/y5bYgz4.png" height="100%" width="100%" alt="Detection Engineering Logo Team Ghost"/>
</p>

<br />
<p align="center">
<img src="https://imgur.com/kh0pvHn.png" height="100%" width="100%" alt="Detection Engineering Logo Team Ghost"/>
</p>

<br />
<p align="center">
<img src="https://imgur.com/iMVgmuA.png" height="100%" width="100%" alt="Detection Engineering Logo Team Ghost"/>
</p>

<br />

### Monitor Security Controls:

To successfully complete the "Monitor Security Controls" section of the NIST Risk Management Framework (RMF), I executed the Continuous Monitoring Plan (CMP), ensuring that all required security controls were continuously assessed and evaluated.

**Structured Monitoring Process:**
The CMP was structured to monitor key security controls across different areas of the organization. Each control had a clearly defined monitoring schedule, responsible team, and deliverables. This structure allowed for organized and efficient monitoring, ensuring that no aspect of the security posture was overlooked.

**Regular Assessment of Controls:**
The CMP outlined specific frequencies for monitoring each control, ranging from daily to quarterly checks. For instance, critical controls such as Continuous Monitoring (CA-7) were assessed daily to maintain real-time awareness of the system’s security status. Other controls, like Authenticator Management (IA-5), were monitored monthly. This regular assessment ensured that any potential security issues were detected promptly.

**Role-Based Accountability:**
Each control was assigned to a specific team or individual responsible for its monitoring and reporting. This clear delegation of responsibilities ensured that the monitoring tasks were executed consistently and that the appropriate expertise was applied to each control. For example, the Identity and Access Management (IAM) Team was responsible for controls related to authentication, ensuring that multi-factor authentication and identity verification processes were properly maintained.

**Consistent Reporting and Documentation:**
As part of the CMP execution, each monitoring activity resulted in the generation of deliverables such as logs, reports, and analysis documents. These deliverables were crucial in providing evidence of the ongoing effectiveness of the security controls. For example, Security Monitoring Logs and Incident Response Reports were generated daily, providing a continuous stream of data to support the security posture of the system.

More information can be found in the LionSec Continous Monitoring Plan.xlsx file.

<br />

<h2>Conclusion</h2>

This project has successfully demonstrated the importance of a structured and methodical approach to cybersecurity governance, risk management, and compliance (GRC). By leveraging the comprehensive guidance provided by key NIST publications, we were able to design, secure, and assess an environment that not only protects Controlled Unclassified Information (CUI) but also meets the requirements for Cybersecurity Maturity Model Certification (CMMC) Level 2 compliance.

The foundation of our security efforts was built upon **NIST SP 800-171: Protecting Controlled Unclassified Information in Nonfederal Systems and Organizations**, which provided the necessary framework for safeguarding CUI. To ensure that these requirements were effectively implemented, we selected and tailored security controls from **NIST SP 800-53: Security and Privacy Controls for Information Systems and Organizations**. These controls were documented in the System Security Plan (SSP), forming the backbone of our compliance strategy.

To gain a clear understanding of the risk landscape, a thorough Baseline Risk Assessment was conducted using **NIST SP 800-30: Guide for Conducting Risk Assessments**. This assessment identified critical vulnerabilities and prioritized them based on their potential impact, guiding our risk management efforts. The entire risk management process was then governed by **NIST SP 800-37: Risk Management Framework for Information Systems and Organizations**, which ensured that risks were systematically managed throughout the system’s life cycle.

In determining the appropriate security categorization for our system, we utilized **NIST SP 800-60: Guide for Mapping Types of Information and Information Systems to Security Categories**. This helped in accurately assessing the impact level for confidentiality, integrity, and availability, which in turn guided the selection of security controls tailored to the organization’s specific risk tolerance and regulatory obligations.

The culmination of these efforts resulted in a significant reduction in the organization’s risk profile, with a calculated 40% reduction in overall risk, effectively lowering the environment’s risk level from 'Moderate' to 'Low'. This achievement not only met the compliance standards outlined in the NIST SP 800-171 but also ensured that the environment is fully compliant with CMMC Level 2, positioning the organization to securely manage and protect CUI in alignment with government standards and industry best practices.

In conclusion, this project not only fulfilled its primary objectives but also established a strong foundation for future security initiatives. The integration of NIST standards into every phase of the project underscores the importance of a rigorous, standards-based approach to cybersecurity, ensuring long-term resilience and success in the face of ever-changing threats.
