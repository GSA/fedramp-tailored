---
title: Appendices
permalink: /appendices/
layout: default
---

# APPENDIX A - FedRAMP _Tailored_ Security Controls Baseline

# APPENDIX B - FedRAMP _Tailored_ Mandatory Templates
*in development*

# APPENDIX C - FedRAMP _Tailored_ ATO Letter Template
[Download as a Word Document](/static/APPENDIX C—FedRAMP Tailored ATO Letter Template DRAFT v 0.1.docx)

> Insert your information `here`

**ATO Letter Template**

`Federal Agency/Office logo`

`Date`

`Cloud System Owner Name`

`Cloud Service Name` Cloud System Owner

`Address`

Mr./Mrs. `CSP System Owner Name`:

`Federal Agency/Office` has completed the security review of the `Cloud Service Provider (CSP) Name` (`CSP Acronym`) `System Name` (`System Acronym`), which leverages the `CSP Name` (`CSP Acronym`) `System Name` (`System Acronym`) `Select IaaS or _PaaS`_. Based on the Federal Information Processing Standard (FIPS) security impact categorization of Low (Confidentiality = Low, Integrity = Low, Availability = Low) and specifically the FedRAMP _Tailored_ Low Impact Software-as-a-Service (LISaaS) Security Requirements,[^1]`Federal Agency/Office` has determined that `System Acronym` meets the information security requirements and is granted `Federal Agency/Office` FedRAMP Authorization to Operate (ATO).

The FedRAMP _Tailored_ LISaaS Baseline established by the FedRAMP Joint Authorization Board (JAB) defines the minimum security requirements for SaaS systems and applications that meet specific criteria for use by agencies.

_`Insert information regarding the appropriate use, purposes and restrictions for use of this SaaS`_

The `Federal Agency/Office` has determined this `CSP system Name` ATOis applicable for use by `Federal Agency/Office` users for the following purposes, and with the following restrictions:

- _Purpose Example: This application is authorized for use by `Federal Agency/Office` users and contractors for Federal business collaboration and management purposes only._
- _Restriction Example: No Personally Identifiable Information (PII) data may be stored, processed, or transmitted with this application__._

Based on the assessment conducted by `Assessment Organization Name`, and review by `Federal Agency/Office's` Authorization Organization the `CSP and/or CSP System Name` has been implemented and is maintained at an acceptable level of risk.

`_Edit the following as appropriate, if known risks or security controls are not implemented and have been accepted by the Authorization Organization specifically for this ATO_`

The following is a list of known vulnerabilities and risks of the `CSP Name/System Name` that have been determined as acceptable for the specific use and with the specified restrictions:

