# Project 1: SIEM Detection Lab (Wazuh + Sysmon)



Built a virtual SIEM lab that collects Windows and Linux telemetry,

then wrote custom detections and tested them with real attack commands.



## Architecture

![Main Screenshot](NEW Wazuh SIEM Architecture)



## Setup notes

\- Versions used: Wazuh 4.14.x, Windows 11 Enterprise eval, Sysmon

\- Problems I hit and how I fixed them: ...



## Detection exercises

| Technique | What I ran | Events seen | Detected? | Missed / improved |

|---|---|---|---|---|

| T1110 Failed logons | net use loop | 4625 x6 | | |

| T1059.001 Encoded PowerShell | -EncodedCommand | Sysmon 1, 4104 | | |



## Custom rules

(Paste your local\_rules.xml rules here and explain what each catches)



## Findings

(Screenshots of alerts and the dashboard)



## Lessons learned

What I would improve next.

