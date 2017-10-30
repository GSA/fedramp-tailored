# CA-6 Security Authorization
## CA-6 Control Requirement
The organization:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(a)	Assigns a senior-level executive or manager as the authorizing official for the information system;

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(b)	Ensures that the authorizing official authorizes the information system for processing before commencing &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;operations; and

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(c)	Updates the security authorization [*FedRAMP Assignment: at least every three years or when a significant &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;change occurs*].

**CA-6c Additional FedRAMP Requirements and Guidance:** Significant change is defined in NIST Special Publication 800-37 Revision 1, Appendix F.  The service provider describes the types of changes to the information system or the environment of operations that would impact the risk posture.  The types of changes are approved and accepted by the Authorizing Official.
### CA-6(a) Control Requirement
Describe how the organization assigns a senior-level executive or manager as the authorizing official for the information system.
### CA-6(a) Control Objective
The objective/ intent of part (a) of this control is to ensure that the CSP has an assigned authorizing official for the Cloud Service Offering (CSO). It is not necessary to name the individual but there must be an associated role and responsibility. This role and responsibility must also align with SSP table 9-2 User Roles and Privileges. As evidenced by the NIST and FedRAMP guidance which is based on the NIST SP 800-53 Revision 4, there is still great emphasis placed on “The security authorization process is an inherently federal responsibility and therefore, authorizing officials must be federal employees”.  This part of the guidance regarding federal authorizing officials applies when the Agency partners with the CSP and the Agency must complete the Agency ATO.

For the CSO level, the CSP must define the CSP senior-level executive or manager as the authorizing official for the information system. This individual must be chosen from the group of “senior organizational officials or executives (i.e., authorizing officials) to authorize operation of information systems and to explicitly accept the risk to organizational operations and assets, individuals, other organizations, and the Nation based on the implementation of agreed-upon security controls. Authorizing officials provide budgetary oversight for organizational information systems or assume responsibility for the mission/business operations supported by those systems.”

Please consider each level of the CSO layer to determine if your organization has a tiered approach or if there is one singular AO.
### CA-6(a) Write the Control
This control applies to every CSP CSO.

(Verb) Describe (What?) how the organization (Verb) assigns a (Noun) senior-level executive or manager as the authorizing official for the information system.

This requirement is a description of how the organization defined the CSO AO assignation to a senior executive or manager. There is no need to name the individual but there must be an associated role and responsibility. This role and responsibility must also align with SSP table 9-2 User Roles and Privileges.
### CA-6(a) Customer Responsibilities
*IaaS* – Service Provider System Specific. It is the responsibility of the IaaS to assign a senior-level executive or manager as the authorizing official for the information system. There is no customer responsibility.

*PaaS* – Service Provider System Specific. It is the responsibility of the PaaS to assign a senior-level executive or manager as the authorizing official for the information system. There is no customer responsibility.

*SaaS* – Service Provider System Specific. It is the responsibility of the SaaS to assign a senior-level executive or manager as the authorizing official for the information system. There is no customer responsibility
### CA-6(b) Control Requirement
Describe how the organization ensures that the authorizing official authorizes the information system for processing before commencing operations.
### CA-6(b) Control Objective
The intent of this part (b) of this control is to provide a description of how the AO authorizes the system for processing before commencing operations. Once the CSP has agreed that the CSO is to be FedRAMP compliant, the federal government relies on the discretion of the CSO AO to ensure that the system is not processing Government data and information before the system is authorized.

The same is true for all partnering Agencies and the associated AO for the Agency aspect of the system. There is traceability and accountability at each point of partnering.

Through the FedRAMP security authorization process, CSO AOs and Agency AOs assume responsibility and are accountable for security risks associated with the operation and use of organizational information systems.
### CA-6(b) Write the Control
(Verb) Describe (What?) how the organization (Verb) ensures that (Who?) the AO (Verb) authorizes (Noun) the information system for processing (When?) BEFORE commencing operations

This part (b) of this control requires a description regarding how the organization ensures that the CSO AO authorizes the information system for processing before commencing operations and partnering with Agencies.
### CA-6(b) Customer Responsibilities
*IaaS* – Service Provider System Specific. It is the responsibility of the IaaS to ensure that the authorizing official authorizes the information system for processing before commencing operations. There is no customer responsibility.

