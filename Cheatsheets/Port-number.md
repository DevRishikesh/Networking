# Common Port Numbers – Cheatsheet

In networking, **port numbers** identify specific processes or services on a device. They help direct incoming and outgoing traffic to the right application.

Here’s a quick reference of commonly used **well-known port numbers (0–1023)** and a few others you’ll likely encounter.

---

## TCP and UDP Port Numbers

| Port | Protocol | Description                        |
|------|----------|------------------------------------|
| 20   | TCP      | FTP (Data Transfer)                |
| 21   | TCP      | FTP (Command/Control)              |
| 22   | TCP      | SSH (Secure Shell)                 |
| 23   | TCP      | Telnet (Unsecured Remote Login)    |
| 25   | TCP      | SMTP (Email Sending)               |
| 53   | UDP/TCP  | DNS (Domain Name System)           |
| 67   | UDP      | DHCP (Server to client)            |
| 68   | UDP      | DHCP (Client to server)            |
| 69   | UDP      | TFTP (Trivial File Transfer)       |
| 80   | TCP      | HTTP (Web Browsing)                |
| 110  | TCP      | POP3 (Email Receiving)             |
| 123  | UDP      | NTP (Time Sync)                    |
| 143  | TCP      | IMAP (Email Receiving - Advanced)  |
| 161  | UDP      | SNMP (Monitoring & Management)     |
| 194  | TCP      | IRC (Internet Relay Chat)          |
| 443  | TCP      | HTTPS (Secure Web Browsing)        |
| 465  | TCP      | SMTP over SSL                      |
| 514  | UDP      | Syslog (System Logging)            |
| 587  | TCP      | SMTP (with STARTTLS encryption)    |
| 993  | TCP      | IMAPS (Secure IMAP)                |
| 995  | TCP      | POP3S (Secure POP3)                |

---

## Security Ports

| Port | Protocol | Use Case                          |
|------|----------|------------------------------------|
| 443  | TCP      | HTTPS (Web Security)               |
| 22   | TCP      | SSH (Secure terminal access)       |
| 993  | TCP      | IMAPS (Encrypted Email)            |
| 995  | TCP      | POP3S (Encrypted Email)            |

---

## Popular UDP Ports (Speed-focused)

| Port | Use Case                     |
|------|------------------------------|
| 53   | DNS                          |
| 67/68| DHCP                         |
| 123  | NTP                          |
| 161  | SNMP                         |
| 69   | TFTP                         |
| 500  | IPsec VPN                    |

---

## Summary

- **Ports 0–1023** = Well-known ports (standard services)
- **TCP** = Reliable, used for most stable connections
- **UDP** = Faster, used for streaming/gaming/DNS
- Memorizing key ports helps in **networking, security, and certifications** like CCNA/CEH

> Pro tip: Learn ports **by service name** (e.g., SSH → 22, DNS → 53, HTTPS → 443)
