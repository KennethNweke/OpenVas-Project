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
 

## Detailed Results and Mitigation Recommendations:

The scan results provided detailed insights into each detected vulnerability, including descriptions, potential impact, and severity levels. Based on the findings, the following mitigation strategies were recommended:

- For End of Life (EOL) Software:
  - Upgrade to supported versions of software or migrate to alternative solutions.

- For Cross-Site Scripting (XSS):
  - Implement input validation and output encoding.
  - Use Content Security Policy (CSP) headers to restrict the sources from which scripts can be loaded.

- For Default Credentials:
  - Change all default credentials to strong, unique passwords.
  - Implement multi-factor authentication (MFA) where possible.

- For File Inclusion Vulnerabilities:
  - Validate and sanitize all user inputs.
  - Use secure coding practices to avoid including files based on user inputs.

- For Injection Vulnerabilities:
  - Use prepared statements and parameterized queries.
  - Sanitize and validate all inputs to prevent injection attacks.

- For Cross-Site Request Forgery (CSRF):
  - Implement anti-CSRF tokens in web forms.
  - Ensure that state-changing operations require a secure, unpredictable token.

## Conclusion:
The vulnerability analysis project using OpenVAS successfully identified multiple security weaknesses within the network. By addressing these vulnerabilities, the overall security posture of the network can be significantly improved, reducing the risk of potential attacks. This project underscores the importance of regular vulnerability assessments and proactive security measures in maintaining a robust defense against evolving threats.

## Technologies and Tools Used:
- OpenVAS: For vulnerability scanning and assessment.
- VMWare Workstation Player: As the hypervisor to manage guest machines.
- Linux Mint, Metasploitable, Cyberops: As target systems for vulnerability analysis.


## Skills Demonstrated:
- Network vulnerability assessment
- Use of OpenVAS for comprehensive security scanning
- Identification and mitigation of various types of vulnerabilities
- Application of security best practices and compliance policies
- Effective use of virtualization technologies

By systematically identifying and addressing the detected vulnerabilities, this project highlights the critical role of regular security assessments in safeguarding network environments.

## Watch the video on YouTube or [View on LinkedIn](https://wwhare&utm_medium=member_desktop)

[![Link to YouTube Video](https://img.youtube.com/vi/g3N7bcDuzYU/0.jpg)](https://www.youtube.com/watch?v=g3N7bcDuzYU)




