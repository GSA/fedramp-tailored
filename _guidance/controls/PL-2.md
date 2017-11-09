# PL-2 System Security plan
## PL-2 Control Requirement
The organization:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;a.	Develops a security plan for the information system that:

1.	Is consistent with the organization’s enterprise architecture;
2.	Explicitly defines the authorization boundary for the system;
3.	Describes the operational context of the information system in terms of missions and business processes;
4.	Provides the security categorization of the information system including supporting rationale;
5.	Describes the operational environment for the information system and relationships with or connections to other information systems;
6.	Provides an overview of the security requirements for the system;
7.	Identifies any relevant overlays, if applicable;
8.	Describes the security controls in place or planned for meeting those requirements including a rationale for the tailoring decisions; and
9.	Is reviewed and approved by the authorizing official or designated representative prior to plan implementation;

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;b.	Distributes copies of the security plan and communicates subsequent changes to the plan to [Assignment: &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;organization-defined personnel or roles];

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;c.	Reviews the security plan for the information system [Assignment: organization-defined frequency];

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;d.	Updates the plan to address changes to the information system/environment of operation or problems identified &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;during plan implementation or security control assessments; and

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;e.	Protects the security plan from unauthorized disclosure and modification.
### PL-2(a) Control Requirement
Describe how the organization develops a security plan for the information system that:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;a.	Is consistent with the organization’s enterprise architecture;

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;b.	Explicitly defines the authorization boundary for the system;

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;c.	Describes the operational context of the information system in terms of missions and business processes;

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;d.	Provides the security categorization of the information system including supporting rationale;

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;e.	Describes the operational environment for the information system and relationships with or connections to other &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;information systems;

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;f.	Provides an overview of the security requirements for the system;

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;g.	Identifies any relevant overlays, if applicable;

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;h.	Describes the security controls in place or planned for meeting those requirements including a rationale for the &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;tailoring and supplementation decisions; and

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;i.	Is reviewed and approved by the authorizing official or designated representative prior to plan implementation;
### PL-2(a) Control Objective
The objective/intent of this control part (a) is to ensure that the organization responsible for the system security authorization boundary understands the content that must be included in the System Security Plan (SSP). From the inception of the security plan document, it has been understood that the document is the narrative regarding a specifically defined system boundary. The purpose of the SSP is to provide an overview of the security requirements of the system and describe the controls in place or planned; and responsibilities and expected behavior of all individuals who access the system. NIST Supplemental Guidance states that the SSPs “do not provide detailed, technical descriptions of the specific design or implementation of the controls/enhancements. Security plans contain sufficient information (including the specification of parameter values for assignment and selection statements either explicitly or by reference) to enable a design and implementation that is unambiguously compliant with the intent of the plans and subsequent determinations of risk to organizational operations and assets, individuals, other organizations, and the Nation if the plan is implemented as intended.”

Please keep in mind that the SSP controls and enhancements are written to specifically address each level of each service layer for which the CSP is responsible.

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
### PL-2(a) Write the Control
The response to this part (a) of this control is lengthy even if it is paraphrased from a governing document. Be sure to include the governing document is any paraphrased verbiage exists.

1.	The FedRAMP SSP is consistent with the organization’s enterprise architecture.

If the organization has an enterprise architecture document, the system boundary must align with the enterprise architecture. Describe the function and the purpose of the system within the overall enterprise. In the current SSP templates available on the FedRAMP website, the information required for this section can be documented in Section 9.1 System Function or Purpose.

2.	The FedRAMP SSP explicitly defines the authorization boundary for the system.

In the FedRAMP SSP templates, the system authorization boundary is defined in both Section 9 General System Description, and Section 10 System Environment and Inventory. In section 9.2 Information System Components and Boundaries, the instruction asks that the writer,

“…provide an explicit definition of the system’s Authorization Boundary.  Provide a diagram that portrays this Authorization Boundary and all its connections and components, including the means for monitoring and controlling communications at the external boundary and at key internal boundaries within the system.

