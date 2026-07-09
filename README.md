# Windows-Security-Hardening
Windows 11 security hardening lab demonstrating attack surface reduction, security best practices, and configuration validation.

## Lab Architecture

This project uses the cybersecurity home lab created in the previous project (https://github.com/jaya049/cybersecurity_home_lab.git). The same VirtualBox environment consisting of a Kali Linux VM and a Windows 11 VM is used to perform Windows security hardening and validation.

- **Kali Linux:** Used as the administration and validation system for later security testing.
- **Windows 11:** Target system being hardened according to security best practices.
- **VirtualBox NAT:** Provides Internet connectivity for updates.
- **Host-Only Network:** Intended for isolated communication between virtual machines.

![](docs/screenshots/architecture.png)


| Threat | Mitigation |
|---------------------------|----------------|
| Unauthorized local access | Disable Guest account |
| Weak passwords | Password policy |
| Malware | Microsoft Defender |
| Unauthorized inbound connections | Windows Firewall |
| Privilege escalation | UAC |
| Legacy protocols | Disable SMBv1 |

## Windows Update

### Objective

Ensure the operating system is updated with the latest security patches.

### Procedure

Checked Windows Update through the Windows Update settings.

### Verification

Confirmed the operating system reports that it is up to date.

### Security Benefit

Security updates reduce the risk of exploitation by patching known vulnerabilities.

