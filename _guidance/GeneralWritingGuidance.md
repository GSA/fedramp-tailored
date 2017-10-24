## Control Writing Process:
1.	Identify control to be described.
2.	Identify control as it appears in NIST.
3.	Identify control as it appears in FedRAMP guidance.
4.	Analyze NIST and FedRAMP for any apparent incongruities.
5.	Ingest NIST Supplemental Guidance for the control as applicable.
6.	Determine the responsible role for the control.
7.	Identify all necessary parameters to be considered for each section of the control.
8.	Identify the NIST required assessment objectives and FEDRAMP testing criteria to understand the intent of the control.
9.	Do not attempt to describe the control without identifying each component piece of the control. Break down each section of the control into the component parts, i.e., a, b, c, d... and then 1, 2, 3... and then i., ii., iii., iv. etc.
10.	For each component part of the control, identify the nouns that must be described and the verbs that must be used to perform the descriptions. (Each sentence must be conjugated into component parts in order to adequately address the section of the control.)
11.	Identify how each of the FedRAMP parameters aligns with the section to which it belongs. Write to the FedRAMP applicable parameter. Describe in detail any deviations from the FedRAMP defined parameters.
12.	Identify the FedRAMP additional guidance as applicable and ensure that the additional guidance has been adequately addressed.
13.	Write the control section.
14.	Cross check the written implementation description with the NIST required assessment objectives and FEDRAMP testing criteria to ensure proper alignment.

## Control Writing Guidance:
* Explain Who uses/defines the System  (Organization, Customer/User Roles & Responsibilities)
* Explain What the System does and uses to perform its capability (e.g., PE Controls)
* Explain When the control(s) are applicable
* Explain Where the System performs its capability (e.g., location, alternate locations)
* Explain Why the System is needed
* Explain HOW the System/Organization performs its capabilities. For example,
  * How does the System perform its capabilities?
  * How does the System function in a temporary failure? A long-term failure?
  * How does the System provide for its Customer/User interaction, Roles, and Responsibilities?
  
## Completing Control Summary Information:
#### *Determine whether the security associated with this control is implemented using the below definitions:*
* **Implemented** - All aspects of the controls are in place, operating as intended, and producing the desired outcome.
* **Partially Implemented** - Some aspects of the control are not in place, causing a security gap that must be addressed.
* **Planned** - Control is not in place and/or partially in place but Plan of Action and Milestones is in place to address the security gap.
* **Alternative Implementation** - Compensating controls in place that provide the necessary security protections afforded by the primary control.
* **Not applicable** - Control is not applicable to the security of the system, i.e., for truly air-gapped systems AC-17 is not applicable.
#### *Check all parties that provides the security control protection, considering using the below definitions:*
* **Configured by Customer (Customer System Specific)** - A control where the customer needs to apply a configuration in order to meet the control requirement.
* **Provided by Customer (Customer System Specific)** - A control where the customer needs to provide additional hardware or software in order to meet the control requirement.
* **Shared (Service Provider and Customer Responsibility)** - A control that is managed and implemented partially by the CSP Name and partially by the customer.
* **Inherited from pre-existing FedRAMP Authorization for `CSP Name here`, `Date of Authorization`** - A control that is inherited from another CSP Name system that has already received a FedRAMP Authorization.
