# AU-3 Content of Audit Records
## AU-3 Control Requirement
Describe how the information system generates audit records containing information that establishes what type of event occurred, when the event occurred, where the event occurred, the source of the event, the outcome of the event, and the identity of any individuals or subjects associated with the event.
## AU-3 Control Objective
The objective/intent of this control is to ensure that the system captures the basic, robust information gathering and/or problem solving content in an audit record that would support an after the fact investigation in case of a negative event. Minimally, this control requires that the following be captured: (WHAT) what type of event occurred; (WHEN) when the event occurred; (WHERE) where the event occurred; (WHAT) the source of the event; (HOW/ HOW MUCH) the outcome of the event; and (WHO) the identity of any individuals or subjects associated with the event.

Depending upon where the audit records are being captured in the system, the content of the audit record may be much more extensive than these few fields. Please ensure that the content is described for each type of audit record that is generated.
## AU-3 Write the Control
(Verb) Describe (Noun) content (of audit records)

**What happened?** What type of event occurred? What is the source of the event?

**Who was involved?** Who is/are the identity of any individuals or subjects associated with the event?

**Where did it take place?** Where did the event occur (where in the system; where is the organization)?

**When did it take place?** When did the event occur?

**Why did that happen?**  The root cause is what must be able to be established by the content generated for each record.

**How did it happen?**  (Although the “how” is normally covered by the “what”, “when”, “where”) What is the outcome of the event?

Be sure to describe the content of the audit records at each level of system auditing that is being performed. Some audit record content may be much more extensive. No audit record content should be less extensive than the minimal content listed here.

For Infrastructure as a Service (IaaS), list all associated audit records in:

*	Virtualization – audit records;
*	Servers – audit records;
*	Storage – audit records;
*	Networking – audit records; and
*	Datacenters audit records, if applicable.

For Platform as a Service (PaaS) that does not also have responsibility for the IaaS, list all associated audit records in:
*	Runtime systems – audit records;
*	Middleware – audit records;
*	Databases – audit records;
*	Operating Systems - audit records; and
*	Anything else if the PaaS also is responsible for the IaaS; list all audit records in both layers.

For Software as a Service (SaaS) that does not have responsibility for the PaaS or the IaaS, list all associated audit records in:
*	Applications – audit records; and
*	Data – audit records.

If the Cloud Service Offering is responsible for the entire stack, the list must include the audit records for all layers in each service model. Also provide audit records for any custom layers that might have been added as included in the CSP Cloud Service Offering.
## AU-3 Customer Responsibilities
*IaaS* – For IaaS, this is Service Provider System Specific. The IaaS provides audit logging capabilities and captures events for their internal compliance. 

*PaaS* – For the PaaS, this is most likely Service Provider System Specific, and Configured by Customer (Customer System Specific) The PaaS provides audit logging capabilities and captures events for the customer. Customers are responsible for reviewing the logs and capturing events required for customer compliance.

*SaaS* – For the SaaS, the SaaS will supply audit logging capabilities and captures events for the customer. However, it is the responsibility of the customers to also audit and monitor the health and performance of the applications they build and those to which they subscribe.


