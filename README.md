# Cybersecurity
*Documentation Format For Milestone Project - Cybersecurity*

*1. Title*  
Cybersecurity Milestone Project

*2. Project name*  
`SecureCorp Network - Implementing Zero Trust & Cloud Security`

*3. Objective*  
To simulate a corporate network and apply cybersecurity principles learned across 5 milestones to identify vulnerabilities, implement security controls, and protect organizational assets from cyber threats.

*4. Problem Statement*  
Small to medium organizations lack proper security controls leading to data breaches, unauthorized access, and privilege escalation. This project addresses these issues by applying Zero Trust, IAM, and system hardening techniques.

*5. Research Findings*  
1. As per IBM 2024 report, average cost of data breach is $4.88 Million  
2. 90% attacks start with phishing and weak passwords  
3. Zero Trust Model and Least Privilege reduce attack surface significantly  
4. Studied MITRE ATT&CK Framework for attack techniques

*6. Methodology*  
1. *Reconnaissance*: Used Nmap to map network and find open ports  
2. *Vulnerability Assessment*: Identified weak configurations  
3. *Access Control*: Implemented IAM roles, MFA, and Least Privilege  
4. *System Hardening*: Disabled unused services, applied patches  
5. *Monitoring*: Configured logging and analyzed traffic using Wireshark  
6. *Incident Response*: Simulated attack and tested detection

*7. Tools used*  
`Kali Linux, Nmap, Wireshark, Metasploit, AWS Cloud, AWS IAM, VirtualBox, Splunk`

*8. Implementation*  
1. Created 3 VMs in VirtualBox: Attacker, Server, Client  
2. Configured AWS IAM with role-based access and MFA enabled  
3. Set up firewall rules to block unwanted traffic  
4. Performed penetration testing and documented findings  
5. Monitored logs for suspicious activity  
*GitHub Link*: `https://github.com/yourname/cybersec-milestone-project`

*9. Screenshots*  
1. Nmap Scan Results  
2. AWS IAM User & MFA Setup  
3. Wireshark Packet Capture  
4. Firewall Rules Configuration  
5. Vulnerability Report

*10. Results*  
1. Identified 5 critical vulnerabilities and patched them  
2. Successfully blocked 100% unauthorized login attempts  
3. Implemented Zero Trust - No implicit trust for any user/device  
4. Reduced risk score from High to Low

*11. Challenges*  
1. *Challenge*: AWS IAM policy errors were hard to debug  
   *Solution*: Used AWS Policy Simulator and documentation  
2. *Challenge*: Too many false positives in Wireshark  
   *Solution*: Applied filters to focus on relevant traffic

*12. Future Scope*  
1. Integrate SIEM tool for automated threat detection  
2. Add IDS/IPS like Snort for real-time monitoring  
3. Implement AI/ML for anomaly detection

*13. Conclusion*  
This Milestone Project gave hands-on experience of real-world cybersecurity. It covered everything from reconnaissance to defense. The project aligns with industry standards and helped me understand how to protect an organization end-to-end.

---

