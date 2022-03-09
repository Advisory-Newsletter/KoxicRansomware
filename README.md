# KoxicRansomware
**Koxic Ransomware**


The following Registry values are added/modified by the ransomware
> SOFTWARE\\Policies\\Microsoft\\Windows NT\\Terminal Services\\MaxDisconnectionTime
> SOFTWARE\\Policies\\Microsoft\\Windows NT\\Terminal Services\\MaxIdleTime
> SOFTWARE\\Policies\\Microsoft\\Windows\\HomeGroup\\DisableHomeGroup
> SOFTWARE\\Policies\\Microsoft\\Windows Defender\\DisableAntiSpyware
> SOFTWARE\\Policies\\Microsoft\\Windows Defender\\AllowFastServiceStartup
> SOFTWARE\\Policies\\Microsoft\\Windows Defender\\ServiceKeepAlive
> SOFTWARE\\Policies\\Microsoft\\Windows Defender\\Real-Time Protection\\DisableRealtimeMonitoring
> SOFTWARE\\Policies\\Microsoft\\Windows Defender\\Real-Time Protection\\DisableBehaviorMonitoring
> SOFTWARE\\Policies\\Microsoft\\Windows Defender\\Real-Time Protection\\DisableScanOnRealtimeEnable
> SOFTWARE\\Policies\\Microsoft\\Windows Defender\\Real-Time Protection\\DisableIOAVProtection
> SOFTWARE\\Policies\\Microsoft\\Windows Defender\\Real-Time Protection\\DisableOnAccessProtection
> SOFTWARE\\Microsoft\\Windows Defender\\Spynet\\DisableBlockAtFirstSeen
> SOFTWARE\\Microsoft\\Windows Defender\\Spynet\\SubmitSamplesConsent
> SOFTWARE\\Microsoft\\Windows Defender\\UX Configuration\\NotificationSuppress
> SOFTWARE\\Microsoft\\Windows Defender\\Features\\TamperProtection
> Software\\Microsoft\\Windows\\CurrentVersion\\Policies\\Explorer\\HideSCAHealth
> Software\\Policies\\Microsoft\\Windows\\Explorer\\DisableNotificationCenter


**Indicators of Compromise:**

Malicious Hashes:
SHA256
699159e695e230a48d94b6103b48940ed596d0b48fb6d936c04d86eed539cecd

Email ID--- wilhelmkox@tutanota[.]com


**Mitigation Steps**:
1. Block the listed IoCs in Security control solutions immediately.
2. Upgrade software and operating systems, applications, and firmware on network assets in a timely manner. Consider using a centralized patch management system.
3. We recommend users to set up multi-factor authentication to remotely access networks from external sources.
4. We recommend victims to run an antivirus tool to eliminate the intruder, protecting your files. Set antivirus/antimalware programs to conduct regular scans of network assets using up-to-date signatures.
5. Secure your back-ups and ensure all data is not accessible for modification or deletion from the system where the data resides. 


**Reference links**
1	Remove Koxic ransomware (virus) - Recovery Instructions Included (2-spyware.com)
2	KOXIC Virus Files — "koxic@cock.li" Ransomware (howtofix.guide)
3	Koxic Ransomware - Decryption, removal, and lost files recovery (updated) (pcrisk.com)
4	Cyble — Koxic Ransomware Deep-dive Analysis

