# Cybersecurity Portfolio

**Hands-on SOC operations | Threat intelligence | Network security monitoring | Security automation**

Welcome to my cybersecurity project portfolio. Here I document practical security engineering and analyst workflows, including how each lab was built, what I validated, challenges encountered, and supporting evidence.

This is a central index of my cybersecurity work. **Each project remains in its own independent GitHub repository**, so it can be reviewed on its own.

## Featured projects

| # | Project | Focus | Evidence |
|---|---|---|---|
| **01** | [OpenCTI + Splunk Threat Intelligence Integration](https://github.com/DaveDave-infosec/opencti-splunk-cti-integration) | Threat intelligence platform integration and SOC enrichment | Setup, configuration and investigation documentation |
| **02** | [Arkime Network Packet Indexer](https://github.com/DaveDave-infosec/arkime-network-packet-indexer) | Packet capture, session indexing and network traffic review | Lab build, service troubleshooting and Arkime session screenshots |
| **03** | [Microsoft Sentinel + AbuseIPDB IP Reputation Enrichment](https://github.com/DaveDave-infosec/sentinel-abuseipdb-ip-enrichment) | SOAR automation with Azure Logic Apps and IP reputation lookups | Successful playbook runs, incident comments and verified screenshots |

| **04** | [SOC Detection Engineering Lab](https://github.com/DaveDave-infosec/SOC-Detection-Engineering-Lab) | Windows, firewall, and network telemetry in Splunk; evidence-based triage | Seven screenshots, two investigations, and documented visibility limitations |
| **05** | [Splunk SOAR Automated Incident Response](https://github.com/DaveDave-infosec/splunk-soar-automated-incident-response) | IP reputation enrichment, analyst approvals, and lab AD response | Two Python/JSON playbooks and six screenshots, including a connector-reported test-account disable result |

### 01 — OpenCTI + Splunk Threat Intelligence Integration

**Skills:** Cyber Threat Intelligence (CTI), Splunk, integrations, SOC workflows

Built a lab project exploring integration between OpenCTI and Splunk to support security monitoring with threat intelligence context. The dedicated repository documents the implementation, configurations and lessons learned.

[**Explore Project 01 →**](https://github.com/DaveDave-infosec/opencti-splunk-cti-integration)

### 02 — Arkime Network Packet Indexer

**Skills:** Network security monitoring, packet analysis, Linux, OpenSearch, Arkime

Deployed Arkime on Ubuntu Server in VMware with OpenSearch as its backend. Troubleshot capture startup and examined captured sessions in the Arkime interface. The repository includes the architecture, validation notes and packet/session screenshots.

[**Explore Project 02 →**](https://github.com/DaveDave-infosec/arkime-network-packet-indexer)

### 03 — Microsoft Sentinel + AbuseIPDB IP Reputation Enrichment

**Skills:** Microsoft Sentinel, Azure Logic Apps, SOAR, REST APIs, JSON, incident enrichment

Built a Sentinel incident-triggered playbook that extracts IP entities, looks up reputation information using AbuseIPDB and posts the results back to the incident. Tested automatic execution and a later manual rerun that generated a SOC-friendly formatted report. Preserved screenshots and disabled automatic execution after the lab.

[**Explore Project 03 →**](https://github.com/DaveDave-infosec/sentinel-abuseipdb-ip-enrichment)

### 04 — SOC Detection Engineering Lab

**Skills:** Splunk SPL, Sysmon, Windows auditing, Active Directory/GPO, pfSense, Zeek, Suricata, VMware

Built a segmented SOC lab and centralized Windows, firewall, and network telemetry in Splunk. Investigated a likely benign Suricata policy alert and failed interactive Windows logons. Seven screenshots document the lab. Sensor visibility was verified for a specific traffic path; full network coverage, a confirmed brute-force attack, and continuously scheduled detection are not claimed. Splunk Free limitations are documented.

[**Explore Project 04 →**](https://github.com/DaveDave-infosec/SOC-Detection-Engineering-Lab)

### 05 — Splunk SOAR Automated Incident Response

**Skills:** Splunk SOAR, AbuseIPDB, VirusTotal, Python/JSON playbooks, analyst approvals, Active Directory LDAP

Built two investigation playbooks for IP reputation enrichment and conditional triage. The RDP workflow updates case severity and tags; the successful-login workflow gates disabling a fixed disposable AD account behind explicit analyst approval. The repository includes both Python/JSON exports and six screenshots, with a connector-reported successful test-account disable result. Documentation distinguishes workflow design from execution evidence and records inactive playbooks, fixed-account targeting, and missing production/error-handling controls.

[**Explore Project 05 →**](https://github.com/DaveDave-infosec/splunk-soar-automated-incident-response)

## Skills and tools

| Area | Technologies practiced |
|---|---|
| SIEM & investigation | Splunk, Microsoft Sentinel |
| Threat intelligence | OpenCTI, AbuseIPDB, VirusTotal, REST API enrichment |
| Network monitoring | Arkime, Zeek, Suricata, pfSense, packet/session analysis |
| Security automation | Azure Logic Apps, Microsoft Sentinel automation rules, Splunk SOAR, AD LDAP response |
| Infrastructure | Ubuntu Server, VMware Workstation, OpenSearch, Active Directory, Group Policy, Sysmon |
| Documentation | Lab architecture, testing evidence, GitHub project reports |

## How to review this portfolio

Select any project above to see its **README**, supporting documentation and lab evidence. Projects describe controlled learning environments and clearly separate simulated activity from real security incidents. Sensitive keys and credentials are not published.

## Upcoming work

Additional hands-on SOC, detection engineering, digital forensics and cloud security projects will be linked here as they are completed and documented.

---

**GitHub:** [DaveDave-infosec](https://github.com/DaveDave-infosec)

*Portfolio index — security projects are maintained independently from other software development and Web3 repositories.*
