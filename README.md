# -Static-route-Palo-Alto

<h2>Description</h2>
In this hands-on lab, we configure static routing to allow devices from both the inside zone and outside zone to communicate, I have also configured loopback addresses on both sides of the inside and outside zone. Therefore I will ensure that routes are configured on both routers respectively before carrying out the Palo Alto static configuration. Its also important to ensure that there is two way reachabliity, in this lab I noticed that there was an issue not being able to route the traffic back due to not advertizing the gateway route.  

<br />

<h2>Languages and Utilities Used</h2>

- <b> Eve ng </b> 
- <b>VM Workstation </b>
- <b> Palo Alto Firewall </b>

<h2>Environments Used </h2>

- <b> Vm Workstation Pro </b> 

<h2>Program walk-through:</h2>

<p align="center">
Setup devices <br/>
<img src="https://i.imgur.com/EFxjh9R.png" height="80%" width="80%" alt="Palo Alto Source NAT"/>
<br />
<br />

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
