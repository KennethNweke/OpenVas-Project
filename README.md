# OpenVas Project
Vulnerability Assessment

## Objective
In this project, I conducted a comprehensive vulnerability analysis using OpenVAS (Open Vulnerability Assessment System) on a network with the IP range of 192.168.244.0/24. The goal was to identify potential security weaknesses across various systems and applications to enhance the overall security posture of the network.


## Scope of Work:

Network Environment:

- IP Range: 192.168.244.0/24
- Devices Scanned: Three guest machines
  - Linux Mint
  - Metasploitable
  - Cyberops
- Hypervisor: VMWare Workstation Player
- OpenVAS Configuration: Updated OpenVAS feed including
  - CVE (Common Vulnerabilities and Exposures)
  - CPE (Common Platform Enumeration)
  - NVT (Network Vulnerability Tests)
  - SCAP (Security Content Automation Protocol)
  - CERT Advisories
  - Compliance Policies

## Vulnerability Detection:

During the analysis, OpenVAS was configured to scan for a wide range of vulnerabilities. The following vulnerabilities were detected:

- End of Life (EOL) Software:
  - Detected software versions that are no longer supported, posing significant security risks due to the lack of updates and patches.

- Cross-Site Scripting (XSS):
  - Identified instances where malicious scripts could be injected into web pages viewed by other users.

- Default Credentials:
  - Found systems and applications using default usernames and passwords, a common oversight that can be easily exploited by attackers.

- File Inclusion Vulnerabilities:
  - Detected potential for arbitrary file inclusion, allowing attackers to execute malicious files on the server.

- Injection Vulnerabilities:
  - Identified various types of injection attacks, such as SQL injection, that could allow attackers to interfere with the queries made to a database.

- Cross-Site Request Forgery (CSRF):
  - Found vulnerabilities where attackers could trick users into executing unwanted actions on a web application in which they are authenticated.
