# HTTP (HyperText Transfer Protocol)

## What is HTTP?
**HTTP (HyperText Transfer Protocol)** is the foundation of data communication on the **World Wide Web**.
It is a **request response protocol** used by web browsers and servers to exchange data such as loading web pages, sending forms, etc.
---
## How It Works
- **Client** (usually a browser) sends an HTTP **request** to the **server**.
- The **server** processes it and sends back an **HTTP response**.
- HTTP is **stateless** it does not remember previous interactions by default.
---
## HTTP Request Format
- GET /index.html HTTP/1.1
- Host: www.example.com
- User-Agent: Mozilla/5.0
- Accept: text/html
---
## Components
-  **Method** (GET, POST, etc.)
-  **URL/Path**
-  **Headers** (Host, User Agent, etc.)
-  **Body** (only in POST, PUT)
---
## HTTP Response Format
- HTTP/1.1 200 OK
- Content Type: text/html
- Content Length: 1234
- **html ... /html**
---
## Components
- **Status Line** (HTTP version, status code, message)
- **Headers** (Content-Type, etc.)
- **Body** (HTML, JSON, etc.)
---
## Common HTTP Methods
 
| Method   | Description                        |
|----------|------------------------------------|
| POST	   | Submit data (form submission, etc.)|
| PUT	     | Update data                        |
| DELETE	 | Remove resource                    |
| PATCH	   | Partially update a resource        |
| HEAD	   | Like GET but returns headers only  |
---
## Real-World Example
- You open https://example.com.
- Browser sends an HTTP GET request to the server.
- Server responds with a 200 OK and sends back the webpage.
- Browser renders the content for you.
## Summary
- HTTP is the protocol of the web everything from HTML to APIs runs on it.
- It’s a stateless, text based protocol with methods, headers, and status codes.
- For secure communication, we use HTTPS (HTTP over TLS).
