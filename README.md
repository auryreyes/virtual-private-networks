<p align="center">
<img src="https://i.imgur.com/7e40z54.png"/>
</p>

<h1>Virtual Private Networks (VPNs)</h1>
In this tutorial, we observe the use of Virtual Private Network (VPN) through ProtonVPN.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop Connection
- ProtonVPN

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Steps</h2>

- Create Virtual Machine in Azure
- Sign up for ProtonVPN and test the VPN connection

A Virtual Private Network (VPN) is a service that secures your privacy online by hiding your internet connection. A VPN "tunnels" communication between the user's device and the distant server while hiding the user's real public IP address.

<h3>!ATTENTION!</h3>

Before we begin, if you haven’t already created an Azure Account or don’t know how to launch a VM in Azure, please refer to my [tutorial](https://github.com/auryreyes/create-azure-virtual-machine).

<h3>Step 1: Create a Virtual Machine in Azure</h3>

On your local computer, visit [WhatsMyIPAdress](https://whatismyipaddress.com/) and take note of the IP Address and where it’s located.
<p>
<img src="https://i.imgur.com/8oRLmOj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

(Create Virtual Machine and Discover IP Address)
<br>
- Make sure the virtual machine you build is located in a different region than you are
- Log into the VM with Remote Desktop Connection
- Visit [WhatsMyIPAdress](https://whatismyipaddress.com/) and take note of the IP Address and where it’s located
<p>
<img src="https://i.imgur.com/LoTjQsU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/AmXr1ou.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/VFYNb8c.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/k1rFTTs.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/ULs2GE4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<h3>Step 2: Sign up for ProtonVPN and test the VPN connection</h3>


On your actual computer, sign up for the free version of [ProtonVPN](https://www.protonvpn.com)
<p>
<img src="https://i.imgur.com/jh2gtFO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

Back within your VM, download the Proton VPN client
- Login to the VPN and choose a VPN server in yet another country (such as Japan)
- Visit [WhatsMyIPAdress](https://whatismyipaddress.com/) and take note of the IP Address and where it’s located. Should have a different IP address and location.

<p>
<img src="https://i.imgur.com/cAe73Tf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/vnNyLxd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/PtYK19m.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/g7WWUPj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/l44lBD8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
See whether there are any differences between Google, Disney, and/or Amazon when compared to the locations of your VPN server. The language or URL, for instance, can be different.

<br>
<br>

Congratulations! You've successfully learned what a VPN is and how it functions. If you want to protect your data, VPNs are essential. Especially if you are working in a foreign country or in public.

<h3>!ATTENTION!</h3>
Because the majority of Azure services are pay-as-you-go, be sure to remove ALL resource groups and virtual machines if you want to keep your free $200 credits.
