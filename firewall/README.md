# Firewall Configuration with UFW

This project sets up and configures a firewall using **UFW (Uncomplicated Firewall)** on `web-01` to block all incoming traffic except for **SSH (22), HTTP (80), and HTTPS (443)**.

## **Requirements**
- Install UFW if not already installed.
- Block all incoming traffic by default.
- Allow outgoing traffic by default.
- Allow specific incoming ports:
  - **22 (SSH)** - For remote access.
  - **80 (HTTP)** - For web traffic.
  - **443 (HTTPS)** - For secure web traffic.
- Enable UFW and verify rules.

---

## **Installation & Configuration Steps**

### **1. Install UFW (If Not Installed)**
```bash
sudo apt update && sudo apt install ufw -y

