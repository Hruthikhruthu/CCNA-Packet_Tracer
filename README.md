# 🌐 Cisco Packet Tracer Networking Labs

<p align="center">
  <img src="https://img.shields.io/badge/Cisco-Packet%20Tracer-049FD9?style=for-the-badge&logo=cisco&logoColor=white" alt="Cisco Packet Tracer"/>
  <img src="https://img.shields.io/badge/Networking-CCNA%20Labs-0B7285?style=for-the-badge" alt="CCNA Networking Labs"/>
  <img src="https://img.shields.io/badge/Focus-Routing%20%26%20Switching-198754?style=for-the-badge" alt="Routing and Switching"/>
  <img src="https://img.shields.io/badge/Status-Hands--On%20Learning-6F42C1?style=for-the-badge" alt="Hands-on Learning"/>
</p>

<p align="center">
  <b>Learn. Configure. Connect. Troubleshoot.</b>
  <br/>
  A practical collection of Cisco Packet Tracer topologies, network configurations, and CCNA-oriented labs designed to build a strong foundation in computer networking.
</p>

---

## 📌 About This Repository

Welcome to my **Cisco Packet Tracer Networking Labs** repository!

This repository contains network topologies, Packet Tracer project files (`.pkt`), Cisco IOS configurations, and hands-on networking exercises created to understand how computer networks operate in real-world environments.

The primary objective is to move beyond theoretical networking concepts and develop practical skills in network design, IP addressing, routing, switching, VLAN segmentation, network security, and troubleshooting.

The labs cover the configuration of routers, Layer 2 switches, multilayer switches, end devices, and interconnected networks. They include both fundamental networking concepts and more advanced CCNA-oriented scenarios.

Whether you are beginning your networking journey, preparing for the **Cisco CCNA certification**, or practising network engineering fundamentals, this repository can serve as a practical learning resource.

## 🎯 Objectives

- Understand how devices communicate within and between networks.
- Develop a strong foundation in IPv4 addressing, subnetting, and CIDR.
- Configure switches, routers, VLANs, trunks, and default gateways.
- Implement inter-VLAN routing using Layer 3 switches and router-on-a-stick.
- Configure DHCP, static routing, and dynamic routing protocols.
- Understand Access Control Lists (ACLs), Network Address Translation (NAT), and basic traffic filtering.
- Practise connectivity testing, packet flow analysis, and systematic troubleshooting.
- Build confidence in configuring and verifying Cisco IOS devices through the command-line interface (CLI).

---

## 🧠 Introduction to Computer Networking

Computer networking is the process of connecting computers, servers, routers, switches, and other devices so that they can exchange information and share resources.

Communication between devices depends on addressing, protocols, switching, routing, and the underlying network infrastructure.

### Essential Networking Concepts

| Concept | Description |
|---|---|
| LAN | A Local Area Network connects devices within a limited geographical area. |
| WAN | A Wide Area Network connects networks across larger geographical distances. |
| OSI Model | A seven-layer conceptual model used to understand network communication and troubleshoot problems. |
| TCP/IP Model | The protocol model underlying communication across modern IP networks. |
| IPv4 Addressing | Assigns logical addresses to network interfaces for communication. |
| Subnetting | Divides an IP network into smaller networks for efficient addressing and segmentation. |
| MAC Address | A Layer 2 hardware address used for local network communication. |
| ARP | Resolves an IPv4 address to a corresponding MAC address on a local network. |
| DHCP | Automatically provides IP addresses and other network settings to clients. |
| DNS | Translates domain names into IP addresses. |
| Default Gateway | Provides a next hop for traffic destined for other IP networks. |
| Switching | Forwards Ethernet frames within a local network using MAC address information. |
| Routing | Forwards IP packets between different networks using routing tables. |
| ACL | Filters traffic according to configured matching rules. |
| NAT | Translates IP addresses between address spaces. |
| PAT / NAT Overload | Allows multiple internal connections to share one translated IP address using transport-layer ports. |

### The OSI Model

| Layer | Name | Primary Function |
|---|---|---|
| 7 | Application | Network services used by applications |
| 6 | Presentation | Data representation, encoding, and related transformations |
| 5 | Session | Establishes and manages communication sessions |
| 4 | Transport | End-to-end transport, ports, reliability, and segmentation |
| 3 | Network | Logical addressing and routing |
| 2 | Data Link | Ethernet frames, MAC addresses, and switching |
| 1 | Physical | Signals, cables, and physical transmission |

Understanding these layers helps identify whether a connectivity problem is related to physical links, VLANs, IP addressing, routing, or higher-level protocols.

---

## 🗺️ Topics Covered

### 1. IP Addressing and Subnetting
- IPv4 addresses and subnet masks
- CIDR notation and prefix lengths
- Network, broadcast, and usable host addresses
- Subnet calculations and address planning
- Point-to-point transit networks
- Default gateways and address allocation

