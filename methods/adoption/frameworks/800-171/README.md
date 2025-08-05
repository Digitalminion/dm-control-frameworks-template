<!-- BEGIN AI HEADER: 65 LINES -->
<!-- BEGIN AI FILE SUMMARY -->
<!--
    TOPICS: nist-800-171, cui-protection, framework-adoption, implementation-checklist
    CONTENT: 800-171-overview, detailed-checklist, implementation-guidance, ai-instructions
    RELATED: methods/agent.md, methods/templates/, methods/adoption/, controls/, frameworks/
    RATING: foundational
    PURPOSE: NIST 800-171 Adoption - Detailed implementation checklist and guidance
    UPDATE: High
    Updated: 2025-01-27
-->
<!-- END AI FILE SUMMARY -->

<!-- BEGIN AI COMMENT -->
<!--
    800-171 FOLDER PURPOSE: This folder contains our detailed approach to adopting
    NIST Special Publication 800-171. It provides comprehensive checklists for each
    control family, enabling systematic implementation tracking.
    
    FRAMEWORK FOCUS: NIST 800-171 provides requirements for protecting controlled
    unclassified information (CUI) in nonfederal systems and organizations. It includes
    14 control families derived from NIST 800-53 for comprehensive CUI protection.
-->
<!-- END AI COMMENT -->

<!-- BEGIN AI INSTRUCTION -->
<!--
    AI AGENTS: For complete guidance see methods/agent.md.
    800-171 specific focus: Work with CUI protection controls across 14 families,
    monitor checkbox changes to trigger documentation creation, and coordinate
    with other frameworks in methods/adoption/frameworks/.
-->
<!-- END AI INSTRUCTION -->
<!-- END AI HEADER: 65 LINES -->

# NIST Special Publication 800-171 Adoption

> **Navigation:** [🏠 Root](../../../../README.md) › [📁 Methods](../../../README.md) › [📁 Adoption](../../README.md) › [📁 Frameworks](../README.md) › **800-171**

## Overview

This folder contains our detailed approach to adopting NIST Special Publication 800-171. This publication provides requirements for protecting controlled unclassified information (CUI) in nonfederal systems and organizations, with comprehensive coverage across 14 control families.

## Framework Structure

### Control Families

NIST 800-171 consists of 14 control families:

1. **Access Control (AC)**: Manage system access and permissions
2. **Awareness and Training (AT)**: Educate personnel on cybersecurity
3. **Audit and Accountability (AU)**: Monitor and log system activities
4. **Configuration Management (CM)**: Manage system configurations
5. **Identification and Authentication (IA)**: Verify user identities
6. **Incident Response (IR)**: Respond to security incidents
7. **Maintenance (MA)**: Maintain system security
8. **Media Protection (MP)**: Protect system media
9. **Personnel Security (PS)**: Ensure personnel trustworthiness
10. **Physical Protection (PE)**: Protect physical assets
11. **Risk Assessment (RA)**: Assess security risks
12. **Security Assessment (SA)**: Assess security controls
13. **System and Communications Protection (SC)**: Protect communications
14. **System and Information Integrity (SI)**: Maintain system integrity

### CUI Requirements

The framework addresses specific requirements for:

- **CUI Marking**: Proper identification and marking of controlled unclassified information
- **CUI Handling**: Secure handling, storage, and transmission of CUI
- **CUI Access**: Controlled access to CUI based on need-to-know
- **CUI Disposal**: Secure disposal of CUI when no longer needed

## Detailed Implementation Checklist

### Access Control (AC)

#### AC.1.001 - Access Control Policy and Procedures
- [ ] **AC.1.001a**: Develop, document, and disseminate access control policy
- [ ] **AC.1.001b**: Develop, document, and disseminate access control procedures
- [ ] **AC.1.001c**: Designate officials to manage access control policy and procedures
- [ ] **AC.1.001d**: Review and update access control policy and procedures

#### AC.1.002 - Account Management
- [ ] **AC.1.002a**: Identify and select account types
- [ ] **AC.1.002b**: Establish conditions for group and role membership
- [ ] **AC.1.002c**: Identify authorized users of the system
- [ ] **AC.1.002d**: Specify authorized privileges for each account type
- [ ] **AC.1.002e**: Require approvals by authorized personnel
- [ ] **AC.1.002f**: Establish, activate, modify, disable, and remove accounts
- [ ] **AC.1.002g**: Monitor the use of accounts
- [ ] **AC.1.002h**: Notify account managers when accounts are no longer required
- [ ] **AC.1.002i**: Authorize access to the system based on valid access authorization
- [ ] **AC.1.002j**: Review accounts for compliance with account management requirements

#### AC.1.003 - Access Enforcement
- [ ] **AC.1.003**: Enforce approved authorizations for logical access to information and system resources