Address all components and managed interfaces of the information system authorized for operation (e.g., routers, firewalls).  

Formal names of components as they are known at the service provider organization in functional specifications, configuration guides, other documents and live configurations shall be named on the diagram and described.  Components identified in the Boundary diagram should be consistent with the Network diagram and the inventory(ies). Provide a key to symbols used.  Ensure consistency between the boundary and network diagrams and respective descriptions (Section 9.4) and the appropriate Security Controls [AC-20, CA-3(1)].”

3.	The FedRAMP SSP describes the operational context of the information system in terms of missions and business processes.

Section 7 Information System Operational Status requires specificity regarding system operational status. Section 10 System Environment and Inventory requires locations of operational facilities. The system mission and business functions must be understood in the context of the system boundary in order to apply the appropriate risk management strategy. According to NIST SP 800-37 Revision 1, Guide for Applying the Risk Management Framework to Federal Information systems A Security Life Cycle Approach, including updates as of 6/5/2014, Risk Management Framework (RMF) Tier 2 defines the business mission and business functions because this is one of the fundamental principles regarding how organizational risk is addressed. “…Well-defined boundaries establish the scope of protection for organizational information systems (i.e., what the organization agrees to protect under its direct management control or within the scope of its responsibilities) and include the people, processes, and information technologies that are part of the systems supporting the organization’s missions and business processes.”

In addition, “…The RMF must simultaneously provide a disciplined and structured approach to mitigating risks from the operation and use of organizational information systems and the flexibility and agility to support the core missions and business operations of the organization in highly dynamic environments of operation.”

4.	The FedRAMP SSP provides the security categorization of the information system including supporting rationale.

Section 2 Information System Categorization provides overall information system sensitivity categorization. In addition, FedRAMP provides the CSPs and Agencies with a FIPS 199 template - + SSP ATTACHMENT 10 - FedRAMP Federal Information Processing Standard (FIPS) 199 Categorization Template.

The RMF described in NIST SP 800-37 R1, defines RMF Step 1 as “Categorize Information System”. The Supplemental Guidance for this section states, “…The results of the security categorization process influence the selection of appropriate security controls for the information system and also, where applicable, the minimum assurance requirements for that system. Security categorization determinations consider potential adverse impacts to organizational operations, organizational assets, individuals, other organizations, and the Nation.”

5.	The FedRAMP SSP describes the operational environment for the information system and relationships with or connections to other information systems.

Section 11 System Interconnections lists, “…all interconnected systems.  Provide the IP address and interface identifier (eth0, eth1, eth2) for the CSP system that provides the connection.  Name the external organization and the IP address of the external system.  Indicate how the connection is being secured.  For Connection Security indicate how the connection is being secured.  For Data Direction, indicate which direction the packets are flowing.  For Information Being Transmitted, describe what type of data is being transmitted.  If a dedicated telecom line is used, indicate the circuit number.  Add additional rows as needed.  This table must be consistent with Table 13 3 CA-3 Authorized Connections.” Thus the crosscheck is Table 13-3 Authorized Connections.

As per NIST SP 800-37 R1, “In accordance with the provisions of FISMA and OMB policy, whenever the interconnection of federal information systems to information systems operated by state/local/tribal governments, contractors, or grantees involves the processing, storage, or transmission of federal information, the information security standards and guidelines described in this publication apply. Specific information security requirements and the terms and conditions of the system interconnections, are expressed in the Memorandums of Understanding and Interconnection Security Agreements established by participating organizations.”

6.	The FedRAMP SSP provides an overview of the security requirements for the system.
Section 13 Minimum Security Controls defines how the system must meet the minimum security control baseline requirements. Table 13-1 is the Summary of Required Security Controls for the system.

