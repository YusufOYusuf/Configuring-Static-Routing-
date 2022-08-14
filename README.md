<h1>Configuring Static Routing</h1>


<h2>Description</h2>
In this lab, I learned to configure static routing. Static routing is the manual configuration and selection of a network route, usually managed by the network administrator. In static routing, you need to define the next hop and network both.
<br />



<h2>Environments Used </h2>

- <b>Ubuntu 20.04.2 LTS</b> 
- <b>PuTTY SSH Client</b>

<h2>Program walk-through:</h2>

<p align="center">
From the left sidebar click PuTTY SSH Client and proceed to put in the IP address, port number, click Telnet and then click open.: <br/>
<img src="https://i.postimg.cc/9fY5zg8Z/Screen-Shot-2022-08-13-at-4-59-58-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />
  
  
<br />
In the R1 terminal window type the commands<br/>
1. show ip route <br/>
2. ping 192.168.1.2 <br/>
<img src="https://i.postimg.cc/FHGw4k7V/Screen-Shot-2022-08-13-at-5-02-25-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
<br />
  
  
  
<br />
 In the R1 terminal type the following commands to configure static routing <br/>
 1.configure terminal <br/>
 2. ip route 192.168.1.0 255.255.255.0 192.168.0.2 <br/>
 3. end <br/>
 <img src="https://i.postimg.cc/RC7BYFQX/Screen-Shot-2022-08-13-at-5-09-27-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>
 
 
 
<br />
Type the following commands to enable mode <br/>
1. show ip route <br/>
2. ping 192.168.1.2 <br/>
<img src="https://i.postimg.cc/52vqBhMY/Screen-Shot-2022-08-13-at-5-15-15-PM.png" height="80%" width="80%" alt="Configuring Advanced Ethernet Options Steps"/>


  
  
 

  
  
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
