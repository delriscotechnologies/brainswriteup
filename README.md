<h1 align="center">TRYHACKME: BRAINS WRITE-UP</h1>

<p align="center">
  A beginner-friendly walkthrough of the TryHackMe Brains room, from reconnaissance and vulnerability research to exploitation and defensive detection.
</p>

<p align="center">
  <a href="https://delriscotechnologies.github.io/brainswriteup/">Full Write-Up</a>
</p>

---

This write-up follows the investigation of an exposed JetBrains TeamCity instance. It covers service discovery with Nmap, identification of TeamCity 2023.11.3, research into CVE-2024-27198, an authorized authentication-bypass and code-execution chain in the TryHackMe lab, and review of related activity in Splunk.

The repository is an educational record of the room and is intended to help learners connect offensive techniques with the logs and behaviors defenders can monitor.

> Use these techniques only in labs or on systems you own or are explicitly authorized to test.

## Topics

- Network reconnaissance with Nmap
- TeamCity version identification and CVE research
- Metasploit exploitation in a controlled lab
- Defensive investigation with Splunk

## Reference

- [TryHackMe: Brains room](https://tryhackme.com/room/brains)
- [JetBrains advisory for CVE-2024-27198 and CVE-2024-27199](https://blog.jetbrains.com/teamcity/2024/03/additional-critical-security-issues-affecting-teamcity-on-premises-cve-2024-27198-and-cve-2024-27199-update-to-2023-11-4-now/)
