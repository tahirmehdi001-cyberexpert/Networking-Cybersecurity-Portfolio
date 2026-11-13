# 🌐 What is Computer Networking?

<p align="center">
  <img src="https://img.shields.io/badge/Topic-Networking%20Fundamentals-0078D4?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Level-Beginner-success?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Domain-Computer%20Science-blueviolet?style=for-the-badge" />
</p>

## 📌 1. Introduction

**Computer Networking** is the process of connecting two or more computing devices so they can communicate, exchange data, and share resources through wired or wireless communication channels.

These devices may include:

- Desktop computers
- Laptops
- Servers
- Smartphones
- Printers
- Routers
- Network switches
- Internet of Things (IoT) devices

Computer networks allow devices to communicate with each other regardless of their physical location, depending on the network infrastructure and communication technologies being used.

### 💡 Simple Example

When you send a message through WhatsApp, watch a YouTube video, access a website, or share a file with another computer, networking technologies make that communication possible.

---

## 🎯 2. Purpose of Computer Networking

The primary purpose of computer networking is to enable communication and resource sharing between connected devices.

Key purposes include:

| Purpose | Explanation |
|---|---|
| Communication | Enables messaging, email, voice and video calls. |
| Resource Sharing | Allows users to share printers, storage and other resources. |
| Data Sharing | Enables the exchange of files and information. |
| Remote Access | Allows users to access systems and resources remotely. |
| Centralized Management | Helps organizations manage users, devices and resources centrally. |
| Collaboration | Supports teamwork through shared applications and platforms. |
| Connectivity | Connects devices and systems across different locations. |

---

## ⚙️ 3. How Does Computer Networking Work?

Computer networking works through communication between connected devices using network hardware, communication channels, addressing systems, and protocols.

A simplified communication process involves the following steps:

1. **Data Generation:** A user creates a request or sends information.
2. **Data Preparation:** The sending device prepares the information for transmission.
3. **Addressing:** Network addressing helps identify the intended destination.
4. **Data Transmission:** Information travels through wired or wireless communication media.
5. **Network Processing:** Network devices forward data towards its destination.
6. **Data Reception:** The destination device receives and processes the information.
7. **Response:** The destination may send a response back to the original device.

### Network Communication Diagram

<p align="center">
  <img src="../Images/network-communication.png" alt="Basic Network Communication Diagram" width="750" />
</p>

*Illustration: A simplified representation of communication between network-connected devices.*

---

## 🧩 4. Basic Components of a Computer Network

A computer network consists of different hardware and software components that work together to establish communication.

| Component | Function |
|---|---|
| Computer / Host | Sends and receives information over a network. |
| Server | Provides services, applications or resources to other devices. |
| Client | Requests services or resources from a server. |
| Network Interface Card (NIC) | Provides a network connection for a device. |
| Router | Forwards packets between different networks. |
| Switch | Connects devices within a LAN and forwards Ethernet frames. |
| Modem | Converts signals for communication over certain ISP access technologies. |
| Access Point | Connects wireless devices to a network. |
| Firewall | Filters network traffic according to security rules. |
| Transmission Media | Carries data through wired or wireless channels. |

---

## 🔄 5. Types of Network Connections

Computer networks use different communication media to connect devices.

### A. Wired Networking

Wired networking uses physical cables to establish network connections.

Common technologies include:

- Ethernet cables
- Fiber-optic cables
- Coaxial cables

**Advantages:**
- Reliable connectivity
- Consistent performance
- Lower interference in many environments
- Suitable for enterprise infrastructure

### B. Wireless Networking

Wireless networking uses radio waves or other wireless technologies to communicate without requiring a physical data cable between devices.

Common technologies include:

- Wi-Fi
- Bluetooth
- Cellular networks
- Satellite communication

**Advantages:**
- Mobility and flexibility
- Easy device connectivity
- Reduced cable requirements
- Convenient access to network resources

---

## 🌍 6. Real-World Applications of Computer Networking

Computer networking plays an essential role in modern technology and everyday life.

| Industry | Networking Applications |
|---|---|
| Education | Online classes, digital libraries and learning platforms. |
| Banking | Online transactions, ATMs and financial systems. |
| Healthcare | Electronic medical systems and connected medical devices. |
| Business | Communication, file sharing and enterprise applications. |
| E-Commerce | Online shopping, payment processing and inventory systems. |
| Government | Digital services and communication infrastructure. |
| Cloud Computing | Access to cloud storage, applications and remote servers. |
| Telecommunications | Mobile communication and internet connectivity. |

---

