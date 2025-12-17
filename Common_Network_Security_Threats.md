# 1.1.2 Common Network Security Threats

## Hacker

A **hacker** is a person with a deep understanding of software design, programming, and computer science.

Different perspectives on hackers:

- **Computer software perspective**:  
  Hackers are individuals who are highly interested in computers and network systems and possess a deep technical understanding of them.

- **Amateur computer technology perspective**:  
  Hackers are amateurs who study how to modify computer-related products and systems.

- **Information security perspective**:  
  Hackers are people who gain **intellectual or technical access to computer security systems in an unauthorized way** (e.g., illegal login, bypassing security mechanisms).

---

## Vulnerability

A **vulnerability** is the **root cause of security problems**.

It refers to a defect or weakness in:
- Hardware
- Software
- Network protocols
- System security policies

Because of vulnerabilities, information security incidents may occur, such as:
- Permission bypass
- Privilege escalation
- Execution of unauthorized instructions
- Data disclosure
- Denial of Service (DoS) attacks

### Vulnerability Scanning

On a live network, engineers perform **vulnerability scanning** to detect weaknesses in a target network or host.  
It can be used for:
- Attack simulation
- Security audits

**Typical process**:
1. Ping sweep  
2. Operating system detection  
3. Port scanning  
4. Vulnerability scanning  

---

## Ransomware Attack

A **ransomware attack** usually follows four main stages:

### 1. Intrusion
The attacker gains initial access through methods such as:
- Weak password cracking (e.g., SQL accounts)
- Phishing attacks
- Malicious emails

### 2. Diffusion
After intruding into a host, the attacker spreads laterally within the target network using various attack methods to:
- Expand the attack scope
- Increase the number of controlled hosts

### 3. Theft
The attacker:
- Traverses the data
- Selects the most valuable targets
- Steals sensitive data
- Uploads the data to a server under the attacker’s control

### 4. Extortion
The attacker:
- Deploys ransomware to crash or encrypt the target network
- Leaves ransom notes to extort money
- May sell stolen data for profit

---

## Information Breach

An **information breach** occurs when sensitive data is exposed without proper protection.

**Example**:
- A security researcher discovers an unprotected database on the network
- The database can be accessed without identity authentication
- The researcher informs the company
- The company secures the database, but the data may already have been leaked

If hackers obtain the leaked data, they may:
- Crack user accounts
- Launch further attacks through phishing emails

---

## DDoS Attacks

A **Distributed Denial of Service (DDoS)** attack aims to exhaust network or system resources of a target server.

### Impact:
- Services are temporarily interrupted or stopped
- Legitimate users cannot access the service

### Modern Characteristics:
- With the emergence of **IoT**, attackers can launch large-scale DDoS attacks by exploiting:
  - Device hardware vulnerabilities
  - Poor device management

- Hackers often:
  - Lease DDoS attack resources as a service
  - Allow attackers with limited skills to customize attacks

This model has become a **mainstream profit method** for hacker organizations with DDoS capabilities.

---

## Supply Chain Attack

A **supply chain attack** targets organizations through their supply chains.

### Characteristics:
- Attacks are launched against supply chain components
- The impact spreads to:
  - Partners
  - Enterprise customers

### Attack Method:
- Intruders implant **backdoor components** into core service or software installation packages
- Partners or customers download or update the official package
- The malicious component spreads automatically across the supply chain
