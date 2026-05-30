# Home Lab — VirtualBox

Virtual environment for practicing networking, 
Active Directory and security concepts.

## Network Diagram

```
[DC01 192.168.10.1] ──── [Win10 192.168.10.2]
         │
         │
[Ubuntu 192.168.10.3]
```

## Environment
| Machine         | OS                    | IP           | Role              |
|----------------|-----------------------|--------------|-------------------|
| DC01           | Windows Server 2022   | 192.168.10.1 | Domain Controller |
| Windows-Client | Windows 10 Pro        | 192.168.10.2 | Domain Client     |
| ubuntu-server  | Ubuntu Server 24.04   | 192.168.10.3 | Linux Server      |

## Projects
- [Active Directory](./active-directory/README.md) 
  — domain, users, OU, GPO
- [Network Configuration](./network-config/README.md) 
  — internal network, static IPs
- [SSH Key Authentication](./ssh-config/README.md) 
  — passwordless login, RSA keys
- [DDoS Simulation](./ddos-simulation/README.md)
  — SYN Flood attack, Wireshark detection, hping3
- [Zabbix Monitoring](./zabbix-monitoring/README.md)
  — Zabbix 7.0, 3 hosts monitored, CPU alerts, DDoS detection

## Skills Practiced
- Active Directory administration
- Network configuration and subnetting
- SSH key-based authentication
- Windows Server 2022 administration
- Linux CLI (Ubuntu Server)
- VirtualBox virtualization
- Zabbix 7.0 monitoring and alerting
- DDoS attack simulation and detection
- Wireshark network traffic analysis
- Incident detection and alert configuration
  
## What I Learned
- How Active Directory manages users and permissions
- Network segmentation using VirtualBox
- SSH key authentication vs password authentication
- Linux CLI administration
- GPO configuration and verification
- How NOC monitors infrastructure in real time
- How to correlate network attacks with system metrics
- How automated alerting works in enterprise environments
- How DDoS traffic appears in monitoring tools
  

