# 🌐 `Basic-Network-Design-Implementation`

> 💡 Overview: *A foundational enterprise network simulation built in Cisco Packet Tracer to connect and manage inter-departmental communication.*

## 📋 Project Summary Table

| Category | Details / Description |
| :--- | :--- |
| Network Scope | `192.168.40.0` (Network Address used to connect Accounts and Delivery departments) |
| Hardware Architecture | • Cisco 2911 Router<br>• Cisco 2960 Switches<br>• PCs (Accounts & Delivery departments) |
| Tools & Skills | • Cisco Packet Tracer<br>• Subnetting<br>• Gateway Configuration<br>• Interface Cabling<br>• Connectivity & Ping Testing |

## 📊 IP Addressing Table

| Device / Department | Host Name | Interface | IP Address | Subnet Mask | Default Gateway |
| :--- | :--- | :--- | :--- | :--- | :--- |
| Router | Router0 | GigabitEthernet0/0 | `192.168.40.1` | `255.255.255.128` | `-` |
| Accounts Dept. | PC 0 | FastEthernet0 | `192.168.40.2` | `255.255.255.128` | `192.168.40.1` |
| Accounts Dept. | PC 1 | FastEthernet0 | `192.168.40.3` | `255.255.255.128` | `192.168.40.1` |
| Delivery Dept. | PC 2 | FastEthernet0 | `192.168.40.65` | `255.255.255.128` | `192.168.40.1` |
| Delivery Dept. | PC 3 | FastEthernet0 | `192.168.40.66` | `255.255.255.128` | `192.168.40.1` |

## 🚀 How to Test
1. Download and open the `.pkt` file in Cisco Packet Tracer.
2. Run a ping test between the Accounts and Delivery department PCs to verify full connectivity.
