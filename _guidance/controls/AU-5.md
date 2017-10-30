# AU-5 Response to Audit Processing Failure
## AU-5 Control Requirement
The information system:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(a)	Alerts [Assignment: organization-defined personnel or roles] in the event of an audit processing failure; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;and

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(b) Takes the following additional actions: [FedRAMP Assignment: organization-defined actions to be taken; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(overwrite oldest record)].
### AU-5(a) Control Requirement
Describe how the information system alerts [Assignment: organization-defined personnel or roles] in the event of an audit processing failure. 
### AU-5(a) Control Objective
The objective/intent of this control is to capture what the information system or organization does in the event of an audit processing failure. Specifically, this section (a) of this control requires a description regarding the position(s) notified and how the system alerts this position, in the event of an audit processing failure.

Please keep in mind that this control must be considered in the context of the overall risk management strategy for the system. It is good practice to ensure that the system notifies (through email, alarm, or other means) an administrator and another stakeholder when the audit logging capacity reaches a certain threshold below 100% capacity. This allows for remedial actions to take place before 100% is reached.

Therefore, by taking some extra audit logging precautions in the system environment, such as having a specific Point of Contact (and a backup to eliminate single point of failure) for failure notification, the chances of capturing malevolent activity by a bad actor is greater than if some general alert goes out to a group of stakeholders.
### AU-5(a) Write the Control
(Noun) Process by which the (Noun) system (Verb) alerts

(Noun) Personnel and/or role(s) when there is (Noun) Failure of audit processing 

When testing this control, the first step is to determine if the personnel or roles in the organization are defined or have this duty assigned via their position description. FedRAMP does not require specific organization-defined personnel or roles such as the Information system Security Officer (ISSO) or Chief Information Security Officer (CISO). However, someone, or some role, must be defined here and this person or role must accept the responsibility for this often overlooked aspect of system auditing.

Then this control requires a description of how the system alerts this/these person and/or role(s).

The process must address each of audit records, in each of the layers, of each of the service models described in AU-3.
### AU-5(a) Customer Responsibilities
*IaaS* – For IaaS, this is Service Provider System Specific. The IaaS provides audit logging capabilities and captures events for their internal compliance. The IaaS would have internal processes and personnel assigned to answer audit logging failures.

*PaaS* – For the PaaS, this is most likely Service Provider System Specific, and Configured by Customer (Customer System Specific) The PaaS provides audit logging capabilities and captures events for the customer.  The PaaS would have internal processes and personnel assigned to answer audit logging failures. Customers are responsible for reviewing the logs and capturing events required for customer compliance. Customers are responsible for their own assigned personnel and the processes in place for the audit logging failures at the customer level.

*SaaS* – For the SaaS, the SaaS will supply audit logging capabilities and captures events for the customer. However, it is the responsibility of the customers to also audit and monitor the health and performance of the applications they build and those to which they subscribe. As such, the auditing failures at the customer level need to be described along with the processes in place for handling the failures.
### AU-5(b) Control Requirement
Describe how the information system takes the following additional action: **_overwrite oldest audit records._**

The process must address each of audit records, in each of the layers, of each of the service models described in AU-3.
### AU-5(b) Control Objective
In AU-5(a), the personnel or role(s) are listed as being responsible for receiving alerts when audit log processing failures occur. There is no need to state this again for this portion of the control.

This section (b) of the control requires that a description be provided that explains how the oldest audit records are overwritten in response to an audit processing failure.

The objective/intent of this control is to capture what the information system or organization does in the event of an audit processing failure. Specifically, this control requires a description what actions are taken (FedRAMP requirement overwrite oldest record or an action much more stringent), in the event of an audit processing failure.

Please keep in mind that this control must be considered in the context of the overall risk management strategy for the system. It is good practice to ensure that the system notifies (through email, alarm, or other means) an administrator and another stakeholder when the audit logging capacity reaches a certain threshold below 100% capacity. This allows for remedial actions to take place before 100% is reached. Take into account that if the system auditing capability is set to “shut down” if the audit logging capacity is hit, this allows a bad actor to potentially generate a Denial of Service (DoS) which would shut down the audit logging capability.

Therefore, by taking some extra audit logging precautions in the system environment (having a specific Point of Contact [and a backup to eliminate single point of failure] for failure notification, setting a threshold, overwriting the logs, etc), the chances of capturing malevolent activity by a bad actor is greater. There is a possibility that some malevolent activity may be overwritten but this is a risk management decision that must be made by the organization and/or system.
### AU-5(b) Write the Control
A process is described in this portion of the control.

(Noun) Process by which the (Noun) system (Verb) Overwrites (Noun) oldest audit records if there is an audit processing failure.

Describe how the information system takes the following additional action: overwrite oldest audit records.

The process must address each of audit records, in each of the layers, of each of the service models described in AU-3.
### AU-5(b) Customer Responsibilities
*IaaS* – For IaaS, this is Service Provider System Specific. The IaaS provides audit logging capabilities and captures events for their internal compliance. The IaaS would have internal processes and personnel assigned to answer audit logging failures and to overwrite oldest records in response to an audit processing failure.

*PaaS* – For the PaaS, this is most likely Service Provider System Specific, and Configured by Customer (Customer System Specific) The PaaS provides audit logging capabilities and captures events for the customer.  The PaaS would have internal processes and personnel assigned to answer audit logging failures. Customers are responsible for reviewing the logs and capturing events required for customer compliance. Customers are responsible for their own assigned personnel and the records overwriting processes in place for the audit logging failures at the customer level.

*SaaS* – For the SaaS, the SaaS will supply audit logging capabilities and captures events for the customer. However, it is the responsibility of the customers to also audit and monitor the health and performance of the applications they build and those to which they subscribe. As such, the auditing failures at the customer level need to be described along with the records overwriting processes in place for handling the failures.
