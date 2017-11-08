# SI-4 Information Systems Monitoring
## SI-4 Control Requirement
The organization:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(a)	Monitors the information system to detect:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(1) Attacks and indicators of potential attacks in accordance with [Assignment: organization-
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;defined monitoring objectives]; and

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(2)	Unauthorized local, network, and remote connections;

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(b)	Identifies unauthorized use of the information system through [Assignment: organization-
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;defined techniques and methods];

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(c)	Deploys monitoring devices:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(1)	Strategically within the information system to collect organization-determined essential
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;information; and

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.	At ad hoc locations within the system to track specific types of transactions of interest to the
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;organization;

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(d)	Protects information obtained from intrusion-monitoring tools from unauthorized access, modification, and deletion;

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(e)	Heightens the level of information system monitoring activity whenever there is an indication of increased risk to
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;organizational operations and assets, individuals, other organizations, or the Nation based on law
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;enforcement information, intelligence information, or other credible sources of information;

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(f)	Obtains legal opinion with regard to information system monitoring activities in accordance with
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;applicable federal laws, Executive Orders, directives, policies, or regulations; and

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(g)	Provides [Assignment: organization-defined information system monitoring information] to
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Assignment: organization-defined personnel or roles] [Selection (one or more): as needed;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Assignment: organization-defined frequency]].
### SI-4(a) Control Requirement
Describe how the organization monitors the information system to detect:
  * Attacks and indicators of potential attacks in accordance with [Assignment: organization- defined monitoring objectives]; and
  * Unauthorized local, network, and remote connections.
### SI-4(a) Control Objective
The objective/ intent of this part (a) of this control is to ensure that the CSP is monitoring the CSO to:

Detect attacks using (a)	Intrusion detection systems (IDSs) alert to attack potential in network traffic. (b) Intrusion prevention systems (IPSs) prevent attacks in network traffic.
  * According to US CERT Incident Response Reporting Guidelines, The Location of Observed Activity (where the observed activity was detected in the network) must be captured.
  * Detect indicators of potential attacks using IDSs
  * US CERT Incident Reporting Guidelines states that the CSP and /or the Agency must provide any indicators of compromise, including signatures or detection measures developed in relationship to the incident.

Detect unauthorized (a) local, (b) network, and (c)remote connections to the CSO - Monitoring networks must also include parameters that alert on unauthorized local, network, and remote connections to the CSO.
  * A local connection is any connection with a device communicating without the use of a network. Local access is any access to organizational information systems by users (or processes acting on behalf of users) where such access is obtained by direct connections without the use of networks.
  * A network connection is any connection with a device that communicates through a network (e.g., local area or wide area network, Internet). Network access is access to organizational information systems by users (or processes acting on behalf of users) where such access is obtained through network connections (i.e., nonlocal accesses). Remote access is a type of network access that involves communication through external networks (e.g., the Internet).
  * A remote connection is any connection with a device communicating through an external network (e.g., the Internet). As per AC-17 Remote Access, the use of encrypted VPNs does not make the access non-remote; however, the use of VPNs, when adequately provisioned with appropriate security controls (e.g., employing appropriate encryption techniques for confidentiality and integrity protection) may provide sufficient assurance to the organization that it can effectively treat such connections as internal networks.
  * Local, network, and remote connections can be either wired or wireless.

The CSP monitoring to detect attacks, detect potential attacks, and monitor networks must also include parameters that alert on unauthorized local, network, and remote connections and must be described for each level and each service layer for which the CSP is responsible.

_Software as a Service (SaaS)_
  * Application level
  * Data level

_Platform as a Service (PaaS)_
  * Runtime systems level
  * Middleware level
  * Databases level
  * Operating Systems level

_Infrastructure as a Service (IaaS)_
  * Virtualization level
  * Servers level
  * Storage level
  * Networking Level
  * Datacenters level

### SI-4(a) Write the Control
(Verb)Describe how the CSP is (verb) defines the following objectives then (verb) monitors the CSO to align with the objectives defined.

  * (i)	Define the objective and then how the monitoring is accomplished to detect attacks
  * (ii)	Define the objective and then how the monitoring is accomplished to detect indicators of potential attacks
  * (iii)	Define the objective and then how the monitoring is accomplished to detect unauthorized (a) local, (b) network, and (c) remote connections to the CSO. Monitoring networks must also include parameters that alert on unauthorized local, network, and remote connections to the CSO.

### SI-4(a) Customer Responsibilities
*IaaS* - Service Provider System Specific. There is no Customer Responsibility.

