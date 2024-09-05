# Using the NIST Cybersecurity Framework to Respond to a Security Incident
> Hello!! Welcome to the case study *"Response to an ICMP Flood DDoS Attack"*. Below, you will find a brief explanation of how to apply the NIST CSF, a summary of the case study, and finally, the incident report.

## Summary
- [Applying the NIST CSF](#applying-the-nist-csf)
- [Case Study: Response to an ICMP Flood DDoS Attack](#case-study-response-to-an-icmp-flood-ddos-attack)
- [Incident Report Analysis (pdf)](https://github.com/mariarithanascimento/NIST-CSF-Portfolio/blob/af187be4e3bfe27f2da68bbfa370d6c0252daa14/An%C3%A1lise%20de%20relat%C3%B3rio%20de%20incidente.pdf)

## `Applying the NIST CSF`

There are five main functions in the NIST CSF: identify, protect, detect, respond, and recover.

![enter image description here](https://github.com/mariarithanascimento/NIST-CSF-Portfolio/blob/0399e53a2d31a3252d2fb68982d5c5ca39688724/nist-framework.png)

These core functions help organizations manage cybersecurity risks, implement risk management strategies, and learn from past mistakes. Plans based on this framework should be continuously updated to stay ahead of the latest security threats. The core functions help ensure that organizations are protected against potential threats, risks, and vulnerabilities. Each function can be used to improve an organization's security:

- **Identify:** Manage security risks through regular audits of internal networks, systems, devices, and access privileges to identify potential security gaps.
- **Protect:** Develop a strategy to protect internal assets by implementing policies, procedures, training, and tools to help mitigate cybersecurity threats.
- **Detect:** Scan for potential security incidents and improve monitoring capabilities to increase detection speed and efficiency.
- **Respond:** Ensure that appropriate procedures are used to contain, neutralize, and analyze security incidents, and implement improvements in the security process.
- **Recover:** Restore affected systems to normal operation and recover data and assets from systems impacted by an incident.

Some aspects to address for each of the five core functions include:

| Function  | Description |
|--|--|
| Identify  | Create an inventory of systems, processes, assets, data, people, and capabilities to protect. Identify affected devices and software, trace the attack within the internal network, and assess impacted business processes. Determine who needs access to the compromised systems.|
| Protect  | Develop and implement safeguards focusing on access control, defining who needs access to the affected items and blocking untrusted sources. Conduct awareness and training campaigns to inform about the attack and how to avoid it in the future. Strengthen the security of impacted data and review or create new procedures to protect assets and ensure service continuity.|
| Detect  | Design a system with tools like a SIEM to detect anomalies and alert the security team in real-time. Implement continuous monitoring solutions such as firewalls and network monitoring systems to identify suspicious events. Use intrusion detection systems (IDS) and behavior analysis to identify attacks and respond quickly to security incidents. |
|  Respond | Create response plans by defining specific actions to handle future attacks, including isolation of resources and damage containment. Establish clear communication between the IT team, end users, and affected parties, ensuring that procedures are known. Perform post-attack analyses to identify vulnerabilities and failures. Implement immediate mitigation measures, such as disconnecting or isolating compromised resources. Promote continuous improvements in response processes based on lessons learned to strengthen defenses against future incidents.|
| Recover  | Develop a recovery plan outlining clear steps to restore affected systems and data, including identifying critical resources and recovery processes. Review and improve existing recovery systems and processes to increase efficiency and reduce downtime. Establish a communication protocol to inform the IT team, end users, and affected parties about restoration procedures, ensuring transparency and coordination during the process.|

The NIST CSF and its five core functions provide a framework that encompasses proactive planning to reactive measures against cybersecurity threats. These functions are essential to ensure that an organization has effective security strategies in place. The organization must have the ability to quickly recover from any damage caused by an incident to minimize its risk level.

## `Case Study: Response to an ICMP Flood DDoS Attack`

#### **Incident Summary**
Recently, the company faced a severe cybersecurity incident when all network services abruptly stopped responding. The investigation revealed that the disruption was caused by a distributed denial-of-service (DDoS) attack characterized by an ICMP flood. The cybersecurity team acted quickly to mitigate the attack by blocking it and shutting down non-critical network services to restore the operation of essential services.

#### 1. Identify
- **Incident Description:** One or more malicious agents directed an ICMP flood attack against the company's network infrastructure. The attack affected the entire internal network, requiring an immediate response to protect and restore critical resources.
- **Action:** The cybersecurity team conducted an analysis to identify the source and nature of the attack, determining that the internal network was saturated with malicious ICMP packets.

#### 2. Protect
- **Measures Implemented:** The cybersecurity team adopted measures to protect the network from the ongoing attack and prevent future incidents:
  - **Firewall Rule:** A new rule was created to limit the rate of incoming ICMP packets, helping to mitigate the impact of the attack.
  - **IDS/IPS System:** An Intrusion Detection and Prevention System (IDS/IPS) was implemented to filter ICMP packets with suspicious characteristics, increasing the network's defense capacity.

#### 3. Detect
- **Actions Taken:** The team configured new detection capabilities to identify similar attacks in the future:
  - **IP Verification:** The firewall was configured to verify source IP addresses, helping to identify spoofed ICMP packets.
  - **Network Monitoring:** Monitoring software was introduced to detect anomalous traffic patterns that could indicate the presence of attacks.

#### 4. Respond
- **Response Plan:** The cybersecurity team developed a response plan to manage future security events:
  - **System Isolation:** Affected systems will be isolated to prevent the spread of the attack and minimize network disruption.
  - **Service Restoration:** Critical services and systems were restored as a priority.
  - **Analysis and Communication:** Network logs were analyzed to identify suspicious activities, and the incident was reported to management and, if necessary, to legal authorities.

#### 5. Recover
- **Recovery Plan:** Recovery from the attack involved the following steps:
  - **Service Restoration:** Network services were restored progressively, starting with critical services and subsequently non-critical ones.
  - **Future Blocking:** Measures were established to block ICMP flood attacks at the firewall, minimizing the risk of future incidents.
  - **Non-Critical Service Shutdown:** During the peak of the attack, non-critical network services were temporarily shut down to reduce internal traffic and facilitate recovery.

The NIST CSF offers a structured and comprehensive approach to cybersecurity management, encompassing the essential functions of identify, protect, detect, respond, and recover. The case study of the DDoS attack demonstrates the practical effectiveness of these functions in protecting critical assets and optimizing incident response. Rigorous application and continuous adaptation of the NIST CSF are imperative to ensure organizational resilience against dynamic and evolving cybersecurity threats.
