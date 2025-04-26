---
layout: page
title: Digital minimum requirements
permalink: /digital-minimum-requirements/
---

| DIMR menu item | DIMR domain | DIMR statement | Hosted | On prem | Mobile |
| --- | --- | --- | --- | --- | --- |
| DIMR\_EU\_1 | End user computing | The Trust’s standard end user computing environment uses recent versions of Windows 10, Windows 11 and Office 365. The solution MUST be compatible with these products. | Yes | Yes | |
| DIMR\_EU\_1a | End user computing | The solution MUST be compatible with modern web browsers | Yes | Yes | Yes |
| DIMR\_EU\_2 | End user computing | The Trust uses recent versions of both Apple IOS and Android as its standard mobile operating systems. The solution MUST be compatible with both environments. | | | Yes |
| DIMR\_EU\_3 | End user computing | The solution provider MUST provide the Trust with a warranted environment specification, setting out all applicable end user computing requirements. It is expected that this document will be refreshed through the life of the contract | Yes | Yes | Yes |
| DIMR\_EU\_4 | End user computing | DIMR\_EU\_4 is withdrawn | | | |
| DIMR\_EU\_5 | End user computing | The solution provider MUST state any known incompatibility or conflict with any system or device listed on the Trust's business and clinical systems compatibility register, available on request. | Yes | Yes | Yes |
| DIMR\_IN\_1 | Infrastructure assurance | The solution SHOULD BE compatible with modern authentication sources such as Azure Active Directory, oAuth or SAML. If the solution stores passwords itself it MUST do so using non-reversible encryption and the current good practice guidance on passwords issued by the National Cyber Security Centre | Yes | Yes | Yes |
| DIMR\_IN\_2 | Infrastructure assurance | The solution MUST be highly available with an appropriate backup and data protection regime | Yes | | |
| DIMR\_IN\_3 | Infrastructure assurance | If present as a feature, the solution MUST be capable of authenticated SMTP (username + password) to facilitate the automated sending of emails | Yes | Yes | Yes |
| DIMR\_IN\_4 | Infrastructure assurance | Where applicable the solution provider MUST provide the Trust with details of deployment and configuration options, especially those relating to silent deployments and automation via Microsoft System Centre Configuration Manager, ADMX templates, Windows registry, XML or INI files etc. | Yes | Yes | |
| DIMR\_IN\_5 | Infrastructure assurance | Where applicable the solution provider MUST provide the Trust with details of the solution's update mechanism and scope where this exists for automation | | Yes | |
| DIMR\_IN\_6 | Infrastructure assurance | The solution SHOULD NOT contain dependencies on particular versions of other client software, e.g. Java,  Silverlight or Flash Player | Yes | Yes | |
| DIMR\_IN\_7 | Infrastructure assurance | The solution SHOULD NOT inhibit the Trust in the enactment of its patch regime. The Trust expects to be able to apply all patches in the month they are released. During the contract any exceptions to this MUST be raised as a formal exception | Yes | Yes | Yes |
| DIMR\_IN\_8 | Infrastructure assurance | If delivered over HTTP, the solution MUST offer TLS 1.2 or 1.3 encryption (HTTPS) by default | Yes | | Yes |
| DIMR\_IN\_9 | Infrastructure assurance | If delivered over HTTP, the solution MUST permit TLS 1.2 or 1.3 encryption (HTTPS) to be applied | | Yes | |
| DIMR\_IN\_10 | Infrastructure assurance | If the solution requires the Trust to provide on-premises server infrastructure the solution provider MUST specify their requirements in a schedule, covering the number of servers, CPU cores, RAM and IOPS | | Yes | |
| DIMR\_IN\_11 | Infrastructure assurance | The solution MUST support IPv4 and MAY support both IPv4 and IPv6 | Yes | Yes | Yes |
| DIMR\_IN\_12 | Infrastructure assurance | The solution MUST be accessible to users with small form factor or mobile devices | | | Yes |
| DIMR\_AC\_1 | Accessibility | Public facing web solutions MUST be compliant with version 2.2 of the [Web Content Accessibility Guidelines (WCAG 2.2)](https://www.w3.org/TR/WCAG22/) | Yes | Yes | Yes |
| DIMR\_AC\_2 | Accessibility | Non public facing web solutions SHOULD be compliant with version 2.2 of the [Web Content Accessibility Guidelines (WCAG 2.2)](https://www.w3.org/TR/WCAG22/) | Yes | Yes | Yes |
| DIMR\_IA\_1 | Information assurance | The solution MUST be penetration tested on an annual basis with appropriate assurance provided to the Trust | Yes | | Yes |
| DIMR\_IA\_2 | Information assurance | The solution provider MUST supply the Trust with an annual statement of alignment against the latest OWASP Top Ten security risks in compliance with assertion 9.3.1 of the NHS Data Security and Protection Toolkit | Yes | | Yes |
| DIMR\_IA\_3 | Information assurance | If not registered with the UK government digital marketplace under a current framework agreement, the solution provider MUST hold Cyber Essentials certification at a minimum | Yes | Yes | Yes |
| DIMR\_IA\_4 | Information assurance | The solution provider MUST have either registered for and submitted the [NHS Data Security and Protection Toolkit](https://www.dsptoolkit.nhs.uk/), or be prepared to do so. | Yes | Yes | Yes |
| DIMR\_IA\_5 | Information assurance | The solution provider MUST NOT store data relating to individuals outside of the European Economic Area, or a jurisdiction that is on the [list of countries](https://commission.europa.eu/law/law-topic/data-protection/international-dimension-data-protection/adequacy-decisions_en) deemed by the European Commission to offer an adequate level of data protection in the context of the UK General Data Protection Regulation and the EU General Data Protection Regulation | Yes | Yes | Yes |
| DIMR\_IA\_6 | Information assurance | The solution provider MUST provide the Trust with details of its ICO registration number and name and contact details of its data protection officer | Yes | Yes | Yes |
| DIMR\_IA\_7 | Information assurance | The solution provider MUST be able to enumerate its data flows with regard to the Trust and provide the Trust with a high level data flow description and diagram | | Yes | Yes |
| DIMR\_IA\_8 | Information assurance | The solution SHOULD be developed in accordance with the principles of Security-by-Design and Security-by-Default, and the solution provider SHOULD be able to evidence this | Yes | Yes | Yes |
| DIMR\_CO\_1 | Commercial | The solution provider MUST provide the Trust with details of available licensing options, and any separately licensable components | Yes | Yes | Yes |
| DIMR\_DA\_1 | Data management | The solution MUST facilitate access for reporting to allow integration with the Trust's data warehouse | Yes | Yes | Yes |
| DIMR\_DA\_2 | Data management | The solution provider MUST provide database schema documentation | Yes | Yes | Yes |
| DIMR\_DA\_3 | Data management | The solution provider MUST describe the solution's data portability capabilities in the event of the solution becoming surplus to the Trust's requirements, covering both migration and archival of data. | Yes | Yes | Yes |
| DIMR\_DA\_4 | Data management | Where a solution provides a test environment, this MUST NOT by default use data from the live environment. Solution providers MUST be capable of providing adequate test data for use in test environments. | Yes | Yes | Yes |
| DIMR\_DA\_5 | Data management | Where a solution produces logs, the solution SHOULD be capable of being configured for those logs to be retained for up to 180 days. The solution SHOULD further permit export to or extraction by modern security information and event management (SIEM) solutions. | Yes | Yes | Yes |
