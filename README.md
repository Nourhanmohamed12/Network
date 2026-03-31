<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=28&pause=1000&color=60A5FA&center=true&vCenter=true&lines=Network+Simulation;%20Routing+%26+Security;99.9%25%20Uptime+%F0%9F%94%8D" />
  <br><br>
  <img src="https://img.shields.io/badge/🌐-Cisco%20Packet%20Tracer-1E40AF?style=for-the-badge&logo=cisco&logoColor=white" />
  <img src="https://img.shields.io/badge/⭐-99.9%25%20Uptime-3B82F6?style=for-the-badge&logo=network-wired&logoColor=white" />
  <img src="https://img.shields.io/badge/🔒-Enterprise%20Security-60A5FA?style=for-the-badge&logo=shield&logoColor=white" />
</div>

---

## <div align="center"><b style="color:#1E40AF">🌐 Project Overview</b></div>

**Enterprise Network Simulation** demonstrating **advanced routing protocols (OSPF, EIGRP, RIP)**, **NAT, DNS, Port Security**, and **Access Lists** in a production-ready network topology. Achieves **99.9% uptime** with comprehensive security and redundancy.

<div align="center">
  <img src="https://img.shields.io/badge/📡-Dynamic%20Routing-3B82F6?style=for-the-badge&logo=router&logoColor=white" />
  <img src="https://img.shields.io/badge/🔐-Port%20Security-60A5FA?style=for-the-badge&logo=lock&logoColor=white" />
  <img src="https://img.shields.io/badge/🚫-Access%20Lists-1E40AF?style=for-the-badge&logo=firewall&logoColor=white" />
</div>

---

## ✨ **Network Features**
rotocol/Feature

Implementation

📡 OSPF Routing

Multi-area OSPF with DR/BDR election

⚡ EIGRP Routing

EIGRP load balancing & convergence

📨 RIP Routing

RIPv2 with authentication

🌍 DNS Server

Local DNS resolution & forwarding

🔒 Port Security

MAC address limiting & violation shutdown

🚫 Access Lists

ACL filtering (Standard/Extended)

🔄 NAT/PAT

Static & Dynamic NAT configurations

🏗️ Network Topology
graph TD
    A[Internet] --> B[NAT Router]
    B --> C[OSPF Core Router]
    C --> D[Branch 1 - EIGRP]
    C --> E[Branch 2 - RIP]
    C --> F[DNS Server]
    C --> G[Secure LAN]
    
    style A fill:#EF4444
    style B fill:#1E40AF
    style C fill:#3B82F6
    style D fill:#10B981
    style E fill:#F59E0B
    style F fill:#8B5CF6
    style G fill:#60A5FA


Project Demo

https://drive.google.com/file/d/1QaPifb0DXJGebYlAXo4EfEGGedmNUho7/view?usp=sharing


    Configuration Highlights
OSPF Multi-Area Configuration
Router(config)# router ospf 1
Router(config-router)# network 192.168.1.0 0.0.0.255 area 0
Router(config-router)# network 10.0.0.0 0.0.255.255 area 1

Port Security Example

Switch(config-if)# switchport port-security
Switch(config-if)# switchport port-security maximum 2
Switch(config-if)# switchport port-security violation shutdown

Extended ACL Example
Router(config)# access-list 101 deny tcp 192.168.2.0 0.0.0.255 any eq 80
Router(config)# access-list 101 permit ip any any
Router(config)# interface fa0/1
Router(config-if)# ip access-group 101 in

erformance Metrics
Metric

Result

Network Uptime

99.9%

Convergence Time

OSPF: < 5s, EIGRP: < 2s

Packet Loss

0%

Security Events

Port violations auto-blocked

DNS Resolution

< 10ms** local

🖥️ Simulation Screenshots
<div align="center"> <table> <tr> <td><b>🌐 Network Topology</b></td> <td><b>📡 OSPF Convergence</b></td> <td><b>🔒 Port Security</b></td> </tr> <tr> <td>![Topology](screenshots/topology.png)</td> <td>![OSPF](screenshots/ospf.png)</td> <td>![Security](screenshots/security.png)</td> </tr> </table> </div>

Testing Commands
# Verify OSPF Neighbors
show ip ospf neighbor

# Check EIGRP Topology
show ip eigrp topology

# Port Security Status
show port-security interface fa0/1

# ACL Hits
show access-lists

Security Implementation
✅ Port Security - MAC limiting & auto-shutdown
✅ Access Lists - Traffic filtering & protection
✅ NAT/PAT - Private IP masquerading
✅ Routing Authentication - Protocol security
✅ DNS Security - Local resolution only


👩‍💻 Author
<div align="center"> <a href="https://linkedin.com/in/nour-mohammed-614753278"> <img src="https://img.shields.io/badge/Nourhan%20Mohammed-1E40AF?style=for-the-badge&logo=linkedin&logoColor=white" /> </a> <img src="https://img.shields.io/badge/Network%20Engineer-3B82F6?style=for-the-badge&logo=network-wired&logoColor=white" /> <img src="https://img.shields.io/badge/CCNA%20Ready-60A5FA?style=for-the-badge&logo=cisco&logoColor=white" /> </div>
