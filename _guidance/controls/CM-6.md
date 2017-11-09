# CM-6 Configuration Settings
## CM-6 Control Requirement
The organization:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;a.	Establishes and documents configuration settings for information technology products employed within the &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;information system using [Assignment: organization-defined security configuration checklists] that reflect the most &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;restrictive mode consistent with operational requirements;

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;b.	Implements the configuration settings;

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;c.	Identifies, documents, and approves any deviations from established configuration settings for [Assignment: &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;organization-defined information system components] based on [Assignment: organization-defined operational &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;requirements]; and

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;d.	Monitors and controls changes to the configuration settings in accordance with organizational policies and &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;procedures.
### CM-6(a) Control Requirement
Describe how the organization establishes and documents configuration settings for information technology products employed within the information system using [Assignment: organization-defined security configuration checklists] that reflect the most restrictive mode consistent with operational requirements.

FedRAMP Additional Requirements:

CM-6 (a) Requirement 1: The service provider shall use the Center for Internet Security guidelines (Level 1) to establish configuration settings or establishes its own configuration settings if USGCB is not available.

CM-6 (a) Requirement 2: The service provider shall ensure that checklists for configuration settings are Security Content Automation Protocol (SCAP) validated or SCAP compatible (if validated checklists are not available).
### CM-6(a) Control Objective
The CSP establishes and documents configuration settings for information technology products employed within the information system using checklists as follows, that reflect the most restrictive mode consistent with operational requirements:

  *	United States Government Configuration Baseline (USGCB) is the ideal. This guidance is found : Information on the USGCB checklists can be found at: http://usgcb.nist.gov/usgcb_faq.html#usgcbfaq_usgcbfdcc .
  *	However, Center for Internet Security guidelines (Level 1) can be used  to establish configuration settings or establishes its own configuration settings if USGCB is not available
  *	Checklists for these configuration settings must be Security Content Automation Protocol (SCAP) validated or SCAP compatible (if validated checklists are not available)

Additionally, FedRAMP Tailored requires that there are specific details of least functionality included in the security control implementation detail.
### CM-6(a) Write the Control
This part (a) of the control has the most parameters, additional requirements, and additional guidance that the writer must ensure are all included in the security control implementation description. 

NIST Supplemental Guidance defines parameters as, “Security-related parameters are those parameters impacting the security state of information systems including the parameters required to satisfy other security control requirements. Security-related parameters include, for example: (i) registry settings; (ii) account, file, directory permission settings; and (iii) settings for functions, ports, protocols, services, and remote connections. Organizations establish organization-wide configuration settings and subsequently derive specific settings for information systems. The established settings become part of the systems configuration baseline.”

When the part (a) security control description is populated with all the extra added security requirements, it reads as follows:

The CSP establishes and documents configuration settings for information technology products employed within the information system using checklists as follows, that reflect the most restrictive mode consistent with operational requirements:

*	United States Government Configuration Baseline (USGCB) is the ideal. This guidance is found : Information on the USGCB checklists can be found at: http://usgcb.nist.gov/usgcb_faq.html#usgcbfaq_usgcbfdcc .
  *	However, Center for Internet Security guidelines (Level 1) can be used  to establish configuration settings or establishes its own configuration settings if USGCB is not available
  * Checklists for these configuration settings must be Security Content Automation Protocol (SCAP) validated or SCAP compatible (if validated checklists are not available)

Additionally, FedRAMP Tailored requires that there are specific details of least functionality included in the security control implementation detail.

Please keep in mind that all of the parameters, requirements, and additional guidance must be addressed at each level of each service layer for which the CSP is responsible and accountable. As per NIST Supplemental Guidance, “Configuration settings are the set of parameters that can be changed in hardware, software, or firmware components of the information system that affect the security posture and/or functionality of the system. Information technology products for which security-related configuration settings can be defined include, for example, mainframe computers, servers (e.g., database, electronic mail, authentication, web, proxy, file, domain name), workstations, input/output devices (e.g., scanners, copiers, and printers), network components (e.g., firewalls, routers, gateways, voice and data switches, wireless access points, network appliances, sensors), operating systems, middleware, and applications.”

