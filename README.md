

- <a href="https://github.com/rafa0c">Home Portfolio</a>

# 🛡️ What is CIA Triad?

<p align="center">
Ref 1: CIA Triad<br/>
<img src="https://i.imgur.com/VQO9Yfh.png" height="45%" width="45%" alt="CIA Triad"/>
<br />
<br />
</p>



The **CIA Triad** is a fundamental model in cybersecurity, which stands for **Confidentiality**, **Integrity**, and **Availability**. These three principles form the foundation of any secure system. Each principle addresses specific aspects of data protection and security, helping to ensure that information systems are robust and secure from unauthorized access, manipulation, or downtime.

## 🔐 Confidentiality
Confidentiality ensures that sensitive information is accessible only to authorized individuals. Its main goal is to prevent unauthorized access or disclosure of data. Protecting confidentiality involves mechanisms such as encryption, access control, and authentication.

- **Key Points:**
  - Data encryption
  - Strong passwords and authentication
  - Role-based access control (RBAC)
 
<p align="center">
Ref 2: Encription<br/>
<img src="https://i.imgur.com/DwiYl1g.png" height="45%" width="45%" alt="CIA Triad"/>
<br />
<br />
</p>
 
Examples:
- Encryption: Encrypting sensitive data (like emails or financial information) ensures that even if intercepted, the data remains unreadable without the decryption key.
- Access Controls: User authentication mechanisms like passwords, biometrics, or multi-factor authentication (MFA) protect data from being accessed by unauthorized users.


Threats to Confidentiality:
- Phishing attacks: Trick users into revealing passwords or other credentials.
- Data breaches: Exploiting system vulnerabilities to gain unauthorized access to data.



## 🛡️ Integrity
Integrity refers to ensuring the accuracy and trustworthiness of data. This principle protects data from being tampered with either intentionally or accidentally during storage transmission, or processing unless authorized changes are made.

- **Key Points:**
  - Hashing
  - Digital signatures
  - Version control systems

 <p align="center">
Ref 2: Encription<br/>
<img src="https://i.imgur.com/gbIebtj.png" height="45%" width="45%" alt="CIA Triad"/>
<br />
<br />
</p>

 

Examples:
- Checksums and Hashing: Used to ensure that files haven’t been tampered with during transit. If the hash values match on both ends, the file is confirmed to be intact.
- Version Control: Ensures that any changes to files or data can be tracked and rolled back if necessary.


Threats to Integrity:
- Man-in-the-Middle (MITM) attacks: Attackers intercept and alter data during transmission.
- Data Corruption: Either due to hardware failure, human error, or malicious actions, which may lead to incorrect data being stored.


## 🕒 Availability
Availability ensures that information and resources are accessible when needed. This involves maintaining system uptime and recovering quickly from failures. The Systems should be designed to withstand disruptions and continue functioning effectively.

Examples:
- Redundancy: Setting up redundant servers and backups to ensure continuous operation, even in the case of a hardware failure.
DDoS Protection: Implementing countermeasures like firewalls and load balancers to defend against distributed denial of service (DDoS) attacks that try to overwhelm and shut down a service.


Threats to Availability:
- DDoS Attacks: Flooding servers with traffic, making them unavailable.
- Natural Disasters: Disruptions from events like earthquakes or floods that affect data centers or communication networks.


- **Key Points:**
  - Redundant systems
  - Regular backups
  - DDoS protection

<p align="center">
Ref 2: Encription<br/>
<img src="https://i.imgur.com/RSfDnTF.png" height="45%" width="45%" alt="CIA Triad"/>
<br />
<br />
</p>

Examples:

- Load Balancers: Distributing network or application traffic across multiple servers to prevent any one system from being overwhelmed and to ensure continued access.
- Data Backups: Regularly backing up data to recover it quickly in case of hardware failure, cyber-attacks, or natural disasters.
- Disaster Recovery Plans: Creating and testing disaster recovery plans to restore services quickly after an unexpected interruption such as natural disasters, cyber-attacks and Windows Maintinence.
- Cloud Services: Using cloud infrastructure to scale resources dynamically and ensure systems remain operational even during high demand.
- High Availability Clusters: Grouping multiple servers or systems so if one fails, another takes over without disrupting the service.


**Conclusion**
By adhering to the CIA Triad, organizations can develop strategies and defenses that ensure their systems are secure. Focusing on Confidentiality, Integrity, and Availability enables balanced protection across different dimensions of security.

---

### Summary
The **CIA Triad** is crucial for maintaining secure information systems. Focusing on **Confidentiality**, **Integrity**, and **Availability** helps organizations protect against data breaches, unauthorized access. The CIA Triad protections across different dimensions of security.

<!--
Ref 2: Virtual box  <br/>
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Ref 3: Add users in AD: <br/>
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Ref 4: User Name File  <br/>
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Ref 5: PowerShell script for new users   <br/>
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Ref 6: create the new users   <br/>
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Ref 7: show the new user in the GUI  <br/>
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
-->



