# Task 4: Research Report on Common Network Security Threats

## Introduction
Network security threats target computer networks to disrupt services, steal sensitive information, or gain unauthorized access. Understanding these threats is essential for security analysts to protect systems and data.

This report discusses common network security threats, their working mechanisms, real-world impacts, and mitigation techniques.

---

## 1. Denial of Service (DoS) and Distributed Denial of Service (DDoS) Attacks

### Description
A Denial of Service (DoS) attack attempts to make a system or network unavailable by overwhelming it with excessive traffic. A Distributed Denial of Service (DDoS) attack uses multiple compromised systems to perform the same attack.

### How It Works
Attackers flood the target server with requests, consuming bandwidth, CPU, or memory resources, causing legitimate user requests to be denied.

### Impact
- Website or service downtime
- Financial losses
- Damage to brand reputation

### Real-World Example
In 2016, the Dyn DNS DDoS attack disrupted major websites such as Twitter, Netflix, and GitHub by overwhelming DNS infrastructure.

### Mitigation
- Traffic filtering and rate limiting
- Use of DDoS protection services
- Network redundancy and load balancing

---

## 2. Man-in-the-Middle (MITM) Attacks

### Description
A Man-in-the-Middle attack occurs when an attacker secretly intercepts and possibly alters communication between two parties without their knowledge.

### How It Works
Attackers position themselves between the client and server using techniques like ARP spoofing or rogue Wi-Fi access points.

### Impact
- Credential theft
- Data manipulation
- Privacy violations

### Real-World Example
Public Wi-Fi attacks in cafes and airports are common MITM scenarios where attackers capture login credentials.

### Mitigation
- Use HTTPS and SSL/TLS encryption
- Avoid unsecured public Wi-Fi
- Implement VPNs and secure authentication

---

## 3. Spoofing Attacks

### Description
Spoofing involves impersonating a trusted device, user, or service to gain unauthorized access or mislead systems.

### Types of Spoofing
- IP Spoofing
- ARP Spoofing
- DNS Spoofing
- Email Spoofing

### How It Works
Attackers falsify identity information in network packets to appear as a legitimate source.

### Impact
- Data interception
- Session hijacking
- Network compromise

### Real-World Example
Email spoofing is commonly used in phishing attacks where attackers impersonate banks or companies.

### Mitigation
- Packet filtering
- Authentication mechanisms
- DNS security extensions (DNSSEC)
- Email verification techniques (SPF, DKIM)

---

## Conclusion
Network security threats pose serious risks to modern systems. Understanding how attacks work and implementing proper security controls is essential to maintaining network integrity, availability, and confidentiality.

Security analysts play a key role in identifying threats, responding to incidents, and implementing preventive measures.
