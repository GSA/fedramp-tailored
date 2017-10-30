# AU-6 Audit Review, Analysis, and Reporting
## AU-6 Control Requirement
The organization:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(a)	Reviews and analyzes information system audit records [*FedRAMP Assignment: at least weekly*] for &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;indications of [*Assignment: organization-defined inappropriate or unusual activity*]; and

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(b) Reports findings to [*Assignment: organization-defined personnel or roles*].
### AU-6(a) Control Requirement
Describe how the organization reviews and analyzes information system audit records at least weekly for indications of [*Assignment: organization-defined inappropriate or unusual activity*].

AU-6 (a). For FedRAMP Tailored systems the organization-defined frequency is **_at least weekly_**.

Additionally, for both parts AU-6(a) and AU-6(b), for FedRAMP Tailored systems FedRAMP requires **_“Coordination between service provider and consumer shall be documented and accepted by the JAB/AO. In multi-tenant environments, capability and means for providing review, analysis, and reporting to consumer for data pertaining to consumer shall be documented.”_**

The process must address each of audit records, in each of the layers, of each of the service models described in AU-3.
### AU-6(a) Control Objective
This requirement must describe a process by which the organization reviews and analyzed audit records at least weekly for indications of abnormalities in such activities as monitoring of account usage, remote access, wireless connectivity, mobile device connection, configuration settings, system component inventory, use of maintenance tools and nonlocal maintenance, physical access, temperature and humidity, equipment delivery and removal, communications at the information system boundaries, use of mobile code, and use of VoIP.

Further the review and analysis of audit records at least weekly must be coordinated between the CSP and the customer. This coordination must be documented either here in the security control implementation detail, or in a policy and procedure. Once the CSP Cloud Service Offering (CSO) SSP receives a JAB or an Agency Authorization, then the means of coordination is accepted by the JAB/AO.

Because the Agency is using the CSO, there is an inherent responsibility for the Agency to take appropriate actions if the CSO audit records are reviewed and analyzed and there is abnormal behavior.
However, this portion of the control requires only that the security control implementation detail describes how both the CSP and the Agency coordinate reviews of the audit records at least weekly for a specific set of abnormalities that should be listed in the security control implementation detail.
### AU-6(a) Write the Control
(Verb) Describe (Adjective) weekly (Noun) process (Verb) of analysis and review (Noun) of system audit records

Then what are you searching for in this weekly process of analysis and review of the audit records? Describe how you are searching for signs of inappropriate or unusual activity.

Describe how the organization reviews and analyzes information system audit records at least weekly for indications of inappropriate or unusual activity within logging for monitoring of account usage, remote access, wireless connectivity, mobile device connection, configuration settings, system component inventory, use of maintenance tools and nonlocal maintenance, physical access, temperature and humidity, equipment delivery and removal, communications at the information system boundaries, use of mobile code, and use of VoIP.

A Security Event and Information Management (SEIM) system tool can facilitate audit record review and analysis. This, because throughout a typical CSO, there can be numerous audit records that should be correlated to manage risk in the system. A manual audit record review and analysis is cumbersome and can be flawed to the inability of a human to adequately review and analyze audit records to the extent required by CSO environments.

The process must address each of audit records, in each of the layers, of each of the service models described in AU-3.
### AU-6(a) Customer Responsibilities
This epitomizes the responsibilities for each member of the stack regarding auditing review and analysis. Each piece of the stack is responsible to itself and to the portion that leverages. The question to ponder is: if an IaaS has a vulnerability, is that vulnerability inherited by each layer? The answer is yes.

*IaaS* – For IaaS, this is Service Provider System Specific. The IaaS provides audit logging capabilities and captures events for their internal compliance. The IaaS should have at least a weekly process of analysis and review of the audit records which is a search for signs of inappropriate or unusual activity. The IaaS is responsible for coordinating the at least weekly review and analysis effort between the IaaS and the customer.

