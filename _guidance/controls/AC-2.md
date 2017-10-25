# AC-2 Account Management
## AC-2 Control Requirement
The organization:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(a)  Identifies and selects the following types of information system accounts to support organizational &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;missions/business functions: [Assignment: organization-defined information system account types];

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(f)  Creates, enables, modifies, disables, and removes information system accounts in accordance with &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Assignment: organization-defined procedures or conditions];

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(g)  Monitors the use of information system accounts; and

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(h)  Notifies account managers:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(1)  When accounts are no longer required;

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(2)  When users are terminated or transferred; and

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(3)  When individual information system usage or need-to-know changes
### AC-2(a) Control Requirement
Identify select organization-defined information system account types to support organizational missions/ business functions. There is no FedRAMP-specific parameter for this control.
### AC-2(a) Control Objective
The requirement is looking for a list of system account types that support the organizational mission and business functions. Once this list is defined in this section of the control, the remaining sections of the control will refer back to this list with the objective of ensuring that the proper security parameters are applied to each of the listed system account types.
In order to fulfill this objective, the system account types must have been already defined, for example, in an automated account management tool or manually in Active Directory Group Policy Objects or Linux Network Information Service (NIS) (etc./group/). Once these are defined, the account types can be easily identified and selected for the control requirement.

The system account types will vary for each layer in the service model but need to be defined for the devices and software in each layer.

_Software as a Service (SaaS)_
  * Application level – access enforcement of accounts with various privileges; access enforcement of administrators that manage the applications
  * Data level – access enforcement of accounts and objects as applicable

_Platform as a Service (PaaS)_
  * Runtime systems – account types
  * Middleware – account types
  * Databases – account types
  * Operating Systems – account types

_Infrastructure as a Service (IaaS)_
  * Virtualization – account types
  * Servers – account types
  * Storage – account types
  * Networking – account types
  * Datacenters account types if applicable
### AC-2(a) Write the Control
(Verb) (i) Define. (Noun) information system account types.

The list of information system account types should exist (be defined) for the system. NIST offers these account types as an example: individual, shared, group, system, guest/anonymous, emergency, developer/manufacturer/vendor, temporary, and service. This list can be located in the automated account management tool used by the organization or manually in the GPO or etc./group/ file of each device.

(Verb) (ii) Identify. (Noun) information system account types.

Of the list of information system account types that are defined, identify which of these account types support the organizational missions/business functions.

(Verb) (iii) Select. (Noun) information system account types.

Now that the list is defined and identified, the list is selected for inclusion in this control requirement.

List the organizationally defined system account types. Use full sentences. This section of the security control implementation description may begin as, "`System Name` has identified and selected the following list of information system account types that support the organizational mission and business functions. Each information system account type is identified within the specific section to which the account type is applicable."

For Infrastructure as a Service (IaaS), list all associated account types in:
  * Virtualization - account types
  * Servers - account types
  * Storage - account types
  * Networking - account types
  * Datacenters account types if applicable

For Platform as a Service (PaaS) that does not also have responsibility for the IaaS, list all associated account types in:
  * Runtime systems - account types
  * Middleware - account types
  * Databases - account types
  * Operating Systems - account types
  * Anything else if the PaaS also is responsible for the IaaS; list all account types in both layers

For Software as a Service (SaaS) that does not have responsibility for the PaaS or the IaaS, list all associated account types in:
  * Applications - account types
  * Data - account types

If the Cloud Service Offering is responsible for the entire stack, the list must include the account types for all layers in each service model. Also provide account types for any custom layers that might have been added as included in the CSP Cloud Service Offering.
### AC-2(a) Customer Responsibilities
*IaaS* - Normally, there is no Customer Responsibility for information system account types to support organizational missions/business functions. System accounts are not provisioned to customers.

*PaaS* - System accounts are provisioned to customers based upon the subscription and based upon the platform service. It is important to clearly define the Customer Responsibilities as these pertain to the PaaS subscription and how accounts are provisioned.

