---
title: FedRAMP Tailored
permalink: /policy/
layout: default
---

# Security Requirements for Low-Impact Software-as-a-Service (LISaaS) Cloud Services
**Version 1.0**

**Revision History**

* 1.0 - Initial version for publication and public comment

## Purpose

The Federal Risk and Authorization Management Program (FedRAMP) currently has three sets of baseline security requirements: The FedRAMP Low Impact Security Baseline, The FedRAMP Moderate Impact Security Baseline, and The FedRAMP High Impact Security Baseline. These three baselines have been focused on getting enterprise-wide services into the Federal space.

In discussions with digital services teams, Chief Technology Officers (CTOs) and Chief Information Officers (CIOs) across the U.S. Government, it is clear that there are many low-impact cloud services for low-risk use cases, for which a traditional enterprise-wide baseline with a one-size-fits-all approach does not work well. The FedRAMP Low Impact Baseline requires some Cloud Service Providers (CSPs) to implement more security controls than needed based on the type of use and the type of information being placed in the system by agencies. FedRAMP _Tailored_ is a means by which FedRAMP can address this problem. FedRAMP has followed National Institute of Standards and Technology (NIST) guidelines to create the current FedRAMP baseline security requirements; FedRAMP _Tailored_ also uses those same NIST guidelines to create a tailored approach to authorizing low-impact cloud services for specific use cases.

The FedRAMP _Tailored_ Baselineis consistent with NIST Special Publication (SP) 800-37, the NIST Risk Management Framework (RMF). Through this approach, FedRAMP has created criteria that allow agencies to approve certain types of cloud services currently in use or planned for use in support of agency-specific unique business and/or mission needs, such as collaborative management tools. This will reduce the time, money, and effort for agencies to approve low-impact systems for use, while maintaining compliance with applicable Federal laws, policies, and mandates.

Although the FedRAMP _Tailored_ Baseline provides a _minimum_ set of security control requirements, Authorizing Officials (AOs) have the responsibility of determining if additional security controls are required for compliance with agency-specific policies, procedures, and risk tolerance in order to issue an informed, risk-based, formal Authorization to Operate (ATO).

This document is the first iteration of the FedRAMP _Tailored_ Baseline and is focused only on Low-Impact Software-as-a-Service (LISaaS), with specific scoping capabilities for these services. Note that this process is designed specifically for agency authorizations of systems like collaboration tools, rather than Infrastructure-as-a-Service (IaaS) or Platform-as-a-Service (PaaS) offerings.

## Authority

The Federal Information Security Management Act [^1] (FISMA) requires agencies to authorize information systems for use. Agencies must follow the Office of Management and Budget (OMB) guidance in Circular A-130 [^2] in order to authorize services using the NIST RMF [^3]. Additionally, when a cloud system is being used, OMB requires that agencies use the FedRAMP requirements [^4] when completing the RMF.

The Joint Authorization Board (JAB), comprised of Chief Information Officers (CIOs) of Department of Homeland Security (DHS), General Services Administration (GSA) and Department of Defense (DoD); and the FedRAMP Management Office (PMO), established the minimum security requirements for cloud technology systems and the standardized policies and procedures for Government-wide adoption of FedRAMP. The FedRAMP requirements incorporate the applicable NIST SP 800-53 security controls, with tailoring of those controls to address implementations specific to cloud technology.

The FedRAMP _Tailored_ Baseline is specific to U.S. Federal Departments and Agencies and provides guidance to authorizing officials in issuing ATOs to cloud services that meet security requirements for specific business needs and use cases requiring protection of Government data with low impact for loss or confidentiality, integrity, and availability [^5].

FedRAMP follows the guidance specified in OMB A-130 and the RMF to tailor the security implementations and NIST security controls and baselines [^6] for cloud usage. To aid in re-use by agencies, FedRAMP develops mandatory templates that agencies and CSPs must use when completing a FedRAMP _Tailored_ LISaaS authorization.

## FedRAMP _Tailored_ LISaaS Requirements

FedRAMP follows the NIST RMF in order to determine the current FedRAMP security control baselines, and applies the steps specified in NIST SP 800-37 to determine a set of security controls for FedRAMP _Tailored_ LISaaS services.