*PaaS* – For the PaaS, this is most likely Service Provider System Specific, and Configured by Customer (Customer System Specific), and Inherited from the IaaS. The PaaS then provides at least a weekly process of analysis and review of the audit records which is a search for signs of inappropriate or unusual activity for the customer. PaaS customers are responsible for reviewing and analyzing events required for PaaS compliance, and coordinating with any leveraging SaaS their review and analysis or inappropriate or unusual activity.

*SaaS* – A SaaS is responsible for weekly review and analysis for the due diligence it requires to be a SaaS. It is the responsibility of the SaaS customers to also review and analyze the health and performance of the applications they build and those to which they subscribe.

Responsibilities in weekly coordination of system anomalies and unusual behavior follow through the entire stack.
### AU-6(b) Control Requirement
Describe how the organization reports findings to [*Assignment: organization-defined personnel or roles*].

But, for both parts AU-6(a) and AU-6(b), for Low, Moderate and High systems FedRAMP requires **_“Coordination between service provider and consumer shall be documented and accepted by the JAB/AO. In multi-tenant environments, capability and means for providing review, analysis, and reporting to consumer for data pertaining to consumer shall be documented.”_**

The process must address each of audit records, in each of the layers, of each of the service models described in AU-3.
### AU-6(b) Control Objective
Part (a) of this control requires that the security control implementation detail must describe how, at least weekly, system audit records are reviewed and analyzed for inappropriate or unusual activity through coordination between the CSP and the customers. This coordination is accepted by the JAB or the AO upon acceptance of the SSP, whether this security control implementation detail describes the process or whether the process is captured in another document that is cited in the control section (a) above.

This is part (b). Once the search for inappropriate or unusual activity yields positive results (i.e., findings identified), to whom would the organization report findings? This must be defined in AU-6(b). According to the FedRAMP and NIST AU-6 Supplemental Guidance, “Findings can be reported to organizational entities that include, for example, incident response team, help desk, information security group/ department. If organizations are prohibited from reviewing and analyzing audit information or unable to conduct such activities (e.g., in certain national security applications or systems), the review/analysis may be carried out by other organizations granted such authority.”

According to the FedRAMP requirements, this must be coordinated between the CSP and the Authorizing Official.
### AU-6(b) Write the Control
(Noun) You (Verb) must describe the (noun) process by which (Noun) unusual findings in the audit review and analysis are reported and to whom these are reported.

There is no need to repeat any portions of the security control implementation detail that was given in part (a).

The process must address each of audit records, in each of the layers, of each of the service models described in AU-3.

When this control is tested, the assessor must first make a determination as to the existence of personnel or roles to which the findings are reported. If it is determined that personnel or roles exist to fulfill this requirement, the next test is to determine if the personnel or roles do accept the reported findings.
### AU-6(b) Customer Responsibilities
*IaaS* – For IaaS, this is Service Provider System Specific. The IaaS provides audit logging capabilities and captures events for their internal compliance. The IaaS should have at least a weekly process of analysis and review of the audit records which is a search for signs of inappropriate or unusual activity. The inappropriate or unusual activity is reported to one person or role. The IaaS is responsible for coordinating the at least weekly review and analysis effort between the IaaS and the customer.

*PaaS* – For the PaaS, this is most likely Service Provider System Specific, and Configured by Customer (Customer System Specific), and Inherited from the IaaS. The PaaS then provides at least a weekly process of analysis and review of the audit records which is a search for signs of inappropriate or unusual activity for the customer. The inappropriate or unusual activity is reported to personnel or roles within the PaaS. PaaS customers are responsible for reviewing and analyzing events required for PaaS compliance, and coordinating with any leveraging SaaS their review and analysis or inappropriate or unusual activity.

*SaaS* – A SaaS is responsible for weekly review and analysis for the due diligence it requires to be a SaaS. It is the responsibility of the SaaS customers to also review and analyze the health and performance of the applications they build and those to which they subscribe. The inappropriate or unusual activity is reported to personnel or roles within the SaaS.

Responsibilities in weekly coordination of system anomalies and unusual behavior follow through the entire stack.
