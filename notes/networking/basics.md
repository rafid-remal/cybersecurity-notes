# 🌐 Networking Basics

---

## 📌 What is an IP Address?
An IP address is a unique identifier for a device on a network.

### Example:
```bash
192.168.1.1
```

---

## 🔢 Types of IP
- IPv4 (32-bit)
- IPv6 (128-bit)

---

## ⚖️ TCP vs UDP

| Feature | TCP | UDP |
|--------|-----|-----|
| Connection | Yes | No |
| Speed | Slower | Faster |
| Reliability | High | Low |

---

## 🌍 What is DNS?
DNS (Domain Name System) converts domain names into IP addresses.

### Example:
```bash
google.com → 142.250.x.x
```

---

# 🚀 Advanced Networking

## 🧭 Check IP address
```bash
ip a
```

---

## 🌐 Test connectivity (ping)
```bash
ping google.com
```

---

## 🛣️ Trace route to a host
```bash
traceroute google.com
```

---

## 🔎 DNS lookup
```bash
nslookup google.com
```

---

## 📡 Show open ports
```bash
netstat -tuln
```

---

## 🔐 Check active connections
```bash
ss -tuln
```

---

## 📥 Download via network
```bash
curl https://example.com
```

---

## 🧠 Important Concepts

### 🔒 Public vs Private IP
- **Public IP**: Visible on the internet
- **Private IP**: Used inside local networks (e.g., 192.168.x.x)

---

### 🧱 Subnet Mask
Defines network and host portions of an IP.

Example:
```bash
255.255.255.0
```

---

### 🚪 Default Gateway
The router that connects your network to the internet.

---

### 🔥 Ports (Common Examples)

| Port | Service |
|------|--------|
| 80 | HTTP |
| 443 | HTTPS |
| 22 | SSH |
| 21 | FTP |
| 53 | DNS |

---

## 🛠️ Pro Tips
- Use `ping` to quickly check if a server is alive  
- Use `traceroute` to debug network delays  
- Use `ss` instead of `netstat` (modern systems)  
- Combine tools like `curl` + `grep` for powerful checks  

---