- _Example risk accepted: Support for acceptance of PIV/CAC credentials for Federal privileged users `has not been implemented_ r _is planned for implementation by `date`._
- _Example risk accepted: Implementation of continuous monitoring is based on `enter continuous monitoring process information here`.  _

The security authorization of the information system will remain in effect for a length of time in alignment with Office of Management and Budget Circular A-130 as long as:

1. `CSP Acronym` satisfies the requirement of implementing continuous monitoring activities in accordance with FedRAMP _Tailored_ LISaaS continuous monitoring requirements and/or as agreed between `Federal Agency/Office` and`System Acronym`.
2. `CSP Acronym` mitigates open vulnerabilities in accordance with FedRAMP requirements and as agreed between `Federal Agency/Office` and `System Acronym`.
3. Significant changes or critical vulnerabilities are identified and managed in accordance with applicable Federal law, guidelines, policies, and best practices.

`System Acronym` is delivered as an SaaS offering using a multi-tenant `Deployment Model` cloud computing environment. It is available to `Insert scope of customers exactly as stated in the documentation (for example, Public, Federal Only, Hybrid community)`.

`Brief system description provided by CSP`

Federal Agencies are encouraged to leverage this Agency FedRAMP ATO as a key element of their own ATO as applicable. The package associated with the IaaS and/or PaaS `System Acronym` ATO must be considered with this `System Acronym`ATO. `Federal Agency/Office` believes the `System Acronym` and `System Acronym`FedRAMP Security Authorization Packages accurately document and clearly define the aggregate outstanding risk considerations, when viewed in concert. Agency customers must consider the aggregate risk for the LISaaS and underlying systems when granting an ATO.

Copies of authorization packages are available for agency review in the FedRAMP Secure Repository. If you have any questions or comments regarding this ATO, please contact `Agency ATO contact information`.

**APPROVED:**
`_______________X`

`Agency AO Name`

`Agency AO Title`

`Agency Name`


[^1]: [_FedRAMP Tailored Low Impact Software-as-a Service (LISaaS) Requirements_ and _FedRAMP Tailored Low Impact Software-as-a-Service__Template_] will be available at [www.fedramp.gov](http://www.fedramp.gov).

# APPENDIX D - FedRAMP _Tailored_ Continuous Monitoring Requirements
*in development*

APPENDIX E - FedRAMP _Tailored_ Self-Attestation Requirements
[Download as a Word Document](/static/static/APPENDIX E—FedRAMP Tailored Self-Attestation Requirements DRAFT v 0.1.docx)

**FedRAMP Tailored Self-Attestation Requirements**

Cloud Service Providers (CSPs) must attest to meeting the intent of the implementations of the security controls below. CSPs are not required to implement the security controls as explicitly stated in the security controls statement, however vendors must attest to meeting the intent of the controls.

For example, for AT-2, a CSP would attest to the fact that CSP staff are appropriate trained on security awareness issues. The details of the training and an assessment of the training are not required as a part of the assessment and authorization under FedRAMP _Tailored_.

If a vendor does not meet the intent of any of the security controls below, a vendor must identify that security control in their attestation to state that they do not implement that control and agency Authorizing Officials must be aware when making a risk based determination to authorize that system for use.

**CSP ATTESTATION**

`CSP` attests to meeting the intent of all of the security controls in table E-1 below. Any details about the security controls agency Authorizing Officials should be aware of are noted in the last column of Table E-1.

`CSP System Owner`
`Signature `
`Date`

TABLE E-1

| Control ID | Control Name                                                                                        | Additional Control Information and Comments                                                                                                                                                      | CSP Implementation Notes |
|------------|-----------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------|
| AC-1       | Access Control Policy and Procedures                                                                |                                                                                                                                                                                                  |                          |
| AC-7       | Unsuccessful Login Attempts                                                                         | NSO - for non-privileged users; Attestation - for privileged users related to multi-factor identification and authentication                                                                     |                          |
| AC-20      | Use of External Information Systems                                                                 |                                                                                                                                                                                                  |                          |
| AT-1       | Security Awareness and Training Policy and Procedures                                               |                                                                                                                                                                                                  |                          |
| AT-2       | Security Awareness Training                                                                         |                                                                                                                                                                                                  |                          |
| AT-3       | Role-Based Security Training                                                                        |                                                                                                                                                                                                  |                          |
| AT-4       | Security Training Records                                                                           |                                                                                                                                                                                                  |                          |
| AU-1       | Audit and Accountability Policy and Procedures                                                      |                                                                                                                                                                                                  |                          |
| AU-2       | Audit Events                                                                                        |                                                                                                                                                                                                  |                          |
| AU-8       | Time Stamps                                                                                         |                                                                                                                                                                                                  |                          |
| AU-9       | Protection of Audit Information                                                                     |                                                                                                                                                                                                  |                          |
| AU-12      | Audit Generation                                                                                    |                                                                                                                                                                                                  |                          |
| CA-1       | Security Assessment and Authorization Policies and Procedures                                       |                                                                                                                                                                                                  |                          |
| CA-2 (1)   | Security Assessments | Independent Assessors                                                        |                                                                                                                                                                                                  |                          |
| CA-3       | System Interconnections                                                                             |                                                                                                                                                                                                  |                          |
| CA-5       | Plan of Action and Milestones                                                                       | Attestation - for compliance with FedRAMP Tailored LISaaS Continuous Monitoring Requirements                                                                                                     |                          |
| CM-1       | Configuration Management Policy and Procedures                                                      |                                                                                                                                                                                                  |                          |
| CM-2       | Baseline Configuration                                                                              |                                                                                                                                                                                                  |                          |
| CM-7       | Least Functionality                                                                                 |                                                                                                                                                                                                  |                          |
| CP-1       | Contingency Planning Policy and Procedures                                                          |                                                                                                                                                                                                  |                          |
| IA-1       | Identification and Authentication Policy and Procedures                                             |                                                                                                                                                                                                  |                          |
| IA-2       | Identification and Authentication (Organizational Users)                                            | NSO -for non-privileged users; Attestation - for privileged users related to multi-factor identification and authentication - specifically include description of management of service accounts |                          |
| IA-4       | Identifier Management                                                                               |                                                                                                                                                                                                  |                          |
| IA-5       | Authenticator Management                                                                            |                                                                                                                                                                                                  |                          |
| IA-5 (1)   | Authenticator Management | Password-Based Authentication                                            |                                                                                                                                                                                                  |                          |
| IA-7       | Cryptographic Module Authentication                                                                 |                                                                                                                                                                                                  |                          |
| IA-8       | Identification and Authentication (NonOrganizational Users)                                         |                                                                                                                                                                                                  |                          |
| IA-8 (3)   | Identification and Authentication (NonOrganizational Users) | Acceptance of FICAM-Approved Products |                                                                                                                                                                                                  |                          |
| IA-8 (4)   | Identification and Authentication (NonOrganizational Users) | Use of FICAM-Issued Profiles          |                                                                                                                                                                                                  |                          |
| IR-1       | Incident Response Policy and Procedures                                                             |                                                                                                                                                                                                  |                          |
| IR-2       | Incident Response Training                                                                          |                                                                                                                                                                                                  |                          |
| IR-5       | Incident Monitoring                                                                                 |                                                                                                                                                                                                  |                          |
| IR-7       | Incident Response Assistance                                                                        |                                                                                                                                                                                                  |                          |
| IR-8       | Incident Response Plan                                                                              | Attestation - Specifically attest to US-CERT compliance                                                                                                                                          |                          |
| IR-9       | Information Spillage Response                                                                       | Attestation - Specifically describe information spillage response processes                                                                                                                      |                          |
| MA-1       | System Maintenance Policy and Procedures                                                            |                                                                                                                                                                                                  |                          |
| MA-2       | Controlled Maintenance                                                                              | CSP includes inherited controls in self-attestation                                                                                                                                              |                          |
| MA-4       | Nonlocal Maintenance                                                                                |                                                                                                                                                                                                  |                          |
| MA-5       | Maintenance Personnel                                                                               | CSP includes inherited controls in self-attestation                                                                                                                                              |                          |
| MP-1       | Media Protection Policy and Procedures                                                              |                                                                                                                                                                                                  |                          |
| MP-2       | Media Access                                                                                        | CSP includes inherited controls in self-attestation                                                                                                                                              |                          |
| MP-6       | Media Sanitization                                                                                  | CSP includes inherited controls in self-attestation                                                                                                                                              |                          |
| MP-7       | Media Use                                                                                           | CSP includes inherited controls in self-attestation                                                                                                                                              |                          |
| PE-1       | Physical and Environmental Protection Policy and Procedures                                         |                                                                                                                                                                                                  |                          |
| PE-2       | Physical Access Authorizations                                                                      | CSP includes inherited controls in self-attestation                                                                                                                                              |                          |
| PE-3       | Physical Access Control                                                                             | CSP includes inherited controls in self-attestation                                                                                                                                              |                          |
| PE-6       | Monitoring Physical Access                                                                          | CSP includes inherited controls in self-attestation                                                                                                                                              |                          |
| PE-8       | Visitor Access Records                                                                              | CSP includes inherited controls in self-attestation                                                                                                                                              |                          |
| PE-12      | Emergency Lighting                                                                                  | CSP includes inherited controls in self-attestation                                                                                                                                              |                          |
| PE-13      | Fire Protection                                                                                     | CSP includes inherited controls in self-attestation                                                                                                                                              |                          |
| PE-14      | Temperature and Humidity Controls                                                                   | CSP includes inherited controls in self-attestation                                                                                                                                              |                          |
| PE-15      | Water Damage Protection                                                                             | CSP includes inherited controls in self-attestation                                                                                                                                              |                          |
| PE-16      | Delivery and Removal                                                                                | CSP includes inherited controls in self-attestation                                                                                                                                              |                          |
| PL-1       | Security Planning Policy and Procedures                                                             |                                                                                                                                                                                                  |                          |
| PL-4       | Rules of Behavior                                                                                   |                                                                                                                                                                                                  |                          |
| PS-1       | Personnel Security Policy and Procedures                                                            |                                                                                                                                                                                                  |                          |
| PS-4       | Personnel Termination                                                                               |                                                                                                                                                                                                  |                          |
| PS-5       | Personnel Transfer                                                                                  |                                                                                                                                                                                                  |                          |
| PS-6       | Access Agreements                                                                                   |                                                                                                                                                                                                  |                          |
| PS-7       | Third-Party Personnel Security                                                                      | Attestation - Specifically stating that any third-party security personnel are treated as CSP employees                                                                                          |                          |
| PS-8       | Personnel Sanctions                                                                                 |                                                                                                                                                                                                  |                          |
| RA-1       | Risk Assessment Policy and Procedures                                                               |                                                                                                                                                                                                  |                          |
| SA-1       | System and Services Acquisition Policy and Procedures                                               |                                                                                                                                                                                                  |                          |
| SA-2       | Allocation of Resources                                                                             |                                                                                                                                                                                                  |                          |
| SA-3       | System Development Life Cycle                                                                       |                                                                                                                                                                                                  |                          |
| SA-4       | Acquisition Process                                                                                 |                                                                                                                                                                                                  |                          |
| SA-4 (10)  | Acquisition Process | Use of Approved PIV Products                                                  |                                                                                                                                                                                                  |                          |
| SA-5       | Information System Documentation                                                                    |                                                                                                                                                                                                  |                          |
| SC-1       | System and Communications Protection Policy and Procedures                                          |                                                                                                                                                                                                  |                          |
| SC-20      | Secure Name /Address Resolution Service (Authoritative Source)                                      |                                                                                                                                                                                                  |                          |
| SC-21      | Secure Name /Address Resolution Service (Recursive or Caching Resolver)                             |                                                                                                                                                                                                  |                          |
| SC-22      | Architecture and Provisioning for Name/Address Resolution Service                                   |                                                                                                                                                                                                  |                          |
| SC-39      | Process Isolation                                                                                   |                                                                                                                                                                                                  |                          |
| SI-1       | System and Information Integrity Policy and Procedures                                              |                                                                                                                                                                                                  |                          |
| SI-5       | Security Alerts, Advisories, and Directives                                                         |                                                                                                                                                                                                  |                          |
| SI-12      | Information Handling and Retention                                                                  | Attestation - Specifically related to US-CERT and FedRAMP communications procedures                                                                                                              |                          |