*PaaS* - Service Provider System Specific. There is no Customer Responsibility.

*SaaS* - Service Provider System Specific. There is no Customer Responsibility.
### SI-4(b) Control Requirement
Describe how the organization identifies unauthorized use of the information system through [Assignment: organization- defined techniques and methods].
### SI-4(b) Control Objective
The objective/ intent of this part (b) of this control is to ensure that the CSP defines then identifies techniques and methods to identify unauthorized use of the CSO.
### SI-4(b) Write the Control
(Verb) Describe with enough detail to ensure that the CSP (i) defines then (ii) identifies techniques and methods to identify unauthorized use of the CSO.
(i)	Define techniques to identify unauthorized use of the CSO.
(ii)	Define methods to identify unauthorized use of the CSO.
(iii)	Identify techniques to identify unauthorized use of the CSO.
(iv)	Identify methods to identify unauthorized use of the CSO.
### SI-4(b) Customer Responsibilities
*IaaS* - Service Provider System Specific. There is no Customer Responsibility.

*PaaS* - Service Provider System Specific. There is no Customer Responsibility.

*SaaS* - Service Provider System Specific. There is no Customer Responsibility.
### SI-4(c) Control Requirement
Describe how the organization deploys monitoring devices:
	* Strategically within the information system to collect organization-determined essential information; and
  * At ad hoc locations within the system to track specific types of transactions of interest to the organization.
### SI-4(c) Control Objective
The objective/ intent of this control is ensuring that the CSP does strategically deploy monitoring devices within the CSO authorization boundary for organization-determined essential information, and at various system locations to track specific transaction types.

This control part (c) must align with SC-7 Boundary Protection. SC-7 ensures that the system environment is comprised of a set of managed interfaces consisting of boundary protection devices arranged in accordance with organizational security architecture. Managed interfaces include, for example, gateways, routers, firewalls, guards, network-based malicious code analysis and virtualization systems, or encrypted tunnels implemented within a security architecture (e.g., routers protecting firewalls or application gateways residing on protected subnetworks).
### SI-4(c) Write the Control
(Verb) Describe how the organization (verb) deploys (noun) monitoring devices:

(i)	(noun) strategical locations within the information system to (verb) collect organization-determined (noun) essential information; and

(ii)	at (noun) ad hoc locations within the system to track (noun) specific types of transactions of interest to the organization.

This control part (c ) must reflect a description on how the CSP determined where to place/deploy the monitoring nodes within the CSO. There must be a reference to analysis of the system and the system boundary that indicates
  * Strategic locations within the system to collect essential information
  * Ad hoc locations within the system to track specific types of transactions
### SI-4(c) Customer Responsibilities
*IaaS* - Service Provider System Specific. There is no Customer Responsibility.

*PaaS* - Service Provider System Specific. There is no Customer Responsibility.

*SaaS* - Service Provider System Specific. There is no Customer Responsibility.
### SI-4(d) Control Requirement
Describe how the organization protects information obtained from intrusion-monitoring tools from unauthorized access, modification, and deletion.
### SI-4(d) Control Objective
The objective/ intent of this part (d) of this control is to ensure that the CSP understands that the information from the intrusion detection /intrusion prevention tools has to be protected from unauthorized access, modification, and deletion. A common error in understanding for this part (d) of the control is that this is for protecting information from the tools and not protecting the tools themselves.
### SI-4(d) Write the Control
(Verb) Describe how the organization (verb) protects (noun) information obtained from intrusion-monitoring tools from (i) unauthorized access, (ii) unauthorized modification, and (iii) unauthorized deletion.

(i)	Describe how the information obtained from the intrusion detection /intrusion prevention tools is protected from unauthorized access.

(ii)	Describe how the information obtained from the intrusion detection /intrusion prevention tools is protected from unauthorized modification.

(iii)	Describe how the information obtained from the intrusion detection /intrusion prevention tools is protected from unauthorized deletion.
### SI-4(d) Customer Responsibilities
*IaaS* - Service Provider System Specific. There is no Customer Responsibility.

*PaaS* - Service Provider System Specific. There is no Customer Responsibility.

*SaaS* - Service Provider System Specific. There is no Customer Responsibility.
### SI-4(e) Control Requirement
Describe how the organization heightens the level of information system monitoring activity whenever there is an indication of increased risk to organizational operations and assets, individuals, other organizations, or the Nation based on law enforcement information, intelligence information, or other credible sources of information.
### SI-4(e) Control Objectives
The objective/ intent of this part (e) of this control is to ensure that the CSP is aware that the level of information system monitoring must be heightened whenever there is an indication of increased risk to organizational operations and assets, individuals, other organizations, or the Nation based on law enforcement information, intelligence information, or other credible sources of information.