## 🔐 7. Computer Networking and Cybersecurity

Networking is one of the most important foundations of cybersecurity.

Understanding how devices communicate helps security professionals identify suspicious activities, investigate network traffic and protect digital infrastructure.

### Why Networking Matters in Cybersecurity

- **Network Monitoring:** Observing communication between connected systems.
- **Traffic Analysis:** Examining packets to understand network activity.
- **Threat Detection:** Identifying suspicious connections and communication patterns.
- **Firewall Management:** Understanding how network traffic is filtered.
- **Incident Investigation:** Analyzing network events during security incidents.
- **Access Control:** Understanding how devices and users access network resources.

### Common Networking Security Threats

| Threat | Description |
|---|---|
| DoS Attack | Attempts to make a service unavailable. |
| DDoS Attack | Uses multiple sources to overwhelm a target service. |
| Man-in-the-Middle | Intercepts or potentially alters communication between parties. |
| IP Spoofing | Uses a forged source IP address. |
| Packet Sniffing | Captures network traffic for analysis or potentially unauthorized observation. |
| DNS Spoofing | Attempts to provide false DNS information. |

Understanding these threats provides a foundation for learning Network Security and SOC operations.

---

## 🛠️ 8. Basic Networking Commands

Practical networking knowledge requires understanding how to inspect and troubleshoot network connections.

### Windows Commands

**1. View Network Configuration**

```powershell
ipconfig
```

Displays basic IP configuration information.

**2. View Detailed Network Configuration**

```powershell
ipconfig /all
```

Displays detailed network adapter information, including IP and MAC addresses.

**3. Test Network Connectivity**

```powershell
ping 8.8.8.8
```

Tests connectivity to a destination using ICMP Echo Requests.

**4. Check Network Route**

```powershell
tracert google.com
```

Displays the network path towards a destination.

**5. Check DNS Resolution**

```powershell
nslookup google.com
```

Queries DNS information for a domain.

### Linux Commands

```bash
ip addr
ip route
ping -c 4 8.8.8.8
traceroute google.com
nslookup google.com
```

These commands help develop practical networking and troubleshooting skills.

---

## 📖 9. Important Networking Terminologies

| Term | Definition |
|---|---|
| Network | A group of interconnected devices. |
| Node | A device or connection point in a network. |
| Host | A network-connected system that can communicate over a network. |
| Client | A system or application requesting a service. |
| Server | A system providing services or resources. |
| IP Address | A logical address used to identify a network interface. |
| MAC Address | A link-layer address associated with a network interface. |
| Protocol | A set of rules governing communication. |
| Packet | A formatted unit of data at the network layer. |
| Bandwidth | Maximum theoretical data transfer capacity. |
| Latency | Time taken for data to travel between endpoints. |
| LAN | Local Area Network. |
| WAN | Wide Area Network. |

---

## 📝 10. Key Takeaways

- Computer networking connects devices to enable communication and resource sharing.
- Networks can use wired or wireless communication technologies.
- Routers, switches, servers and other components perform different networking functions.
- Communication protocols establish rules for exchanging information.
- Networking supports businesses, education, banking, healthcare and cloud services.
- Networking knowledge is essential for understanding cybersecurity and SOC operations.

---

## 🧠 11. Knowledge Check

Test your understanding of computer networking:

1. What is computer networking?
2. What is the primary purpose of a computer network?
3. What is the difference between a router and a switch?
4. What is the role of a server in a network?
5. What is the difference between wired and wireless networking?
6. What is an IP address?
7. Why is networking important in cybersecurity?
8. Which command can be used to test network connectivity?

---

## 📚 12. References & Further Learning

- [Cisco Networking Academy](https://www.netacad.com/)
- [Cisco Official Website](https://www.cisco.com/)
- [Cloudflare Learning Center](https://www.cloudflare.com/learning/)
- [Wireshark Documentation](https://www.wireshark.org/docs/)

---

## 🔗 Related Topics

- [Purpose of Networking](./02-Purpose-of-Networking.md)
- [Importance of Networking](./03-Importance-of-Networking.md)
- [Advantages and Disadvantages](./04-Advantages-and-Disadvantages.md)
- [How Computer Networks Work](./05-How-Computer-Networks-Work.md)
- [Basic Networking Terminologies](./07-Basic-Networking-Terminologies.md)

---

<p align="center">
  <b>Networking & Cybersecurity Portfolio</b>
  <br/>
  <i>Learn • Practice • Document • Improve</i>
  <br/><br/>
  ⭐ Building a strong foundation in Computer Networking and Cybersecurity.
</p>