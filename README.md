# Cisco VLAN Configuration with Router-on-a-Stick

## 📌 Project Overview

This project demonstrates the configuration of two VLANs using Cisco Packet Tracer.

The network contains:

- 2 VLANs
- 2 PCs in each VLAN
- 1 Cisco switch
- 1 Cisco router
- Router-on-a-Stick for inter-VLAN routing

## 🏗️ Network Topology

```text
                    Cisco Router
                         |
                     802.1Q Trunk
                         |
                    Cisco Switch
                  /      |       \
             VLAN 10             VLAN 20
             Sales               Marketing
             /   \                /   \
           PC0   PC1            PC2   PC3