*SaaS* - Depending upon the subscription, system accounts are provisioned to customers to perform some basic management functions. The Customer Responsibility must be fully defined for provisioning these accounts.
### AC-2(f) Control Requirement
Describe how the organization creates, enables, modifies, disables, and removes information system accounts in accordance with [Assignment: organization-defined procedures or conditions].
### AC-2(f) Control Objective
This control requirement is looking for two procedures. All aspects (create, enable, modify, disable, remove) of the system accounts or account types addressed in AC-2, must be addressed in both procedures in this implementation description.

The first procedure must address how the organization defines procedures and conditions surrounding (i) creating information system accounts, (ii) enabling information system accounts, (iii) modifying information system accounts, (iv) disabling information system accounts, and (v) removing information system accounts.

The second procedure must address how in actuality, the system management of the information system accounts listed in AC-2 aligns with the organizationally defined procedure just defined in the first procedure.

Please use the appropriate citation guidance as prescribed by your organization.
### AC-2(f) Write the Control
AC-2(f) (Noun) Organization-defined procedures or conditions.  (Noun) Information system accounts.

AC-2(f) [1] (Verb) Describe. This is the first procedure to illustrate how the organization defines procedures or conditions surrounding information system accounts. These procedures must address each of the following actions:
  * AC-2(f) [1] [a] (Verb) Create. Creating accounts.
  * AC-2(f) [1] [b] (Verb) Enable. Enabling accounts.
  * AC-2(f) [1] [c] (Verb) Modify. Modifying accounts.
  * AC-2(f) [1] [d] (Verb) Disable. Disabling accounts.
  * AC-2(f) [1] [e] (Verb) Remove. Removing accounts.
  
AC-2(f) [2] (Verb) Describe. This is the second procedure to illustrate how the system management of information system accounts aligns with the organization-defined management of information system accounts outlined above.
  * AC-2(f) [2] [a] (Verb) Create. Creating information system accounts in accordance with organization-defined procedures or conditions.
  * AC-2(f) [2] [b] (Verb) Enable. Enabling information system accounts in accordance with organization-defined procedures or conditions.
  * AC-2(f) [2] [c] (Verb) Modify. Modifying information system accounts in accordance with organization-defined procedures or conditions.
  * AC-2(f) [2] [d] (Verb) Disable. Disabling information system accounts in accordance with organization-defined procedures or conditions.
  * AC-2(f) [2] [e] (Verb) Remove. Removing information system accounts in accordance with organization-defined procedures or conditions.
### AC-2(f) Customer Responsibilities
*IaaS* - Normally, there is no Customer Responsibility for information system account types to support organizational missions/business functions. System accounts are not provisioned to customers. Therefore there are no requirements to instruct customers about procedures on handling the information system account types by authorized users.

*PaaS* - System accounts are provisioned to customers based upon the subscription and based upon the platform service. It is important to clearly define the process by which system account types are created, enabled, modified, disabled, removed, as these pertain to the PaaS subscription.

*SaaS* - Depending upon the subscription, system accounts are provisioned to customers to perform some basic management functions. Define the process by which system account types are created, enabled, modified, disabled, removed, as these pertain to the SaaS subscription.
### AC-2(g) Control Requirement
Describe how the organization monitors the use of information system accounts.
### AC-2(g) Control Objective
This requirement is looking for a process. The objective for this control is to define the process by which the use of system accounts or account types are monitored by the organization. The monitoring exercise normally has specific objectives defined by the organization. These organizational objectives can be for audit monitoring, incident monitoring, network monitoring, and physical access monitoring. The organization monitors the use of information system accounts for anomalous behaviors based upon the list of the access authorizations and attributes defined in AC-2(d).  

The organization use monitoring includes monitoring; and

The use of guest/anonymous and temporary accounts:
  * For atypical usage of information system accounts
  * For Privileged role assignments use or misuse
  * For unauthorized remote access to the information system
  * Of remote access sessions which allows organizations to audit user activities on a variety of information system components (e.g., servers, workstations, notebook/laptop computers) and to ensure compliance with remote access policy
  * For unauthorized wireless access to the information system
  * For unauthorized connections of mobile devices to organizational information systems
  * For the information system connections on an ongoing basis verifying enforcement of security requirements
  
