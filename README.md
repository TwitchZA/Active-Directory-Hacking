# 🛡️ Active Directory Pentesting Playbook (Netexec)

## 📌 Overview
This repository provides a **lawful penetration testing playbook** for Active Directory environments using **Netexec (nxc)**.

Designed for:
- Red Teamers
- Cybercrime Investigators (DPCI / Law Enforcement)
- OSCP / PNPT Students

---

## 🔥 Capabilities Covered
- LDAP Enumeration
- Credential Testing
- ASREPRoasting
- Kerberoasting
- BloodHound Collection
- Privilege Escalation Paths

---

## 🧰 Tools Used
- Netexec (nxc)
- BloodHound
- Hashcat
- Impacket

---

## 🗺️ Methodology

1. Reconnaissance
2. Enumeration
3. Credential Access
4. Privilege Escalation
5. Lateral Movement
6. Persistence

---

## 🔄 Attack vs Defence Mapping

| Attack | Detection | Prevention |
|-------|--------|-----------|
| LLMNR Poisoning | Multicast traffic spikes | Disable LLMNR |
| ASREPRoast | Kerberos anomalies | Enforce pre-auth |
| Kerberoast | SPN requests | Strong passwords |
| Credential Dumping | LSASS access | Credential Guard |
| BloodHound | LDAP spikes | Query monitoring |

## ⚠️ Legal Disclaimer
All techniques in this repository must be used **ONLY in authorised environments**.

---

## 👤 Author
Levi Goddard  
DPCI Cybercrime / Pentester
