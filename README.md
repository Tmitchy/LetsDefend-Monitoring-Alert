# LetsDefend-Monitoring-Alert
## Analysis:
On 14 March 2021 at 07:15 PM, alert SOC137 - Malicious File/Script Download Attempt was triggered, indicating a potential malware-related activity. The alert is mapped to MITRE ATT&CK Technique T1204 (User Execution), suggesting that a user may have executed or attempted to download a malicious file or script. As a security analyst, I would investigate the affected host, identify the source URL or IP address, review downloaded files, analyze process execution events, and determine whether the download was successful. Additional analysis would include checking endpoint logs, antivirus detections, and network traffic to assess the scope and impact of the activity. Given the Medium severity, the event requires validation to determine whether it represents a genuine compromise or a false positive.

## Objective: 
Determine whether the file/script download was malicious, identify the affected system and user, assess any subsequent execution activity, and recommend containment or remediation actions if compromise is confirmed.


<img width="750" height="279" alt="image" src="https://github.com/user-attachments/assets/46156a6d-2078-4e92-9a17-5807fc89a058" />

