# SC-7 Boundary Protection
## SC-7 Control Requirement
The information system:
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(a)	Monitors and controls communications at the external boundary of the system and at key internal boundaries within the system;

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(b)	Implements subnetworks for publicly accessible system components that are [Selection: physically; logically] separated from internal
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;organizational networks; and

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(c)	Connects to external networks or information systems only through managed interfaces consisting of boundary protection devices arranged
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;in accordance with organizational security architecture.
### SC-7(a) Control Requirement
Describe how the information system monitors and controls communications at the external boundary of the system and at key internal boundaries within the system.
### SC-7(a) Control Objective
The objective/ intent of this control is for the CSP to provide assurance that the CSP monitors and controls communications at the external boundary of the system and at key internal boundaries within the system. Restricting external web traffic only to organizational web servers within managed interfaces and prohibiting external traffic that appears to be spoofing an internal address as the source are examples of restricting and prohibiting communications. Managed interfaces employing boundary protection devices include, for example, proxies, gateways, routers, firewalls, guards, or encrypted tunnels arranged in effective security architecture (e.g., routers protecting firewalls and application gateways residing on a protected sub network commonly referred to as a demilitarized zone or DMZ).

System monitoring and controlling communications at the system external boundary and at key internal boundaries must be fully defined for all levels of all service layers for which the CSP is responsible.

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
### SC-7(a) Write the Control
There are four (4) distinct sections that must be addressed for this security control implementation detail.
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;i.	(Noun) Communications at the external boundary:
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;a.	(verb) monitors (noun) communications (where?) at the external boundary of the information system
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;b.	(verb) controls (noun) communications (where?) at the external boundary of the information system

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ii.	(Noun) Communications at key internal boundaries:
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;a.	(verb) monitors (noun) communications (where?) at key internal boundaries within the system
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;b.	(verb) controls (noun) communications (where?) at key internal boundaries within the system
### SC-7(a) Customer Responsibility
*IaaS* - Service Provider System Specific. There is no Customer Responsibility.

*PaaS* - Service Provider System Specific. There is no Customer Responsibility.

*SaaS* - Service Provider System Specific. There is no Customer Responsibility.
### SC-7(b) Control Requirement
Describe how the information system implements subnetworks for publicly accessible system components that are [Selection: physically; logically] separated from internal organizational networks.
### SC-7(b) Control Objective
The objective/ intent of this control is to ensure that the CSP understands and fully describes that physical and logical segregation must exist / does exist between the internal organizational network and publicly accessible system components.
### SC-7(b) Write the Control
This security control implementation description must describe how the system implements sub networks for publicly accessible system components that are either:
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;i.	physically separated from internal organizational networks; and/or
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ii.	logically separated from internal organizational networks.

Describe the sub networks at all levels of all service layers for which the CSP is responsible.
### SC-7(b) Customer Responsibility
*IaaS* - Service Provider System Specific. There is no Customer Responsibility.

*PaaS* - Service Provider System Specific. There is no Customer Responsibility.

*SaaS* - Service Provider System Specific. There is no Customer Responsibility.
### SC-7(c) Control Requirement
Describe how the information system connects to external networks or information systems only through managed interfaces consisting of boundary protection devices arranged in accordance with organizational security architecture
### SC-7(c) Control Objective
The objective/ intent of this control is for the CSP to provide assurance that the CSP connects to external networks or information systems only through managed interfaces consisting of boundary protection devices arranged in accordance with an organizational security architecture.
### SC-7(c) Write the Control
(Verb) Describe how the system (verb) connects to (noun) external networks or (noun) information systems only through (Noun) managed interfaces consisting of boundary protection devices arranged in accordance with organizational security architecture.

For this security control implementation description, the writer must address the connections or interconnections to (i) external networks only through managed interfaces consisting of boundary protection devices arranged in accordance with organizational security architecture.

The writer must address the connections or interconnections to other information systems only through managed interfaces consisting of boundary protection devices arranged in accordance with organizational security architecture.
### SC-7(c) Customer Responsibility
*IaaS* - Service Provider System Specific. There is no Customer Responsibility.

*PaaS* - Service Provider System Specific. There is no Customer Responsibility.

*SaaS* - Service Provider System Specific. There is no Customer Responsibility.
