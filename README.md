# Hey, I'm Oscar 👋

Systems Administration graduate from Castellón, Spain. I spent two years deep in Linux, networking and Windows Server, and now I'm shifting everything toward cloud and DevOps — not by following tutorials, but by building real things and figuring out what breaks.

📍 Castellón, Spain · Open to remote · B2 English (working toward C1)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://es.linkedin.com/in/oscar-mu%C3%B1oz-herrera-051332275)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:oherreram06@gmail.com)

---

## About me

I finished my Systems Administration degree with a solid foundation in sysadmin work, but what interests me most is the overlap between infrastructure and cloud engineering. I'm currently deploying real infrastructure on AWS, learning Docker hands-on, and building tools that I'd actually find useful.

I've done internships at three different companies across both my degrees: Forcada (Kyocera printer and document management solutions, plus IT services and system maintenance), Modula (automated warehouse storage systems and industrial logistics), and currently Record Go (vehicle rental company managing fleets, booking platforms and digital operations) — 3 months each. Different environments, different tech stacks, same approach: figure out how things actually work before touching anything.

---

## Technologies I work with

| Area | Tools |
|---|---|
| **Systems** | Linux (Ubuntu), Windows Server, Proxmox VE |
| **Networking** | TCP/IP, DNS, VLANs, OPNsense, WireGuard VPN, firewall rules |
| **Containers** | Docker, Docker Compose, Kubernetes (k3s) |
| **Cloud** | AWS EC2, Elastic IPs, Security Groups |
| **Scripting** | Bash, PowerShell, Python (basic) |
| **Databases** | PostgreSQL |
| **Monitoring** | Grafana, Prometheus, Node Exporter |
| **Web** | Nginx, Let's Encrypt, TypeScript |

---

## Projects

### 🔹 AD Manager
A PowerShell tool to manage Active Directory users, groups and OUs through an interactive menu. Built it to practice real scripting on Windows Server and understand how to automate admin tasks without relying on the GUI.

→ [View repository](https://github.com/oscarmunozh/AD-Manager)

### 🔹 NeoLink — Corporate Infrastructure Platform
Full corporate infrastructure project built as my Systems Administration degree capstone, developed in a team of three.

NeoLink centralises identity management, internal services and secure remote access for a mid-sized company — a self-hosted alternative to fragmented tools like Microsoft 365 or disconnected open-source stacks.

**What we built:**
- Proxmox virtualisation cluster (2 nodes) running all services as VMs
- OPNsense as the network perimeter — firewall, VLAN segmentation (admin, DMZ, servers, VPN...), WireGuard VPN, ACLs between all segments
- Active Directory for centralised user and permissions management with MFA
- WireGuard VPN server deployed via Docker on AWS EC2, with Nginx as reverse proxy and Let's Encrypt TLS certificates
- Odoo ERP (Docker) — invoicing, inventory, internal chat
- Wiki.js (Docker) for internal documentation
- Grafana + Prometheus for infrastructure monitoring
- Static corporate website in TypeScript, containerised with Docker, served via Nginx
- k3s (lightweight Kubernetes) for container orchestration

**Stack:** Proxmox · OPNsense · Active Directory · WireGuard · Docker · Nginx · AWS EC2 · PostgreSQL · Odoo · Grafana · Prometheus · TypeScript · Kubernetes

---

## What I'm looking for

A Cloud or DevOps role at a company where infrastructure actually matters — somewhere with scale, technical depth, and room to grow fast. Remote preferred.

---

*Open to work · Open to feedback*
