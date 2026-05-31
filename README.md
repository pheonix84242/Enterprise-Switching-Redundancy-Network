# Enterprise Switching Redundancy Network

## Overview
This project demonstrates an Enterprise Switching Redundancy Network designed in Cisco Packet Tracer using a hierarchical network architecture consisting of Core, Distribution, and Access layers. The network is built to provide high availability, fault tolerance, and efficient traffic management through redundant links and Layer 2 switching technologies.

## Technologies Used
- VLANs
- VTP (VLAN Trunking Protocol)
- EtherChannel (LACP)
- Rapid PVST+
- STP Root Bridge Configuration
- Redundant Trunk Links

## Network Design
The topology consists of:
- 1 Core Switch (CORE-SW1)
- 2 Distribution Switches (DISTR-SW1 & DISTR-SW2)
- 2 Access Switches (ACCESS-SW1 & ACCESS-SW2)
- 4 End Devices (PCs)

VLANs are used to separate departments, while VTP simplifies VLAN management across switches. EtherChannel bundles multiple links together to increase bandwidth and provide redundancy. Rapid PVST+ prevents Layer 2 loops and automatically activates backup paths when link failures occur.

## VLAN Structure
| VLAN | Department |
| 10 | HR |
| 20 | Finance |
| 30 | IT |
| 99 | Management |

## Key Features
- Centralized VLAN management using VTP
- Increased bandwidth with EtherChannel
- Loop prevention using Rapid PVST+
- Root Bridge election for optimized traffic flow
- Redundant links for fault tolerance
- Automatic failover during link failures
- Scalable enterprise network design

## Skills Demonstrated
- Enterprise Network Design
- Layer 2 Switching
- VLAN Configuration
- VTP Deployment
- EtherChannel (LACP)
- Rapid PVST+
- Network Redundancy
- High Availability Implementation
- Cisco Packet Tracer

## Outcome
Successfully designed and implemented a resilient enterprise switching network capable of maintaining connectivity during failures while ensuring efficient traffic forwarding, loop prevention, and centralized VLAN administration.