*PaaS* – Service Provider System Specific. It is the responsibility of the PaaS to ensure that the authorizing official authorizes the information system for processing before commencing operations. There is no customer responsibility.

*SaaS* – Service Provider System Specific. It is the responsibility of the SaaS to ensure that the authorizing official authorizes the information system for processing before commencing operations. There is no customer responsibility.
### CA-6(c) Control Requirement
Describe how the organization updates the security authorization **_at least every three (3) years or when a significant change occurs. Significant change is defined in NIST Special Publication 800-37 Revision 1, Appendix F. The service provider describes the types of changes to the information system or the environment of operations that would impact the risk posture. The types of changes are approved and accepted by the Authorizing Official._**

There is a FedRAMP specific parameter for this control.

CA-6 (c) [at least every three (3) years or when a significant change occurs]
There is additional FedRAMP guidance for this control.

CA-6c Guidance: Significant change is defined in NIST Special Publication 800-37 Revision 1, Appendix F. The service provider describes the types of changes to the information system or the environment of operations that would impact the risk posture.

The types of changes are approved and accepted by the Authorizing Official.
### CA-6(c) Control Objective
The objective/ intent of this control is to provide a description of how the CSP ensures that the CSO updates the security authorization for the CSO at least every three (3) years or when there is a significant change to the system. Further, the description must specifically refer to what a significant change is for the system; how the determination of a significant change is made (through a workflow or Change Control Board?); and does the change affect the risk posture of the CSO. Finally, the description must provide detail as to how the significant changes are approved and accepted by the JAB/AO.

A CSO has an inherent responsibility to maintain an agreed upon security posture that may be disrupted by a significant change. Please keep in mind that a significant change to a system also affects other leveraging systems. Therefore it is imperative that organizational decisions for significant changes must take into consideration how the change affects the security and risk posture of the leveraging systems.
### CA-6(c) Write the Control
There are several aspects of this part (c) of this control that must be described in the security control implementation description.

(i)	Describe how the CSP updates the security authorization documentation at least every three years or when a significant change occurs.

Several aspects must be captured in this description regarding updating the security authorization documentation. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;a.	How did the CSP arrive at the policy which defines updating the security authorization documentation at least &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;every three years or when a significant change occurs? Please describe.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;b.	What security authorization documentation is updated? The SSP, SAP, SAR, related POAMs, related policies &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;and procedures? Please describe.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;c.	Describe the policy and/or procedures in place that force the security authorization update every 3 years or &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;when there is a significant change.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;d.	Describe the CSP definition of a significant change that impacts the risk posture of the CSO.

Here is the definition of a **_significant change_** according to NIST SP 800-37 Revision 1, Appendix F:

**_“A significant change is defined as a change that is likely to affect the security state of an information system. Significant changes to an information system may include for example: (i) installation of a new or upgraded operating system, middleware component, or application; (ii) modifications to system ports, protocols, or services; (iii) installation of a new or upgraded hardware platform; (iv) modifications to cryptographic modules or services; or (v) modifications to security controls. Examples of significant changes to the environment of operation may include for example: (i) moving to a new facility; (ii) adding new core missions or business functions; (iii) acquiring specific and credible threat information that the organization is being targeted by a threat source; or (iv) establishing new/modified laws, directives, policies, or regulations.” Keep in mind that these listed examples are, “only significant when they meet the threshold established in the definition of significant change (i.e., a change that is likely to affect the security state of the information system).”
(ii)	Describe the process by which the significant changes, i.e., the changes to the information system or the environment of operations that would impact the risk posture are approved and accepted by the JAB/AO._**
### CA-6(c) Customer Responsibilities
*IaaS* – Service Provider System Specific. It is the responsibility of the IaaS to update the security authorization documentation at least every three years or when a significant change occurs. There is no customer responsibility.

*PaaS* – Service Provider System Specific. It is the responsibility of the PaaS to update the security authorization documentation at least every three years or when a significant change occurs. There is no customer responsibility.

*SaaS* – Service Provider System Specific. It is the responsibility of the SaaS to update the security authorization documentation at least every three years or when a significant change occurs. There is no customer responsibility.
