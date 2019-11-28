
# Incident Response Procedure <!-- omit in toc -->

## Overview <!-- omit in toc -->

This project is a partial incident response procedure for a 100-1000 person company with a small
internal security team with the following prioritized goals:

1. Prevent events from repeating
2. Recovery should be fast
3. Enable data collection to pursue legal action

This is a project for GVSU's Information Security Principles course (CIS 615). See the
[assignment](Assignment.md) for more details.

## Contents <!-- omit in toc -->

- [1. Introduction](#1-introduction)
  - [1.1 Scope](#11-scope)
  - [1.2 Context](#12-context)
- [2. Incident Response Procedures](#2-incident-response-procedures)
  - [2.1 General Procedures](#21-general-procedures)
    - [2.1.1 Preparation](#211-preparation)
    - [2.1.2 Detection & Analysis](#212-detection--analysis)
    - [2.1.3 Containment, Eradication, & Recovery](#213-containment-eradication--recovery)
    - [2.1.4 Post-incident Activity](#214-post-incident-activity)
  - [2.2 Incident Specific Procedures](#22-incident-specific-procedures)
    - [2.2.1 Incident: Distributed Denial Of Service](#221-incident-distributed-denial-of-service)
    - [2.2.2 Incident: Insider Breach](#222-incident-insider-breach)
- [3. Scenario Discussions](#3-scenario-discussions)
  - [3.1 Scenario: Domain Name System (DNS) Server Denial of Service (DoS)](#31-scenario-domain-name-system-dns-server-denial-of-service-dos)
  - [3.2 Scenario: Unauthorized Access to Payroll Records](#32-scenario-unauthorized-access-to-payroll-records)
- [License](#license)

# 1. Introduction

## 1.1 Scope

This is a partial incident response plan. NIST provides a comprehensive approach in [SP
800-61](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-61r2.pdf) consisting of
four stages:

1. Preparation
2. Detection & Analysis
3. Containment, Eradication, & Recovery
4. Post-incident Activity

This project establishes basic procedures for each stage as shown in figure 1.

![Incident Response Lifecycle](images/Incident_Response_Lifecycle.png)  
*Figure 1: Incident Response Lifecycle ([NIST SP
800-61](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-61r2.pdf) p. 21)*

The document is organized according to general procedures, incident specific procedures for two
incident types, and discussions of two scenarios posed in NIST SP 800-61 Appendix A (p. 52). Stages
1, 2, and 4 are primarily covered under the general procedures. Stage 3 is largely particular to the
incident type, and is covered under incident specific procedures.

## 1.2 Context

This incident response procedure is written in the context of a 100-1000 person company with a small
internal security team with the following prioritized goals:

1. Prevent events from repeating
2. Recovery should be fast
3. Enable data collection to pursue legal action

This company prefers to deal with incidents internally. It is willing to invest in extra hardware in
order to expedite recovery.

# 2. Incident Response Procedures

<!--
1. Preparation
   - Internal and external contact information is gathered
   - A centralized logging service is established
   - Backups for critical systems are updated monthly and stored for one year
   - An issue tracking system is established
   - Dedicated forensics workstations are prepared
   - Bootable images and clean application installation files are available on removable media
2. Detection & Analysis
   - The organization has some capacity to monitor logs and detect precursors and indicators
   - Incidents are documented immediately
   - Incidents are triaged according to functional impact, integrity impact, and recoverability
3. Containment, Eradication, & Recovery
   - TBD
4. Post-incident Activity
   - TBD
-->

## 2.1 General Procedures

### 2.1.1 Preparation

### 2.1.2 Detection & Analysis

### 2.1.3 Containment, Eradication, & Recovery

### 2.1.4 Post-incident Activity

## 2.2 Incident Specific Procedures

### 2.2.1 Incident: Distributed Denial Of Service

### 2.2.2 Incident: Insider Breach

# 3. Scenario Discussions

## 3.1 Scenario: Domain Name System (DNS) Server Denial of Service (DoS)

Scenario description ([NIST SP
800-61](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-61r2.pdf) p. 53):

> On a Saturday afternoon, external users start having problems accessing the organization's public
websites. Over the next hour, the problem worsens to the point where nearly every access attempt
fails. Meanwhile, a member of the organization's networking staff responds to alerts from an
Internet border router and determines that the organization’s Internet bandwidth is being consumed
by an unusually large volume of User Datagram Protocol (UDP) packets to and from both the
organization's public DNS servers. Analysis of the traffic shows that the DNS servers are receiving
high volumes of requests from a single external IP address. Also, all the DNS requests from that
address come from the same source port.

## 3.2 Scenario: Unauthorized Access to Payroll Records

Scenario description ([NIST SP
800-61](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-61r2.pdf) p. 55):

> On a Wednesday evening, the organization's physical security team receives a call from a payroll
administrator who saw an unknown person leave her office, run down the hallway,and exit the
building. The administrator had left her workstation unlocked and unattended for only a few minutes.
The payroll program is still logged in and on the main menu, as it was when she left it, but the
administrator notices that the mouse appears to have been moved. The incident response team has been
asked to acquire evidence related to the incident and to determine what actions were performed.

# License

This project is licensed under the Creative Commons Attribution 4.0 International license. The text
is copyrighted by Kevin Kredit, but is reusable provided credit and license notice. See the license
[text](LICENSE) for more details.
