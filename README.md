# Cyber Security Portfolio — Junaid Rehman

Coursework and hands-on projects from my BSc (Hons) Cyber Security at Sheffield Hallam University.

## DFIR Investigation of Captured Network Traffic
Investigated three PCAP files in Security Onion 2.4.200 (Ethical Hacking and Intrusion Detection module). Identified:
- A DarkGate command-and-control infection
- A TCP SYN port scan
- Mirai/Zmap-style NTP DDoS scanning activity
- 25 confirmed Log4Shell (CVE-2021-44228) exploitation attempts, including WAF evasion techniques

Wrote six custom Suricata detection rules in response, and produced a full incident investigation report. See `/dfir-investigation/`.

## Penetration Testing Report
Structured penetration tests against TryHackMe rooms (command injection, file inclusion/path traversal) using the PTES methodology. Findings scored and referenced against CVSS, CWE, and OWASP frameworks, with remediation recommendations. See `/pentest-report/`.
