# SI-3 Malicious Code protection
## SI-3 Control Requirement
The organization:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(a) Employs malicious code protection mechanisms at information system entry and exit points to detect and eradicate &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;malicious code;

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(b) Updates malicious code protection mechanisms whenever new releases are available in accordance with &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;organizational configuration management policy and procedures;

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(c) Configures malicious code protection mechanisms to:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(1) Perform periodic scans of the information system [Assignment: organization-defined frequency] and real-time &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;scans of files from external sources at [Selection (one or more); endpoint; network entry/exit points] as the files are &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;downloaded, opened, or executed in accordance with organizational security policy; and

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(2) [Selection (one or more): block malicious code; quarantine malicious code; send alert to administrator; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Assignment: organization-defined action]] in response to malicious code detection; and

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(d) Addresses the receipt of false positives during malicious code detection and eradication and the resulting potential &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;impact on the availability of the information system.
### SI-3(a) Control Requirement
Describe how the organization employs malicious code protection mechanisms at information system entry and exit points to detect and eradicate malicious code.
### SI-3(a) Control Objective
The objective/ intent of this control is to ensure that the CSP understands that FedRAMP requires malicious code protection mechanisms, that both detect and eradicate the malicious code, at system boundary entry and exit points.

The malicious code protection mechanisms that both detect and eradicate the malicious code at entry and exit points must be described for each level and each service layer for which the CSP is responsible.
### SI-3(a) Write the Control
(Verb) Describe how the organization (verb) implements/employs (noun) malicious code protection mechanisms at information system (noun) entry points and (noun) exit points to (verb) detect malicious code and (verb) eradicate malicious code.
### SI-3(a) Customer Responsibility
*IaaS* - Service Provider System Specific. There is no Customer Responsibility.

*PaaS* - Service Provider System Specific. There is no Customer Responsibility.

*SaaS* - Service Provider System Specific. There is no Customer Responsibility.
### SI-3(b) Control Requirement
Describe how the organization updates malicious code protection mechanisms whenever new releases are available in accordance with organizational configuration management policy and procedures.
### SI-3(b) Control objective
The objective/ intent of this control part (b) is to describe the malicious code protection mechanism update procedures when new releases of each piece of the protection mechanisms listed within the system, become available.

This part (b) of the control should align with the Part (a) of this control which also mentions the establishment of “a malicious protection software policy to ensure that preventive, detective, and corrective procedures are in place to protect the system and technologies within the system boundary.” This malicious protection software policy should be included in the organizational configuration management policy and procedures.
### SI-3(b) Write the Control
(Verb) Describe how the organization (verb) updates (noun) malicious code protection mechanisms (when?) whenever (noun) new releases are available in accordance with (noun) organizational configuration management policy and procedures.

When speaking about “updates” to “malicious code protection mechanisms” this most often refers to “malicious code protection mechanisms installed on all devices to include antivirus software that is kept current with antivirus signatures and repudiation based technologies”, as described in part (a) of this control.

Explain how this is integrated into the organizational configuration management policy and procedures.
### SI-3(b) Customer Responsibility
*IaaS* - Service Provider System Specific. There is no Customer Responsibility.

*PaaS* - Service Provider System Specific. There is no Customer Responsibility.

*SaaS* - Service Provider System Specific. There is no Customer Responsibility.
### SI-3(c) Control Requirement
Describe how the organization configures malicious code protection mechanisms to:
  * Perform periodic scans of the information system [Assignment: organization-defined frequency] and real-time scans of files from external sources at [Selection (one or more); endpoint; network entry/exit points] as the files are downloaded, opened, or executed in accordance with organizational security policy.
  * [Selection (one or more): block malicious code; quarantine malicious code; send alert to administrator; [Assignment: organization-defined action]] in response to malicious code detection.
### SI-3(c) Control Objective
The objective/ intent of this part (c ) of this control is to ensure that the CSP is aware that the FedRAMP requirements for a Low or Moderate system:
  * Describe how the organization configures malicious code protection mechanisms to perform periodic scans of the information system at least weekly and real-time scans of files from external sources at to include endpoints, as the files are downloaded, opened, or executed in accordance with organizational security policy.
  * Describe how the organization configures malicious code protection mechanisms to include alerting administrator or defined security personnel in response to malicious code detection.

The CSP must fully document that this is being accomplished and provide documented verbiage that supports this control.
### SI-3(c) Write the Control
For a Low or Moderate system:
  * (Verb) Describe how the organization (verb) configures (noun) malicious code protection mechanisms to (verb) perform (adjective) periodic (noun) scans of the information system (i) at least weekly and (ii) real-time scans of files from external sources to include endpoints, as the files are either (a)downloaded, opened, or executed in accordance with organizational security policy.
  * (Verb) Describe how the organization (verb) configures (noun) malicious code protection mechanisms to include (verb) alerting (noun) administrator or (noun) defined security personnel in response to (noun) malicious code detection.

The CSP must fully document that this is being accomplished and provide documented verbiage that supports this control.
### SI-3(c) Customer Responsibility
*IaaS* - Service Provider System Specific. There is no Customer Responsibility.

*PaaS* - Service Provider System Specific. There is no Customer Responsibility.

*SaaS* - Service Provider System Specific. There is no Customer Responsibility.
### SI-3(d) Control Requirement
Describe how the organization addresses the receipt of false positives during malicious code detection and eradication and the resulting potential impact on the availability of the information system.
### SI-3(d) Control objective
The objective/ intent of this part (d) of this control is to address “false positives” identified during malicious code detection and eradication and the resulting potential impact on the availability of the information system.

It is the responsibility of the CSP to adequately address false positive identification and evaluation to limit the unnecessary production system disruptions to a level that is acceptable to all stakeholders.
### SI-3(d) Write the Control
(Verb) Describe how the organization (verb) addresses the (noun) receipt of false positives (when) during (verb) malicious code detection.
  * (Verb) Describe the resulting (noun) potential impact on the (noun) availability of the information system.

(Verb) Describe how the organization (verb) addresses the (noun) receipt of false positives during (verb) malicious code eradication.
  * (Verb) Describe the resulting (noun) potential impact on the (noun) availability of the information system.
### SI-3(d) Customer Responsibility
*IaaS* - Service Provider System Specific. There is no Customer Responsibility.

*PaaS* - Service Provider System Specific. There is no Customer Responsibility.

*SaaS* - Service Provider System Specific. There is no Customer Responsibility.
