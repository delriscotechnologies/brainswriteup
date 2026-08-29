<h1 align="center">TRYHACKME: BRAINS WRITE-UP</h1>

<p align="center">
  A beginner-friendly walkthrough of the TryHackMe Brains room, from reconnaissance and vulnerability research to exploitation and defensive detection.
</p>

<p align="center">
  <a href="https://delriscotechnologies.github.io/brainswriteup/">Full Write-Up</a>
</p>

---

This write-up follows an investigation of a vulnerable JetBrains TeamCity instance in the TryHackMe Brains lab.

It covers reconnaissance, TeamCity version identification, CVE-2024-27198 research, authorized exploitation with Metasploit, and defensive investigation with Splunk.

> Use these techniques only in labs or on systems you own or are explicitly authorized to test.

## References

- [TryHackMe: Brains room](https://tryhackme.com/room/brains)
- [JetBrains advisory for CVE-2024-27198 and CVE-2024-27199](https://blog.jetbrains.com/teamcity/2024/03/additional-critical-security-issues-affecting-teamcity-on-premises-cve-2024-27198-and-cve-2024-27199-update-to-2023-11-4-now/)
