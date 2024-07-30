<h1>Home Network Lab</h1>

<h2>Description</h2>
This project's goal is to learn more about networking by creating my own home network. I installed pfSense on a physical machine (with only one ethernet port, which WILL cause my problems further along in the project) and connected it to my personal fiber ONT. Then I configured pfSense to make all routing decisions and act as the default gateway for my home network. I also purchased a smart switch and configured two VLANs. One will be for Internet of Things devices and the other will be a guest Wi-Fi network. The traffic on these VLANs will be logically seperated by my switch and protected from each other by firewall rules. Finally I configured the existing SOHO devices I owned to act as wireless access points to create my Wi-Fi networks.
<br />


<h2>Languages and Programs Used</h2>

- <b>pfSense</b> 
- <b>Balena Etcher</b>
- <b>CLI commands on FreeBSD/pfSense</b>

<h2>Environments Used </h2>

- <b>FreeBSD/pfSense</b>
- <b>Windows 11 Home</b>

<h2>Program walk-through:</h2>

<p align="center">
Create a network diagram: <br/>
<img src="https://i.imgur.com/PaWR7XM.png" height="80%" width="80%"/>
<br />
<br />
Create bootable usb with pfSense ISO and then install on Dell machine:  <br/>
<img src="https://i.imgur.com/iw3tjwf.png" height="80%" width="80%"/>
<br />
<br />
Install pfSense and access via web configurator:  <br/>
<img src="" height="80%" width="80%"/>
<br />
<br />
Create bootable usb with pfSense ISO and then install on Dell machine:  <br/>
<img src="https://i.imgur.com/iw3tjwf.png" height="80%" width="80%"/>
<br />
<br />
Create bootable usb with pfSense ISO and then install on Dell machine:  <br/>
<img src="https://i.imgur.com/iw3tjwf.png" height="80%" width="80%"/>
<br />

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
