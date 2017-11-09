# CA-2 Security Assessments
## CA-2 Control Requirement
The organization:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(a)  Develops a security assessment plan that describes the scope of the assessment including:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(1)  Security controls and control enhancements under assessment;

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(2)  Assessment procedures to be used to determine security control effectiveness; and

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(3)  Assessment environment, assessment team, and assessment roles and responsibilities;

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(b)  Assesses the security controls in the information system and its environment of operation [*FedRAMP &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Assignment: at least annually*] to determine the extent to which the controls are implemented correctly, &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;operating as intended, and producing the desired outcome with respect to meeting established security &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;requirements;

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(c)  Produces a security assessment report that documents the results of the assessment; and

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(d)  Provides the results of the security control assessment to [*FedRAMP Assignment: individuals or roles to &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;include the FedRAMP PMO*].
### CA-2(a) Control Requirement
Describe how the organization develops a security assessment plan that describes the scope of the assessment including:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.  Security controls and control enhancements under assessment;

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.  Assessment procedures to be used to determine security control effectiveness; and

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3.  Assessment environment, assessment team, and assessment roles and responsibilities;
### CA-2(a) Control Objective
The objective/ intent of this part (a) of the control is to describe the process by which the organization develops a security assessment plan that describes the scope of the information system assessment. For this description, the scope includes the (i) security controls and control enhancements under assessment; (ii) assessment procedures to be used to determine security control effectiveness; and (iii) assessment environment, assessment team, and assessment roles and responsibilities.

CA-2 is the basis for the system risk management strategy. The initial security assessment conducted on the system by an independent assessor provides the system security baseline regarding whether the security controls are implemented correctly, operating as intended, and producing the desired outcome with respect to meeting the security requirements of the information system. The security controls are applied at, and must be described for each level of the service layer.

When describing the scope of the assessment, each of the levels of the service layers of the CSO must be considered because the testing / assessment procedures may vary based upon the layer and level in the stack. Each variation must be noted in the security assessment plan. A security control matrix (SCM) gives a basis for defining the security required in each level of the service layer and is a good way to provide an overall security view of the system and understand where there are deficiencies. Most independent 3PAOs will provide this to a CSP as a way to illustrate how security testing on the CSO must be accomplished.
### CA-2(a) Write the Control
(Verb) Describe (What?) how the organization (Verb) develops a (Noun) security assessment plan which (Verb) includes the (Noun) scope of the assessment.

FedRAMP does provide a template for a security assessment plan but the assessor may find that more detail must be added to the template in order to fulfill the CSO testing requirements. The scope of this security assessment plan must minimally include:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.	Security controls and control enhancements under assessment – Is this the FedRAMP Low, Moderate, High &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;baseline set of controls? Are there additional groups of controls that are added to the baseline set? Consider &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;these types of questions for each level of the service layers involved.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.	Assessment procedures to be used to determine security control effectiveness – Are there assessment &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;procedures? Are these the required FedRAMP assessment procedures? If there are other assessment &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;procedures, do the other procedures adequately determine security control effectiveness? Consider these &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;types of questions for each level of the service layers involved.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3.	Assessment environment, assessment team, and assessment roles and responsibilities – Is the system &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;environment authorization boundary clear and precise in order that an Agency examining the package can &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;clearly delineate the assessment environment? What is the level of independence of the independent 3PAO? &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Who within the organization plays a part and has defined responsibilities in the assessment process?

There are a number of parts that must be defined within this part (a).

First, consider that each level of the service layer in the CSO must be included in this description. Therefore, it may become apparent quickly that the security control implementation description should be divided in a logical grouping to ensure that detail enough is captured for each of the levels for each of the layers.

If for instance, the CSO is a SaaS and the SaaS is responsible for only the Application Level and the Data Level, it may be more logical to describe the security control implementation detail as follows:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;a.	A security assessment plan regarding the Application Level to include:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.	Security controls and control enhancements under assessment;

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.	Assessment procedures to be used to determine security control effectiveness; and

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3.	Assessment environment, assessment team, and assessment roles and responsibilities.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;b.	A security assessment plan regarding the Data Level to include:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.	Security controls and control enhancements under assessment;

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.	Assessment procedures to be used to determine security control effectiveness; and

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3.	Assessment.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;i.	environment

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ii.	team

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;iii.	roles and responsibilities