This list is not all-encompassing but serves as a basis from which the organization can describe or define monitoring system account usage.
### AC-2(g) Write the Control
AC-2(g) (Verb) Monitor.  Describe how the organization monitors the use of information system accounts. Monitoring the use of system accounts can be a very wide description or very narrow based upon the numbers and types of information system accounts utilized by the system. 

In the Objectives section above, there are specific examples cited. If the organization employs automated account management, these automated tools provide the attributes that are monitored. If the organization employs automated monitoring through an Intrusion Detection system (IDS) or an intrusion Prevention System (IPS) or a Security Information and Event Management (SIEM) system, these events are captured within the tool and can be easily referenced and described.
### AC-2(g) Customer Responsibilities
*IaaS* - Normally, there is no Customer Responsibility for information system account types to support organizational missions/business functions. System accounts are not provisioned to customers. Therefore there are no requirements to monitor use of system account types.

*PaaS* - System accounts are provisioned to customers based upon the subscription and based upon the platform service. It is important to clearly define the process by which the use of system account types are monitored, as these pertain to the PaaS subscription.

*SaaS* - Depending upon the subscription, system accounts are provisioned to customers to perform some basic management functions. Define the process by which the use of system account types are monitored.
### AC-2(h) Control Requirement
Describe how the organization notifies account managers:
  * When accounts are no longer required;
  * When users are terminated or transferred; and
  * When individual information system usage or need-to-know changes.
  
There is no FedRAMP-specific parameter for this control.
### AC-2(h) Control Objective
The account managers for each of the information system accounts are described in AC-2(b).

When describing this process, please be clear about how the description provided aligns with each of the required attributes.

Please note that the second sub requirement applies to both "Terminated" and "Transferred."

Please note that the third sub requirement applies to both "Individual information system usage" and "Individual need-to-know" changes.

This requirement is looking for a process. The process may be automated and included in an organizational workflow. If that is the scenario, the organizational workflow must be described with enough detail to determine exactly how account managers are notified (i) when information system accounts are no longer required; (ii) when users are terminated or (iii) transferred; and (iv) when  individual information system usage or (v) need-to-know changes.

If a diagram is provided, then it must be accompanied by a description of these five attributes.

The process may be manual and each step should be fully outlined for each action regarding how account managers are notified  (i) when information system accounts are no longer required; (ii) when users are terminated or (iii) transferred; and (iv) when  individual information system usage or (v) need-to-know changes.
### AC-2(h) Write the Control
AC-2(h) (Verb) Notify. Describe how the organization notifies account managers regarding accounts.

AC-2(h) (1) (Verb) Describe how the organization notifies account managers when accounts are no longer required.

AC-2(h) (2) (Verb) Describe how the organization notifies account managers when users are terminated.

Describe how the organization notifies account managers when users are transferred.

AC-2(h) (3) (Verb) Describe how the organization notifies account managers when individual information system usage changes.

Describe how the organization notifies account managers when the need to know changes.
### AC-2(h) Customer Responsibilities
*IaaS* - Normally, there is no Customer Responsibility for information system account types to support organizational missions/business functions. System accounts are not provisioned to customers. Therefore there are no requirements to instruct customers how they should notify account managers when accounts are no longer required; when users are terminated or transferred; when individual information system usage or need to know changes.

*PaaS* - System accounts are provisioned to customers based upon the subscription and based upon the platform service. It is important for customers to clearly define the process by which account managers are notified when accounts are no longer required; when users are terminated or transferred; when individual information system usage or need to know changes, as these pertain to the PaaS subscription.

*SaaS* - Depending upon the subscription, system accounts are provisioned to customers to perform some basic management functions. Customers must define the process by which account managers are notified when accounts are no longer required; when users are terminated or transferred; when individual information system usage or need to know changes, as these pertain to the SaaS subscription.
