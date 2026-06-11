# Enterprise Network Implementation Lab
## Network Topology 
<img width="1207" height="552" alt="Screenshot 2026-06-11 151514" src="https://github.com/user-attachments/assets/ee0f9f5c-4953-4624-bd61-dafb68de7a08" />

## Project Overview
This networking project documents the design and configuration of an enterprise enviornment by utilizing multiple core technologies. 
The goal of this lab was to replicate and improve my networking skills by applying different technologies including:
- EIGRP (Dynamic Routing) - Efficient and Scalable routing across multiple routers 
- VTP (VLAN Trunking Protocol) - Centralized VLAN management
- SSH (Secure Remote Access) - Secured device management
- Inter-VLAN Routing - Seamless communication between different VLANs
- DHCP (Dynamic Host configuration Protocol)
- Structured Network Design - Organized topology for better scalability

## Logical Topology (MAYBE CHANGE  NAME)
**Network Devices**
- 1 Multilayer Switch (MLS1)
- 5 Routers (R1-R5)
- 13 Access Switches (S1-S13) MAYBE CHANGE NAMING CONVENTION
- 54 PCs

## IP addressing Plan
(add some words in here about why we did it like this)
| Link | Network |
| --- | --- |
| MLS-R1 | 10.0.1.0/30 |
| MLS-R2 | 10.0.2.0/30 |
| MLS-R3 | 10.0.3.0/30 |
| MLS-R4 | 10.0.4.0/30 |
| MLS-R5 | 10.0.5.0/30 |

## VLAN addressing Plan
(add some words in here about why we did it like this
| VLAN | Department | Network |
| --- | --- | --- |
| 10 | Administration | 192.168.10.0/24 |
| 20 | HR | 192.168.20.0/24 |
| 30 | Finance | 192.168.30.0/24 |
| 40 | IT | 192.168.40.0/24 |
| 50 | Sales | 192.168.50.0/24 |
| 60 | Engineering | 192.168.60.0/24 |


## Key Learning Outcomes
1. How to design a scalable enterprise network
2. Practical implementation of routing and switching integration
3. Importance of network security using SSH
4. Real-world troubleshooting and optimization