Creating an efficient and effective security control implementation detail for this part (a) of the control will make it easier to then describe the security control implementation detail for the parts (b), (c), and (d).
### CA-2(a) Customer Responsibilities
*IaaS* – Service Provider System Specific. It is the responsibility of the IaaS to define the scope of the security assessment plan in order that the independent 3PAO may then test the environment. There is no customer responsibility.

*PaaS* – Service Provider System Specific, Configured by Customer (Customer System Specific). It is the responsibility of the PaaS customer to create the scope of the security assessment plan to test the security controls for which the customer is responsible. The PaaS will inherit controls from the IaaS that are not subject to the PaaS security assessment plan.

*SaaS* – while the SaaS customer inherits many of the security controls from the PaaS, it is the SaaS customer responsibility to ensure that they do due diligence and incorporate this Shared (Service Provider and Customer Responsibility) model into the security assessment plan for their implementation of the SaaS.
### CA-2(b) Control Requirement
Describe how the organization assesses the security controls in the information system and its environment of operation at least annually to determine the extent to which the controls are implemented correctly, operating as intended, and producing the desired outcome with respect to meeting established security requirements;

FedRAMP requirements:

CA-2 (b) [at least annually]
### CA-2(b) Control Objective
The objective/intent of this part (b) of the security control requirement is to provide a security control implementation description that adequately describes how the system is assessed at least annually. This assessment description must define how the testing is conducted to ensure that the system risk posture remains stable and secure.

To illustrate some salient points in maintaining a stable risk posture, this means that the security controls implementation details must not have changed significantly since the last annual assessment and are implemented correctly, operating as intended, and producing the desired outcome with respect to meeting established security requirements. If there are changes to the system between the annual assessments what controls are in place to ensure that the risk management strategy is stable and the security posture has not changed? Are the security controls still implemented correctly, operating as intended, and producing the desired outcome with respect to meeting established security requirements?
### CA-2(b) Write the Control
There are specific points that must be made in this security control implementation description.

(Verb) Describe (Noun) security controls that are in place. Are these security controls:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;a.	implemented correctly;

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;b.	operating as intended; and

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;c.	producing desired outcome  with respect to meeting established security requirements

The FedRAMP parameter is that these controls must be assessed, at this level of scrutiny, at least annually.

Based on the security controls matrix you created (or referenced) in part (a) as the basis for answering this control, the response can be a description of the system and organizational risk management strategy which incorporates this annual assessment. Or, perhaps, the organizational risk management strategy is an ongoing workflow and the system is continuously monitored.

Regardless of the overall CSP risk management strategy, this security control implementation description must highlight that the security controls are assessed at least annual to the rigor prescribed by FedRAMP (and NIST) and are “implemented correctly, operating as intended, and producing the desired outcome with respect to meeting established security requirements”.
### CA-2(b) Customer Responsibilities
*IaaS* - Service Provider System Specific. It is the responsibility of the IaaS to define the scope of the security assessment plan in order that the independent 3PAO may then test the environment. There is no customer responsibility.

*PaaS* - Service Provider System Specific, Configured by Customer (Customer System Specific). It is the responsibility of the PaaS customer to create the scope of the security assessment plan to test the security controls for which the customer is responsible. The PaaS will inherit controls from the IaaS that are not subject to the PaaS security assessment plan.

*SaaS* – While the SaaS customer inherits many of the security controls from the PaaS, it is the SaaS customer responsibility to ensure that they do due diligence and incorporate this Shared (Service Provider and Customer Responsibility) model into the security assessment plan for their implementation of the SaaS.
### CA-2(c) Control Requirement
Describe how the organization produces a security assessment report that documents the results of the assessment.
### CA-2(c) Control Objective
The objective/intent of this part (c ) of the control is to state how the security assessment report documents the results of the security assessment. FedRAMP does provide the security assessment report template which is used by the 3PAOs. However, this part of the control requires a response to define the 3PAO methodology by which the report is created.
### CA-2(c) Write the Control
(Verb) Describe (what) how the organization produces a (Noun) security assessment report

