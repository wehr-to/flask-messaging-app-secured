# flask-messaging-app-secured

A secure real-time chat app built with Flask and Flask-SocketIO. Designed to simulate stored XSS risks, session handling flaws, and insecure message handling. Includes audit logging, optional WebSocket authentication, and real-time message flows.

## 🎯 Learning Goals

- Build a messaging app with WebSocket or polling
- Handle user login, sessions, and logout securely
- Prevent stored XSS in message bodies
- Validate message length, content, and format
- Log message events for auditability

## 🔐 Security Audit Focus

- ❌ Stored XSS via chat input  
- ❌ Lack of token/session validation for message sending  
- ❌ Insecure or missing logout flow  
- ✅ Optional: message sanitization  
- ✅ Optional: audit log of chat events  

See [`audit-checklist.md`](./audit-checklist.md) for details.

## 🤝 Contributions
Pull requests are welcome! If you’d like to add features, improve security hardening, optimize code, or extend functionality, feel free to open an issue or PR. This is a learning-focused lab project, and collaboration is encouraged.

## ✅ Features

- Real-time chat using Flask-SocketIO
- Basic login/logout with session tracking
- Message length and format validation
- Optional input sanitization (HTML escape)
- Audit log of messages and user events
- Optional: WebSocket token validation
