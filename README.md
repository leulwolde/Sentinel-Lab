<h1>RDP Brute force to IP Geolocation information</h1>

<h2>Description</h2>
<b>The Powershell script in this repository is responsible for parsing out Windows Event Log information for failed RDP attacks and using a third party API to collect geographic information about the attackers location.
</b>
<br />
<br />
<h2>Languages Used</h2>

- <b>PowerShell:</b> Extract RDP failed logon logs from Windows Event Viewer 

<h2>Utilities Used</h2>

- <b>ipgeolocation.io:</b> IP Address to Geolocation API


<h2>World map of incoming attacks after 24 hours (built custom logs including geodata)</h2>

<p align="center">
 <img src="https://raw.githubusercontent.com/leulwolde/Sentinel-Lab/refs/heads/main/rdp_hack%20attempts_map.png" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