NIST SP 800-37 R1, RMF Step 2 is entitled, “Select Security Controls.” Once the system has been categorized, “…the security controls are selected based on the security categorization of the information system. After selecting the applicable security control baseline, organizations apply the tailoring process to align the controls more closely with the specific conditions within the organization (i.e., conditions related to organizational risk tolerance, missions/business functions, information systems, or environments of operation).”

7.	The FedRAMP SSP identifies any relevant overlays, if applicable.

This is rare that additional overlays are noted since FedRAMP requirements are actually a more rigorous overlay for the relevant FISMA security control baseline. If any overlays are relevant, these may be captured as appendices to the FedRAMP SSP or these may be included as the extra controls within the security controls implementation description families. If these overlays are required, the Section 13 Minimum Security Controls and Table 13-1 Summary of Required Security Controls must indicate the extent of the overlays applied.

8.	The FedRAMP SSP describes the security controls in place or planned for meeting those requirements including a rationale for the tailoring and supplementation decisions.

As per the requirements of the FedRAMP SSP, “Security controls must meet minimum security control baseline requirements. Upon categorizing a system as Low, Moderate, or High sensitivity in accordance with FIPS 199, the corresponding security control baseline standards apply. Some of the control baselines have enhanced controls which are indicated in parentheses. As per NIST SP 800-37 R1, “After selecting the applicable security control baseline, organizations apply the tailoring process to align the controls more closely with the specific conditions within the organization (i.e., conditions related to organizational risk tolerance, missions/business functions, information systems, or environments of operation).” “…Tailoring (the security control baseline) provides flexibility in applying the risk management concepts associated with the RMF in a manner that is most suitable for the organizations and the information systems involved.”

Security controls that are representative of the sensitivity of the system are described fully. Security controls that are designated as “Not Selected” or “Withdrawn by NIST” are not described unless they have additional FedRAMP controls. Guidance on how to describe the implemented standard can be found in NIST 800-53, Rev 4. Control enhancements are marked in parentheses in the sensitivity columns.

Systems that are categorized as FIPS 199 Low use the controls designated as Low, systems categorized as FIPS 199 Moderate use the controls designated as Moderate and systems categorized as FIPS 199 High use the controls designated as High.  A summary of which security standards pertain to which sensitivity level is found in Table 13 1 Summary of Required Security Controls…”

9.	The FedRAMP SSP is reviewed and approved by the authorizing official or designated representative prior to plan implementation.
As per the FedRAMP requirements, the SSP must be reviewed and approved by the Authorizing Official(s) and/or the Authorizing Official’s Designated Representative(s) prior to plan implementation.
### PL-2(a) Customer Responsibility
*IaaS* - Service Provider System Specific. There is no Customer Responsibility.

*PaaS* - Service Provider System Specific. There is no Customer Responsibility.

*SaaS* - Service Provider System Specific. There is no Customer Responsibility.
### PL-2(b) Control Requirement
Describe how the organization distributes copies of the security plan and communicates subsequent changes to the plan to [Assignment: organization-defined personnel or roles].
### PL-2(b) Control Objective
The objective/ intent of this part (b) of this control is to ensure that the CSP and the Agency realize that this SSP is a living document and the system state changes when there are changes to the system. There must be an established change management process to change the verbiage in the SSP at least annually or when there is a significant change to the system. While there are not specific FedRAMP defined personnel or roles to which these changes are propagated, it is understood through other related controls that the FedRAMP PMO, at least, must be one of the recipients.
### PL-2(b) Write the Control
As with most of the security controls, writing this part (b) of this control is like writing a “proof”, and defining inferential arguments for the mathematical statement. However, in this case, one is defining the inferential arguments for the security control statement. First one must define the personnel, the actions, the outcomes. Then one must write logically how the control is proven.

(Verb) Describe how the organization (verb) defines (noun) personnel or roles (including FedRAMP) to whom copies of the security plan are to be distributed and subsequent changes to the plan are to be communicated.

