# Cyber Security Penetration Testing Writeups

A comprehensive collection of penetration testing reports and walkthroughs from various cybersecurity challenges and platforms.

## 📁 Repository Structure

```
├── Full writeups/          # Complete detailed penetration testing reports
│   ├── HTB Bizness.html    # Apache OFBiz RCE (CVE-2023-49070), weak SHA-1 password hashing, and password reuse for root access
│   ├── HTB BoardLight.pdf  # Network enumeration, service exploitation, and lateral movement
│   ├── HTB Broker.html     # Apache ActiveMQ RCE (CVE-2023-46604), NGINX configuration abuse for file upload, and SSH key injection to root
│   ├── HTB Cap.html        # IDOR leading to PCAP file download, credential exposure in network captures, and CVE-2021-4034 (PwnKit) privilege escalation
│   ├── HTB Chemistry.html  # RCE via malicious .cif file upload exploiting Python sandbox escape, MD5 hash cracking from SQLite database, and path traversal in aiohttp service
│   ├── HTB Code.html       # Python sandbox escape in web code editor, SQLite password hash cracking, and backup utility symlink manipulation for root access
│   ├── HTB Codify.pdf      # Code execution vulnerabilities, sandbox escape, and root access
│   ├── HTB CozyHosting.html # Spring Boot Actuator information disclosure, command injection in admin panel, hardcoded database credentials, and sudo SSH LocalCommand abuse
│   ├── HTB Devvortex.html  # Joomla information disclosure (CVE-2023-23752), RCE via template modification, password hash cracking, and CVE-2023-1326 (apport-cli) privilege escalation
│   ├── HTB Dog.html        # Exposed .git repository leading to credential disclosure, Backdrop CMS authenticated RCE, password reuse, and command injection in sudo utility
│   ├── HTB Editorial.html  # SSRF in file upload feature, internal API credential disclosure, Git commit history exposure, and CVE-2022-24439 (GitPython) command injection
│   ├── HTB GreenHorn.html  # Gitea repository credential exposure, Pluck CMS authenticated RCE via module upload, password reuse, and OpenVAS sudo abuse with Depix password recovery
│   ├── HTB Headless.html   # XSS in User-Agent header for session hijacking, command injection in admin dashboard, and sudo path hijacking via syscheck script
│   ├── HTB Instant.html    # Hardcoded admin JWT in Android APK, authenticated LFI in API endpoint for SSH key theft, and Solar-PuTTY backup file decryption
│   ├── HTB Keeper.html     # Default Request Tracker credentials, KeePass master password recovery (CVE-2023-32784) from memory dump, and root SSH key stored in database
│   ├── HTB Lame.html       # Multiple exploitation vectors: vsftpd v2.3.4 backdoor (CVE-2011-2523), distccd command execution (CVE-2004-2687), and Samba usermap_script RCE (CVE-2007-2447)
│   ├── HTB LinkVortex.html # Exposed .git repository on dev subdomain, Ghost CMS arbitrary file read (CVE-2023-40028), credential exposure, and sudo symlink chain bypass
│   ├── HTB Nocturnal.html  # Local File Inclusion (LFI) with null byte bypass, credential disclosure, password reuse, and ISPConfig authenticated RCE (CVE-2023-46818) privilege escalation
│   ├── HTB Perfection.html # Server-Side Template Injection (SSTI) in Ruby ERB leading to RCE, password hash cracking with disclosed schema, and excessive sudo privileges
│   ├── HTB PermX.html      # Chamilo LMS unauthenticated RCE (CVE-2023-4220), credential exposure and reuse, and privilege escalation via sudo script symlink bypass
│   └── HTB Pilgrimage.html # Exposed .git repository leading to source code disclosure, ImageMagick RCE via EXIF injection, and privilege escalation via Binwalk RCE (CVE-2022-4510) triggered by cron job
├── Walkthroughs/           # Step-by-step walkthroughs and guides
│   ├── WT - HTB Alert.pdf  # Quick reference for Alert machine exploitation techniques
│   └── WT - HTB Analytics.pdf # Step-by-step guide for Analytics machine solution
└── README.md              # This file
```

## 🎯 About This Repository

This repository contains detailed penetration testing writeups and walkthroughs from various cybersecurity platforms, primarily focusing on:

- **HackTheBox (HTB)** machines and challenges
- Complete exploitation methodologies
- Vulnerability analysis and exploitation techniques
- Post-exploitation strategies
- Privilege escalation techniques

## 📋 Contents

### Full Writeups
Detailed, comprehensive reports that include:
- Target reconnaissance and enumeration
- Vulnerability identification and analysis
- Exploitation steps with detailed explanations
- Post-exploitation activities
- Privilege escalation techniques
- Root/system access achievement
- Lessons learned and key takeaways

### Walkthroughs
Step-by-step guides that provide:
- Quick reference for solving specific challenges
- Essential commands and techniques
- Common pitfalls and solutions
- Time-efficient approaches

## 🛠️ Technologies & Tools Covered

- **Reconnaissance**: Nmap, Gobuster, Dirb, Nikto
- **Web Application Testing**: Burp Suite, OWASP ZAP, SQLMap
- **Exploitation**: Metasploit, Custom exploits, Buffer overflows
- **Post-Exploitation**: Privilege escalation, Lateral movement
- **Cryptography**: Hash cracking, Encryption/Decryption
- **Network Security**: Port scanning, Service enumeration

## 📚 Learning Objectives

These writeups are designed to help with:
- Understanding penetration testing methodologies
- Learning common vulnerability patterns
- Developing exploitation skills
- Improving cybersecurity knowledge
- Preparing for cybersecurity certifications

## ⚠️ Disclaimer

This repository is for educational purposes only. The techniques and tools demonstrated here should only be used on:
- Authorized penetration testing engagements
- Dedicated learning platforms (like HackTheBox, TryHackMe, etc.)
- Your own systems and networks
- Systems you have explicit written permission to test

**Never use these techniques on systems you don't own or don't have explicit permission to test.**

## 📖 How to Use This Repository

1. **Browse by Platform**: Look for specific platforms (HTB, etc.) in the folder structure
2. **Choose Your Level**: 
   - Use "Walkthroughs" for quick reference and learning
   - Use "Full writeups" for comprehensive understanding
3. **Follow Along**: Try to solve challenges yourself before reading the solutions
4. **Learn and Apply**: Understand the methodology, not just the commands

## 🔄 Contributing

If you'd like to contribute to this repository:
1. Fork the repository
2. Add your writeups following the existing structure
3. Ensure proper documentation and explanations
4. Submit a pull request

## 📝 License

This project is for educational purposes. Please respect the terms of service of the platforms mentioned and use responsibly.

## 🔗 Related Resources

- [HackTheBox](https://www.hackthebox.com/)
- [OWASP Testing Guide](https://owasp.org/www-project-web-security-testing-guide/)
- [NIST Cybersecurity Framework](https://www.nist.gov/cyberframework)

---

**Happy Hacking! 🚀**

*Remember: With great power comes great responsibility. Use your skills ethically and legally.*
