# 📌 Webserv

**Type:** HTTP Web Server 
**Tecnologies:** C++, Unix Sockets, Non-blocking I/O, CGI, Makefile
**Status:** Completed

---

## 📖 Description
Webserv is a project aimed at creating a fully functional HTTP/1.1 web server from scratch in C++. Developed as part of the 42 curriculum, it demonstrates mastery of low-level networking, server-side programming, and protocol implementation.

The server handles static and dynamic content, processes multiple client connections concurrently, and is designed to comply with the HTTP/1.1 standard. Webserv emphasizes robustness, performance, and proper resource management.

---

## ✨ Highlighted Features
- 🖥️ **HTTP/1.1 Implementation**: Request parsing, response generation, and persistent connections.
- ⚡ **Non-blocking I/O**: Using poll() to handle multiple simultaneous connections efficiently.
- 📝 **CGI Support**: Execute dynamic content through Common Gateway Interface scripts.
- 🗂️ **Configurable Server**: Custom configuration parser inspired by Nginx.
- 🛠️ **Error Handling & Logging**: Robust management of client errors and server logs.
- 🔄 **Process Management**: Handle child processes safely for CGI execution.

---

## 🖼️ Screenshots
![Webserv Banner](../assets/webserv/webserv_01.png)

---

## 🏗️ Challenges
- Implementing a compliant HTTP/1.1 server from scratch in C++.
- Efficiently handling multiple simultaneous client connections with non-blocking I/O.
- Safely managing child processes for CGI execution.
- Building a flexible configuration parser while maintaining performance.

---

## 📅 Timeline
- **Development started:** 02/2024
- **Stable release:**
- **Last update:** 04/2024
