# Cisco-Ultron-Academy-Ethical-Hacker

## Module 1: Introduction to Ethical Hacking and Penetration Testing

### PenTesting Careers
- [Hacking is NOT a Crime](https://www.hackingisnotacrime.org/)
- [National Initiative for Cybersecurity Careers and Studies (NICCS) Cyber Career Pathways Tool](https://niccs.cisa.gov/workforce-development/cyber-career-pathways-tool)

### Surveying Different Standards and Methodologies
- [MITRE ATT&CK Framework](https://attack.mitre.org)
- [OWASP Web Security Testing Guide (WSTG)](https://owasp.org/www-project-web-security-testing-guide/)
- [National Institute of Standards and Technology (NIST) Special Publication (SP) 800-115](https://csrc.nist.gov/pubs/sp/800/115/final)
- [Open Source Security Testing Methodology Manual (OSSTMM)](https://www.isecom.org)
- [Penetration Testing Execution Standard (PTES)](http://www.pentest-standard.org)
- Information Systems Security Assessment Framework (ISSAF)

### Building Your Own Lab
- [Omar Santos GitHub Repository](https://github.com/The-Art-of-Hacking/h4cker)
- [Building Your Own Cybersecurity Lab and Cyber Range](https://github.com/The-Art-of-Hacking/h4cker/tree/master/build_your_own_lab)
- [Pre-Built Customized Kali VM](https://skillsforall.com/resources/lab-downloads?courseLang=en-US)
- [Investigate Kali Linux](https://www.kali.org/docs/)

## Module 2: Planning and Scoping a Penetration Testing Assessment

### Regulatory Compliance Considerations
- [Payment Card Industry Data Security Standard (PCI DSS)](https://www.pcisecuritystandards.org/)
- [Health Insurance Portability and Accountability Act of 1996 (HIPAA)](https://www.cdc.gov/phlp/publications/topic/hipaa.html)
- [Federal Risk and Authorization Management Program (FedRAMP)](https://www.fedramp.gov/)
- [General Data Protection Regulation (GDPR)](https://gdpr-info.eu/)
- [NIST General Key Management Guidance (NIST SP 800-57)](https://csrc.nist.gov/projects/key-management/key-management-guidelines)

## Module 3: Information Gathering and Vulnerability Scanning

### Using OSINT Tools
- [OSINT Framework](https://osintframework.com/)
- [WhatsMyName Web](https://whatsmyname.app/)
- [OSINT Combine](https://whatsmyname.app/)
- [SMART - Start Me Aggregated Resource Tool](https://smart.myosint.training/)
- **SpiderFoot** is an automated OSINT scanner
- **Recon-ng** is an OSINT framework that is similar to the Metasploit exploitation framework or the Social-Engineering Tooklit (SET)
- [Omar Santos GitHub Repository](https://github.com/The-Art-of-Hacking/h4cker/tree/master/osint)
- [WebSploit Labs](https://websploit.org/)
  
### DNS Lookups
- **DNSRecon Example -** $dnsrecon -d h4cker.org
- **Using Dig to Obtain Information About a Given Domain -** $dig h4cker.org
- **Obtaining the MX Record of h4cker.org -** $dig h4cker.org mx

### Identification of Technical and Administrative Contacts
- **Whois Information for the Domain h4cker.org -** $whois h4cker.org
- **Showing Technical and Administrative Email Contacts -** $whois cisco.com | grep '@cisco.com'

### Cloud vs. Self-Hosted Applications and Related Subdomains
- **DNS Name Resolution for netflix.com -** $host netflix.com
- **Example of the Ownership of IP Addresses and Applications Hosted in the Cloud-** $whois 3.230.129.93 | grep OrgName

### Cryptographic Flaws
- **The Digital Certificate Assigned to h4cker.org -** [Let’s Encrypt](https://letsencrypt.org/)
- [Certificate Transparency](https://certificate.transparency.dev/)