#### AC.1.004 - Information Flow Enforcement
- [ ] **AC.1.004**: Enforce approved authorizations for controlling the flow of information within the system and between interconnected systems

#### AC.1.005 - Separation of Duties
- [ ] **AC.1.005a**: Identify and document separation of duties
- [ ] **AC.1.005b**: Document separation of duties of individuals
- [ ] **AC.1.005c**: Define system access authorizations supporting separation of duties

#### AC.1.006 - Least Privilege
- [ ] **AC.1.006a**: Employ the principle of least privilege
- [ ] **AC.1.006b**: Use non-privileged accounts or roles when accessing non-security functions
- [ ] **AC.1.006c**: Authorize access to security functions and security-relevant information

#### AC.1.007 - Unsuccessful Logon Attempts
- [ ] **AC.1.007a**: Enforce a limit of consecutive invalid logon attempts
- [ ] **AC.1.007b**: Automatically lock the account/node for a time period
- [ ] **AC.1.007c**: Delay next logon prompt when the maximum number of unsuccessful attempts is exceeded
- [ ] **AC.1.007d**: Notify the system administrator when the maximum number of unsuccessful attempts is exceeded
- [ ] **AC.1.007e**: Take additional actions when the maximum number of unsuccessful attempts is exceeded

#### AC.1.008 - System Use Notification
- [ ] **AC.1.008a**: Display an approved system use notification message
- [ ] **AC.1.008b**: Retain the notification message or banner on the screen
- [ ] **AC.1.008c**: Delay the display of the user interface until users acknowledge the notification message

#### AC.1.009 - Previous Logon (Access) Notification
- [ ] **AC.1.009a**: Notify the user upon successful logon (access) to the system
- [ ] **AC.1.009b**: Notify the user of the number of unsuccessful logon attempts since the last successful logon
- [ ] **AC.1.009c**: Notify the user upon successful logon (access) to the system

#### AC.1.010 - Concurrent Session Control
- [ ] **AC.1.010**: Limit the number of concurrent sessions for each account and/or account type

#### AC.1.011 - Session Lock
- [ ] **AC.1.011a**: Prevent further access to the system by initiating a session lock
- [ ] **AC.1.011b**: Retain the session lock until the user reestablishes access using established identification and authentication procedures

#### AC.1.012 - Session Termination
- [ ] **AC.1.012a**: Automatically terminate a user session after a defined time period
- [ ] **AC.1.012b**: Terminate a user session after a defined time period of inactivity
- [ ] **AC.1.012c**: Terminate a user session after a defined time period of inactivity

#### AC.1.013 - Supervision and Review - Access Control
- [ ] **AC.1.013a**: Employ automated mechanisms to facilitate the supervision and review of user actions
- [ ] **AC.1.013b**: Employ automated mechanisms to facilitate the supervision and review of user actions

#### AC.1.014 - Permitted Actions Without Identification or Authentication
- [ ] **AC.1.014a**: Identify user actions that can be performed on the system without identification or authentication
- [ ] **AC.1.014b**: Document and provide supporting rationale in the security plan for the system

#### AC.1.015 - Remote Access
- [ ] **AC.1.015a**: Establish and document the remote access methods that are allowed
- [ ] **AC.1.015b**: Establish and document the remote access methods that are allowed
- [ ] **AC.1.015c**: Establish and document the remote access methods that are allowed
- [ ] **AC.1.015d**: Establish and document the remote access methods that are allowed
- [ ] **AC.1.015e**: Establish and document the remote access methods that are allowed
- [ ] **AC.1.015f**: Establish and document the remote access methods that are allowed
- [ ] **AC.1.015g**: Establish and document the remote access methods that are allowed
- [ ] **AC.1.015h**: Establish and document the remote access methods that are allowed
- [ ] **AC.1.015i**: Establish and document the remote access methods that are allowed
- [ ] **AC.1.015j**: Establish and document the remote access methods that are allowed

#### AC.1.016 - Wireless Access
- [ ] **AC.1.016a**: Establish usage restrictions and configuration/connection requirements for wireless access
- [ ] **AC.1.016b**: Authorize wireless access to the system prior to allowing such connections
- [ ] **AC.1.016c**: Monitor for unauthorized wireless connections to the system
- [ ] **AC.1.016d**: Disconnect or disable wireless access to the system when such access is no longer authorized

