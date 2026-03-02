# CMMC Compliance Checklist — CMMC Level 2 Self-Assessment Guide

[![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC_BY--SA_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/)
[![CMMC Version](https://img.shields.io/badge/CMMC-2.0-blue.svg)]()
[![NIST SP 800-171](https://img.shields.io/badge/NIST-SP_800--171_Rev_2-green.svg)]()

A comprehensive, open-source **CMMC compliance checklist** for defense contractors and organizations in the Defense Industrial Base (DIB) preparing for **CMMC Level 2 certification**. This checklist covers all 110 security requirements from NIST SP 800-171 Rev. 2, organized by control family with implementation guidance and assessment tips.

> **Maintained by [Petronella Technology Group](https://petronellatech.com)** — A cybersecurity and compliance firm based in Raleigh, NC with 23+ years of experience helping organizations achieve and maintain compliance. For professional CMMC assessment and implementation services, visit our [CMMC Compliance page](https://petronellatech.com/compliance/cmmc/).

---

## Table of Contents

- [What is CMMC?](#what-is-cmmc)
- [Who Needs CMMC Compliance?](#who-needs-cmmc-compliance)
- [CMMC 2.0 Levels Overview](#cmmc-20-levels-overview)
- [How to Use This Checklist](#how-to-use-this-checklist)
- [CMMC Level 2 Checklist by Control Family](#cmmc-level-2-checklist-by-control-family)
  - [Access Control (AC)](#access-control-ac)
  - [Awareness and Training (AT)](#awareness-and-training-at)
  - [Audit and Accountability (AU)](#audit-and-accountability-au)
  - [Configuration Management (CM)](#configuration-management-cm)
  - [Identification and Authentication (IA)](#identification-and-authentication-ia)
  - [Incident Response (IR)](#incident-response-ir)
  - [Maintenance (MA)](#maintenance-ma)
  - [Media Protection (MP)](#media-protection-mp)
  - [Personnel Security (PS)](#personnel-security-ps)
  - [Physical Protection (PE)](#physical-protection-pe)
  - [Risk Assessment (RA)](#risk-assessment-ra)
  - [Security Assessment (CA)](#security-assessment-ca)
  - [System and Communications Protection (SC)](#system-and-communications-protection-sc)
  - [System and Information Integrity (SI)](#system-and-information-integrity-si)
- [CMMC Assessment Preparation Tips](#cmmc-assessment-preparation-tips)
- [Scoring Your Self-Assessment](#scoring-your-self-assessment)
- [Common CMMC Compliance Gaps](#common-cmmc-compliance-gaps)
- [CMMC Timeline and Deadlines](#cmmc-timeline-and-deadlines)
- [Additional Resources](#additional-resources)
- [About](#about)

---

## What is CMMC?

The **Cybersecurity Maturity Model Certification (CMMC)** is the Department of Defense's framework for verifying that defense contractors implement adequate cybersecurity practices to protect **Controlled Unclassified Information (CUI)** and **Federal Contract Information (FCI)**. CMMC 2.0 streamlined the original five-level model into three levels, with Level 2 aligning directly to the 110 security requirements in NIST SP 800-171 Rev. 2.

Under the **CMMC 2.0 Final Rule** (32 CFR Part 170), defense contractors handling CUI must achieve CMMC Level 2 certification through either a self-assessment or a third-party assessment conducted by a CMMC Third-Party Assessment Organization (C3PAO), depending on the sensitivity of the CUI involved.

## Who Needs CMMC Compliance?

CMMC compliance is required for:

- **Prime contractors** holding DoD contracts involving CUI
- **Subcontractors** at any tier who handle, process, store, or transmit CUI
- **IT service providers** (MSPs/MSSPs) supporting defense contractors
- **Cloud service providers** hosting CUI for DIB organizations
- **Manufacturers and suppliers** in the defense supply chain

If your organization has a DFARS 252.204-7012 clause in any contract, you are expected to comply with NIST SP 800-171 and will eventually need CMMC certification.

## CMMC 2.0 Levels Overview

| Level | Name | Requirements | Assessment Type |
|-------|------|-------------|-----------------|
| **Level 1** | Foundational | 17 practices (FAR 52.204-21) | Annual self-assessment |
| **Level 2** | Advanced | 110 requirements (NIST SP 800-171) | Self-assessment or C3PAO assessment |
| **Level 3** | Expert | 110+ requirements (NIST SP 800-172) | Government-led assessment (DIBCAC) |

This checklist focuses on **CMMC Level 2**, which is the most common requirement for defense contractors handling CUI.

## How to Use This Checklist

1. **Download or fork** this repository
2. **Work through each control family** systematically
3. **Mark each requirement** as Implemented, Partially Implemented, Planned, or Not Applicable
4. **Document evidence** for each implemented control (policies, screenshots, configurations)
5. **Create POA&Ms** (Plans of Action and Milestones) for any gaps
6. **Calculate your SPRS score** using the scoring methodology in NIST SP 800-171A
7. **Submit your score** to the Supplier Performance Risk System (SPRS)

For a downloadable CSV version of this checklist, see [`cmmc-level2-checklist.csv`](cmmc-level2-checklist.csv).

---

## CMMC Level 2 Checklist by Control Family

### Access Control (AC)

The Access Control family contains 22 requirements focused on limiting system access to authorized users, processes, and devices.

| # | Requirement ID | Requirement | Status |
|---|---------------|-------------|--------|
| 1 | 3.1.1 | Limit system access to authorized users, processes acting on behalf of authorized users, and devices (including other systems) | [ ] |
| 2 | 3.1.2 | Limit system access to the types of transactions and functions that authorized users are permitted to execute | [ ] |
| 3 | 3.1.3 | Control the flow of CUI in accordance with approved authorizations | [ ] |
| 4 | 3.1.4 | Separate the duties of individuals to reduce the risk of malevolent activity without collusion | [ ] |
| 5 | 3.1.5 | Employ the principle of least privilege, including for specific security functions and privileged accounts | [ ] |
| 6 | 3.1.6 | Use non-privileged accounts or roles when accessing nonsecurity functions | [ ] |
| 7 | 3.1.7 | Prevent non-privileged users from executing privileged functions and capture the execution of such functions in audit logs | [ ] |
| 8 | 3.1.8 | Limit unsuccessful logon attempts | [ ] |
| 9 | 3.1.9 | Provide privacy and security notices consistent with applicable CUI rules | [ ] |
| 10 | 3.1.10 | Use session lock with pattern-hiding displays to prevent access and viewing of data after a period of inactivity | [ ] |
| 11 | 3.1.11 | Terminate (automatically) a user session after a defined condition | [ ] |
| 12 | 3.1.12 | Monitor and control remote access sessions | [ ] |
| 13 | 3.1.13 | Employ cryptographic mechanisms to protect the confidentiality of remote access sessions | [ ] |
| 14 | 3.1.14 | Route remote access via managed access control points | [ ] |
| 15 | 3.1.15 | Authorize remote execution of privileged commands and remote access to security-relevant information | [ ] |
| 16 | 3.1.16 | Authorize wireless access prior to allowing such connections | [ ] |
| 17 | 3.1.17 | Protect wireless access using authentication and encryption | [ ] |
| 18 | 3.1.18 | Control connection of mobile devices | [ ] |
| 19 | 3.1.19 | Encrypt CUI on mobile devices and mobile computing platforms | [ ] |
| 20 | 3.1.20 | Verify and control/limit connections to and use of external systems | [ ] |
| 21 | 3.1.21 | Limit use of portable storage devices on external systems | [ ] |
| 22 | 3.1.22 | Control CUI posted or processed on publicly accessible systems | [ ] |

**Implementation Tips:**
- Deploy a centralized identity management solution (Active Directory, Azure AD, or equivalent)
- Implement role-based access control (RBAC) across all systems in the CUI boundary
- Configure account lockout policies (e.g., 3-5 failed attempts, 15-30 minute lockout)
- Enable screen lock timeout at 15 minutes or less for all workstations
- Use FIPS-validated encryption (AES-256) for all remote access (VPN, RDP)
- Maintain an access control policy document reviewed at least annually

### Awareness and Training (AT)

| # | Requirement ID | Requirement | Status |
|---|---------------|-------------|--------|
| 23 | 3.2.1 | Ensure that managers, systems administrators, and users of organizational systems are made aware of the security risks associated with their activities and of the applicable policies, standards, and procedures related to the security of those systems | [ ] |
| 24 | 3.2.2 | Ensure that personnel are trained to carry out their assigned information security-related duties and responsibilities | [ ] |
| 25 | 3.2.3 | Provide security awareness training on recognizing and reporting potential indicators of insider threat | [ ] |

**Implementation Tips:**
- Conduct security awareness training within 30 days of hire and at least annually thereafter
- Include phishing simulation exercises as part of the training program
- Document all training activities with dates, attendees, and topics covered
- Cover topics: social engineering, phishing, password hygiene, physical security, CUI handling, incident reporting

### Audit and Accountability (AU)

| # | Requirement ID | Requirement | Status |
|---|---------------|-------------|--------|
| 26 | 3.3.1 | Create and retain system audit logs and records to the extent needed to enable the monitoring, analysis, investigation, and reporting of unlawful or unauthorized system activity | [ ] |
| 27 | 3.3.2 | Ensure that the actions of individual system users can be uniquely traced to those users, so they can be held accountable for their actions | [ ] |
| 28 | 3.3.3 | Review and update logged events | [ ] |
| 29 | 3.3.4 | Alert in the event of an audit logging process failure | [ ] |
| 30 | 3.3.5 | Correlate audit record review, analysis, and reporting processes to support organizational processes for investigation and response to indications of unlawful, unauthorized, suspicious, or unusual activity | [ ] |
| 31 | 3.3.6 | Provide audit record reduction and report generation to support on-demand analysis and reporting | [ ] |
| 32 | 3.3.7 | Provide a system capability that compares and synchronizes internal system clocks with an authoritative source to generate time stamps for audit records | [ ] |
| 33 | 3.3.8 | Protect audit information and audit logging tools from unauthorized access, modification, and deletion | [ ] |
| 34 | 3.3.9 | Limit management of audit logging functionality to a subset of privileged users | [ ] |

**Implementation Tips:**
- Deploy a SIEM solution for centralized log collection and analysis
- Enable audit logging on all systems within the CUI boundary (Windows Event Logs, syslog, application logs)
- Configure NTP synchronization across all systems
- Retain audit logs for a minimum of 90 days online, 1 year archived
- Review logs at least weekly for anomalous activity

### Configuration Management (CM)

| # | Requirement ID | Requirement | Status |
|---|---------------|-------------|--------|
| 35 | 3.4.1 | Establish and maintain baseline configurations and inventories of organizational systems (including hardware, software, firmware, and documentation) throughout the respective system development life cycles | [ ] |
| 36 | 3.4.2 | Establish and enforce security configuration settings for information technology products employed in organizational systems | [ ] |
| 37 | 3.4.3 | Track, review, approve or disapprove, and log changes to organizational systems | [ ] |
| 38 | 3.4.4 | Analyze the security impact of changes prior to implementation | [ ] |
| 39 | 3.4.5 | Define, document, approve, and enforce physical and logical access restrictions associated with changes to organizational systems | [ ] |
| 40 | 3.4.6 | Employ the principle of least functionality by configuring organizational systems to provide only essential capabilities | [ ] |
| 41 | 3.4.7 | Restrict, disable, or prevent the use of nonessential programs, functions, ports, protocols, and services | [ ] |
| 42 | 3.4.8 | Apply deny-by-exception (blacklisting) policy to prevent the use of unauthorized software or deny-all, permit-by-exception (whitelisting) policy to allow the execution of authorized software | [ ] |
| 43 | 3.4.9 | Control and monitor user-installed software | [ ] |

**Implementation Tips:**
- Use CIS Benchmarks or DISA STIGs as baseline configurations
- Implement a formal change management process with documented approvals
- Maintain a current hardware and software inventory (updated at least quarterly)
- Disable unnecessary services, ports, and protocols on all systems
- Consider application whitelisting for systems processing CUI

### Identification and Authentication (IA)

| # | Requirement ID | Requirement | Status |
|---|---------------|-------------|--------|
| 44 | 3.5.1 | Identify system users, processes acting on behalf of users, and devices | [ ] |
| 45 | 3.5.2 | Authenticate (or verify) the identities of users, processes, or devices, as a prerequisite to allowing access to organizational systems | [ ] |
| 46 | 3.5.3 | Use multifactor authentication for local and network access to privileged accounts and for network access to non-privileged accounts | [ ] |
| 47 | 3.5.4 | Employ replay-resistant authentication mechanisms for network access to privileged and non-privileged accounts | [ ] |
| 48 | 3.5.5 | Prevent reuse of identifiers for a defined period | [ ] |
| 49 | 3.5.6 | Disable identifiers after a defined period of inactivity | [ ] |
| 50 | 3.5.7 | Enforce a minimum password complexity and change of characters when new passwords are created | [ ] |
| 51 | 3.5.8 | Prohibit password reuse for a specified number of generations | [ ] |
| 52 | 3.5.9 | Allow temporary password use for system logons with an immediate change to a permanent password | [ ] |
| 53 | 3.5.10 | Store and transmit only cryptographically-protected passwords | [ ] |
| 54 | 3.5.11 | Obscure feedback of authentication information | [ ] |

**Implementation Tips:**
- Deploy MFA for all user accounts (hardware tokens, authenticator apps, or push notifications)
- Set minimum password length to 14+ characters per current NIST guidance
- Disable accounts after 90 days of inactivity
- Prohibit reuse of at least the last 24 passwords
- Use FIPS 140-2 validated cryptographic modules for password storage

### Incident Response (IR)

| # | Requirement ID | Requirement | Status |
|---|---------------|-------------|--------|
| 55 | 3.6.1 | Establish an operational incident-handling capability for organizational systems that includes preparation, detection, analysis, containment, recovery, and user response activities | [ ] |
| 56 | 3.6.2 | Track, document, and report incidents to designated officials and/or authorities both internal and external to the organization | [ ] |
| 57 | 3.6.3 | Test the organizational incident response capability | [ ] |

**Implementation Tips:**
- Develop a written incident response plan (see our [Incident Response Plan Template](https://github.com/capetron/incident-response-plan-template))
- Designate an incident response team with defined roles and responsibilities
- Conduct tabletop exercises at least annually
- Know your reporting obligations: DFARS requires reporting cyber incidents to DIBNet within 72 hours
- Document all incidents, actions taken, and lessons learned

### Maintenance (MA)

| # | Requirement ID | Requirement | Status |
|---|---------------|-------------|--------|
| 58 | 3.7.1 | Perform maintenance on organizational systems | [ ] |
| 59 | 3.7.2 | Provide controls on the tools, techniques, mechanisms, and personnel used to conduct system maintenance | [ ] |
| 60 | 3.7.3 | Ensure equipment removed for off-site maintenance is sanitized of any CUI | [ ] |
| 61 | 3.7.4 | Check media containing diagnostic and test programs for malicious code before the media are used in organizational systems | [ ] |
| 62 | 3.7.5 | Require multifactor authentication to establish nonlocal maintenance sessions via external network connections and terminate such connections when nonlocal maintenance is complete | [ ] |
| 63 | 3.7.6 | Supervise the maintenance activities of maintenance personnel without required access authorization | [ ] |

### Media Protection (MP)

| # | Requirement ID | Requirement | Status |
|---|---------------|-------------|--------|
| 64 | 3.8.1 | Protect (i.e., physically control and securely store) system media containing CUI, both paper and digital | [ ] |
| 65 | 3.8.2 | Limit access to CUI on system media to authorized users | [ ] |
| 66 | 3.8.3 | Sanitize or destroy system media containing CUI before disposal or release for reuse | [ ] |
| 67 | 3.8.4 | Mark media with necessary CUI markings and distribution limitations | [ ] |
| 68 | 3.8.5 | Control access to media containing CUI and maintain accountability for media during transport outside of controlled areas | [ ] |
| 69 | 3.8.6 | Implement cryptographic mechanisms to protect the confidentiality of CUI stored on digital media during transport unless otherwise protected by alternative physical safeguards | [ ] |
| 70 | 3.8.7 | Control the use of removable media on system components | [ ] |
| 71 | 3.8.8 | Prohibit the use of portable storage devices when such devices have no identifiable owner | [ ] |
| 72 | 3.8.9 | Protect the confidentiality of backup CUI at storage locations | [ ] |

### Personnel Security (PS)

| # | Requirement ID | Requirement | Status |
|---|---------------|-------------|--------|
| 73 | 3.9.1 | Screen individuals prior to authorizing access to organizational systems containing CUI | [ ] |
| 74 | 3.9.2 | Ensure that organizational systems containing CUI are protected during and after personnel actions such as terminations and transfers | [ ] |

### Physical Protection (PE)

| # | Requirement ID | Requirement | Status |
|---|---------------|-------------|--------|
| 75 | 3.10.1 | Limit physical access to organizational systems, equipment, and the respective operating environments to authorized individuals | [ ] |
| 76 | 3.10.2 | Protect and monitor the physical facility and support infrastructure for organizational systems | [ ] |
| 77 | 3.10.3 | Escort visitors and monitor visitor activity | [ ] |
| 78 | 3.10.4 | Maintain audit logs of physical access | [ ] |
| 79 | 3.10.5 | Control and manage physical access devices | [ ] |
| 80 | 3.10.6 | Enforce safeguarding measures for CUI at alternate work sites | [ ] |

### Risk Assessment (RA)

| # | Requirement ID | Requirement | Status |
|---|---------------|-------------|--------|
| 81 | 3.11.1 | Periodically assess the risk to organizational operations (including mission, functions, image, or reputation), organizational assets, and individuals, resulting from the operation of organizational systems and the associated processing, storage, or transmission of CUI | [ ] |
| 82 | 3.11.2 | Scan for vulnerabilities in organizational systems and applications periodically and when new vulnerabilities affecting those systems and applications are identified | [ ] |
| 83 | 3.11.3 | Remediate vulnerabilities in accordance with risk assessments | [ ] |

**Implementation Tips:**
- Conduct vulnerability scans at least monthly (internal and external)
- Perform a comprehensive risk assessment at least annually
- Remediate critical and high vulnerabilities within 30 days
- Maintain a risk register and track remediation progress

### Security Assessment (CA)

| # | Requirement ID | Requirement | Status |
|---|---------------|-------------|--------|
| 84 | 3.12.1 | Periodically assess the security controls in organizational systems to determine if the controls are effective in their application | [ ] |
| 85 | 3.12.2 | Develop and implement plans of action designed to correct deficiencies and reduce or eliminate vulnerabilities in organizational systems | [ ] |
| 86 | 3.12.3 | Monitor security controls on an ongoing basis to ensure the continued effectiveness of the controls | [ ] |
| 87 | 3.12.4 | Develop, document, and periodically update system security plans that describe system boundaries, system environments of operation, how security requirements are implemented, and the relationships with or connections to other systems | [ ] |

**Implementation Tips:**
- Develop a System Security Plan (SSP) that documents your CUI boundary and all 110 controls
- Create POA&Ms for all non-compliant controls with realistic remediation timelines
- Review and update the SSP at least annually or after significant changes
- Conduct internal security assessments at least annually

### System and Communications Protection (SC)

| # | Requirement ID | Requirement | Status |
|---|---------------|-------------|--------|
| 88 | 3.13.1 | Monitor, control, and protect communications (i.e., information transmitted or received by organizational systems) at the external boundaries and key internal boundaries of organizational systems | [ ] |
| 89 | 3.13.2 | Employ architectural designs, software development techniques, and systems engineering principles that promote effective information security within organizational systems | [ ] |
| 90 | 3.13.3 | Separate user functionality from system management functionality | [ ] |
| 91 | 3.13.4 | Prevent unauthorized and unintended information transfer via shared system resources | [ ] |
| 92 | 3.13.5 | Implement subnetworks for publicly accessible system components that are physically or logically separated from internal networks | [ ] |
| 93 | 3.13.6 | Deny network communications traffic by default and allow network communications traffic by exception (i.e., deny all, permit by exception) | [ ] |
| 94 | 3.13.7 | Prevent remote devices from simultaneously establishing non-remote connections with organizational systems and communicating via some other connection to resources in external networks (i.e., split tunneling) | [ ] |
| 95 | 3.13.8 | Implement cryptographic mechanisms to prevent unauthorized disclosure of CUI during transmission unless otherwise protected by alternative physical safeguards | [ ] |
| 96 | 3.13.9 | Terminate network connections associated with communications sessions at the end of the sessions or after a defined period of inactivity | [ ] |
| 97 | 3.13.10 | Establish and manage cryptographic keys for cryptography employed in organizational systems | [ ] |
| 98 | 3.13.11 | Employ FIPS-validated cryptography when used to protect the confidentiality of CUI | [ ] |
| 99 | 3.13.12 | Prohibit remote activation of collaborative computing devices and provide indication of devices in use to users present at the device | [ ] |
| 100 | 3.13.13 | Control and monitor the use of mobile code | [ ] |
| 101 | 3.13.14 | Control and monitor the use of Voice over Internet Protocol (VoIP) technologies | [ ] |
| 102 | 3.13.15 | Protect the authenticity of communications sessions | [ ] |
| 103 | 3.13.16 | Protect the confidentiality of CUI at rest | [ ] |

### System and Information Integrity (SI)

| # | Requirement ID | Requirement | Status |
|---|---------------|-------------|--------|
| 104 | 3.14.1 | Identify, report, and correct system flaws in a timely manner | [ ] |
| 105 | 3.14.2 | Provide protection from malicious code at designated locations within organizational systems | [ ] |
| 106 | 3.14.3 | Monitor system security alerts and advisories and take action in response | [ ] |
| 107 | 3.14.4 | Update malicious code protection mechanisms when new releases are available | [ ] |
| 108 | 3.14.5 | Perform periodic scans of organizational systems and real-time scans of files from external sources as files are downloaded, opened, or executed | [ ] |
| 109 | 3.14.6 | Monitor organizational systems, including inbound and outbound communications traffic, to detect attacks and indicators of potential attacks | [ ] |
| 110 | 3.14.7 | Identify unauthorized use of organizational systems | [ ] |

**Implementation Tips:**
- Deploy endpoint detection and response (EDR) on all endpoints within the CUI boundary
- Enable automatic updates for operating systems and applications
- Subscribe to vulnerability feeds (CISA, vendor advisories)
- Patch critical vulnerabilities within 14 days of release
- Monitor network traffic with IDS/IPS at boundary points

---

## CMMC Assessment Preparation Tips

### Before Your Assessment

1. **Define your CUI boundary** — Know exactly where CUI enters, is processed, stored, and exits your environment
2. **Complete your SSP** — The System Security Plan is the single most important document for your assessment
3. **Prepare evidence binders** — Organize evidence for each of the 110 requirements (policies, configurations, screenshots, logs)
4. **Conduct a mock assessment** — Walk through every control as if a C3PAO assessor were asking the questions
5. **Train your staff** — Everyone in the CUI boundary should understand their role in protecting CUI
6. **Update your SPRS score** — Ensure your current score is accurately reported

### Common Evidence Types

| Evidence Type | Examples |
|--------------|---------|
| **Policies** | Access Control Policy, Incident Response Policy, System Security Plan |
| **Procedures** | Account provisioning procedures, change management procedures |
| **Technical** | Firewall rules, GPO screenshots, SIEM dashboards, MFA configuration |
| **Records** | Training records, audit logs, vulnerability scan reports, incident reports |
| **Plans** | POA&Ms, contingency plans, configuration management plans |

## Scoring Your Self-Assessment

CMMC Level 2 self-assessments use the NIST SP 800-171 DoD Assessment Methodology:

- **Maximum score**: 110 (all requirements fully implemented)
- **Each requirement starts at the value assigned** in the methodology (1, 3, or 5 points)
- **Deductions** are taken for unimplemented or partially implemented requirements
- **POA&Ms** can be used for some requirements but your score reflects the current state
- **Your score must be submitted to SPRS** (Supplier Performance Risk System)

A score of 110 means full compliance. Most organizations initially score between 50-80 and must remediate gaps before certification.

## Common CMMC Compliance Gaps

Based on industry experience, these are the most frequently observed gaps during CMMC assessments:

1. **Multifactor Authentication (3.5.3)** — MFA not deployed for all accounts, especially non-privileged network access
2. **Audit Log Review (3.3.5)** — Logs collected but not regularly reviewed or correlated
3. **FIPS-Validated Encryption (3.13.11)** — Using encryption that is not FIPS 140-2 validated
4. **CUI Boundary Definition** — Scope is too broad or too narrow, or data flows are not well documented
5. **System Security Plan** — SSP is incomplete, outdated, or does not reflect actual implementation
6. **Vulnerability Management (3.11.2)** — Scans not performed regularly, or remediation timelines not met
7. **Media Protection (3.8.3)** — No documented process for sanitizing media before disposal
8. **Security Awareness Training (3.2.1)** — Training is generic and does not cover CUI-specific handling
9. **Incident Response Testing (3.6.3)** — No evidence of tabletop exercises or incident response drills
10. **Configuration Baselines (3.4.1)** — No documented baseline configurations or system inventory

## CMMC Timeline and Deadlines

The CMMC 2.0 Final Rule was published in October 2024, with a phased implementation:

- **Phase 1** (starting 2025): CMMC Level 1 self-assessments and Level 2 self-assessments appear in contracts
- **Phase 2** (starting 2026): Level 2 C3PAO assessments begin appearing in contracts
- **Phase 3** (starting 2027): Level 3 requirements appear in contracts
- **Phase 4** (starting 2028): Full implementation across all applicable contracts

Organizations should begin preparation now, as remediation typically takes 6-18 months depending on the current security posture.

## Additional Resources

### Official Sources
- [NIST SP 800-171 Rev. 2](https://csrc.nist.gov/publications/detail/sp/800-171/rev-2/final) — The source requirements for CMMC Level 2
- [NIST SP 800-171A](https://csrc.nist.gov/publications/detail/sp/800-171a/final) — Assessment procedures
- [CMMC Program Website](https://dodcio.defense.gov/CMMC/) — Official DoD CMMC program page
- [SPRS Portal](https://www.sprs.csd.disa.mil/) — Submit your self-assessment score
- [Cyber AB (The Accreditation Body)](https://cyberab.org/) — Find C3PAOs and registered practitioners

### Related Open-Source Resources
- [NIST 800-171 Controls Matrix](https://github.com/capetron/nist-800-171-controls-matrix) — Detailed controls mapping with cross-references
- [Incident Response Plan Template](https://github.com/capetron/incident-response-plan-template) — Free IR plan template for CMMC compliance

### Professional CMMC Services
For organizations that need expert guidance on their CMMC compliance journey, [Petronella Technology Group](https://petronellatech.com/compliance/cmmc/) provides:

- **CMMC readiness assessments** and gap analysis
- **System Security Plan (SSP)** development
- **POA&M development** and remediation support
- **Managed security services** for ongoing compliance
- **CMMC assessment preparation** and evidence gathering support
- **CUI boundary scoping** and network architecture review

> Visit [petronellatech.com/compliance/cmmc/](https://petronellatech.com/compliance/cmmc/) to learn more about our CMMC compliance services.

---

## About

This CMMC compliance checklist is maintained by **[Petronella Technology Group](https://petronellatech.com)**, a cybersecurity and IT compliance firm headquartered in Raleigh, North Carolina. Founded in 2002, Petronella Technology Group has over 23 years of experience helping organizations in the Defense Industrial Base achieve and maintain compliance with CMMC, NIST, HIPAA, and other regulatory frameworks.

### Other Compliance Resources
- [HIPAA Security Risk Assessment Template](https://github.com/capetron/hipaa-security-risk-assessment-template)
- [NIST 800-171 Controls Matrix](https://github.com/capetron/nist-800-171-controls-matrix)
- [Incident Response Plan Template](https://github.com/capetron/incident-response-plan-template)
- [Cybersecurity Awareness Training Materials](https://github.com/capetron/cybersecurity-awareness-training-materials)

---

*This checklist is provided for informational purposes and should not be considered legal or compliance advice. Organizations should consult with qualified CMMC compliance professionals and legal counsel for their specific situation. This checklist is based on NIST SP 800-171 Rev. 2 and CMMC 2.0 requirements as of 2026.*

*Licensed under [CC-BY-SA-4.0](LICENSE). Contributions welcome — see [CONTRIBUTING.md](CONTRIBUTING.md).*
