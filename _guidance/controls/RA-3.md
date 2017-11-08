# RA-3 Risk Assessment
## RA-3 Control Requirement
The organization:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;a.	Conducts an assessment of risk, including the likelihood and magnitude of harm, from the unauthorized access, use, disclosure,
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;disruption, modification, or destruction of the information system and the information it processes, stores, or transmits;

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;b.	Documents risk assessment results in [Selection: security plan; risk assessment report; [Assignment: organization-defined document]];

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;c.	Reviews risk assessment results [Assignment: organization-defined frequency];

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;d.	Disseminates risk assessment results to [Assignment: organization-defined personnel or roles]; and

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;e.	Updates the risk assessment [Assignment: organization-defined frequency] or whenever there are significant changes to the information
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;system or environment of operation (including the identification of new threats and vulnerabilities), or other conditions that may impact the security state of the system.
### RA-3(a) Control Requirement
Describe how the organization conducts an assessment of risk, including the likelihood and magnitude of harm, from the unauthorized access, use, disclosure, disruption, modification, or destruction of the information system and the information it processes, stores, or transmits.
### RA-3(a) Control Objective
The objective/ intent of this control is to determine if the CSP does employ an adequate risk management strategy for the CSO. The risk assessment is further defined in the NIST Supplemental Guidance:

“Risk assessments (either formal or informal) can be conducted at all three tiers in the risk management hierarchy (i.e., organization level, mission/business process level, or information system level) and at any phase in the system development life cycle. Risk assessments can also be conducted at various steps in the Risk Management Framework, including categorization, security control selection, security control implementation, security control assessment, information system authorization, and security control monitoring. RA-3 is noteworthy in that the control must be partially implemented prior to the implementation of other controls in order to complete the first two steps in the Risk Management Framework. Risk assessments can play an important role in security control selection processes, particularly during the application of tailoring guidance, which includes security control supplementation.”

Therefore, it is apparent that risk assessments are an integral item in the CSO risk management strategy. As stated above, “RA-3 (Risk Assessment) is noteworthy in that the control must be partially implemented prior to the implementation of other controls in order to complete the first two steps in the Risk Management Framework.” Thus, the RMF cannot be complete without the integration of risk assessments.

This control must also address the risk assessments that are completed at each level of each service layer for which the CSP is responsible. In hyperscale systems there may be multiple risk assessments completed in an organizational workflow just on one single vulnerability identified.

_Software as a Service (SaaS)_
  * Application level
  * Data level

_Platform as a Service (PaaS)_
  * Runtime systems
  * Middleware
  * Databases
  * Operating Systems

_Infrastructure as a Service (IaaS)_
  * Virtualization
  * Servers
  * Storage
  * Networking
  * Datacenters
### RA-3(a) Write the Control
(Verb) Describe how the organization (verb) conducts an (noun) assessment of risk.

All of the following elements must be discussed as these pertain to the:

a.	Cloud Service Offering; and

b.	Information that the CSO processes/stores/transmits.

The assessment of risk must include the:

(I)	likelihood of the exploitation of the risk; and

(II)	magnitude of harm to the system if the exploitation is successful (worst case scenario)

From the differing ways that the exploitation may occur to include:

a.	Unauthorized access,

b.	Unauthorized use,

c.	Unauthorized disclosure,

d.	Unauthorized disruption,

e.  Unauthorized modification, and / or

f.	Unauthorized destruction of the information system and the information it:
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.	Processes,
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.	Stores, and / or
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3.	Transmits.

This control must address how the organization conducts a risk assessment at each level of each service layer for which it is responsible.  
### RA-3(a) Customer Responsibility
*IaaS* - Service Provider System Specific. There is no Customer Responsibility.

*PaaS* - Service Provider System Specific. There is no Customer Responsibility.

*SaaS* - Service Provider System Specific. There is no Customer Responsibility.
### RA-3(b) Control Requirement
Describe how the organization documents risk assessment results in [Selection: security plan; risk assessment report; [Assignment: organization-defined document]].
### RA-3(b) Control Objective
The objective of this part (b) of this control is to ensure that the risk assessments described in part (a) are captured in the security assessment report.

In more complex systems the risk assessment is automatically included in an internal work flow to ensure proper documentation of the risk assessment by all parties involved and the ultimate sign off by a responsible party of the outcome of the risk assessment.

