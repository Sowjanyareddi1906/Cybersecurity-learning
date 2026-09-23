# Web Security Notes

Web security focuses on identifying and understanding vulnerabilities in web applications.

## How a Web Application Works

User
→ Frontend
→ HTTP/HTTPS Request
→ Web Server
→ Backend
→ Database
→ Response

## Important Concepts

- HTTP Methods
- HTTP Headers
- Cookies
- Sessions
- Authentication
- Authorization
- Parameters
- APIs
- Client-side vs Server-side processing

## Common Web Vulnerabilities

### SQL Injection (SQLi)

Occurs when untrusted input is improperly included in a database query.

### Cross-Site Scripting (XSS)

Occurs when attacker-controlled input is executed as JavaScript in a user's browser.

Types:

- Reflected XSS
- Stored XSS
- DOM-based XSS

### Server-Side Template Injection (SSTI)

Occurs when user-controlled input is interpreted as a server-side template.

### IDOR

Insecure Direct Object Reference occurs when an application exposes an object or resource without properly checking authorization.

### File Upload Vulnerabilities

Applications that accept file uploads must properly validate file type, content, filename, and storage location.

### Path Traversal

Occurs when an application allows users to access files outside the intended directory.

## Web Security Testing Workflow

1. Reconnaissance
2. Identify technologies
3. Discover endpoints
4. Analyze requests and responses
5. Test input parameters
6. Identify vulnerabilities
7. Validate findings in an authorized lab
8. Document the result

## Tools

- Burp Suite
- Nmap
- Browser Developer Tools
- CyberChef

## Practice Platforms

- TryHackMe
- PortSwigger Web Security Academy
- CTF platforms

All testing should be performed only on authorized systems and labs.
