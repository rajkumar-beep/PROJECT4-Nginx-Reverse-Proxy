# PROJECT 4 - Nginx Reverse Proxy Setup

## Overview

This project demonstrates how to run a Node.js application behind an Nginx Reverse Proxy using Docker and Docker Compose.

Nginx receives requests from users and forwards them to the application container internally.

---

## Architecture

Internet → Nginx Container → Node.js Application Container

---

## What I Learned

- Reverse Proxy
- Docker Compose
- Multi-container applications
- Docker networking
- Port forwarding
- Nginx basic configuration

---

## Technologies Used

- Node.js
- Docker
- Docker Compose
- Nginx

---

## How It Works

1. User sends request from browser
2. Request reaches Nginx container
3. Nginx forwards request to Node.js app container
4. Application sends response back to user

---

## Output

The application was successfully accessed through Nginx on browser.

---

## Conclusion

This project helped me understand how Nginx works as a Reverse Proxy in a multi-container Docker environment.
