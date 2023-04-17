# Threat-Hunting

Qbot BB22

Microsoft Defender :

**DeviceProcessEvents
| where InitiatingProcessFileName contains "winzip" and 
FileName contains "wscript.exe" and
ProcessCommandLine contains "wsf"
**
