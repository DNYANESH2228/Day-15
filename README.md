# Day-15
 Understanding Attack Surface
 
## Objective
The objective of this task is to understand the concept of an **attack surface** and identify different entry points through which an attacker may attempt to access or exploit a computer system.

An **attack surface** includes all the possible ways an attacker can try to enter a system, network, or application to extract data or cause damage. These entry points may exist in hardware, software, network connections, or user behavior.

Understanding attack surfaces helps cybersecurity professionals identify vulnerabilities and reduce the risk of cyber attacks.

---

## Attack Surfaces Identified on My System

After analyzing my computer system, I identified the following three possible attack surfaces.

---

## 1. Web Browser and Browser Extensions

### Description
A web browser is one of the most commonly used applications on a computer. It allows users to access websites, download files, and interact with online services. Browsers also support extensions that add additional features.

### Why it could be risky
Web browsers interact with many websites on the internet. Some websites may contain malicious scripts, phishing pages, or harmful downloads. Browser extensions can also request permissions to access browsing data, which may lead to privacy risks.

### How an attacker might misuse it
Attackers can create malicious websites designed to steal sensitive information such as usernames, passwords, or banking details. They may also distribute harmful browser extensions that collect personal data or install malware.

### Risk Reduction
- Install extensions only from trusted sources
- Keep the browser updated
- Avoid suspicious websites
- Enable browser security features

---

## 2. Open Network Ports and Running Services

### Description
Applications and services running on a computer communicate through network ports. Some services open ports to allow communication over a network.

### Why it could be risky
If unnecessary ports remain open or vulnerable services are running, attackers may attempt to exploit them to gain unauthorized access to the system.

### How an attacker might misuse it
Attackers may perform **port scanning** to identify open ports on a system. After discovering open ports, they can attempt to exploit vulnerabilities in the services running on those ports.

### Risk Reduction
- Disable unnecessary services
- Close unused ports
- Use a firewall
- Keep system software updated

---

## 3. USB Devices and External Storage

### Description
USB drives and other external storage devices are commonly used to transfer files between systems.

### Why it could be risky
External storage devices can contain malicious files or malware that may infect a system when connected.

### How an attacker might misuse it
An attacker might distribute infected USB drives that automatically install malware when plugged into a computer.

### Risk Reduction
- Avoid using unknown USB devices
- Scan external storage with antivirus software
- Disable automatic file execution
- Use trusted storage devices

---

## Realization About My System Security

During this task, I realized that many everyday tools such as browsers, USB devices, and network services can become potential entry points for attackers. Proper security practices are necessary to reduce the risk of exploitation.

---

## Step to Reduce Attack Surface

One important step to reduce the attack surface is **removing unnecessary software and services from the system**. Fewer running programs mean fewer vulnerabilities that attackers can exploit.

Regular updates, strong passwords, and firewall protection also help improve system security.


Understanding attack surfaces is an important concept in cybersecurity. By identifying and reducing potential entry points, systems can be made more secure and resistant to cyber attacks.
