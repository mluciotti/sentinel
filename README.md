<h1>Logging failed RDP attempts using Microsoft (Azure) Sentinel</h1>


<h2>Description</h2>
<b>Using a Powershell script and parsing out Windows Event Log information for failed RDP attacks, a third party API was used to collect geographic information about the attacker's location.
</b>
<br />
<br />
Microsoft (Azure) Sentinel (SIEM) was connected to a live virtual machine acting as a honey pot. The attacker information was ultimately plotted on a Microsoft (Azure) Sentinel Map. 
<br />
<br />

<h2>Utilities Used</h2>

- <b>ipgeolocation.io:</b> IP Address to Geolocation API

<p align="center">
<img src="https://i.imgur.com/lOGsOPg.png" height="100%" width="100%" alt="RDP"/>
</p>


<h2>Attacks incoming and custom logs outputting geodata</h2>

<p align="center">
<img src="https://i.imgur.com/HzZ8LjO.png" height="100%" width="100%" alt="RDP"/>
</p>

<h2>World Map with attempted intrusions plotted</h2>

<p align="center">
<img src="https://i.imgur.com/948OSPv.png" height="100%" width="100%" alt="RDP"/>
</p>