The FedRAMP _Tailored_ Baseline is applicable only to cloud services that are implemented in FedRAMP Authorized cloud system with a current JAB Provisional Authorization (P-ATO) or an Agency FedRAMP ATO.

### Step 1 - Categorize Information System

To date, FedRAMP has prepared baselines for extremely broad and varied cloud systems and the information that can reside in them. We have defaulted to L-L-L, M-M-M, or H-H-H data types of information that could reside in those systems.

Federal Information Processing Standard 199 [^7] (FIPS 199), however, allows for a full range of information types. In order to meet specific, unique needs of systems, agencies can specify the types of information being placed in the cloud environment. For FedRAMP _Tailored_, agencies must specify the type of information that can reside in LISaaS systems.

To be considered a FedRAMP _Tailored_ LISaaS cloud service, the answer to all of the following questions must be &quot;yes&quot;:

1. Does the service operate in the cloud?
2. Is the cloud service fully operational?
3. Is the cloud service a Software-as-a-Service (SaaS), rather than Infrastructure-as-a-Service (IaaS) or a Platform-as-a-Service (PaaS)?
4. Does the cloud service provide services without requiring the collection of personally identifiable information (PII)? [^8]
5. Is the cloud service low-security-impact, according to the FIPS 199 definition?
6. Is the cloud service hosted within a FedRAMP Authorized infrastructure?

Such low-impact cloud services are the target for FedRAMP _Tailored._

### Step 2 - Select Security Controls

When examining L-L-L, M-M-M, or H-H-H information in SaaS systems in cloud environments for enterprise use, it makes sense that we have tailored above the NIST-recommended baselines. This was intended to maximize re-use by having enterprise-wide services that would fit all definitions of information in that environment.

For low-impact SaaS services, the L-L-L baseline requires some CSPs to implement more security controls than needed based on the type of use and the type of information being placed in the system by agencies. FedRAMP _Tailored_ will allow agencies to select a smaller set of controls, based on information types and use, for both appropriate and easier authorizations by agencies for these types of services. This tailoring process is explicitly allowed within NIST SP 800-53 revision 4.

Appendix A contains the FedRAMP recommended tailoring actions that have been carved out as security controls for the FedRAMP _Tailored_Baseline in accordance with the tailoring criteria established by NIST and FedRAMP. There are two criteria for eliminating a security control or control enhancement from the FedRAMP _Tailored LISaaS_ baseline:

- The control or control enhancement is uniquely Federal (i.e., primarily the responsibility of the Federal government);
- The control or control enhancement does not directly impact the security of a Cloud SaaS, as determined by FedRAMP. [^9]

In addition, the CSP is required to provide a self-attestation for those controls or control enhancements that are expected to be routinely satisfied by the CSP without further specification for implementation, and meet the intent of the security requirements. Appendix E contains the FedRAMP controls recommended for self-attestation by the CSP.

The CSP is also required to include those controls or control enhancements that are fully implemented by the infrastructure CSP and considered as FedRAMP &quot;inherited&quot; controls as part of the CSP self-attestation.

The criteria for tailoring of the FedRAMP _Tailored_Baseline and the results of the tailoring actions taken are documented in Appendix A, FedRAMP _Tailored_ Security Controls Baseline

### Step 3 - Implement Security Controls

CSPs must implement the controls and describe (in the FedRAMP _Tailored_ templates) how the controls are employed within the information system and its environment of operation.

The FedRAMP _Tailored_ Baseline also includes those controls and control enhancements that are implemented by the supporting infrastructure CSP and are indicated as &quot;inherited&quot; by the LISaaS CSP.

CSPs must also clearly delineate control implementations that are the responsibility of the agency customer to implement in order to fully meet the intent of the security requirement.

### Step 4 - Assess Security Controls

Appendix B provides mandatory templates and tailored test cases specific for FedRAMP _Tailored_. These must be used and applied to assure that the FedRAMP _Tailored_ controls have been implemented correctly, operate as intended, and produce the desired outcome to meet the security requirements of the system. The CSP is required to complete the templates; however, an agency may also assist the CSP in completing the documents.

Assessment of the implemented controls may be performed by an independent trusted third-party, such as a FedRAMP Accredited Third-Party Assessment Organization (3PAO), or the agency may perform the assessment. The degree of independence required is at the discretion of the Agency Authorizing Official (AO).