#### AC.1.017 - Access Control for Mobile Devices
- [ ] **AC.1.017a**: Establish usage restrictions and configuration/connection requirements for mobile devices
- [ ] **AC.1.017b**: Authorize mobile device access to the system
- [ ] **AC.1.017c**: Monitor for unauthorized mobile device connections to the system
- [ ] **AC.1.017d**: Disconnect or disable mobile device access to the system when such access is no longer authorized
- [ ] **AC.1.017e**: Establish usage restrictions and configuration/connection requirements for mobile devices
- [ ] **AC.1.017f**: Authorize mobile device access to the system
- [ ] **AC.1.017g**: Monitor for unauthorized mobile device connections to the system
- [ ] **AC.1.017h**: Disconnect or disable mobile device access to the system when such access is no longer authorized

#### AC.1.018 - Use of External Information Systems
- [ ] **AC.1.018a**: Establish terms and conditions for authorized use of external information systems
- [ ] **AC.1.018b**: Verify that the external information system implements required security controls
- [ ] **AC.1.018c**: Verify that the external information system implements required security controls
- [ ] **AC.1.018d**: Verify that the external information system implements required security controls
- [ ] **AC.1.018e**: Verify that the external information system implements required security controls
- [ ] **AC.1.018f**: Verify that the external information system implements required security controls
- [ ] **AC.1.018g**: Verify that the external information system implements required security controls
- [ ] **AC.1.018h**: Verify that the external information system implements required security controls
- [ ] **AC.1.018i**: Verify that the external information system implements required security controls
- [ ] **AC.1.018j**: Verify that the external information system implements required security controls

#### AC.1.019 - Information Sharing
- [ ] **AC.1.019a**: Facilitate information sharing by enabling authorized users to determine whether access authorizations match access restrictions
- [ ] **AC.1.019b**: Employ automated mechanisms or manual processes for users to determine whether access authorizations match access restrictions
- [ ] **AC.1.019c**: Employ automated mechanisms or manual processes for users to determine whether access authorizations match access restrictions

#### AC.1.020 - Publicly Accessible Content
- [ ] **AC.1.020a**: Designate individuals authorized to post information onto publicly accessible information systems
- [ ] **AC.1.020b**: Train authorized individuals to ensure that publicly accessible information does not contain nonpublic information
- [ ] **AC.1.020c**: Review the content on publicly accessible information systems for nonpublic information
- [ ] **AC.1.020d**: Remove nonpublic information from publicly accessible information systems

### Awareness and Training (AT)

#### AT.1.001 - Awareness and Training Policy and Procedures
- [ ] **AT.1.001a**: Develop, document, and disseminate awareness and training policy
- [ ] **AT.1.001b**: Develop, document, and disseminate awareness and training procedures
- [ ] **AT.1.001c**: Designate officials to manage awareness and training policy and procedures
- [ ] **AT.1.001d**: Review and update awareness and training policy and procedures

#### AT.1.002 - Literacy Training and Awareness
- [ ] **AT.1.002a**: Provide basic security awareness training to all users
- [ ] **AT.1.002b**: Provide basic security awareness training to all users
- [ ] **AT.1.002c**: Provide basic security awareness training to all users
- [ ] **AT.1.002d**: Provide basic security awareness training to all users
- [ ] **AT.1.002e**: Provide basic security awareness training to all users
- [ ] **AT.1.002f**: Provide basic security awareness training to all users
- [ ] **AT.1.002g**: Provide basic security awareness training to all users
- [ ] **AT.1.002h**: Provide basic security awareness training to all users
- [ ] **AT.1.002i**: Provide basic security awareness training to all users
- [ ] **AT.1.002j**: Provide basic security awareness training to all users

#### AT.1.003 - Role-Based Security Training
- [ ] **AT.1.003a**: Provide role-based security training to personnel with assigned security roles and responsibilities
- [ ] **AT.1.003b**: Provide role-based security training to personnel with assigned security roles and responsibilities
- [ ] **AT.1.003c**: Provide role-based security training to personnel with assigned security roles and responsibilities
- [ ] **AT.1.003d**: Provide role-based security training to personnel with assigned security roles and responsibilities
- [ ] **AT.1.003e**: Provide role-based security training to personnel with assigned security roles and responsibilities
- [ ] **AT.1.003f**: Provide role-based security training to personnel with assigned security roles and responsibilities
- [ ] **AT.1.003g**: Provide role-based security training to personnel with assigned security roles and responsibilities
- [ ] **AT.1.003h**: Provide role-based security training to personnel with assigned security roles and responsibilities
- [ ] **AT.1.003i**: Provide role-based security training to personnel with assigned security roles and responsibilities
- [ ] **AT.1.003j**: Provide role-based security training to personnel with assigned security roles and responsibilities

