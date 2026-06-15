# REvil Corp - TryHackMe Writeup

This repository contains my writeup for the TryHackMe room **REvil Corp**.

In this room, I investigated a ransomware-infected Windows host using **Redline**. The scenario involved a user reporting that files had been renamed with an unfamiliar extension, which led to a host-based investigation of file system artifacts, browser history, timeline events, and malware indicators.

## Room Information

- Platform: TryHackMe
- Room: REvil Corp
- Category: Incident Response / Digital Forensics
- Tool Used: Redline

## Investigation Summary

The investigation focused on identifying the compromised user, the malicious executable, the download source, the ransomware extension, ransom note, changed wallpaper, and malware family names.

During the analysis, I used Redline to review:

- System information
- User accounts
- File system artifacts
- File download history
- Browser URL history
- Timeline events
- File hashes

The malware was associated with the ransomware family names **REvil**, **Sodin**, and **Sodinokibi**.

## Key Skills Practiced

- Redline host investigation
- Ransomware artifact analysis
- File system review
- Timeline analysis
- Browser history investigation
- Hash-based malware lookup
- Incident response documentation

## Writeup

The full writeup is available as a PDF:

[REvil-Corp-TryHackMe-Writeup.pdf](./REvil-Corp-TryHackMe-Writeup.pdf)

## Disclaimer

This writeup is for educational purposes only. The investigation was completed in a controlled TryHackMe lab environment.
