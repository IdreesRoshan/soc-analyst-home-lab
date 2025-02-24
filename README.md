# SOC Analyst Home Lab 
This lab is following the guided project by Eric Capuono - [So you want to be a SOC Analyst](https://blog.ecapuano.com/p/so-you-want-to-be-a-soc-analyst-intro)

## Overview
This project sets up a home Security Operations Center (SOC) using LimaCharlie for Endpoint Detection and Response (EDR) and Sliver C2 for adversary simulation.

- LimaCharlie Setup: Configured a Windows sensor, automated Sysmon event log collection, and added Sigma rules for threat detection.
- Attack & Defend: Deployed a Sliver C2 implant, analyzed EDR telemetry in LimaCharlie, and identified Indicators of Compromise (IOCs).
- Adversarial Testing: Elevated privileges, dumped lsass.exe credentials, and created custom detection rules to track malicious activity.
- Blocking Attacks: Developed D&R rules to terminate ransomware-like processes, preventing volume shadow copy deletion.
- Automating YARA Scanning: Implemented YARA and EDR rules to automatically detect, scan, and alert on suspicious files and processes.