### 2. Switching and VLANs
- Layer 2 switching fundamentals
- VLAN creation and management
- Access ports and trunk ports
- IEEE 802.1Q VLAN tagging
- VLAN segmentation and broadcast domains
- MAC address learning and forwarding
- Inter-VLAN communication

### 3. Layer 3 Switching and Inter-VLAN Routing
- Cisco multilayer switch configuration
- Switched Virtual Interfaces (SVIs)
- Enabling IP routing on multilayer switches
- Routed physical interfaces using `no switchport`
- Static routes between connected networks
- Default routes and next-hop selection

### 4. Router-on-a-Stick
- Router subinterfaces
- IEEE 802.1Q encapsulation
- VLAN-specific default gateways
- Trunk configuration between switches and routers
- Inter-VLAN routing using a single physical router interface

### 5. DHCP
- DHCP pools and address allocation
- Excluded addresses
- Network and default-router statements
- DNS server configuration
- DHCP client verification and troubleshooting

### 6. Routing
- Directly connected routes
- Static routing
- Default routing
- Routing tables and longest-prefix matching
- Open Shortest Path First (OSPF)
- OSPF process configuration, router IDs, areas, and neighbor relationships
- Static routing combined with dynamic routing

### 7. Access Control Lists
- Standard ACLs
- Extended ACLs
- Source and destination IP matching
- Protocol and port-based filtering
- Inbound and outbound ACL application
- Wildcard masks
- Implicit deny and rule ordering
- Permitting internal traffic while restricting selected destinations
- ACL verification and troubleshooting

### 8. NAT and Internet Connectivity
- Inside and outside NAT interfaces
- Static NAT
- Dynamic NAT concepts
- PAT / NAT overload
- NAT translation tables
- Default routes toward an upstream gateway
- End-to-end connectivity testing
- Understanding return routes and upstream NAT requirements

### 9. Network Troubleshooting
- Interface status and IP configuration checks
- VLAN and trunk verification
- DHCP troubleshooting
- Routing table inspection
- OSPF neighbor verification
- Ping and traceroute testing
- ACL counter inspection
- NAT translation verification
- Identifying incorrect gateways, missing routes, and asymmetric routing

*The topics above describe the repository's learning scope; consult the individual lab files to see which features are implemented in each topology.*

---

## 🏗️ Network Topologies and Lab Scenarios

The repository contains Cisco Packet Tracer topologies designed to demonstrate how different network components work together.

| Lab / Scenario | Main Concepts |
|---|---|
| Basic Network Connectivity | End devices, switches, routers, and IP addressing |
| VLAN Configuration | VLAN creation, access ports, and network segmentation |
| Inter-VLAN Routing | SVIs, multilayer switching, and router-on-a-stick |
| DHCP Configuration | Automatic IPv4 address assignment and default gateways |
| Static Routing | Manually configured routes between different networks |
| OSPF Routing | Dynamic route exchange between participating routers |
| ACL Configuration | Permitting and denying selected network traffic |
| NAT and Internet Access | Address translation, default routing, and upstream connectivity |
| Integrated Network Assessment | VLANs, multilayer switching, DHCP, routing, ACLs, and NAT |

Each topology can be explored individually to understand its network design, interface connections, IP addressing scheme, and configuration logic.

---

## 🛠️ Technologies and Tools

<p align="center">
  <img src="https://img.shields.io/badge/Cisco-IOS-049FD9?style=flat-square&logo=cisco&logoColor=white" alt="Cisco IOS"/>
  <img src="https://img.shields.io/badge/Packet%20Tracer-Network%20Simulation-049FD9?style=flat-square" alt="Packet Tracer"/>
  <img src="https://img.shields.io/badge/IPv4-Addressing-0B7285?style=flat-square" alt="IPv4"/>
  <img src="https://img.shields.io/badge/OSPF-Routing-198754?style=flat-square" alt="OSPF"/>
  <img src="https://img.shields.io/badge/VLAN-Layer%202%20%2F%203-6F42C1?style=flat-square" alt="VLAN"/>
  <img src="https://img.shields.io/badge/ACL-Traffic%20Filtering-C0392B?style=flat-square" alt="ACL"/>
</p>

- **Cisco Packet Tracer:** Network simulation and topology design.
- **Cisco IOS CLI:** Device configuration and operational verification.
- **Cisco 2911 Routers:** Routing, subinterfaces, and WAN/LAN connectivity in supported labs.
- **Cisco 3560 Multilayer Switches:** VLANs, SVIs, and Layer 3 routing in supported labs.
- **Layer 2 Switches:** Ethernet switching, access ports, and trunk links.
- **PC End Devices:** DHCP, IP configuration, and connectivity testing.

*Device models and supported commands may differ between individual labs and Packet Tracer versions.*

---

## 📥 How to Download the Repository

You can download the entire repository as a ZIP file without using Git commands.

### Option 1 — Download as ZIP