(Verb) Describe how the organization actually (verb) distributes (noun) copies of the security plan and (verb) communicates subsequent (noun) changes to the plan to (noun) personnel or roles (including FedRAMP).
### PL-2(b) Customer Responsibility
*IaaS* - Service Provider System Specific. There is no Customer Responsibility.

*PaaS* - Service Provider System Specific. There is no Customer Responsibility.

*SaaS* - Service Provider System Specific. There is no Customer Responsibility.
### PL-2(c) Control Requirement
Describe how the organization reviews the security plan for the information system [Assignment: organization-defined frequency] [at least annually].
### PL-2(c) Control Objective
The objective/ intent of part (c ) of this control is to describe how the SSP is reviewed at least annually.
### PL-2(c) Write the Control
For this part (c ) of this control, (verb) describe how the (noun) SSP is reviewed (when) at least annually. Describe how proof of this can be offered to substantiate the claim.
### PL-2(c) Customer Responsibility
*IaaS* - Service Provider System Specific. There is no Customer Responsibility.

*PaaS* - Service Provider System Specific. There is no Customer Responsibility.

*SaaS* - Service Provider System Specific. There is no Customer Responsibility.
### PL-2(d) Control Requirement
Describe how the organization updates the plan to address changes to the information system/ environment of operation or problems identified during plan implementation or security control assessments.
### PL-2(d) Control Objective
The objective/ intent of this part (d) of this control is to ensure that the changes to the system authorization boundary or issues identified within the system authorization boundary are identified and documented because the senior officials responsible for overseeing the system risk must be aware of the changes and issues to ensure that the risk to the system remains stable and the risk management strategy is still viable. This is all about appropriately managing risk. Most often, the security plan is considered a Configuration Item (CI) and managed according to the organizational Configuration Change Control process.
### PL-2(d) Write the Control
There are 3 scenarios that must be addressed in this part (d) of this security control implementation description. (Verb) Describe how the (noun) SSP is (verb) updated to address:

(i)	changes to the information system/environment of operation;
(ii)	problems identified during plan implementation or security control assessments; and
(iii)	problems identified during security control assessments.

In the security control implementation description, take care to specifically address each scenario. Sometimes it is feasible to divide the implementation description into these three sections and then write to each section.

The complexity for writing is introduced if there are different procedures for each level of each service layer for which the CSP is responsible. It is necessary to provide the description, accordingly.
### PL-2(d) Customer Responsibility
*IaaS* - Service Provider System Specific

*PaaS* - Service Provider System Specific; or Service Provider System Specific, Provided by Customer (Customer System Specific), and Inherited

*SaaS* - Service Provider System Specific; or Service Provider System Specific, Provided by Customer (Customer System Specific), and Inherited
### PL-2(e) Control Requirement
Describe how the organization protects the security plan from unauthorized disclosure and modification.
### PL-2(e) Control Objective
The objective/ intent of this part (e ) of this control is to ensure that the SSP is not altered or distributed to people without a right to know - either wittingly or unwittingly (benevolently or malevolently). This document is the one upon which the proper officials and stakeholders base their risk management decisions for the system. This document must be maintained in a trustworthy and uncorrupt state.
### PL-2(e) Write the Control
For this part (e ) of this control it is necessary to describe two aspects  of maintaining a trustworthy SSP:

(i)	(Verb) Describe how the organization ensures that the (noun) SSP documentation is protected from (what?) unauthorized disclosure.

(ii)	(Verb) Describe how the organization ensures that the (noun) SSP documentation is protected from (what?) unauthorized modification.

As illustrated in part (d) Write the Control, the complexity for writing is introduced if there are different procedures for each level of each service layer for which the CSP is responsible. However, since this is the overall SSP documentation, most often there is one set of processes or procedures governing these efforts to protect the SSP.
### PL-2(e) Customer Responsibility
*IaaS* - Service Provider System Specific. There is no Customer Responsibility.

*PaaS* - Service Provider System Specific. There is no Customer Responsibility.

*SaaS* - Service Provider System Specific. There is no Customer Responsibility.
