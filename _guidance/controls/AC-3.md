# AC-3 Access Enforcement
## Control Requirement
The information system enforces approved authorizations for logical access to information and system resources in accordance with applicable access control policies.

There is not a FedRAMP specific parameter for this control.
## Control Objective
The requirement is looking for a description of access control enforcement for approved authorizations to ensure that this aligns with the system access control policies. Note that authorization is not equivalent to authentication. These terms and their definitions are frequently confused. Authentication is providing and validating identity. Authorization includes the execution rules that determine what functionality and data the privileged or nonprivileged user may access, ensuring the proper allocation of access rights, i.e., access enforcement after authentication is successful. 

Access control policies are identity-based policies, role-based policies, attribute-based policies; and access enforcement mechanisms are access control lists, access control matrices, cryptography utilized by organizations to control logical access between users (or processes acting on behalf of users) and objects (i.e., devices, files, records, processes, programs, domains) in the system. In addition to enforcing authorized access at the information-system level, access enforcement mechanisms are utilized at the application level, to provide increased security for the organization.

If encryption of stored information is employed as an access enforcement mechanism, the cryptography used is FIPS 140-2 compliant (http://csrc.nist.gov/groups/STM/cmvp/documents/140-1/140val-all.htm) and/or NSA approved. For classified information, the cryptography used is dependent on the classification level of the information and the clearances of the individuals having access to the information. Mechanisms implemented by AC-3 are configured to enforce authorizations determined by other security controls.

This system access enforcement is normally through automation employed within the system that enforces approved authorizations for logical access control to the system at the information system level; and application and service levels.  This security control implementation description must include access control enforcement for privileged and non-privileged accounts. This includes the access between users/ objects; and objects/ objects. In smaller systems access enforcement is implemented and maintained manually. If manual methods are used, the process must be fully defined within the organization access control policy and procedures document or associated documentation.

For any organization to determine the proper method of access enforcement, a risk assessment needs to be performed to identify threats and vulnerabilities specific to the environment, so that the proper access control methodology is identified. The organizational policies must enforce and align with this methodology. In situations where the system is bigger or hyperscale, there may be organization methodologies that utilize many types of access enforcement depending upon the level of defense in depth. These methodologies are granularly defined in organizational policies and procedures and inherent in the organizational account management system.

There are many methods of access enforcement. Here are some access control frameworks from which access control matrices are enabled.

* Permission-Based Access Control abstracts application actions (read, write, execute) into a set of permissions. This is broadly defined access enforcement. Access enforcement is determined by checking if the current user has the permission associated with the requested application action.

* Role-Based Access Control (RBAC), access decisions are based on an individual's roles and responsibilities within the organization or user base. RBAC can be used by SaaS security administrators with the ability to determine who can perform what actions, when, from where, in what order, and in some cases under what relational circumstances.

* Discretionary Access Control (DAC) restricts access based on the identity of users and/or membership in certain groups. Access enforcement decisions are based on the authorizations granted to a user based on credentials. This is more finely tuned access enforcement and should be considered with privileged accounts.

* Mandatory Access Control (MAC) enforcement of organizational security policy does not rely on voluntary web application user compliance. MAC secures information by assigning sensitivity labels on information and comparing this to the level of sensitivity to which a user is operating. MAC is appropriate for extremely secure systems including multilevel secure military applications or mission critical data applications.

Please note that the AC-2 control identifies the accounts that have access to the system at all levels. There is no need to restate everything that is stated in AC-2. The AC-3 control now requires a description of the mechanisms by which the system enforces the approved authorizations granted through account management. Please note that FedRAMP mandates cryptography is utilized where appropriate in addition to other access enforcement methodologies.

_Software as a Service (SaaS)_
  * Application level – access enforcement of accounts with various privileges; access enforcement of administrators that manage the applications
  * Data level – access enforcement of accounts and objects as applicable
  
## Write the Control
(Verb) Enforce. (Noun) approved authorizations for logical access (Noun) to information and system resources.
Describe how the CSP Cloud Service Offering (CSO) (enforces) forcibly imposes approved authorizations for logical access to information and system resources in accordance with applicable access control policies. Organizations may use interconnection security agreements (ISAs) to enforce access restrictions for remote connections. But then a description is required as proof that documentation i.e., ISAs are an enforcement mechanism.

Understand that the account types that are approved and have logical access to the CSO, are defined in AC-2. AC-3 requires descriptions as to how access enforcement is forcibly imposed upon each account or account type in each layer of the SaaS, PaaS, IaaS. The logical access enforcement must be fully defined in CSO access control policies.

For each layer of the stack, the IaaS, the PaaS, or the SaaS, there are likely different access enforcement mechanisms. Focus on a specific layer, then write/describe the access enforcement description for each service within that layer, as applicable to the CSO.

For Infrastructure as a Service (IaaS), list all associated access enforcement mechanisms in:
*	Virtualization
*	Servers 
*	Storage
*	Networking
*	Datacenters account types if applicable

For Platform as a Service (PaaS) that does not also have responsibility for the IaaS, list all associated access enforcement mechanisms in:
*	Runtime systems
*	Middleware
*	Databases
*	Operating Systems
*	Anything else if the PaaS also is responsible for the IaaS; list all associated access enforcement mechanisms in both layers.

For Software as a Service (SaaS) that does not have responsibility for the PaaS or the IaaS, list all associated enforcement mechanisms in:
*	Applications
*	Data
If the CSO is responsible for the entire stack, the list must include the access enforcement mechanisms for all layers in each service model. Also provide access enforcement mechanisms for any custom layers that might have been added as included in the CSP CSO.
