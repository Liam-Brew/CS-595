# Chapter 1 Information Security Overview

## Table of Contents

- [Chapter 1 Information Security Overview](#chapter-1-information-security-overview)
  - [Table of Contents](#table-of-contents)
  - [Availability](#availability)
  - [Information Technology Infrastructure Domains](#information-technology-infrastructure-domains)
  - [Basic Information Security Concepts](#basic-information-security-concepts)
    - [Vulnerabilities](#vulnerabilities)
    - [Threats](#threats)
    - [Risks](#risks)
    - [Safeguards](#safeguards)
  - [Information Security Concerns](#information-security-concerns)
    - [Shoulder Surfing](#shoulder-surfing)
    - [Social Engineering](#social-engineering)
    - [Phishing, Spear Phishing, and Whaling](#phishing-spear-phishing-and-whaling)
    - [Malware](#malware)
    - [Spyware and Keystroke Loggers](#spyware-and-keystroke-loggers)
    - [Logic Bombs](#logic-bombs)
    - [Backdoors/Trapdoors](#backdoorstrapdoors)
    - [Denial of Service (DoS) Attacks](#denial-of-service-dos-attacks)
  - [Information Security Protection](#information-security-protection)
    - [Organizational Governance](#organizational-governance)

## Availability

A **single point of failure** is a piece of hardware or an application that is key to the functioning of the entire system. If this item fails, then a critical portion of or even the entire system can fail

A **denial of service (DoS) attack** targets an information system's availability, bringing them offline and preventing users from accessing them. These attacks can target the information system itself as well as consumed resources such as its power or network connection

## Information Technology Infrastructure Domains

The seven infrastructure domains are:

1. **user domain**: any forward-facing technologies used by end users
2. **workstation domain**: computing devices, such as laptops, used by end users
3. **LAN domain**: local area network connection of two or more computers
4. **WAN domain**: wide area network of a large geographical area. Examples include the internet and organizations with several remote locations
5. **LAN-to-WAN domain**: infrastructure that connects a LAN to a WAN
6. **remote access domain**: processes and procedures that end users use to remote access infrastructure and data
7. **system/application domain**: equipment and data an organization uses to support its infrastructure. Includes hardware, operating systems, database software, and client-server applications

## Basic Information Security Concepts

### Vulnerabilities

**Vulnerabilities** are weaknesses or flaws in a system that can be exploited to harm information security. They can be construction and design mistakes or may alternatively be flaws in how a safeguard is used or not used. Types of vulnerabilities are:

- people: **separation of duties** violations can result in one person knowing too much about a system or having too much power
- process: flaws in organization processes such as skipping steps in a checklist (or not having one) or failing to patch software
- facility: weaknesses in physical security
- technology: improperly designed systems or systems that haven't been patched

**Exploits** are successful attacks against a vulnerability. These take place during the **window of vulnerability**, a time period between when the vulnerability is discovered and when it is eliminated or mitigated. **Zero-day vulnerabilities** are vulnerabilities that are exploited as soon as they are discovered

### Threats

**Threats** are anything that can harm an information system and are successful exploits against vulnerabilities. Categories of threats are:

- human: both internal and external attackers. Can include good-intentioned actors as well as malicious actors
- natural: natural events such as earthquakes
- technological and operational: threats that operate inside information systems. Examples are malicious code, hardware and software failures, and improperly running processes
- physical and environmental: facility-based threats such as breaches or loss of heating

**Internal attackers** have current relationships with the organization. They may be employees, contractors, or business contacts that have access to the organization's network

### Risks

A **risk** is the likelihood that a threat will exploit a vulnerability and impact the organization. Common risk management strategies are:

- **risk avoidance**: applying safeguards to avoid a negative impact. Risk avoidance seeks to eliminate all risk and is often times the most expensive option
- **risk mitigation**: applying safeguards to lower risk to an acceptable level. The leftover risk is called **residual risk**
- **risk transfer**: risk is passed to another entity such as insurance policies
- **risk acceptance**: accepting the risk as inevitable and deeming the cost of avoiding, mitigating, or transferring it to be too high

### Safeguards

A **safeguard**, also known as a control, reduces the harm posed by information security vulnerabilities or threats. Types of safeguards are:

- administrative: actions, rules, and policies which dictate how information is to be handled and systems used, with an example being **need to know** rule regarding the distribution of information
- technical/logical: operational rules for hardware and software, with an example being the **least privilege** governing access to computer permissions and resources
- physical: actions taken to protect physical resources, such as keeping unauthorized individuals out of controlled areas

Safeguards can also be classified based on how they act and what their objectives are, with the following categories existing:

- **preventative**: used to prevent security incidents
- **detective**: used to detect a security incident while it's in progress
- **corrective**: used to limit the damage caused by a security incident

| **Safeguard Theme**   | **Preventative**                 | **Detective**                     | **Corrective**                                      |
| --------------------- | -------------------------------- | --------------------------------- | --------------------------------------------------- |
| **Administrative**    | organization hiring policy       | periodic background checks policy | discipline policy                                   |
| **Technical/Logical** | least privilege principle        | antivirus software                | updating firewall rules                             |
| **Physical**          | locks on doors to critical areas | burglar alarms                    | locking a door that was inadvertently left unlocked |

## Information Security Concerns

### Shoulder Surfing

**Shoulder surfing** occurs when an attacker observes a user who is currently viewing sensitive information. This can be in terms of physically watching them or through the use of a key-logger or similar software. Shoulder surfing is especially dangerous in public places such as ATMs, coffee shops or airports

### Social Engineering

**Social engineering** uses social interaction to take advantage of human nature. Employees may be tricked by an attacker impersonating a coworker into providing information, credentials, or data that should otherwise not be made public

### Phishing, Spear Phishing, and Whaling

**Phishing** attacks are disguised as legitimate messages from a known organization familiar to the target. They usually attempt to get targets to enter personal information on a fake website that the target believes to be valid

**Spear phishing** is a targeted phishing campaign against a specific organization, and are typically more complex than standard phishing attacks. These attacks research the target and use information and logos to make the phishing attack seem authentic. These attacks seek to obtain information about the targeted organization such as authentication credentials

**Whaling** targets corporate executives, whose authentication credentials are typically much more valuable within an organization than those of a typical worker

### Malware

**Malware** includes software such as viruses, worms, and Trojan Horses. Viruses spread themselves across a computer or network by copying their code, thereby infecting all aspects of a system. Worms are self-contained viruses that don't require outside assistance to propagate themselves. Trojan Horses are pieces of malware that are disguised as legitimate software

### Spyware and Keystroke Loggers

**Spyware** is software that collects information about a user. It is oftentimes hidden in Internet downloads. Spyware may track website history through cookies (potentially revealing stored passwords and credentials)

**Keystroke loggers** save keyboard entries as raw data. Attackers then parse this data and examine it to reveal confidential information and credentials

### Logic Bombs

A **logic bomb** is harmful, dormant code that is embedded in a system. When certain conditions are met, such as a date being reached, the code executes. Upset employees typically use this to get back at employers

### Backdoors/Trapdoors

A **backdoor/trapdoor** is a way to bypass the standard authentication procedure and gain access to the system. Programmers sometimes use them to help debug code more quickly, while others are built in by disenfranchised employees for later breaching of the deployed system

### Denial of Service (DoS) Attacks

**DoS** attacks target the availability of an information system in an attempt to bring it down

**Distributed Denial of Service (DDoS)** attacks are DoS attacks on a much larger scale. The attacker uses thousands of "zombie" computers connected via the botnet or malware to overload the target's infrastructure

## Information Security Protection

### Organizational Governance

Documents relating to the organizational governance of information security are:

- **policies**: the first level of governance for information protection. Tells an organization how it must act and the consequences for failing to act properly
- **standards**: state the activities and actions necessary to meet policy goals, reduce risks and meet requirements. They don't refer to particular technologies
- **guidelines**: recommended actions and guides for employees
- **procedures**: step-by-step checklists explaining how to meet security goals. Representing the lowest level of governance documents, they are tailored to a certain type of technology, to a certain department, or for certain use cases
