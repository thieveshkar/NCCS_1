# Network Infrastructure for Campus ABC

## Introduction

This project was developed as part of a **first-year, first-semester assignment** under the **COMP40002 Networking Concepts and Cybersecurity** module at the **Asia Pacific Institute of Information Technology (APIIT), Sri Lanka**, partnered with **Staffordshire University, UK**. The primary objective of this assignment was to design and implement a comprehensive network infrastructure for **Campus ABC**, which consists of three locations: the **Main Campus (HQ)**, the **Research and Development Centre**, and the **Kandy Branch**. This network solution incorporates **VLANs**, **routing**, **security**, and **WAN** technologies to facilitate efficient communication, collaboration, and secure data transfer across the campus sites.

## Learning Outcomes

Upon completion of this assignment, the following learning outcomes were achieved:
- Demonstrated knowledge of the **OSI** and **TCP/IP models**, **IP addressing**, and **network design (subnetting)** principles.
- Applied **VLANs**, **RIP routing**, **HSRP**, and **DHCP** technologies in the design and implementation of a multi-location network.
- Configured **network devices (routers, switches)** and implemented **security** protocols to ensure safe and efficient communication.
- Implemented a **three-layer network topology** with appropriate redundancy and high availability.
- Demonstrated the ability to design and configure a network based on real-world business requirements.

## Project Structure

The network design and configuration are based on the following locations and their requirements:

### Locations and Departments:

1. **Main Campus (HQ)**  
   - Computing School  
   - Business School  
   - Marketing  
   - Human Resources  
   - Academic Administration  

2. **Research and Development Centre**  
   - Human Resources  
   - Marketing  
   - Research and Development  
   - Server Room  

3. **Kandy Branch**  
   - Computing School  
   - Business School  
   - Academic Administration  
   - Human Resources  
   - Marketing  

### Network Configuration Overview:

- **Core Switches**, **Access Switches**, **Routers**  
- **VLANs** for department segmentation  
- **RIP Routing Protocol** for network reachability  
- **HSRP** for redundancy  
- **DOT1Q Trunking** for VLAN communication  
- **DHCP** for automatic IP assignment  

### Key Features:

- **IP Addressing**: Subnetting based on department needs
- **WAN Technologies**: Implementation of secure and fast inter-site communication
- **Security Measures**: Password protection, encryption, and secure access controls

## Network Configuration Summary

### Main Campus (HQ)

- **Core Switch**  
- **VLANs** created and assigned to access switchports  
- **Routing & Security**:  
  - **DOT1Q trunking** for VLAN management  
  - **HSRP** for router redundancy  
  - **DHCP** for automatic IP assignment  
  - Password encryption enabled  
  - Console, remote connection, and privilege mode password protection  

### Research and Development Centre

- **Core Switch**  
- **VLANs** created and assigned to access switchports  
- **Routing & Security**:  
  - **DOT1Q trunking** for VLAN management  
  - **RIP** routing protocol implemented  
  - **DHCP** for automatic IP assignment  

### Kandy Branch

- **Core Switch**  
- **VLANs** created and assigned to access switchports  
- **Routing & Security**:  
  - **DOT1Q trunking** for VLAN management  
  - **RIP** routing protocol configured and verified  
  - **DHCP** for automatic IP assignment  

### Packet Tracer Implementation

**Inter-Branch Connectivity**:  
- HQ <--> Research & Development  
- HQ <--> Kandy Branch  
- Research & Development <--> Kandy Branch  

## Repository Contents

- **NCCS1-CB014079-CB013288-CB013248.pkt** - Packet Tracer project file  
- **NCCS1-CB014079-CB013288-CB013248.pdf** - Project report document  
- **README.md** - Project overview and instructions  

## How to Use

1. Open **Packet Tracer** and load **NCCS1-CB014079-CB013288-CB013248.pkt**  
2. Review configurations using `show run` on routers and switches  
3. Test network connectivity using `ping` commands  
4. Modify and expand the network as needed to meet specific requirements  

## License

This project is for educational purposes only. You may use this project only if authorized by one of the contributors.

## Contributors

- **Thieveshkar**  
- **Anuji Ranasinghe**  
- **Olivia Palix**  

