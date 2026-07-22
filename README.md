# Project Overview

This project expands upon the **Sky Tier Capital Enterprise IT Infrastructure Simulation** by introducing a foundational network environment using Cisco Packet Tracer.

The purpose of this lab was to design and configure a small Local Area Network (LAN) that represents the beginning stages of an enterprise network environment. The network was built to provide connectivity between client workstations, establish proper IPv4 addressing, and validate communication between connected systems.

This project builds upon the existing Sky Tier Capital infrastructure, which includes Windows Server 2022, Active Directory, DNS, and Group Policy services. By adding the networking layer, this environment begins to simulate how enterprise systems communicate within an organization's internal infrastructure.

---

# Network Topology

The current Sky Tier Capital network consists of a Cisco Catalyst 3650 switch connecting two workstation endpoints, STC1 and STC2.
     
## Network Devices

| Device | Purpose |
|:---:|:---:|
| Cisco Catalyst 3650 Switch | Enterprise-grade Layer 3 capable switch providing centralized network connectivity |
| STC1 | Client workstation |
| STC2 | Client workstation |

---

# Switch Configuration

## Cisco Catalyst 3650

The network was built using a **Cisco Catalyst 3650 Series Switch** within Cisco Packet Tracer.

The Catalyst 3650 is a commonly used enterprise access-layer switch designed to provide reliable connectivity between end-user devices and network infrastructure.

In a production environment, switches like the Catalyst 3650 are commonly deployed to:

- Connect employee workstations and endpoint devices
- Provide reliable wired network access
- Support VLAN segmentation and network organization
- Enable communication between connected devices
- Serve as an access layer component within larger enterprise networks

For this lab, the switch was configured as the central connectivity point between the Sky Tier Capital workstation endpoints.

Configured switch:

The switch provided the Layer 2 connectivity required for STC1 and STC2 to communicate within the local network environment.

---

# Workstation Configuration

The endpoint systems were configured to represent user devices within the Sky Tier Capital environment.
