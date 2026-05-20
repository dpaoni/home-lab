# Personal Cybersecurity Home Lab

A hands-on cybersecurity lab I built to practice real-world penetration testing techniques in a safe, controlled environment.

---

## Lab Overview

This lab is designed to simulate real attack and defense scenarios using industry-standard tools. It runs entirely on a Windows host machine using VirtualBox for virtualization.

| Component | Details |
|---|---|
| Host OS | Windows |
| Hypervisor | VirtualBox |
| Attacker Machine | Kali Linux (Live USB with persistence) |
| Target Machine | Metasploitable 2 |
| Network Mode | Host-Only (isolated from internet) |

---

## Tools & Techniques

### Reconnaissance
- **Nmap** - network scanning, port discovery, service/version detection
- **Gobuster** - directory and file enumeration on web servers
- **Nikto** - web server vulnerability scanning

### Exploitation
- **Metasploit Framework** - vulnerability exploitation and post-exploitation
  - Used msfconsole, db_nmap, and workspaces for organized testing
  - Successfully exploited vsftpd 2.3.4 backdoor vulnerability on Metasploitable 2

### Environment
- **VirtualBox** - VM setup and network configuration (NAT, Host-Only, Bridged)
- **Kali Linux** - primary penetration testing OS
- **Metasploitable 2** - intentionally vulnerable Linux target

---

## Concepts Practiced

- Penetration testing methodology
- Network scanning and enumeration
- Vulnerability identification and exploitation
- VM networking and isolation
- Linux command line fundamentals
- Firewall configuration using VMs

---

## Background

Built alongside my coursework in the **Cybersecurity & High Tech Engineering program** at Capital Area Career Center (CACC) in Springfield, IL. Currently pursuing a B.S. in Cybersecurity at the University of Illinois Springfield.
