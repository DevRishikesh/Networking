# TCP/IP Model

The **TCP/IP model** (Transmission Control Protocol/Internet Protocol) is the foundational communication model used in the internet and most modern networks.

It describes how data is packaged, transmitted, and received across networks.

---

## Overview

- Developed by the **U.S. Department of Defense (DoD)**.
- Has **4 layers** (sometimes 5 if we separate physical).
- More practical than OSI; directly maps to real-world protocols.

---

## TCP/IP Model Layers

| Layer (Top to Bottom)   | Description                                                   | Real-World Protocols                |
|-------------------------|---------------------------------------------------------------|-------------------------------------|
| **Application Layer**   | User-facing services like web, email, file transfer           | HTTP, FTP, SMTP, DNS, SSH           |
| **Transport Layer**     | Provides reliable/unreliable delivery of data                 | TCP, UDP                            |
| **Internet Layer**      | Handles addressing and routing of data across networks        | IP, ICMP, ARP                       |
| **Network Access Layer**| Deals with physical transmission of data over the network     | Ethernet, Wi-Fi, MAC                |

---

## Layer Functions Explained

### 1. Application Layer
- Interface for end-user services.
- Handles protocols like web browsing (HTTP), email (SMTP), file transfer (FTP), etc.

### 2. Transport Layer
- Ensures reliable (TCP) or fast (UDP) data delivery.
- Handles segmentation, error checking, and flow control.

### 3. Internet Layer
- Adds IP addresses to data.
- Routes packets between networks.
- Handles packet fragmentation.

### 4. Network Access Layer
- Combines OSI’s **Data Link** + **Physical** layers.
- Manages hardware-level communication: cables, switches, MAC addresses.

---

## TCP/IP vs OSI Model

| Feature             | TCP/IP Model                | OSI Model                    |
|---------------------|-----------------------------|------------------------------|
| Layers              | 4                            | 7                             |
| Practicality        | More practical, real-world   | More theoretical              |
| Developed By        | DoD (USA)                    | ISO                           |
| Usage               | Internet, real networking    | Conceptual understanding      |
| Layer Mapping       | Combines lower OSI layers    | Separate Physical & Data Link |

---

## Real-World Data Flow (Simplified)

1. User opens a website → Application layer (HTTP)
2. Data passed to TCP → Transport layer
3. IP adds address info → Internet layer
4. Ethernet/Wi-Fi sends data → Network Access layer
5. Reverse process on receiving device

---

## Summary

- The **TCP/IP model** is the basis of internet communication.
- It has 4 layers: **Application, Transport, Internet, Network Access**.
- It maps directly to real-world protocols like TCP, IP, HTTP, etc.
- Simpler and more practical than the OSI model.
