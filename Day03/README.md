# Day 3 - Flask Request Lifecycle & Session Security

## Topics Covered

### Flask Fundamentals
- app.run()
- Routing and Routing Tables
- Request Lifecycle
- print() vs return()
- GET vs POST
- Request Object

### Web Application Components
- Database Fundamentals
- User Authentication
- Authorization

### Security Concepts
- Multi-Factor Authentication (MFA)
- Sessions
- Cookies
- Session Hijacking
- Session Fixation
- Secure Cookies
- HttpOnly Cookies
- SameSite Cookies
- Logout Workflow
- Session Expiration

## Key Learning

Learned how web applications authenticate users, manage sessions, store cookies, and defend against common session-based attacks.

## Important Workflows

### Request Lifecycle
Browser → Flask → Routing Table → Function → Response

### Session Workflow
Login → Session Created → Session ID Generated → Stored on Server

### Cookie Workflow
Server → Cookie → Browser → Future Requests

### Session Hijacking
Victim Login → Session ID Stolen → Attacker Uses Session ID → Unauthorized Access

## Outcome

Developed a strong foundation in Flask internals, authentication systems, session management, cookie security, and web application security concepts.
