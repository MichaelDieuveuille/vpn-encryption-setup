# ProtonVPN Connection Setup

## Overview
This repository documents the configuration of ProtonVPN on an Azure-hosted Windows 10 Virtual Machine to establish secure tunneling and encrypted internet traffic.

## Environments and Technologies Used
- Microsoft Azure Virtual Machine
- ProtonVPN (Free Plan)
- Remote Desktop Connection

## Operating Systems Used
- Windows 10 (21H2)

## High-Level Steps
1. Created a free ProtonVPN account.
2. Downloaded and installed the ProtonVPN client within the Azure VM.
3. Logged into ProtonVPN and selected a VPN server in another country (e.g., Japan).
4. Verified new IP address using WhatIsMyIPAddress.com.

## Actions and Observations
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Installing ProtonVPN Client"/>
</p>
<p>
Installed ProtonVPN on the Azure VM and authenticated the connection using a free account.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Selecting VPN Server"/>
</p>
<p>
Connected to a VPN server in Japan to test routing and encryption of outbound traffic.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Verifying New IP"/>
</p>
<p>
Confirmed that the VM’s IP address now reflected the VPN’s region (Japan), confirming tunnel success.
</p>
<br />
