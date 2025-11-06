# Configuring a Site-to-Site VPN in Azure

## Overview
This repository demonstrates the configuration of a secure Site-to-Site VPN connection between an on-premises network and an Azure virtual network to enable secure communication and resource sharing.

## Environments and Technologies Used
- Microsoft Azure (Virtual Network, Gateway Subnet, VPN Gateway)
- Local Network Gateway
- Windows 10 VM (Client)
- PowerShell and Azure Portal

## Operating Systems Used
- Windows 10
- Azure Cloud Environment

## High-Level Steps
1. Create a Virtual Network and Gateway Subnet in Azure.
2. Configure a Virtual Network Gateway for VPN.
3. Set up a Local Network Gateway to simulate on-premises.
4. Connect the gateways using a shared key.
5. Verify connectivity between the on-premises and Azure networks.

## Actions and Observations
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Creating Virtual Network"/>
</p>
<p>
Created an Azure Virtual Network and configured a dedicated gateway subnet for VPN connectivity.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Configuring VPN Gateway"/>
</p>
<p>
Deployed a VPN Gateway in Azure and linked it to the Virtual Network, enabling routing between networks.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Creating Local Network Gateway"/>
</p>
<p>
Configured a Local Network Gateway representing the on-premises side of the connection.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Connecting Gateways"/>
</p>
<p>
Established a Site-to-Site VPN connection using a shared key and verified successful handshake and connectivity through PowerShell.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Testing Connectivity"/>
</p>
<p>
Tested secure communication between the on-premises network and Azure using ping and tracert commands.
</p>
<br />