1. Open this repository on GitHub.
2. Click the green **Code** button.
3. Select **Download ZIP**.
4. Wait for the ZIP file to download.
5. Extract the ZIP file on your computer.
6. Open Cisco Packet Tracer.
7. Open the required `.pkt` file using **File → Open**.

**Note:** Downloading the ZIP downloads the files currently stored in the repository. It does not automatically install Cisco Packet Tracer or open the topology.

### Option 2 — Clone Using Git

If Git is installed, open a terminal and run:

```bash
git clone <YOUR_REPOSITORY_URL>
```

Replace `<YOUR_REPOSITORY_URL>` with the HTTPS URL of this repository.

Move into the downloaded folder and open the required `.pkt` file in Cisco Packet Tracer.

---

## 🚀 How to Use the Labs

1. **Explore the topology:** Identify routers, switches, PCs, interface connections, and network segments.
2. **Study the addressing:** Determine each subnet, gateway, and routed link.
3. **Inspect the configurations:** Review the Cisco IOS commands used on each device.
4. **Run verification commands:** Check interface status, VLANs, routes, and protocol neighbors.
5. **Test connectivity:** Use `ping` and `tracert` from end devices where supported.
6. **Investigate failures:** Check IP addresses, masks, gateways, trunks, routes, ACLs, and NAT.
7. **Experiment safely:** Modify the lab, observe the results, and document what changes.

For the best learning experience, try configuring a topology yourself before referring to the completed configuration.

---

## 💻 Essential Cisco IOS Verification Commands

The following commands are useful when analysing and troubleshooting the labs.

### Interface and IP Configuration

```text
show ip interface brief
show interfaces
show running-config
show ip route
```

### VLANs and Trunks

```text
show vlan brief
show interfaces trunk
show interfaces switchport
```

### Routing and OSPF

```text
show ip route
show ip protocols
show ip ospf neighbor
show ip ospf interface brief
```

### DHCP

```text
show ip dhcp pool
show ip dhcp binding
show ip dhcp server statistics
```

### ACLs and NAT

```text
show access-lists
show ip interface
show ip nat translations
show ip nat statistics
```

### Connectivity Testing

```text
ping <destination-ip>
traceroute <destination-ip>
```

On Windows PCs, use:

```bat
ipconfig /all
ping <destination-ip>
tracert <destination-ip>
```

These commands help verify network operation rather than relying only on whether a topology appears connected visually.

---

## 🔍 Understanding Packet Flow

When a PC communicates with another device, the forwarding process depends on whether the destination belongs to the same IP subnet.

**Communication within the same subnet**

`PC → Access Switch → Destination PC`

The local switch forwards Ethernet frames based on its MAC address table, provided the VLAN and Layer 2 connectivity are correct.

**Communication between different VLANs**

`PC → Access Switch → Default Gateway (SVI or Router Subinterface) → Destination Network`

The Layer 3 device routes the packet between IP networks.

**Communication with an external network**

`PC → Switch → Layer 3 Gateway → Router → Upstream Gateway → Destination`

The path requires correct routing and return routing. If private IPv4 addresses are used to access the public Internet, NAT or another suitable address-routing arrangement is generally required.

Understanding these packet flows is fundamental to diagnosing connectivity problems.

---

## 📚 Recommended Learning Roadmap

Follow this progression to build networking knowledge systematically.

- [ ] Networking fundamentals and OSI / TCP-IP models
- [ ] IPv4 addressing, subnetting, and CIDR
- [ ] Ethernet switching and MAC address learning
- [ ] VLANs, access ports, and trunk ports
- [ ] SVIs and inter-VLAN routing
- [ ] DHCP and default gateway configuration
- [ ] Static routes and default routes
- [ ] OSPF and dynamic routing
- [ ] Standard and extended ACLs
- [ ] NAT, PAT, and Internet connectivity
- [ ] Integrated topology configuration
- [ ] End-to-end troubleshooting and verification

The goal is not just to memorise commands, but to understand **why each command is required, how packets move through the network, and how to identify and resolve failures.**

---

## 🤝 Contributions and Feedback

Suggestions, corrections, and improvements are welcome.

If you find an issue in a topology or configuration:

1. Identify the affected lab.
2. Describe the observed behaviour and expected result.
3. Include relevant command output or screenshots when possible.
4. Suggest an improvement or submit a pull request.

Please test changes before sharing them so the labs remain useful for learning and practice.

---

## 👨‍💻 Author

**Hruthik P**

Computer Science and Engineering | Networking & CCNA Learning

- GitHub: [@Hruthikhruthu](https://github.com/Hruthikhruthu)
- LinkedIn: [Hruthik P](https://www.linkedin.com/in/hruthik-p-1718vk/)

This repository reflects my hands-on learning journey in computer networking, routing and switching, network security fundamentals, and systematic troubleshooting.

---

<p align="center">
  <b>Understand the network. Configure with purpose. Troubleshoot with confidence.</b>
  <br/>
  <i>Building practical networking skills, one topology at a time.</i>
</p>