#### AT.1.004 - Training Records
- [ ] **AT.1.004a**: Document and monitor individual information system security training activities
- [ ] **AT.1.004b**: Document and monitor individual information system security training activities
- [ ] **AT.1.004c**: Document and monitor individual information system security training activities
- [ ] **AT.1.004d**: Document and monitor individual information system security training activities
- [ ] **AT.1.004e**: Document and monitor individual information system security training activities
- [ ] **AT.1.004f**: Document and monitor individual information system security training activities
- [ ] **AT.1.004g**: Document and monitor individual information system security training activities
- [ ] **AT.1.004h**: Document and monitor individual information system security training activities
- [ ] **AT.1.004i**: Document and monitor individual information system security training activities
- [ ] **AT.1.004j**: Document and monitor individual information system security training activities

#### AT.1.005 - Contacts with Security Groups and Associations
- [ ] **AT.1.005a**: Establish and maintain contacts with security groups and associations
- [ ] **AT.1.005b**: Establish and maintain contacts with security groups and associations
- [ ] **AT.1.005c**: Establish and maintain contacts with security groups and associations
- [ ] **AT.1.005d**: Establish and maintain contacts with security groups and associations
- [ ] **AT.1.005e**: Establish and maintain contacts with security groups and associations
- [ ] **AT.1.005f**: Establish and maintain contacts with security groups and associations
- [ ] **AT.1.005g**: Establish and maintain contacts with security groups and associations
- [ ] **AT.1.005h**: Establish and maintain contacts with security groups and associations
- [ ] **AT.1.005i**: Establish and maintain contacts with security groups and associations
- [ ] **AT.1.005j**: Establish and maintain contacts with security groups and associations

### Audit and Accountability (AU)

#### AU.1.001 - Audit and Accountability Policy and Procedures
- [ ] **AU.1.001a**: Develop, document, and disseminate audit and accountability policy
- [ ] **AU.1.001b**: Develop, document, and disseminate audit and accountability procedures
- [ ] **AU.1.001c**: Designate officials to manage audit and accountability policy and procedures
- [ ] **AU.1.001d**: Review and update audit and accountability policy and procedures

#### AU.1.002 - Audit Events
- [ ] **AU.1.002a**: Determine that the information system is capable of auditing the events
- [ ] **AU.1.002b**: Coordinate the security audit function with other organizational entities requiring audit-related information
- [ ] **AU.1.002c**: Provide audit information to other organizations as needed
- [ ] **AU.1.002d**: Deploy automated mechanisms to integrate audit monitoring, analysis, and reporting
- [ ] **AU.1.002e**: Deploy automated mechanisms to integrate audit monitoring, analysis, and reporting
- [ ] **AU.1.002f**: Deploy automated mechanisms to integrate audit monitoring, analysis, and reporting

#### AU.1.003 - Content of Audit Records
- [ ] **AU.1.003a**: Create audit records containing information that establishes what type of event occurred
- [ ] **AU.1.003b**: Create audit records containing information that establishes when the event occurred
- [ ] **AU.1.003c**: Create audit records containing information that establishes where the event occurred
- [ ] **AU.1.003d**: Create audit records containing information that establishes the source of the event
- [ ] **AU.1.003e**: Create audit records containing information that establishes the outcome of the event
- [ ] **AU.1.003f**: Create audit records containing information that establishes the identity of any individuals or subjects associated with the event
- [ ] **AU.1.003g**: Create audit records containing information that establishes the identity of any individuals or subjects associated with the event
- [ ] **AU.1.003h**: Create audit records containing information that establishes the identity of any individuals or subjects associated with the event
- [ ] **AU.1.003i**: Create audit records containing information that establishes the identity of any individuals or subjects associated with the event
- [ ] **AU.1.003j**: Create audit records containing information that establishes the identity of any individuals or subjects associated with the event

#### AU.1.004 - Audit Storage Capacity
- [ ] **AU.1.004**: Allocate sufficient audit record storage capacity and configure auditing to reduce the likelihood of such capacity being exceeded

#### AU.1.005 - Response to Audit Processing Failures
- [ ] **AU.1.005a**: Alert designated organizational officials in the event of an audit processing failure
- [ ] **AU.1.005b**: Take the following additional actions: shut down the system, overwrite oldest audit records, stop generating audit records
- [ ] **AU.1.005c**: Provide a warning when allocated audit record storage volume reaches a defined percentage of maximum audit record storage capacity
- [ ] **AU.1.005d**: Provide a warning when allocated audit record storage volume reaches a defined percentage of maximum audit record storage capacity

