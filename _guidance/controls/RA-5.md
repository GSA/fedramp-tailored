# RA-5 Vulnerability Scanning
## RA-5 Control Requirement
The organization:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;a.	Scans for vulnerabilities in the information system and hosted applications [Assignment: organization-defined &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;frequency and/or randomly in accordance with organization-defined process] and when new vulnerabilities potentially &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;affecting the system/applications are identified and reported;

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;b.	Employs vulnerability scanning tools and techniques that facilitate interoperability among tools and automate parts of &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;the vulnerability management process by using standards for:

1.	Enumerating platforms, software flaws, and improper configurations;
2.	Formatting checklists and test procedures; and
3.	Measuring vulnerability impact;

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;c.	Analyzes vulnerability scan reports and results from security control assessments;

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;d.	Remediates legitimate vulnerabilities [Assignment: organization-defined response times] in accordance with an &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;organizational assessment of risk; and

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;e.	Shares information obtained from the vulnerability scanning process and security control assessments with &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Assignment: organization-defined personnel or roles] to help eliminate similar vulnerabilities in other information systems &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(i.e., systemic weaknesses or deficiencies).
### RA-5(a) Control Requirement
Describe how the organization scans for vulnerabilities in the information system and hosted applications [Assignment: organization-defined frequency and/or randomly in accordance with organization-defined process] and when new vulnerabilities potentially affecting the system/applications are identified and reported.
### RA-5(a) Control Objective
The objective/ intent of this control involves addressing three specific aspects of Cloud Service Offering (CSO) vulnerability scanning. The first aspect (1) is to ensure that the CSP is completing vulnerability scanning at least to the FedRAMP defined frequency of monthly scanning for operating system/infrastructure; web applications and databases. The second requirement also involves frequency of scanning and (2) further mandates that the CSP will implement scanning efforts when new vulnerabilities potentially affecting the system/applications are identified and reported. The third aspect addresses the 3PAO scanning frequency and that the (3) CSP must also be cognizant of the 3PAO annual scanning requirement. All three of these aspects must be addressed for the control to be answered appropriately.

This control must address the vulnerability scanning requirements as these pertain at each level of each service layer for which the CSP is responsible. In hyperscale systems there may be multiple levels of vulnerability scanning that feed an incident response workflow capability. This means that vulnerabilities identified go through a triage and are viewed as an incident based upon impact to the risk posture of the system.

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
### RA-5(a) Write the Control
(Verb) Describe how the (noun) frequencies are defined for each of the (noun) three aspects that follow; and then how the CSP can (verb) provide (noun) positive proof that the scanning frequencies are being followed.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;a.	The CSP must address the first aspect which is to ensure that the CSP is completing vulnerability scanning at least to &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;the FedRAMP defined frequency of monthly scanning for operating system/infrastructure; web applications and &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;databases.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;b.	The second requirement also involves frequency of scanning and further mandates that the CSP will implement &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;scanning efforts when new vulnerabilities potentially affecting the system/applications are identified and reported.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;c.	The third aspect addresses the 3PAO scanning frequency and that the CSP must also be cognizant of the 3PAO annual &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;scanning requirement and how that frequency and effort is accomplished.
### RA-5(a) Customer Responsibility
*IaaS* - Service Provider System Specific. There is no Customer Responsibility.

*PaaS* - Service Provider System Specific. There is no Customer Responsibility.

*SaaS* - Service Provider System Specific. There is no Customer Responsibility.
### RA-5(b) Control Requirement
Describe how the organization employs vulnerability scanning tools and techniques that facilitate interoperability among tools and automate parts of the vulnerability management process by using standards for:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;a.	Enumerating platforms, software flaws, and improper configurations;

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;b.	Formatting checklists and test procedures; and

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;c.	Measuring vulnerability impact.
### RA-5(b) Control Objective
The objective/ intent of this control is to ensure that the CSP understands the efficiency gained by facilitating scanning tools interoperability and automation of the vulnerability management process. The internal and external threat environment never abates and grows daily. Unless the CSO is very small with a very small user base, the CSP is at a disadvantage if trying to manage the CSO risk posture manually and with tools that are not interoperable. It would take an exorbitant amount of resources to correlate findings and make a determination as to the risk posed to the system.
### RA-5(b) Write the Control
(Verb) Describe (Noun) three specific aspects of the CSO vulnerability scanning effort for Operating Systems (OS)/infrastructure, web applications, and databases, at a minimum. If the CSP goes beyond this minimal scanning requirement, please explain the details.

a.	How does the CSP facilitate interoperability among tools and automate parts of the vulnerability management process by using standards for:
  * enumerating platforms;
  *	enumerating software flaws; and
  *	enumerating improper configurations?

b.	How does the CSP facilitate interoperability among tools and automate parts of the vulnerability management process by using standards for:
  * formatting checklists; and
  * formatting test procedures?

