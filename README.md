# Network Infrastructure for Campus ABC

## Introduction

A thorough network infrastructure plan is necessary to ease Campus ABC's growth and improve communication throughout its Main Campus (HQ), Research and Development Centre, and Kandy Branch. As the focal point, the Main Campus will need improved security, a dedicated server room, and fast internet to support departmental decision-making and coordination, including the Computing School, Business School, and HR. The R&D Centre will need dedicated support for safe storage and high-speed data transport because it focuses on student projects and technical developments. In the meantime, to ensure efficient integration and communication, the Kandy Branch would need to have smooth access to the main campus, even with its hillside location. The implementation of safe, effective communication channels throughout all sites and IP address optimization will be given top priority in the network design.

This project was completed as part of a first-year, first-semester assignment under the Networking and Cyber Security module.

## Network Configuration Summary

### Main Campus (HQ)

- **Core Switch**
- **VLANs** created and assigned to access switchports
- **Access Switches**  
  VLAN configurations for departments:
  - Computing School
  - Business School
  - Human Resources
  - Academic Administration
  - Marketing
- Removed incorrect VLAN 30 and reconfigured correctly

### Routing & Security

- DOT1Q Trunking for network redundancy
- **HSRP Protocol**: Main router designated as primary (priority 150), backup router as standby (priority 100)
- **DHCP** enabled for automatic IP assignment
- **RIP routing** implemented for network reachability
- Console, remote connection, and privilege mode password protection
- Password encryption enabled using service password-encryption

### Research & Development Centre

- **Core Switch**
- **VLANs** created and assigned to access switchports

### Routing & Security

- DOT1Q Trunking for VLAN management
- **DHCP** enabled for automatic IP assignment
- **RIP routing** configured and verified with HQ and Kandy Branch

### Kandy Branch

- **Core Switch**
- **VLANs** created and assigned to access switchports
- **Access Switches**  
  VLAN configurations for departments:
  - Computing School
  - Business School
  - Academic Administration
  - Human Resources
  - Marketing

### Routing & Security

- DOT1Q Trunking for VLAN management
- **DHCP** enabled for automatic IP assignment
- **RIP routing** configured and verified with HQ and Research & Development

### Packet Tracer Implementation

**Inter-Branch Connectivity Confirmed:**
- HQ <--> Research & Development
- HQ <--> Kandy Branch
- Research & Development <--> Kandy Branch

## Repository Contents

- **NCCS1-CB014079-CB013288-CB013248.pkt** - Packet Tracer project file
- **NCCS1-CB014079-CB013288-CB013248.pdf** - Project report document
- **README.md** - Project overview and instructions

## How to Use

1. Open Packet Tracer and load **NCCS1-CB014079-CB013288-CB013248.pkt**
2. Review configurations using `show run` on routers and switches
3. Test network connectivity with `ping` commands
4. Modify and expand the network as needed

## License

This project is for educational purposes only. You may use this project only if authorized by me or one of my group members.

## Contributors

- **Thieveshkar**
- **Anuji Ranasinghe**
- **Olivia Palix**