Organizational risk management strategy is based on key risk indicators and the responses to these indicators. The risk management framework involves identifying particular events or circumstances relevant to the organization's objectives (risks and opportunities), assessing risks and opportunities in terms of likelihood and magnitude of impact, determining a response strategy, and monitoring progress. By identifying and proactively addressing risks and opportunities, business enterprises protect and create value for their entire set of stakeholders.

Key risk indicators show the risk associated with an activity. The key risk indicators are the possibility of future adverse impact to a system in the form of metrics that provide an early signal of increasing risk exposure in various areas of the organization.

Each key risk indicator has a threshold and a trigger with associated notification methods, recipients, and action sequences. If a key risk indicator is triggered, this is a warning sign that information system monitoring may need to be heightened especially in a particular area of the organization or maybe throughout the entire organization.
### SI-4(e) Write the Control
(Verb) Describe how the organization (verb) elevates/heightens the (noun) level of information system monitoring activity (when?) whenever there is an indication of increased risk to organizational operations and assets, individuals, other organizations, or the Nation based on law enforcement information, intelligence information, or other credible sources of information.

This CSO monitoring escalation is based upon the organizational risk management strategy and key risk indicators.

US-CERT Federal Incident Notification Guidelines provides guidance for Major Incidents, “FISMA requires the Office of Management and Budget (OMB) to define a major incident and directs agencies to report major incidents to Congress within 7 days of identification. Agencies should comply with the criteria set out in the most recent OMB guidance when determining whether an incident should be designated as major.”
### SI-4(e) Customer Responsibility
*IaaS* - Service Provider System Specific. There is no Customer Responsibility.

*PaaS* - Service Provider System Specific. There is no Customer Responsibility.

*SaaS* - Service Provider System Specific. There is no Customer Responsibility.
### SI-4(f) Control Requirement
Describe how the organization obtains legal opinion with regard to information system monitoring activities in accordance with applicable federal laws, Executive Orders, directives, policies, or regulations.
### SI-4(f) Control Objective
The objective/ intent of this part (f) is to ensure that the CSP understands that all system monitoring activities must be accomplished in accordance with the law, Executive Orders, directives, policies, or regulations. This because the CSO is processing, storing , transmitting or providing federal data in use to federal personnel and individuals acting on behalf of the Federal government.
### SI-4(f) Write the Control
(Verb) Describe how the CSP (verb) obtains (noun) legal opinion with regard to information system monitoring activities (why?) in accordance with applicable federal laws, Executive Orders, directives, policies, or regulations.

Because the CSP is storing processing, transmitting and/or providing access to federal data-in-use, legal opinion must be sought to ensure that the monitoring is conducted appropriately and IAW applicable federal laws, Executive Orders, directives, policies, or regulations.
### SI-4(f) Customer Responsibility
*IaaS* - Service Provider System Specific. There is no Customer Responsibility.

*PaaS* - Service Provider System Specific. There is no Customer Responsibility.

*SaaS* - Service Provider System Specific. There is no Customer Responsibility.
### SI-4(g) Control Requirement
Describe how the organization provides [Assignment: organization-defined information system monitoring information] to [Assignment: organization-defined personnel or roles] [Selection (one or more): as needed; [Assignment: organization-defined frequency]].
### SI-4(g) Control Objective
The objective/ intent of this part (g) of this control is to ensure that the organization provides organization-defined information system monitoring information to organization-defined personnel or roles as needed or at an organization-defined frequency.
### SI-4(g) Write the Control
Define the personnel or roles to which information system monitoring information is to be provided.

Define the information system monitoring data and information that is provided to these organization-defined personnel or roles.

Define the frequency to provide organization-defined information system monitoring to organization-defined personnel or roles.

Define is the CSP provides information system monitoring information to organization-defined personnel or roles either:
 *	As needed; and/or
 *	With the organization-defined frequency.

This control implementation may differ IAW the level of the service layer for which the CSP is responsible.
### SI-4(g) Customer Responsibility
*IaaS* - Service Provider System Specific. There is no Customer Responsibility.

*PaaS* - Service Provider System Specific. There is no Customer Responsibility.

*SaaS* - Service Provider System Specific. There is no Customer Responsibility.