c.	How does the CSP facilitate interoperability among tools and automate parts of the vulnerability management process by using standards for:
  *	measuring vulnerability impact?
### RA-5(b) Customer Responsibility
*IaaS* - Service Provider System Specific. There is no Customer Responsibility.

*PaaS* - Service Provider System Specific. There is no Customer Responsibility.

*SaaS* - Service Provider System Specific. There is no Customer Responsibility.
### RA-5(c) Control Requirement
Describe how the organization analyzes vulnerability scan reports and results from security control assessments.
### RA-5(c) Control Objective
The objective/ intent of this control is to ensure through the description provided, that the CSP does analyze both the (i) vulnerability scan reports and (ii) results from security control assessments.
### RA-5(c) Write the Control
(Verb) Describe how the organization (verb) analyzes (noun) vulnerability scan reports and (verb) analyzes (noun) results from security control assessments.

Be sure to describe both the vulnerability scan reports and the results from security control assessments.
### RA-5(c) Customer Responsibility
*IaaS* - Service Provider System Specific. There is no Customer Responsibility.

*PaaS* - Service Provider System Specific. There is no Customer Responsibility.

*SaaS* - Service Provider System Specific. There is no Customer Responsibility.
### RA-5(d) Control Requirement
Describe how the organization remediates legitimate vulnerabilities [Assignment: organization-defined response times] in accordance with (IAW) an organizational assessment of risk.
### RA-5(d) Control Objective
The objective/ intent of this control is to ensure that the CSP does remediate/mitigate identified vulnerabilities within the FedRAMP defined timeframes of 30 days for High and 90 days for Moderate vulnerabilities and deficiencies. The most efficient way to ensure this is to ensure that risk mitigation strategies are developed and followed throughout the CSO and inherently throughout the CSO corporate environment since security is a mindset/culture and not a setting on a device.

Within any FedRAMP CSO, FedRAMP engenders a “security mindset.” Therefore, vulnerabilities must be remediated / mitigated in specified timeframes which are IAW an organizational assessment of risk. The organizational assessment of risk is maintained through CA-7 Continuous Monitoring; ongoing CM-4 Security Impact Analysis of changes to the system that affect CM-6 the security Configuration Settings of the system; CA-2 formal and informal Security Assessments.
### RA-5(d) Write the Control
(Verb) Describe how the organization (verb) remediates or mitigates (noun) legitimate high-risk vulnerabilities within thirty (30) days from date of discovery; (noun) moderate-risk vulnerabilities (when?) within ninety (90) days from date of discovery (why) in accordance with (IAW) an organizational assessment of risk.

In order to adequately define this security control implementation detail, the writer must describe the response times as being defined and at least FedRAMP compliant (30 days High, 90 days Moderate). The remediation / mitigation response times can be more stringent than the FedRAMP defined parameters. Also, the description must explain how the determination for the timeframes aligns IAW the organizational assessment of risk.

Once the definitions for the response timeframes are established, the description must provide detail as to how the response times are proven to be followed. Then explain how this aligns with the organization acceptance of risk.
### RA-5(d) Customer Responsibility
*IaaS* - Service Provider System Specific. There is no Customer Responsibility.

*PaaS* - Service Provider System Specific. There is no Customer Responsibility.

*SaaS* - Service Provider System Specific. There is no Customer Responsibility.
### RA-5(e) Control Requirement
Describe how the organization shares information obtained from the vulnerability scanning process and security control assessments with [Assignment: organization-defined personnel or roles] to help eliminate similar vulnerabilities in other information systems (i.e., systemic weaknesses or deficiencies).
### RA-5(e) Control Objective
The objective/ intent of this control is to define the FedRAMP-required personnel or roles with whom information obtained from the (i) vulnerability scanning process and (ii) security control assessments is to be shared, and to provide assurance that the information is actually shared as stated.
### RA-5(e) Write the Control
(Verb) Describe how the organization (verb) shares (noun) information obtained from the (noun) vulnerability scanning process and (noun) security control assessments to include the (noun) Risk Executive and for JAB authorizations to include (noun) FedRAMP (why?) to help eliminate similar vulnerabilities in other information systems (i.e., systemic weaknesses or deficiencies).

The writer of this control must make it clear that the Risk Executive function and FedRAMP are defined as recipients of the residual risk posture from the vulnerability scanning process and security control assessments.

Then, provide a description that gives proof that the Risk Executive and FedRAMP are the recipients of the residual risk posture from the vulnerability scanning process and security control assessments.
### RA-5(e) Customer Responsibility
*IaaS* - Service Provider System Specific. There is no Customer Responsibility.

*PaaS* - Service Provider System Specific. There is no Customer Responsibility.

*SaaS* - Service Provider System Specific. There is no Customer Responsibility.
