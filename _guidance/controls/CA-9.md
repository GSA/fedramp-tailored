# CA-9 Internal System Connections (Conditional)
## CA-9 Control Requirement
The organization:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;a.	Authorizes internal connections of [Assignment: organization-defined information system components or classes of 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;components] to the information system; and

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;b.	Documents, for each internal connection, the interface characteristics, security requirements, and the nature of the &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;information communicated.
### CA-9(a) Control Requirement
Describe how the organization: authorizes internal connections of [Assignment: organization-defined information system components or classes of components] to the information system.

FedRAMP-Tailored: Control is applicable if there are internal system connection(s). Connections (if any) shall be (identified and) authorized and:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;a.	Identify the interface/connection;

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;b.	Detail what data is involved and its sensitivity;

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;c.	Whether the connection is one-way or bidirectional; and

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;d.	How the connection is secured.
### CA-9(a) Control Objective
The objective/ intent of this part (a) of the control is to first define/identify information system components or classes of components to be authorized as internal connections to the system. Note that the NIST Supplemental Guidance for internal connections is, “…intra-system connections… including, for example, system connections with mobile devices, notebook/desktop computers, printers, copiers, facsimile machines, scanners, sensors, and servers. Instead of authorizing each individual internal connection, organizations can authorize internal connections for a class of components.”

Most Cloud Service Offerings have already considered the desktops and laptops that are used for the system administrators to administer the system but have not considered the mobile devices that the system administrators my use even minimally to connect to the system.

All components that connect to the system must be considered internal connections.

Another aspect of this defining of internal connections to the system is that the defining has to be done at each level of the service layer. This is so because the level of security may differ at each level of the service layer. This may be a particular challenge for a SaaS that is responsible and accountable for the entire stack. Internal connections for components or classes of components, at each layer and at each level MUST be accounted and identified.
### CA-9(a) Write the Control
This part (a) of the control must first define/identify information system components or classes of components to be authorized as internal connections to the system. Note that the NIST Supplemental Guidance for internal connections is, “…intra-system connections… including, for example, system connections with mobile devices, notebook/desktop computers, printers, copiers, facsimile machines, scanners, sensors, and servers. Instead of authorizing each individual internal connection, organizations can authorize internal connections for a class of components.

Please be concise and list the components and classes of components that are intra-connected at each level of each service layer. Also, before components or classes of components can be authorized, these must be identified.

This security control implementation detail must first (Verb) define the (Noun) information system components or classes of components to be authorized as internal connections to the information system at each level of each service layer for which the CSP is responsible.

Once components and/or classes of components are defined, the security control implementation detail must describe how these components and/or classes of components are authorized as internal connections of the CSO.
### CA-9(a) Customer Responsibility
*IaaS* – This responsibility lies with Service Provider System Specific, or possibly Service Provider Hybrid (Service Provider Corporate and Service Provider System Specific) but there is no customer responsibility to authorize internal connections. The CSP must authorize internal connections.

*PaaS* – This responsibility lies with Service Provider System Specific, or possibly Service Provider Hybrid (Service Provider Corporate and Service Provider System Specific) but there is no customer responsibility to authorize internal connections. The CSP must authorize internal connections.

*SaaS* – This responsibility lies with Service Provider System Specific, or possibly Service Provider Hybrid (Service Provider Corporate and Service Provider System Specific) but there is no customer responsibility to authorize internal connections. The CSP must authorize internal connections.
### CA-9(b) Control Requirement
Describe how the organization: documents, for each internal connection, the interface characteristics, security requirements, and the nature of the information communicated.
### CA-9(b) Control Objective
The objective/ intent of this part (b) of the control is to document information system components or classes of components to be authorized as internal connections to the system that are listed in part (a).

For this part (b) of the control, the documentation must include (i) the interface characteristics, (ii) security requirements, and (iii) the nature of the information communicated. These parameters must be documented for each level of each service layer of the CSO.
### CA-9(b) Write the Control
Since the part (b) of this control requires multiple parameters defined, depending upon the complexity of the intra-connections at each level of each layer, it might be an idea to create a table to capture all the information that this security control implementation detail requires.

Since the writer has identified all intra-connections in part (a) the table can be expanded to include the following details about each intra-connection.

For this part (b) of the control, the documentation must include (i) the interface characteristics, (ii) security requirements, and (iii) the nature of the information communicated. These parameters must be documented for each level of each service layer of the CSO.

The FedRAMP Tailored adds some additional parameters that must be defined in the security control implementation description. FedRAMP Tailored baseline states that this control is applicable if there are internal system connection(s). Connections (if any) shall be (identified and) authorized and:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;a.	Identify the interface/connection (interface characteristics);

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;b.	Detail what data is involved and its sensitivity (the nature of the information communicated);

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;c.	Whether the connection is one-way or bidirectional (the nature of the information communicated); and

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;d.	How the connection is secured (security requirements).
### CA-9(b) Customer responsibility
*IaaS* – This responsibility lies with Service Provider System Specific, or possibly Service Provider Hybrid (Service Provider Corporate and Service Provider System Specific) but there is no customer responsibility to authorize internal connections. The CSP must authorize internal connections.

*PaaS* – This responsibility lies with Service Provider System Specific, or possibly Service Provider Hybrid (Service Provider Corporate and Service Provider System Specific) but there is no customer responsibility to authorize internal connections. The CSP must authorize internal connections.

*SaaS* – This responsibility lies with Service Provider System Specific, or possibly Service Provider Hybrid (Service Provider Corporate and Service Provider System Specific) but there is no customer responsibility to authorize internal connections. The CSP must authorize internal connections.

