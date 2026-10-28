# Hands-on-SIEM-Splunk-Operations-Digital-Forensics-Incident-Response-CTF-Labs-SecByte-Index
A practical collection of cybersecurity CTF labs covering SIEM &amp; Log Analysis (Splunk, Syslog, Windows Event Logs, Linux Logs), Digital Forensics (Memory Forensics, Malicious Documents), Incident Response Handling, and Defensive Security Fundamentals.
# Enterprise SIEM Operations, Digital Forensics & Incident Response CTF Labs

Welcome to the **Enterprise SIEM Operations, Digital Forensics & Incident Response CTF Lab Collection**. This repository serves as an organized, searchable catalog of practical cybersecurity labs hosted on Learn SecByte.

This collection covers foundational and operational defensive disciplines—including **Enterprise SIEM & Splunk Search Processing**, **Cross-Platform Log Correlation (Windows, Linux, Syslog)**, **Digital Forensics (Memory & Suspicious Documents)**, and **Incident Response Handling Procedures**.

---

## Lab Collection Index

### 1. Defensive Security & SIEM Fundamentals
* **Defensive Security Fundamentals**  
  *Lab Link:* [https://learn.secbyte.org/ctf/defensive-security-fundamentals](https://learn.secbyte.org/ctf/defensive-security-fundamentals)  
  *Focus:* Core principles of defense-in-depth, security operations architecture, threat mitigation strategies, and security control baselines.

* **SIEM Fundamentals**  
  *Lab Link:* [https://learn.secbyte.org/ctf/siem-fundamentals](https://learn.secbyte.org/ctf/siem-fundamentals)  
  *Focus:* Log ingestion architectures, normalization, index management, parsing rules, and real-time alert generation.

* **Splunk Essentials: Mastering SIEM Operations**  
  *Lab Link:* [https://learn.secbyte.org/ctf/splunk-essentials-mastering-siem-operations](https://learn.secbyte.org/ctf/splunk-essentials-mastering-siem-operations)  
  *Focus:* Writing Search Processing Language (SPL) queries, creating custom dashboards, configuring lookup tables, and building correlation alerts.

<Image src="image_agent_tag_11788743540783844239" alt="Splunk SPL search interface displaying event log analysis and search statistics" caption="Splunk SPL Log Analysis Interface" />

---

### 2. Multi-Source Log Analysis & Correlation
* **Log Correlation Mastery**  
  *Lab Link:* [https://learn.secbyte.org/ctf/log-correlation-mastery](https://learn.secbyte.org/ctf/log-correlation-mastery)  
  *Focus:* Correlating multi-vendor log sources (firewall, SIEM, endpoint, auth logs) across temporal windows to track adversary movement.

* **Syslog Investigation**  
  *Lab Link:* [https://learn.secbyte.org/ctf/syslog-investigation](https://learn.secbyte.org/ctf/syslog-investigation)  
  *Focus:* Parsing standard Syslog facilities/severities (RFC 5424), configuring Rsyslog/Syslog-ng collectors, and analyzing centralized network logs.

* **Linux Log Analysis Basics**  
  *Lab Link:* [https://learn.secbyte.org/ctf/linux-log-analysis-basics](https://learn.secbyte.org/ctf/linux-log-analysis-basics)  
  *Focus:* Analyzing `/var/log` artifacts (`auth.log`, `syslog`, `auditd`, `dmesg`), tracking SSH authentication attempts, and command line history audits.

* **Windows Event Logging: Basics to IR**  
  *Lab Link:* [https://learn.secbyte.org/ctf/windows-event-logging-basics-to-ir](https://learn.secbyte.org/ctf/windows-event-logging-basics-to-ir)  
  *Focus:* Analyzing Windows Security Event IDs (4624, 4625, 4672, 4720, 7045) for incident response, timeline creation, and anomaly identification.

### 3. Digital Forensics & Malware Artifacts
* **Digital Forensics Fundamentals**  
  *Lab Link:* [https://learn.secbyte.org/ctf/digital-forensics-fundamentals](https://learn.secbyte.org/ctf/digital-forensics-fundamentals)  
  *Focus:* Forensic acquisition principles, chain of custody maintenance, hash integrity verification, disk imaging, and artifact extraction.

* **Memory Forensics: Uncovering Digital Artifacts**  
  *Lab Link:* [https://learn.secbyte.org/ctf/memory-forensics-uncovering-digital-artifacts](https://learn.secbyte.org/ctf/memory-forensics-uncovering-digital-artifacts)  
  *Focus:* Analyzing RAM dumps with Volatility, identifying injected processes, extracting network sockets, unhooking DLLs, and recovering passwords.

<Image src="image_agent_tag_11788743540783845308" alt="Volatility memory forensics terminal output displaying process memory string extraction" caption="Volatility Memory Forensics Investigation" />

---

* **Malware Forensics: Suspicious Document**  
  *Lab Link:* [https://learn.secbyte.org/ctf/malware-forensics-suspicious-document](https://learn.secbyte.org/ctf/malware-forensics-suspicious-document)  
  *Focus:* Deconstructing malicious Office/PDF documents using `oletools` and `pdf-parser`, analyzing VBA macros, shellcode extraction, and payload URL recovery.

### 4. Incident Handling & Response Procedures
* **Incident Response Basics**  
  *Lab Link:* [https://learn.secbyte.org/ctf/incident-response-basics](https://learn.secbyte.org/ctf/incident-response-basics)  
  *Focus:* Understanding the NIST and SANS Incident Response lifecycles (Preparation, Detection, Containment, Eradication, Recovery, Lessons Learned).

* **Incident Handling Process**  
  *Lab Link:* [https://learn.secbyte.org/ctf/incident-handling-process](https://learn.secbyte.org/ctf/incident-handling-process)  
  *Focus:* Operationalizing incident handling playbooks, containment procedures, evidence collection protocols, and technical post-incident reporting.

---

## Learning Path

### Path A: SIEM Operator & Log Analyst
1. **Defensive & SIEM Foundations:** Start with [Defensive Security Fundamentals](https://learn.secbyte.org/ctf/defensive-security-fundamentals) and [SIEM Fundamentals](https://learn.secbyte.org/ctf/siem-fundamentals).
2. **Platform Mastery:** Master Splunk searching via [Splunk Essentials](https://learn.secbyte.org/ctf/splunk-essentials-mastering-siem-operations).
3. **Log Analysis:** Analyze multi-source telemetry in [Syslog Investigation](https://learn.secbyte.org/ctf/syslog-investigation), [Linux Log Analysis Basics](https://learn.secbyte.org/ctf/linux-log-analysis-basics), [Windows Event Logging](https://learn.secbyte.org/ctf/windows-event-logging-basics-to-ir), and [Log Correlation Mastery](https://learn.secbyte.org/ctf/log-correlation-mastery).

### Path B: Digital Forensics & Incident Response (DFIR) Specialist
1. **Forensics Foundations:** Begin with [Digital Forensics Fundamentals](https://learn.secbyte.org/ctf/digital-forensics-fundamentals).
2. **Deep-Dive Forensics:** Analyze artifacts using [Memory Forensics](https://learn.secbyte.org/ctf/memory-forensics-uncovering-digital-artifacts) and [Malware Forensics: Suspicious Document](https://learn.secbyte.org/ctf/malware-forensics-suspicious-document).
3. **Incident Operations:** Manage response lifecycles through [Incident Response Basics](https://learn.secbyte.org/ctf/incident-response-basics) and [Incident Handling Process](https://learn.secbyte.org/ctf/incident-handling-process).

---

## How to Use the Labs

1. Select a practice scenario from the **Lab Collection Index**.
2. Click the direct link to open the exercise environment hosted on Learn SecByte.
3. Review scenario directives, log datasets, memory images, or suspicious file samples.
4. Execute Splunk SPL queries, analyze event logs, extract forensic artifacts with Volatility, or run incident response playbooks to capture flags.

---

## Target Audience

* **SOC Analysts & SIEM Operators:** Master Splunk SPL, correlate logs across heterogeneous systems, and build SIEM alerts.
* **Digital Forensics Examiners:** Conduct memory forensics, analyze malicious documents, and extract digital evidence safely.
* **Incident Responders:** Operationalize NIST/SANS incident handling processes, contain active threats, and conduct post-incident reviews.
* **Cybersecurity Students:** Acquire practical experience in log analysis, forensics tools, and enterprise security operations.

---

## Disclaimer

All lab links in this repository direct to official training environments hosted on Learn SecByte. All materials and exercises are provided strictly for educational purposes, defensive skill building, and authorized security research.
