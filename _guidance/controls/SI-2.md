# SI-2 Flaw Remediation
## SI-2 Control Requirement
The organization:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(a) Identifies, reports, and corrects information system flaws;

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(b) Tests software and firmware updates related to flaw remediation for effectiveness and potential side effects before &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;installation;

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(c)	Installs security-relevant software and firmware updates within [Assignment: organization-defined time period]
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;of the release of the updates; and

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(d) Incorporates flaw remediation into the organizational configuration management process.
### SI-2(a) Control Requirement
Describe how the organization identifies, reports, and corrects information system flaws.
### SI-2(a) Control Objective
The objective/ intent of this part (a) of this control is to ensure that the CSP does identify, report, and then correct flaws identified in the CSO. Today, there are three categories of exploits: (i) traditional hacking of the hosting network; (ii) social engineering; and (iii) manipulation of vulnerabilities.

Based on this, identifying flaws is a challenge to all organizations. But each category of exploit can be mitigated to a lower organizational risk if the CSP maintains a sound risk management strategy that integrates industry best practices for maintaining awareness of the threat environment. For identifying, reporting, and correcting flaws, FedRAMP minimally recommends that CSPs implement periodic security assessments of the CSO and then conduct continuous monitoring exercises. The CSP may choose to implement automation in the environment that provides a near real-time continuous monitoring perspective of the CSO.

The flaw remediation activities of identification, reporting, and correcting information system flaws must be described for each level and each service layer for which the CSP is responsible.

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
### SI-2(a) Write the Control
There are three specific sections to writing this security control implementation detail.

(Verb) Describe how the organization:
  * (verb) identifies,
  * (verb) reports, and
  * (verb) corrects information system flaws.

The identification and reporting of flaws should at least align with the security control implementation details provided in:
  *	CA-2 Security Assessments
  *	CA-7 Continuous Monitoring
  *	CM-3 Configuration Change Control
  *	IR-4 Incident Handling
  *	RA-5 Vulnerability Scanning
  *	SI-11 Error Handling

The correcting of information system flaws should at least align with the security control implementation details provided in:
  *	CM-5 Access Restrictions for Change
  *	CM-8 Information System Component Inventory
  *	MA-2 Controlled Maintenance
  *	SA-10 Developer Configuration Management
  *	SA-11 Developer Security Testing and Evaluation
### SI-2(a) Customer Responsibility
*IaaS* - Service Provider System Specific. There is no Customer Responsibility.

*PaaS* - Service Provider System Specific. There is no Customer Responsibility.

*SaaS* - Service Provider System Specific. There is no Customer Responsibility.
### SI-2(b) Control Requirement
Describe how the organization tests software and firmware updates related to flaw remediation for effectiveness and potential side effects before installation.
### SI-2(b) Control Objective
The objective/ intent of this control is to ensure that the CSP understands that both (i) software and (ii) firmware updates related to flaw remediation must be tested before implementation/installation, to determine the effects of the changes to the system.
### SI-2(b) Write the Control
(Verb) Describe how the organization (verb)  tests (noun) (i) software updates related to flaw remediation and (noun) (ii) firmware updates related to flaw remediation (why?) for effectiveness and potential side effects before installation.

Describe how the organization tests software updates related to flaw remediation for effectiveness and potential side effects before installation.

Describe how the organization tests firmware updates related to flaw remediation for effectiveness and potential side effects before installation.

This part (b) of this control will align with a sound configuration management capability.

The Related Controls with which this part (b) must align are:
  *	CM-3 Configuration Change Control
  *	CM-5 Access Restrictions for Change
  *	MA-2 Controlled Maintenance
  *	SA-11 Developer Security Testing and Evaluation
### SI-2(b) Customer Responsibility
*IaaS* - Service Provider System Specific. There is no Customer Responsibility.

*PaaS* - Service Provider System Specific. There is no Customer Responsibility.

*SaaS* - Service Provider System Specific. There is no Customer Responsibility.
### SI-2(c) Control Requirement
Describe how the organization installs security-relevant software and firmware updates within [Assignment: organization- defined time period] of the release of the updates.
### SI-2(c) Control Objective
The objective/ intent of this control is to ensure that the CSP understands that FedRAMP requires that security-relevant software and firmware updates are installed within 30 days of release of the update. This requirement is included in the CSO configuration management capability and in the incident handling capability. This requirement should align with the controlled maintenance and developer security testing and evaluation capability. As stated in the NIST Supplemental Guidance for this control, “Organization-defined time periods for updating security-relevant software and firmware may vary based on a variety of factors including, for example, the security category of the information system or the criticality of the update (i.e., severity of the vulnerability related to the discovered flaw)”. However, FedRAMP requires the maximum timeframe is maintained at 30 days. Ensure that the security control implementation descriptions align with the following:
  *	CM-3 Configuration Change Control
  *	IR-4 Incident Handling
  *	MA-2 Controlled Maintenance
  *	SA-11 Developer Security Testing and Evaluation
### SI-2(c) Write the Control
There are four sections that must be addressed within this part (c) security control implementation description.
  * Describe how the CSP defines the FedRAMP 30 day timeframe within which to install security-relevant software updates after the release of the updates.
  * Describe how the CSP defines the FedRAMP 30 day timeframe within which to install security-relevant firmware updates after the release of the updates.
  * Provide descriptive proof that the 30 day timeframe within which to install security-relevant software updates after the release of the updates is followed.
  * Provide descriptive proof that the 30 day timeframe within which to install security-relevant firmware updates after the release of the updates is followed.
### SI-2(c) Customer Responsibility
*IaaS* - Service Provider System Specific. There is no Customer Responsibility.

*PaaS* - Service Provider System Specific. There is no Customer Responsibility.

*SaaS* - Service Provider System Specific. There is no Customer Responsibility.
### SI-2(d) Control Requirement
Describe how the organization incorporates flaw remediation into the organizational configuration management process.
### SI-2(d) Control Objective
The objective/ intent of this control is to ensure that the CSP has incorporated FedRAMP requirements for flaw remediation into the organization configuration management process. If the organization has a sound configuration management process, there is a better chance that flaw remediation is being conducted according to the organizational risk management strategy. Ad hoc configuration management means ad hoc flaw remediation and does not support a risk management strategy because the lack of detail does not provide the required risk management consistency.
### SI-2(d) Write the Control
(Verb) Describe how the organization (verb) incorporates (noun) flaw remediation into the organizational (noun) configuration management process.

If the organization has provided security control implementation detail without alternate implementations for part (a), (b), (c), the chance is greater that the organization has incorporated flaw remediation into the organizational configuration management process.
### SI-2(d) Customer Responsibility
*IaaS* - Service Provider System Specific. There is no Customer Responsibility.

*PaaS* - Service Provider System Specific. There is no Customer Responsibility.

*SaaS* - Service Provider System Specific. There is no Customer Responsibility.
