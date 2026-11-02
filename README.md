# Networkwalks Cybersecurity Internship – Week 1
## Kali Linux Lab Setup Using Oracle VirtualBox

**Name:** Sakina Aftab  
**Batch:** B084  
**Program:** Networkwalks Cybersecurity Internship  
**Week:** 01  
**Project:** Cybersecurity Lab Setup

---

## 1. Project Overview

This project focuses on setting up a basic cybersecurity lab environment using Kali Linux inside Oracle VirtualBox. The purpose was to prepare a virtual machine for practicing cybersecurity concepts and learning hands-on security tools in an isolated environment.

## 2. Objectives

- Install and configure Kali Linux using Oracle VirtualBox.
- Configure virtual machine hardware resources.
- Set up a NAT Network for network connectivity.
- Verify internet and network connectivity.
- Create a clean snapshot of the configured virtual machine.

## 3. Tools and Technologies

- **Host Operating System:** Windows 11 Pro
- **Virtualization Software:** Oracle VirtualBox
- **Guest Operating System:** Kali Linux
- **Network Configuration:** NAT Network
- **Terminal Tools:** `ip`, `ping`, `nslookup`, `nmap`

## 4. Lab Environment Configuration

| Component | Configuration |
|---|---|
| Host OS | Windows 11 Pro |
| Virtualization | Oracle VirtualBox |
| Guest OS | Kali Linux |
| RAM | 4096 MB |
| Processors | 2 CPU cores |
| Network Adapter | NAT Network |
| DHCP | Enabled |
| Snapshot | Clean Kali - Network Setup |

## 5. Implementation Steps

### Step 1: Virtual Machine Setup

Opened Oracle VirtualBox and configured the Kali Linux virtual machine.

![VirtualBox Manager](Screenshots/01-virtualbox.png)

### Step 2: Hardware Configuration

Allocated 4096 MB RAM and 2 CPU cores to the virtual machine.

![VM Hardware Settings](Screenshots/02-vm-settings.png)

### Step 3: Network Configuration

Configured a NAT Network named `NatNetwork` and enabled DHCP to allow the virtual machine to obtain network configuration automatically.

![NAT Network Configuration](Screenshots/03-nat-network.png)

### Step 4: Kali Linux Startup

Started the Kali Linux virtual machine and verified that the operating system loaded successfully.

![Kali Linux Desktop](Screenshots/04-kali-desktop.png)

### Step 5: Network Verification

Used terminal commands to check network interfaces, routing, internet connectivity, DNS resolution, and Nmap installation.

**Commands used:**

```bash
ip a
ip route
ping -c 4 8.8.8.8
nslookup networkwalks.com
nmap --version
```

![Network Verification](Screenshots/05-network-verification.png)

### Step 6: Snapshot Creation

Created a snapshot named `Clean Kali - Network Setup` to preserve the working lab configuration and provide a recovery point.

![Kali Snapshot](Screenshots/06-kali-snapshot.png)

## 6. Learning Outcomes

Through this project, I learned how to:

- Set up a virtual cybersecurity lab.
- Configure virtual machine hardware resources.
- Understand and configure NAT Network connectivity.
- Perform basic network troubleshooting and verification.
- Use basic Linux networking commands.
- Create snapshots to preserve a virtual machine's state.

## 7. Conclusion

The Week 1 project successfully established a Kali Linux environment using Oracle VirtualBox. Network connectivity was verified, and a clean snapshot was created. This lab environment will be used for further hands-on cybersecurity learning and practical exercises.

---

**Networkwalks Cybersecurity Internship – Batch B084**

#Networkwalks #Cybersecurity #KaliLinux #VirtualBox