The security assessment report methodology description should include documentation of the security assessment results in enough detail to provide the reader with assurance that the controls are “implemented correctly, operating as intended, and producing the desired outcome with respect to meeting established security requirements”.
### CA-2(c) Customer Responsibilities
*IaaS* – Service Provider System Specific. It is the responsibility of the IaaS to ensure that the security assessment completed by the independent 3PAO organization is compliant with FedRAMP standards. There is no customer responsibility.

*PaaS* – Service Provider System Specific, Configured by Customer (Customer System Specific). It is the responsibility of the PaaS customer to test the security controls for which the PaaS customer is responsible and to ensure that the security assessment completed by the independent 3PAO is compliant with FedRAMP standards. The PaaS will inherit controls from the IaaS that are not subject to the PaaS security assessment but the PaaS customer does inherit the risk from the IaaS for any security controls that are deficient at the IaaS level.

*SaaS* – While the SaaS customer inherits many of the security controls from the PaaS, it is the SaaS customer responsibility to ensure that they do due diligence and incorporate this Shared (Service Provider and Customer Responsibility) model into the security assessment for their implementation of the SaaS. The SaaS inherits controls from the PaaS that are not subject to the SaaS security assessment but the SaaS customer does inherit the risk from the PaaS for any security controls that are deficient at the PaaS level.
### CA-2(d) Control Requirement
Describe how the organization provides the results of the security control assessment to **_individuals or roles to include FedRAMP PMO._**

There is a FedRAMP specific parameter for this control.

CA-2 (d) [individuals or roles to include FedRAMP PMO]
### CA-2(d) Control Objective
The objective/intent of this control is provide written assurance via the security control implementation detail, from the CSP, that the CSP and 3PAO understand that the results of the security control assessment must be provided to other stakeholders which includes the FedRAMP PMO, the JAB, and the Agency Authorizing Officials (AOs) and Authorizing Official Designated Representatives (AODRs).
### CA-2(d) Write the Control
(Verb) Describe (What?) how the organization (Verb) provides (Noun) the results of the security control assessment to (Whom?) **_individuals or roles to include FedRAMP PMO._**

Do not simply state that the results are provided. There are individuals who must take responsibility for the dissemination of this documentation. The organization should have assigned individuals in place for tasks such as this.

Please explain the process by which this dissemination is completed. Please explain to whom the documentation is disseminated and why the decision was made to disseminate as such. If this is a dissemination procedure that is captured elsewhere, please synopsize the required verbiage and use the citation that you have provided throughout this documentation.
### CA-2(d) Customer Responsibilities
*IaaS* – Service Provider System Specific. It is the responsibility of the IaaS to ensure that the security assessment completed by the independent 3PAO organization is compliant with FedRAMP standards and the documentation is disseminated as defined. There is no customer responsibility.

*PaaS* – Service Provider System Specific, Configured by Customer (Customer System Specific). It is the responsibility of the PaaS customer to test the security controls for which the PaaS customer is responsible and to ensure that the security assessment documentation completed by the independent 3PAO is disseminated as per FedRAMP standards. The PaaS inherits controls from the IaaS that are not subject to the PaaS security assessment but the PaaS customer does inherit the risk from the IaaS for any security controls that are deficient at the IaaS level. Therefore, it is the PaaS responsibility to ensure that the PaaS customer is aware of the most current security posture of the IaaS system which it leverages.

*SaaS* – While the SaaS customer inherits many of the security controls from the PaaS, it is the SaaS customer responsibility to ensure that they do due diligence and incorporate this Shared (Service Provider and Customer Responsibility) model into the security assessment for their implementation of the SaaS. The SaaS inherits controls from the PaaS that are not subject to the SaaS security assessment but the SaaS customer does inherit the risk from the PaaS for any security controls that are deficient at the PaaS level. Therefore, it is the SaaS responsibility to ensure that the SaaS customer is aware of the most current security posture of the PaaS system which it leverages.