#### AU.1.006 - Audit Review, Analysis, and Reporting
- [ ] **AU.1.006a**: Review and analyze information system audit records for indications of inappropriate, unusual, or anomalous activity
- [ ] **AU.1.006b**: Report findings to designated organizational officials
- [ ] **AU.1.006c**: Adjust the level of audit review, analysis, and reporting within the system when there is a change in risk
- [ ] **AU.1.006d**: Correlate audit record reviews with physical access monitoring
- [ ] **AU.1.006e**: Correlate audit record reviews with physical access monitoring
- [ ] **AU.1.006f**: Correlate audit record reviews with physical access monitoring
- [ ] **AU.1.006g**: Correlate audit record reviews with physical access monitoring
- [ ] **AU.1.006h**: Correlate audit record reviews with physical access monitoring
- [ ] **AU.1.006i**: Correlate audit record reviews with physical access monitoring
- [ ] **AU.1.006j**: Correlate audit record reviews with physical access monitoring

#### AU.1.007 - Audit Reduction and Report Generation
- [ ] **AU.1.007a**: Provide an audit reduction and report generation capability
- [ ] **AU.1.007b**: Provide an audit reduction and report generation capability
- [ ] **AU.1.007c**: Provide an audit reduction and report generation capability
- [ ] **AU.1.007d**: Provide an audit reduction and report generation capability
- [ ] **AU.1.007e**: Provide an audit reduction and report generation capability
- [ ] **AU.1.007f**: Provide an audit reduction and report generation capability
- [ ] **AU.1.007g**: Provide an audit reduction and report generation capability
- [ ] **AU.1.007h**: Provide an audit reduction and report generation capability
- [ ] **AU.1.007i**: Provide an audit reduction and report generation capability
- [ ] **AU.1.007j**: Provide an audit reduction and report generation capability

#### AU.1.008 - Time Stamps
- [ ] **AU.1.008a**: Use internal system clocks to generate time stamps for audit records
- [ ] **AU.1.008b**: Record time stamps for audit records that can be mapped to Coordinated Universal Time
- [ ] **AU.1.008c**: Synchronize internal system clocks with an authoritative time source
- [ ] **AU.1.008d**: Synchronize internal system clocks with an authoritative time source
- [ ] **AU.1.008e**: Synchronize internal system clocks with an authoritative time source
- [ ] **AU.1.008f**: Synchronize internal system clocks with an authoritative time source
- [ ] **AU.1.008g**: Synchronize internal system clocks with an authoritative time source
- [ ] **AU.1.008h**: Synchronize internal system clocks with an authoritative time source
- [ ] **AU.1.008i**: Synchronize internal system clocks with an authoritative time source
- [ ] **AU.1.008j**: Synchronize internal system clocks with an authoritative time source

#### AU.1.009 - Protection of Audit Information
- [ ] **AU.1.009a**: Protect audit information and audit logging tools from unauthorized access, modification, and deletion
- [ ] **AU.1.009b**: Protect audit information and audit logging tools from unauthorized access, modification, and deletion
- [ ] **AU.1.009c**: Protect audit information and audit logging tools from unauthorized access, modification, and deletion
- [ ] **AU.1.009d**: Protect audit information and audit logging tools from unauthorized access, modification, and deletion
- [ ] **AU.1.009e**: Protect audit information and audit logging tools from unauthorized access, modification, and deletion
- [ ] **AU.1.009f**: Protect audit information and audit logging tools from unauthorized access, modification, and deletion
- [ ] **AU.1.009g**: Protect audit information and audit logging tools from unauthorized access, modification, and deletion
- [ ] **AU.1.009h**: Protect audit information and audit logging tools from unauthorized access, modification, and deletion
- [ ] **AU.1.009i**: Protect audit information and audit logging tools from unauthorized access, modification, and deletion
- [ ] **AU.1.009j**: Protect audit information and audit logging tools from unauthorized access, modification, and deletion

#### AU.1.010 - Non-repudiation
- [ ] **AU.1.010a**: Associate the identity of the sender with information transmitted
- [ ] **AU.1.010b**: Associate the identity of the sender with information transmitted
- [ ] **AU.1.010c**: Associate the identity of the sender with information transmitted
- [ ] **AU.1.010d**: Associate the identity of the sender with information transmitted
- [ ] **AU.1.010e**: Associate the identity of the sender with information transmitted
- [ ] **AU.1.010f**: Associate the identity of the sender with information transmitted
- [ ] **AU.1.010g**: Associate the identity of the sender with information transmitted
- [ ] **AU.1.010h**: Associate the identity of the sender with information transmitted
- [ ] **AU.1.010i**: Associate the identity of the sender with information transmitted
- [ ] **AU.1.010j**: Associate the identity of the sender with information transmitted

