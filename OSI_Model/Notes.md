# OSI Model (Open Systems Interconnection)

The **OSI model** is a conceptual framework that standardizes the functions of a communication system into **seven layers**. It helps understand **how data travels from one computer to another**.

---

## Why OSI Model?
- Developed by the **ISO** (International Standards Organization).
- Helps in designing and understanding networks.
- Each layer has a specific role in **data transmission**.
- Promotes interoperability between vendors and systems.

---

## The 7 Layers of the OSI Model

| Layer No. | Layer Name       | Function                                | Examples                           |
|-----------|------------------|-----------------------------------------|------------------------------------|
| 7         | Application       | User interface; network services        | HTTP, FTP, SMTP, DNS               |
| 6         | Presentation      | Data format, encryption, compression    | SSL, JPEG, MPEG                    |
| 5         | Session           | Manages sessions/connections            | NetBIOS, PPTP                      |
| 4         | Transport         | Reliable delivery, error control        | TCP, UDP                           |
| 3         | Network           | Logical addressing and routing          | IP, ICMP, ARP                      |
| 2         | Data Link         | MAC addressing, framing, error detection| Ethernet, PPP                      |
| 1         | Physical          | Raw bit transmission over medium        | Cables, Hubs, Wi-Fi, NIC           |

---

## Layer Functions Explained

### 7. Application Layer
- Closest to the user.
- Provides services like email, file transfer, web browsing.

### 6. Presentation Layer
- Translates data formats (e.g., encryption, compression, encoding).

### 5. Session Layer
- Controls sessions between applications (start, maintain, terminate).

### 4. Transport Layer
- Ensures reliable delivery (TCP) or faster but unreliable (UDP).
- Handles segmentation, flow control, and error checking.

### 3. Network Layer
- Adds logical addressing (IP).
- Chooses path to destination (routing).

### 2. Data Link Layer
- Deals with physical addressing (MAC).
- Responsible for framing, error detection.

### 1. Physical Layer
- Sends bits over a physical medium.
- Includes cables, switches, NICs, voltage levels.

---

## OSI vs TCP/IP Model

| OSI Layer          | TCP/IP Layer        |
|--------------------|---------------------|
| Application        | Application         |
| Presentation       | Application         |
| Session            | Application         |
| Transport          | Transport           |
| Network            | Internet            |
| Data Link + Physical| Network Access     |

---

## Memory Trick (Mnemonic)
**"Please Do Not Throw Sausage Pizza Away"**

> Physical, Data Link, Network, Transport, Session, Presentation, Application

---

## Summary

- The OSI model has **7 layers**, each with a specific function.
- Helps us understand **how data moves through a network**.
- Often used in **troubleshooting**, **protocol design**, and **network architecture**.
