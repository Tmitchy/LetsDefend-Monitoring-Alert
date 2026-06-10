# LetsDefend-Monitoring-Alert
## Analysis:
On 14 March 2021 at 07:15 PM, alert SOC137 - Malicious File/Script Download Attempt was triggered, indicating a potential malware-related activity. The alert is mapped to MITRE ATT&CK Technique T1204 (User Execution), suggesting that a user may have executed or attempted to download a malicious file or script. As a security analyst, I would investigate the affected host, identify the source URL or IP address, review downloaded files, analyze process execution events, and determine whether the download was successful. Additional analysis would include checking endpoint logs, antivirus detections, and network traffic to assess the scope and impact of the activity. Given the Medium severity, the event requires validation to determine whether it represents a genuine compromise or a false positive.

## Objective: 
- Determine whether the file/script download was malicious,
- Identify the affected system and user,
- Assess any subsequent execution activity,
- and recommend containment or remediation actions if compromise is confirmed.<br><br>


<img width="823" height="350" alt="image" src="https://github.com/user-attachments/assets/46156a6d-2078-4e92-9a17-5807fc89a058" /><br>
*Fig 1*

<img width="823" height="350" alt="image" src="https://github.com/user-attachments/assets/8126e74c-cb68-48ea-a3ef-ca10f517cef3" /><br>
*Fig 2*
## Event Description

The event reported a blocked attempt to download a potentially malicious file named `INVOICE PACKAGE LINK TO DOWNLOAD.docm`, as shown in the images below. The images display the hashed file along with the device/host information and the assigned IP address. This crucial information necessitates further analysis to determine whether the file is indeed malicious and to implement any required protective measures.

<img width="823" height="200" alt="image" src="https://github.com/user-attachments/assets/f34fe10e-48b6-4265-a794-dfc705405dae" /><br>
*Fig 3*

<img width="823" height="200" alt="image" src="https://github.com/user-attachments/assets/1f70db7c-642e-45d3-b3c2-df3a69890bb2" /><br>
*Fig 4*<br>

I began by collecting information, including the hostname and IP address of the device. Once I discovered the host on the network, the first step was to quarantine the device by disconnecting it from the network, as shown in the image below. After that, I examined the processes, network activity, terminal History, and browser history to gather more information about the alerted malicious file.

<img width="675" height="117" alt="image" src="https://github.com/user-attachments/assets/6eef784e-7371-4343-8285-6b49c65130af" />

<img width="823" height="350" alt="image" src="https://github.com/user-attachments/assets/7f6dd59a-a241-47d3-a97d-83936ac08bda" /><br>

<img width="823" height="350" alt="image" src="https://github.com/user-attachments/assets/27fcef12-d7d5-4967-b35b-d11f308549e9" /><br>



<img width="823" height="300" alt="image" src="https://github.com/user-attachments/assets/0843df54-8753-4cf2-9428-0febb43e11fa" /><br>

<img width="823" height="350" alt="image" src="https://github.com/user-attachments/assets/7a14fe7f-7ccc-442e-86b7-56871b427b7e" /><br>

<img width="676" height="266" alt="image" src="https://github.com/user-attachments/assets/012f107c-a098-4ed8-9713-b39fec1e66ca" /><br>

<img width="683" height="259" alt="image" src="https://github.com/user-attachments/assets/7186e686-7297-4be7-b704-5c9e15254d09" /><br>

<img width="920" height="428" alt="image" src="https://github.com/user-attachments/assets/8bf4031c-c970-4506-934d-58483480436c" />

<img width="899" height="307" alt="image" src="https://github.com/user-attachments/assets/a60cf25c-d39e-4031-91b4-bfe88e4bc8b4" />

<img width="433" height="229" alt="image" src="https://github.com/user-attachments/assets/cfd0dc94-b61c-42e8-8cdd-aa14b4484486" />



<img width="479" height="272" alt="image" src="https://github.com/user-attachments/assets/f10cda6c-17b8-4cb9-b90b-a49fa9413918" />

<img width="776" height="350" alt="image" src="https://github.com/user-attachments/assets/cff15b9f-806e-4e7a-a2b4-a5ee375e755d" />