When testing this control, the 3PAO is specifically looking for the following details:

&nbsp;&nbsp;&nbsp;&nbsp;a.	Specifically defined configuration settings and security configuration checklists (i.e., USGCB, CIS) for all technology &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;products within the system security boundary

&nbsp;&nbsp;&nbsp;&nbsp;b.	These configuration settings must be provably set at the most restrictive mode consistent with operational &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;requirements with specific emphasis on “least functionality” for FedRAMP Tailored

&nbsp;&nbsp;&nbsp;&nbsp;c.	In lockstep with provability is the requirement, the configuration settings must be provably established and &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;documented configuration for all information technology products employed within the information system by using &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;SCAP validated or SCAP compatible security configuration checklists (of which USGCB and CIS are SCAP validated).

To illustrate, this means that each level of each service layer for which the CSP is responsible baseline configuration settings must be established and documented for all devices within the system boundary. In other words, what are the established and documented baseline configuration settings for all devices associated with the Application level of the SaaS? What are the established and documented baseline configuration settings for all devices associated with the Data level of the SaaS? If the SaaS is also responsible for the Platform, what are the established and documented baseline configuration settings for all devices associated with the Runtime systems level of the SaaS? What are the established and documented baseline configuration settings for all devices associated with the Middleware level of the SaaS? This exercise must be completed for each level of each layer for which the CSP is responsible.
In NIST SP 800-128, Guide for Security-Focused Configuration Management of Information Systems, the following section emphasizes planning for secure configuration settings.

As with many security activities, planning can greatly impact the success or failure of the effort. As a part of planning, the scope or applicability of SecCM processes are identified. Planning includes developing policy and procedures to incorporate SecCM into existing information technology and security programs, and then disseminating the policy throughout the organization. Policy addresses areas such as the implementation of SecCM plans, integration into existing security program plans, Configuration Control Boards (CCBs), configuration change control processes, tools and technology, the use of common secure configurations13 and baseline configurations, monitoring, and metrics for compliance with established SecCM policy and procedures. It is typically more cost-effective to develop and implement a SecCM plan, policies, procedures, and associated SecCM tools at the organizational level.


### CM-6(a) Customer Responsibility
*IaaS* – This responsibility lies with Service Provider System Specific, or possibly Service Provider Hybrid (Service Provider Corporate and Service Provider System Specific). There is no customer responsibility.

*PaaS* – This responsibility lies with Service Provider System Specific, or possibly Service Provider Hybrid (Service Provider Corporate and Service Provider System Specific). There is no customer responsibility.

*SaaS* – This responsibility lies with Service Provider System Specific, or possibly Service Provider Hybrid (Service Provider Corporate and Service Provider System Specific). There is no customer responsibility.
### CM-6(b) Control Requirement
Describe how the organization implements the configuration settings that are established and documented in CM-6(a).
### CM-6(b) Control Objective
The objective/ intent of this part (b) of this control is to fully describe how the configuration settings that are established and documented as part (a) are implemented within the system. The implementation must be described at leach level of each service layer, and must follow the listing that is set forth in part (a) of this control. For large systems it may be more visually feasible if the writer creates a matrix to capture this data and information. This matrix captures the elements of part (a) “establish and document” and part (b) explains the implementation process.
### CM-6(b) Write the Control
(Verb) Describe how the organization (Verb) implements the (Noun) configuration settings that are established and documented in CM-6(a).

This part (b) of the control requires descriptions of processes to implement the established and documented baseline configurations listed in part (a) of this control. The writer may use matrices to help with this security control implementation description. Remember to include each level of each service layer for which the CSP is responsible.

Automated mechanisms that accomplish this implementation must still be described. The writer cannot answer this part (b) of the control by saying something to the effect, “…This process is automated.” That security control implementation description is not acceptable for any control.
### CM-6(b) Customer Responsibility
*IaaS* – This responsibility lies with Service Provider System Specific, or possibly Service Provider Hybrid (Service Provider Corporate and Service Provider System Specific). There is no customer responsibility.

*PaaS* – This responsibility lies with Service Provider System Specific, or possibly Service Provider Hybrid (Service Provider Corporate and Service Provider System Specific). There is no customer responsibility.

