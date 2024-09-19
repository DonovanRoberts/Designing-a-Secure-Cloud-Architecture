<h1>☁️Transitioning to Cloud-Based Architecture with Docker Containers</h1>



<h2>Description</h2>
This lab focuses on the transition from a traditional server cluster to a cloud-based architecture. Traditional web applications rely on tightly controlled networks, with network security managed at the entry point. In contrast, cloud-based systems involve provisioning services from cloud providers, such as load balancers and database servers, which can be connected via a virtual network. This setup can offer similar security to traditional models but requires trust in the cloud vendor.

An alternative approach explored in this lab is the zero-trust model, where all resources require credentials and communication channels are encrypted. The lab involves designing a cloud-based system to scale client-facing servers using Docker containers, provisioning machines from various cloud providers, and maintaining a private Docker registry for container images. Initial stages include keeping the registry and persistent storage in-house. Future labs will cover identity and access management and advanced security tools.
<br />


<h2>Languages and Utilities Used</h2>

- <b>SCAP</b> 
- <b>Wazuh</b>
- <b>Docker</b>
- <b>Dia</b>

<h2>Environments Used </h2>

- <b>vWorkstation</b>
- <b>SecServer</b>
- <b>pfSense</b>
- <b>DockerServer</b>
- <b>DockerRunner</b> (21H2)

<h2>Program Reflection & Code:</h2>

<p align="center">
Created Cloud architecture diagram via Dia: <br/>
<img src="https://i.imgur.com/dkc47Rz.png" height="80%" width="80%" alt="Transitioning to Cloud-Based Architecture with Docker Containers"/>
<br />
<br />
Scan machines using SCAP documents & Customize a SCAP profile:  <br/>
<img src="https://i.imgur.com/mV9B1ma.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/MYdN2eS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enable SCAP scans in Wazuh:  <br/>
<img src="https://i.imgur.com/ZW6AGPp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enable SCAP scans in Wazuh:  <br/>
<img src="https://i.imgur.com/ZW6AGPp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enable Docker scans in Wazuh:  <br/>
<img src="https://i.imgur.com/sCEFSPq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