#### AU.1.011 - Audit Record Retention
- [ ] **AU.1.011a**: Retain audit records for a defined time period to support after-the-fact investigations of security incidents
- [ ] **AU.1.011b**: Retain audit records for a defined time period to support after-the-fact investigations of security incidents
- [ ] **AU.1.011c**: Retain audit records for a defined time period to support after-the-fact investigations of security incidents
- [ ] **AU.1.011d**: Retain audit records for a defined time period to support after-the-fact investigations of security incidents
- [ ] **AU.1.011e**: Retain audit records for a defined time period to support after-the-fact investigations of security incidents
- [ ] **AU.1.011f**: Retain audit records for a defined time period to support after-the-fact investigations of security incidents
- [ ] **AU.1.011g**: Retain audit records for a defined time period to support after-the-fact investigations of security incidents
- [ ] **AU.1.011h**: Retain audit records for a defined time period to support after-the-fact investigations of security incidents
- [ ] **AU.1.011i**: Retain audit records for a defined time period to support after-the-fact investigations of security incidents
- [ ] **AU.1.011j**: Retain audit records for a defined time period to support after-the-fact investigations of security incidents

#### AU.1.012 - Audit Generation
- [ ] **AU.1.012a**: Provide audit record generation capability for the auditable events defined in AU.1.002
- [ ] **AU.1.012b**: Allow designated organizational personnel to select which auditable events are to be audited by specific components of the system
- [ ] **AU.1.012c**: Generate audit records for the events defined in AU.1.002 with the content defined in AU.1.003

### Configuration Management (CM)

#### CM.1.001 - Configuration Management Policy and Procedures
- [ ] **CM.1.001a**: Develop, document, and disseminate configuration management policy
- [ ] **CM.1.001b**: Develop, document, and disseminate configuration management procedures
- [ ] **CM.1.001c**: Designate officials to manage configuration management policy and procedures
- [ ] **CM.1.001d**: Review and update configuration management policy and procedures

#### CM.1.002 - Baseline Configuration
- [ ] **CM.1.002a**: Develop, document, and maintain under configuration control, a current baseline configuration of the information system
- [ ] **CM.1.002b**: Develop, document, and maintain under configuration control, a current baseline configuration of the information system
- [ ] **CM.1.002c**: Develop, document, and maintain under configuration control, a current baseline configuration of the information system
- [ ] **CM.1.002d**: Develop, document, and maintain under configuration control, a current baseline configuration of the information system
- [ ] **CM.1.002e**: Develop, document, and maintain under configuration control, a current baseline configuration of the information system
- [ ] **CM.1.002f**: Develop, document, and maintain under configuration control, a current baseline configuration of the information system
- [ ] **CM.1.002g**: Develop, document, and maintain under configuration control, a current baseline configuration of the information system
- [ ] **CM.1.002h**: Develop, document, and maintain under configuration control, a current baseline configuration of the information system
- [ ] **CM.1.002i**: Develop, document, and maintain under configuration control, a current baseline configuration of the information system
- [ ] **CM.1.002j**: Develop, document, and maintain under configuration control, a current baseline configuration of the information system

#### CM.1.003 - Configuration Change Control
- [ ] **CM.1.003a**: Determine the types of changes to the information system that are configuration controlled
- [ ] **CM.1.003b**: Determine the types of changes to the information system that are configuration controlled
- [ ] **CM.1.003c**: Determine the types of changes to the information system that are configuration controlled
- [ ] **CM.1.003d**: Determine the types of changes to the information system that are configuration controlled
- [ ] **CM.1.003e**: Determine the types of changes to the information system that are configuration controlled
- [ ] **CM.1.003f**: Determine the types of changes to the information system that are configuration controlled
- [ ] **CM.1.003g**: Determine the types of changes to the information system that are configuration controlled
- [ ] **CM.1.003h**: Determine the types of changes to the information system that are configuration controlled
- [ ] **CM.1.003i**: Determine the types of changes to the information system that are configuration controlled
- [ ] **CM.1.003j**: Determine the types of changes to the information system that are configuration controlled

#### CM.1.004 - Security Impact Analysis
- [ ] **CM.1.004a**: Analyze changes to the information system to determine potential security impacts
- [ ] **CM.1.004b**: Analyze changes to the information system to determine potential security impacts
- [ ] **CM.1.004c**: Analyze changes to the information system to determine potential security impacts
- [ ] **CM.1.004d**: Analyze changes to the information system to determine potential security impacts
- [ ] **CM.1.004e**: Analyze changes to the information system to determine potential security impacts
- [ ] **CM.1.004f**: Analyze changes to the information system to determine potential security impacts
- [ ] **CM.1.004g**: Analyze changes to the information system to determine potential security impacts
- [ ] **CM.1.004h**: Analyze changes to the information system to determine potential security impacts
- [ ] **CM.1.004i**: Analyze changes to the information system to determine potential security impacts
- [ ] **CM.1.004j**: Analyze changes to the information system to determine potential security impacts

