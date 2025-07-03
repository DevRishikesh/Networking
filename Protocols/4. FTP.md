# FTP (File Transfer Protocol)

## What is FTP?
**FTP** is a **standard network protocol** used to **transfer files** between a **client and server** over a TCP-based network like the internet.
It works in a **client-server model**, where the client requests files and the server provides access.
Defined in **RFC 959**, FTP is one of the oldest internet protocols still in use.
---
## Key Features
- Upload and download files
- User authentication with username/password
- Two modes: Active and Passive
- Uses **TCP ports 21 (command)** and **20 (data)**
---
## FTP Modes
| Mode    | Description |
|---------|-------------|
| **Active**  | Server connects back to client for data transfer |
| **Passive** | Client opens both connections (better for firewalls/NAT) |
---
## FTP Commands (Examples)
| Command | Description              |
|---------|--------------------------|
| `USER`  | Sends username            |
| `PASS`  | Sends password            |
| `LIST`  | Lists files in directory  |
| `RETR`  | Retrieves (downloads) a file |
| `STOR`  | Stores (uploads) a file   |
| `QUIT`  | Ends the session          |
---
## Security Concerns
- **Unencrypted** credentials and data sent in plain text
- Vulnerable to sniffing and man-in-the-middle attacks
### Secure Alternatives
| Protocol | Description                |
|----------|----------------------------|
| **FTPS** | FTP over SSL/TLS encryption |
| **SFTP** | SSH File Transfer Protocol (completely different, runs over SSH) |
---
## Real-World Use Cases
- Hosting services (uploading files to web servers)
- Corporate file sharing (intranet)
- Large batch transfers (legacy systems)
---
## FTP vs HTTP
| Feature       | FTP                         | HTTP                     |
|---------------|-----------------------------|--------------------------|
| Purpose       | File transfer               | Web content delivery     |
| Authentication| Username/password (optional)| Cookies, sessions        |
| Encryption    | None (by default)           | HTTPS provides encryption|
| Ports         | 21 (control), 20 (data)     | 80 (HTTP), 443 (HTTPS)   |
---
## Summary
- **FTP** is a protocol for transferring files between computers on a network.
- It works on **TCP**, uses **ports 20/21**, and has two connection modes.
- Use **FTPS or SFTP** for secure file transfers.

> Think of FTP as the **digital truck** used to move files from one server to another just make sure it’s not leaking (use encryption)!
