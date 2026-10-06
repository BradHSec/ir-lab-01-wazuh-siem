\# Project 1: SIEM Detection Lab (Wazuh + Sysmon)



Built a virtual SIEM lab that collects Windows and Linux telemetry,

then wrote custom detections and tested them with real attack commands.



\## Architecture

(Add a diagram image here: Kali -> Windows 11 victim -> Wazuh SIEM)



| VM | Role |

|---|---|

| Wazuh OVA | SIEM server |

| Windows 11 | Victim, Sysmon + Wazuh agent |

| Kali | Attacker |

| Ubuntu | Second victim, Wazuh agent |



\## Setup notes

\- Versions used: Wazuh 4.14.x, Windows 11 Enterprise eval, Sysmon

\- Problems I hit and how I fixed them: ...



\## Detection exercises

| Technique | What I ran | Events seen | Detected? | Missed / improved |

|---|---|---|---|---|

| T1110 Failed logons | net use loop | 4625 x6 | | |

| T1059.001 Encoded PowerShell | -EncodedCommand | Sysmon 1, 4104 | | |



\## Custom rules

(Paste your local\_rules.xml rules here and explain what each catches)



\## Findings

(Screenshots of alerts and the dashboard)



\## Lessons learned

What I would improve next.