#### CM.1.005 - Access Restrictions for Change
- [ ] **CM.1.005a**: Define, document, approve, and enforce physical and logical access restrictions associated with changes to the information system
- [ ] **CM.1.005b**: Define, document, approve, and enforce physical and logical access restrictions associated with changes to the information system
- [ ] **CM.1.005c**: Define, document, approve, and enforce physical and logical access restrictions associated with changes to the information system
- [ ] **CM.1.005d**: Define, document, approve, and enforce physical and logical access restrictions associated with changes to the information system
- [ ] **CM.1.005e**: Define, document, approve, and enforce physical and logical access restrictions associated with changes to the information system
- [ ] **CM.1.005f**: Define, document, approve, and enforce physical and logical access restrictions associated with changes to the information system
- [ ] **CM.1.005g**: Define, document, approve, and enforce physical and logical access restrictions associated with changes to the information system
- [ ] **CM.1.005h**: Define, document, approve, and enforce physical and logical access restrictions associated with changes to the information system
- [ ] **CM.1.005i**: Define, document, approve, and enforce physical and logical access restrictions associated with changes to the information system
- [ ] **CM.1.005j**: Define, document, approve, and enforce physical and logical access restrictions associated with changes to the information system

#### CM.1.006 - Configuration Settings
- [ ] **CM.1.006a**: Establish and document configuration settings for information technology products employed within the information system
- [ ] **CM.1.006b**: Establish and document configuration settings for information technology products employed within the information system
- [ ] **CM.1.006c**: Establish and document configuration settings for information technology products employed within the information system
- [ ] **CM.1.006d**: Establish and document configuration settings for information technology products employed within the information system
- [ ] **CM.1.006e**: Establish and document configuration settings for information technology products employed within the information system
- [ ] **CM.1.006f**: Establish and document configuration settings for information technology products employed within the information system
- [ ] **CM.1.006g**: Establish and document configuration settings for information technology products employed within the information system
- [ ] **CM.1.006h**: Establish and document configuration settings for information technology products employed within the information system
- [ ] **CM.1.006i**: Establish and document configuration settings for information technology products employed within the information system
- [ ] **CM.1.006j**: Establish and document configuration settings for information technology products employed within the information system

#### CM.1.007 - Least Functionality
- [ ] **CM.1.007a**: Configure the information system to provide only essential capabilities
- [ ] **CM.1.007b**: Configure the information system to provide only essential capabilities
- [ ] **CM.1.007c**: Configure the information system to provide only essential capabilities
- [ ] **CM.1.007d**: Configure the information system to provide only essential capabilities
- [ ] **CM.1.007e**: Configure the information system to provide only essential capabilities
- [ ] **CM.1.007f**: Configure the information system to provide only essential capabilities
- [ ] **CM.1.007g**: Configure the information system to provide only essential capabilities
- [ ] **CM.1.007h**: Configure the information system to provide only essential capabilities
- [ ] **CM.1.007i**: Configure the information system to provide only essential capabilities
- [ ] **CM.1.007j**: Configure the information system to provide only essential capabilities

#### CM.1.008 - Information System Component Inventory
- [ ] **CM.1.008a**: Develop and document an inventory of information system components that accurately reflects the current information system
- [ ] **CM.1.008b**: Develop and document an inventory of information system components that accurately reflects the current information system
- [ ] **CM.1.008c**: Develop and document an inventory of information system components that accurately reflects the current information system
- [ ] **CM.1.008d**: Develop and document an inventory of information system components that accurately reflects the current information system
- [ ] **CM.1.008e**: Develop and document an inventory of information system components that accurately reflects the current information system
- [ ] **CM.1.008f**: Develop and document an inventory of information system components that accurately reflects the current information system
- [ ] **CM.1.008g**: Develop and document an inventory of information system components that accurately reflects the current information system
- [ ] **CM.1.008h**: Develop and document an inventory of information system components that accurately reflects the current information system
- [ ] **CM.1.008i**: Develop and document an inventory of information system components that accurately reflects the current information system
- [ ] **CM.1.008j**: Develop and document an inventory of information system components that accurately reflects the current information system

#### CM.1.009 - Software Usage Restrictions
- [ ] **CM.1.009a**: Control the use of software and associated documentation and protect software and associated documentation from unauthorized use
- [ ] **CM.1.009b**: Control the use of software and associated documentation and protect software and associated documentation from unauthorized use
- [ ] **CM.1.009c**: Control the use of software and associated documentation and protect software and associated documentation from unauthorized use
- [ ] **CM.1.009d**: Control the use of software and associated documentation and protect software and associated documentation from unauthorized use
- [ ] **CM.1.009e**: Control the use of software and associated documentation and protect software and associated documentation from unauthorized use
- [ ] **CM.1.009f**: Control the use of software and associated documentation and protect software and associated documentation from unauthorized use
- [ ] **CM.1.009g**: Control the use of software and associated documentation and protect software and associated documentation from unauthorized use
- [ ] **CM.1.009h**: Control the use of software and associated documentation and protect software and associated documentation from unauthorized use
- [ ] **CM.1.009i**: Control the use of software and associated documentation and protect software and associated documentation from unauthorized use
- [ ] **CM.1.009j**: Control the use of software and associated documentation and protect software and associated documentation from unauthorized use