### Step 5 - Authorize Information System

An Agency AO must examine the implementation of the system and the risks associated with it in order to make a risk-based determination of its security posture. This is the basis for the Agency AO to authorize the system [^10] for use in their agency.

CSPs are required to address all the controls as specified in the FedRAMP _Tailored_ Baseline, whether the control is required for implementation, conditional for implementation, inherited from the infrastructure provider, and/or required for CSP self-attestation. The residual risks and determination of level of risk posture is based on those controls where the security requirements are not fully met by the CSP. Agency AOs will issue ATOs based on their agency-specific policies and procedures for their determination of an acceptable level of residual risk.

The evidence for this authorization rests in the ATO letter from the AO to the CSP. The letter should include the following:

1. Description of any agency control tailoring
2. Agency-specific authorized use of the system
3. Who assessed the system
4. Identification of the residual risks that were accepted by the AO in issuing the ATO

Appendix C contains the FedRAMP _Tailored_ ATO Letter Template.

Following the current FedRAMP processes and procedures, agencies can reuse a FedRAMP _Tailored_ LISaaS Authorization from another agency by reviewing the authorization package, making their own risk-based decision (including determining whether additional controls are required), and issue their own ATO.

### Step 6 - Monitor Security Controls

Agencies must monitor the effectiveness of security controls for all authorized systems. CSPs must employ a program of continuous monitoring that includes assessing control effectiveness, documenting changes to the system or its environment of operation, conducting security impact analyses of the associated changes, and reporting the security state of the system. CSPs must report on this program to Agency AOs for continued security authorizations for use.

FedRAMP provides guidance on how agencies must continuously monitor authorized systems for continued use and management of risk. FedRAMP _Tailored_ provides specialized monitoring procedures targeted at the FedRAMP _Tailored_ Baseline set of controls. Appendix D contains the FedRAMP _Tailored_ Continuous Monitoring Requirements.

## References

[^1]: [Federal Information Security Management Act of 2002](http://csrc.nist.gov/drivers/documents/FISMA-final.pdf)

[^2]: [_MEMORANDUM FOR HEADS OF EXECUTIVE DEPARTMENTS AND AGENCIES: Management of Federal Information Resources_, July 28, 2016](https://www.federalregister.gov/documents/2016/07/28/2016-17872/revision-of-omb-circular-no-a-130-managing-information-as-a-strategic-resource)

[^3]: [NIST Special Publication 800-37 Revision 1, _Guide for Applying the Risk Management Framework to Federal Information Systems,_ February 2010 (NIST SP 800-377](http://csrc.nist.gov/publications-nistpubs/800-37rev1/sp800-37)

[^4]: [_MEMORANDUM FOR CHIEF INFORMATION OFFICERS: Security Authorization of Information Systems in Cloud Computing Environments_, December 8, 2011](https://www.whitehouse.gov/sites/default/files/omb/assets/egov_docs/fedrampmemo.pdf)

[^5]: Refer to the _Agency Guide for FedRAMP Authorizations Handbook_ for specific, step-by-step details in completing initial FedRAMP ATOs and for re-using FedRAMP ATOs issued by other Government entities.

[^6]: [NIST Special Publication 800-53 Revision 4, _Security and Privacy Controls for Federal Information Systems and Organizations controls_, April 2013](http://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-53r4.pdf)

[^7]: [FIPS Pub 199: FEDERAL INFORMATION PROCESSING STANDARDS PUBLICATION: _Standards for Security Categorization of Federal Information and Information Syste_ms, February 2004](http://csrc.nist.gov/publications/fips/fips199/FIPS-PUB-199-final.pdf)

[^8]: Agencies have the responsibility of managing users and agency data to ensure that the LISaaS CSP services are utilized in accordance with Federal mandates and agency policies and procedures.

[^9]: FedRAMP used guiding principles from NIST SP 800-171 and the NIST Cybersecurity Framework when determining which controls were appropriate for the baseline for LISaaS solutions.

[^10]: All authorizations using FedRAMP _Tailored_ will be at the agency level and are not appropriate for Joint Authorization Board Provisional Authorizations, due to the unique scoping and specific use for each service authorized.
