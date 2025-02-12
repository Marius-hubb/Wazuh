<h1>Implement Host-based IDS functionality using Wazuh HIDS and Sguil</h1>

 ## [Video Demonstration](https://drive.google.com/file/d/1Y5gEA6FMT6xhZWAioCGLsOSGqLOF9wkO/view?usp=sharing)

<h2>Description</h2>
This lab will demonstrate the use of Wazuh HIDS and agent to capture network traffic and show how to monitor the captured traffic for malicious activities in Sguil.<br />
<br />

<h2>Lab walk-through:</h2>

<p align="center">Adding the webserver 10.10.1.16 machine as Wazuh agent
<br/>
<img src="https://i.imgur.com/55MK1xc.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<br />
<p align="center">Extract the Agent key
<br/>
<img src="https://i.imgur.com/NvH0Kal.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<br />
<br />
<p align="center">creating key.txt file that will contain the Agent key. 
<br/>
<img src="https://i.imgur.com/GMSAjNg.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<br />
<br />
<p align="center">Copying the key.txt file into the shared folder on 10.10.1.16
<br/>
<img src="https://i.imgur.com/bsYP7lI.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<br />
<br />
<p align="center">Configuring the firewall to communicate with the agent
<br/>
<img src="https://i.imgur.com/TSrTMic.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<br />
<br />

<p align="center">Installing Wazuh agent on WebServer machine
<br/>
<img src="https://i.imgur.com/iRfQUMu.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<br />
<br />
<p align="center">Restarting Wazuh
<br/>
<img src="https://i.imgur.com/Oo8DdvY.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<br />
<br />
<p align="center">Verifying that the agent is active
<br/>
<img src="https://i.imgur.com/yMh3Hyy.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<br />
<br />
<p align="center">Performing a brute-forece attack or RDP service runnng on 10.10.1.16 using hydra
<br/>
<img src="https://i.imgur.com/jO3iBMC.png" height="50%" width="50%" alt="Disk Sanitization Steps"/>
<br />
<br />
