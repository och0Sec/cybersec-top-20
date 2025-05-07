# 🚀 Active Directory Penetration Testing Methodology

- **Pre-Engagement Preparation**: Define scope, objectives, rules of engagement; obtain authorizations; gather preliminary AD environment details.  
- **Reconnaissance**: Passive and active AD information gathering—identify domain controllers, users, groups, GPOs, and network services.  
- **Enumeration & Scanning**: Leverage automated tools and manual scripts to enumerate objects, SPNs, ACLs, trusts, and policy settings.  
- **Exploitation**: Exploit weak credentials and misconfigurations via password spraying, Kerberoasting, Pass-the-Hash, and relay attacks.  
- **Post-Exploitation**: Escalate privileges, maintain persistence, move laterally, and extract sensitive data (hashes, tickets, credentials).  
- **Reporting**: Document findings, attack chains, and provide prioritized remediation recommendations.

# 🔧 Top 20 GitHub Tools for Windows Active Directory Penetration Testing

1. [BloodHound](https://github.com/BloodHoundAD/BloodHound) – Visualize AD relationships and attack paths.  
2. [Impacket](https://github.com/SecureAuthCorp/impacket) – Python toolkit for SMB, Kerberos, and network protocol attacks.  
3. [NetExec](https://github.com/Pennyw0rth/NetExec) – Actively maintained fork of CrackMapExec preserving all core features and adding:  
   - Expanded protocol support (SMB, SSH, LDAP, FTP, WMI, WinRM, RDP, VNC, MSSQL)  
   - Multi-domain capabilities and modular plugin system  
   - New attack modules (Kerberos Constrained Delegation automation, credential dumping from multiple sources)
   - [CrackMapExec](https://github.com/byt3bl33d3r/CrackMapExec) – Swiss-army knife for AD enumeration and multi-protocol attacks.  
4. [PowerView](https://github.com/PowerShellMafia/PowerView) – Pure PowerShell AD enumeration and situational awareness library.  
5. [Mimikatz](https://github.com/gentilkiwi/mimikatz) – Extract plaintext passwords, hashes, and Kerberos tickets from memory.  
6. [Rubeus](https://github.com/GhostPack/Rubeus) – Kerberos abuse toolkit for ticket extraction, over-pass, and forging.  
7. [Responder](https://github.com/lgandx/Responder) – Poison LLMNR, NBT-NS, and MDNS to capture credentials.  
8. [ADSuit](https://github.com/toneemarqus/AD-Suit) – GUI suite for AD enumeration and attack automation.  
9. [ActiveDirectoryAttackTool (ADAT)](https://github.com/The-Viper-One/ActiveDirectoryAttackTool) – Scripted AD attack workflow and payload delivery.  
10. [SharpHound](https://github.com/BloodHoundAD/SharpHound) – C# data collector for BloodHound graph ingestion.  
11. [LDAPDomainDump](https://github.com/dirkjanm/ldapdomaindump) – Dump AD objects and ACLs via LDAP queries.  
12. [ADRecon](https://github.com/sense-of-security/ADRecon) – Automate AD enumeration and generate detailed reports.  
13. [PingCastle](https://github.com/netwrix/pingcastle) – One-click AD health, misconfigurations, and risk assessment.  
14. [Seatbelt](https://github.com/GhostPack/Seatbelt) – Post-exploitation reconnaissance tool for Windows hosts.  
15. [SharpHound.ps1](https://github.com/BloodHoundAD/SharpHound/blob/master/SharpHound.ps1) – PowerShell version of SharpHound for stealthy data collection.  
16. [Certify](https://github.com/GhostPack/Certify) – Enumerate and abuse AD Certificate Services misconfigurations.  
17. [powerview.py](https://github.com/aniqfakhrul/powerview.py) – Python port of PowerView for interactive AD reconnaissance.  
18. [ADExplorer](https://docs.microsoft.com/sysinternals/downloads/adexplorer) – GUI to browse AD objects & permissions (Sysinternals).  
19. [KeeThief](https://github.com/tevora-threat/KeeThief) – Extract credentials from KeePass in AD environments.  
20. [DSInternals](https://github.com/Microsoft/DSInternals) – PowerShell module to analyze and attack the AD database (NTDS.dit).

---

⭐️ **Getting Started**  
1. Clone the tool repo of your choice.  
2. Review prerequisites and usage instructions in the project README.  
3. Practice in a lab environment and always follow legal/ethical guidelines.  