#### CM.1.010 - User-Installed Software
- [ ] **CM.1.010a**: Establish policies governing the installation of software by users
- [ ] **CM.1.010b**: Establish policies governing the installation of software by users
- [ ] **CM.1.010c**: Establish policies governing the installation of software by users
- [ ] **CM.1.010d**: Establish policies governing the installation of software by users
- [ ] **CM.1.010e**: Establish policies governing the installation of software by users
- [ ] **CM.1.010f**: Establish policies governing the installation of software by users
- [ ] **CM.1.010g**: Establish policies governing the installation of software by users
- [ ] **CM.1.010h**: Establish policies governing the installation of software by users
- [ ] **CM.1.010i**: Establish policies governing the installation of software by users
- [ ] **CM.1.010j**: Establish policies governing the installation of software by users

## Implementation Guidance

### Checkbox Interpretation

The checkboxes above indicate our current documentation status for each 800-171 control:

- **`[ ]` Unchecked**: No documentation exists yet - agents should create comprehensive documentation
- **`[x]` Checked**: Documentation exists - agents should review, enhance, and iterate on existing documentation

### Agent Actions Based on Documentation Status

#### For Unchecked Items (`[ ]`) - Create Documentation
When an item is unchecked, agents should create comprehensive documentation:

1. **Create Control Namespace**: Generate control documentation using templates from `methods/templates/controls/`
2. **Develop Implementation Guide**: Create step-by-step implementation procedures
3. **Assess Requirements**: Determine organizational requirements and constraints
4. **Plan Implementation**: Develop implementation roadmap and resource requirements
5. **Create Assessment Framework**: Establish evaluation criteria and testing procedures
6. **Document Compliance**: Create compliance tracking and audit requirements
7. **Assess Risks**: Develop risk assessment and mitigation strategies
8. **Map Dependencies**: Identify related controls and system dependencies

#### For Checked Items (`[x]`) - Iterate and Improve
When an item is checked, agents should enhance existing documentation:

1. **Review Existing Documentation**: Assess current documentation quality and completeness
2. **Identify Gaps**: Find areas needing improvement or updates
3. **Enhance Documentation**: Improve existing control documentation
4. **Update Procedures**: Refresh implementation procedures and guidelines
5. **Validate Effectiveness**: Assess control effectiveness and compliance
6. **Optimize Implementation**: Improve efficiency and reduce costs
7. **Integrate Improvements**: Incorporate lessons learned and best practices

### Implementation Priority

Agents should prioritize unchecked items (documentation creation) based on:

1. **High Priority**: Critical security controls and compliance requirements
2. **Medium Priority**: Important but not critical controls
3. **Low Priority**: Nice-to-have controls and enhancements

### Required Documentation Types

For each 800-171 control, agents should create or enhance:

- **Control Overview**: Comprehensive control description and requirements
- **Implementation Guide**: Step-by-step implementation procedures
- **Assessment Framework**: Evaluation criteria and testing procedures
- **Compliance Tracking**: Audit requirements and evidence collection
- **Risk Assessment**: Control-specific risk considerations and mitigation
- **Dependencies**: Related controls and system dependencies

### Workflow Process

1. **Monitor Checkbox Changes**: Agents should monitor when checkboxes are updated
2. **Create Documentation**: For newly checked items, create all required documentation types
3. **Iterate on Existing**: For items that remain checked, continuously improve documentation
4. **Maintain Quality**: Ensure all documentation meets established quality standards
5. **Cross-Reference**: Link documentation between related controls and frameworks

## Next Steps

### Immediate Actions

1. **Framework Assessment**: Evaluate current 800-171 implementation status
2. **Gap Analysis**: Identify missing controls and documentation
3. **Priority Setting**: Determine high-priority controls for implementation
4. **Resource Planning**: Allocate resources for implementation
5. **Documentation Creation**: Begin creating comprehensive documentation

### Future Enhancements

1. **Framework Integration**: Integrate 800-171 with other NIST frameworks
2. **Automation**: Automate control implementation and monitoring
3. **Advanced Analytics**: Implement security analytics and reporting
4. **Threat Intelligence**: Integrate threat intelligence capabilities
5. **Continuous Monitoring**: Implement real-time security monitoring

This 800-171 adoption approach ensures systematic implementation of the framework while maintaining comprehensive documentation for each control. 