For FedRAMP, the security assessment report (SAR) is the ultimate documentation of risk because the SAR is used for the initial and annual assessments, and for the risk assessment conducted on changes to the system. If the CSP wishes to make a change to the system, a Significant Change form must be submitted to FedRAMP. If FedRAMP accepts the request for the change, the CSP must conduct a risk impact (risk assessment) analysis of the change to the security status of the system. The results of the analysis are captured in a SAR specific to that change and associated risk assessment. Once the change is implemented, the change is integrated in the SSP.
### RA-3(b) Write the Control
(Verb) Describe how the (Noun) risk assessments described in part (a) are captured in the (noun) SAR. Be sure to include all ways that risk is assessed within the CSO and how the results are captured and reported.
### RA-3(b) Customer Responsibility
*IaaS* - Service Provider System Specific. There is no Customer Responsibility.

*PaaS* - Service Provider System Specific. There is no Customer Responsibility.

*SaaS* - Service Provider System Specific. There is no Customer Responsibility.
### RA-3(c) Control Requirement
Describe how the organization reviews risk assessment results [Assignment: organization-defined frequency].
### RA-3(c) Control Objective
The objective/ intent of this control part (c ) is to ensure that the CSP reviews the results of the risk assessments conducted on the CSO.
### RA-3(c) Write the Control
(Verb) Describe how the (noun) CSP reviews the (noun) results of the risk assessments conducted on the CSO.
### RA-3(c) Customer Responsibility
*IaaS* - Service Provider System Specific. There is no Customer Responsibility.

*PaaS* - Service Provider System Specific. There is no Customer Responsibility.

*SaaS* - Service Provider System Specific. There is no Customer Responsibility.
### RA-3(d) Control Requirement
Describe how the organization disseminates risk assessment results to [Assignment: organization-defined personnel or roles].
### RA-3(d) Control Objective
The objective/ intent of this part (d) of this control is to ensure that the CSP is aware that all stakeholders must receive and must be situationally aware of risk assessment results. The security control implementation description must include narrative regarding how the risk assessment results are distributed to organization defined personnel or roles and to all Authorizing Officials and FedRAMP ISSOs.

The objective is to ensure that the CSP is aware that all stakeholders must receive and must be situationally aware of risk assessment results.
### RA-3(d) Write the Control
(Verb) Describe how the (noun) risk assessment results are (verb) distributed to (noun) organization-defined personnel or roles and to (noun) all Authorizing Officials and (noun) FedRAMP ISSOs.

Describe how this distribution is effected and can be proven.
### RA-3(d) Customer Responsibility
*IaaS* - Service Provider System Specific. There is no Customer Responsibility.

*PaaS* - Service Provider System Specific. There is no Customer Responsibility.

*SaaS* - Service Provider System Specific. There is no Customer Responsibility.
### Ra-3(e) Control Requirement
Describe how the organization updates the risk assessment [Assignment: organization-defined frequency] or whenever there are significant changes to the information system or environment of operation (including the identification of new threats and vulnerabilities), or other conditions that may impact the security state of the system.
### RA-3(e) Control Objective
The objective/ intent for this part (e ) of this control is to ensure that the system risk posture remains current. This ensures that the risk management strategy for the system remains stable.

The CSP must describe how the organization updates the risk assessment at least annually for High systems; at least every 3 years for low/Moderate system and/or whenever there are significant changes to the information system or environment of operation (including the identification of new threats and vulnerabilities), or other conditions that may impact the security state of the system.

The risk management strategy for the system may not vary depending upon the service layer for which the CSP is responsible. However, if the risk management strategy does vary, be sure to describe the variances in the security control implementation detail.
### RA-3(e) Write the Control
The security control implementation description must be written to address the FedRAMP requirements, the significant change requirements, and the system specific requirements.

(Verb) Describe how the organization (verb) updates the (noun) risk assessment (when?)

(i)	at least annually for High systems or at least every 3 years for Low/Moderate systems and/or

(ii)	whenever there are significant changes to the information system or environment of operation (including the identification of new threats and vulnerabilities), or

(iii)	other conditions that may impact the security state of the system.

The other conditions that may impact the security state of the system must be described as specific to the CSO.
### RA-3(e) Customer Responsibility
*IaaS* - Service Provider System Specific. There is no Customer Responsibility.

*PaaS* - Service Provider System Specific. There is no Customer Responsibility.

*SaaS* - Service Provider System Specific. There is no Customer Responsibility.