*SaaS* – This responsibility lies with Service Provider System Specific, or possibly Service Provider Hybrid (Service Provider Corporate and Service Provider System Specific). There is no customer responsibility.
### CM-6(c) Control Requirement
Describe how the organization identifies, documents, and approves any deviations from established configuration settings for [Assignment: organization-defined information system components] based on [Assignment: organization-defined operational requirements].
### CM-6(c) Control Objective
The objective/ intent of this control is threefold – (i) identify, (ii) document, and (iii) approve deviations from the list established and documented in part (a) for which the implementation was then described for each in part (b).

Part (c) requires that the writer describe how deviations to the established, documented, implemented secure baseline configurations are (i) identified, (ii) documented, and (iii) approved.

Because secure baseline configurations are a cornerstone of security, it is paramount that the CSP have a risk management strategy that fully incorporates all aspects of this CM-6 control, for all levels of each service layer for which the CSP is responsible.
### CM-6(c) Write the Control
The requirement for this part (c) is looking for an explanation of deviations from established baselines on the component level and at the system level.

The writer must first describe the scenario by which there are specific systems components with established configuration settings for which deviations from the established configuration baseline must be (i) identified, (ii) documented, and (iii) approved.

The writer must then describe any operational requirements that support deviations from established, documented configuration settings. The description must include the identification, documentation, and approval of these deviations from established configuration settings.

The writer must then explain the process of identifying any deviations from established configuration settings for organization-defined information system components based on organizational-defined operational requirements.

The writer must then explain the process of documenting any deviations from established configuration settings for organization-defined information system components based on organizational-defined operational requirements.

The writer must then explain the process of approving any deviations from established configuration settings for organization-defined information system components based on organizational-defined operational requirements.
### CM-6(c) Customer Responsibility
*IaaS* – This responsibility lies with Service Provider System Specific, or possibly Service Provider Hybrid (Service Provider Corporate and Service Provider System Specific). There is no customer responsibility.

*PaaS* – This responsibility lies with Service Provider System Specific, or possibly Service Provider Hybrid (Service Provider Corporate and Service Provider System Specific). There is no customer responsibility.

*SaaS* – This responsibility lies with Service Provider System Specific, or possibly Service Provider Hybrid (Service Provider Corporate and Service Provider System Specific). There is no customer responsibility.
### CM-6(d) Control Requirement
Describe how the organization monitors and controls changes to the configuration settings in accordance with organizational policies and procedures.
### CM-6(d) Control Objective
The objective/ intent of this part (d) of this control is to describe how the system effectively monitors and controls the deviations from the established configuration settings in accordance with organizational policies and procedures. Many CSPs prefer to have this as an automated, centrally managed process.
### CM-6(d) Write the Control
For this part (d) of this control, the writer must describe the monitoring and controlling of the deviations to the established, documented, implemented secure baseline configurations that are (i) identified, (ii) documented, and (iii) approved at each level of each service layer for which the CSP is responsible.

Key verbs are “monitor” and “control” and the noun is “deviations”. As evidenced by parts (a), (b), (c) of this control, configuration baseline settings for all devices within the established authorization boundary must be fully documented and controlled. When the writer addresses this last part (d) of this control, special consideration must be given to the monitoring and controlling of changes/deviations to this established authorization boundary.

The writer must ensure that each level of the service layer must be addressed.

Additionally, the CSP must ensure that the monitoring and controlling of the deviations must be in accordance with the organizational policies and procedures governing the security of the system.
### CM-6(d) Customer Responsibility
*IaaS* – This responsibility lies with Service Provider System Specific, or possibly Service Provider Hybrid (Service Provider Corporate and Service Provider System Specific). There is no customer responsibility.

*PaaS* – This responsibility lies with Service Provider System Specific, or possibly Service Provider Hybrid (Service Provider Corporate and Service Provider System Specific). There is no customer responsibility.

*SaaS* – This responsibility lies with Service Provider System Specific, or possibly Service Provider Hybrid (Service Provider Corporate and Service Provider System Specific). There is no customer responsibility.

