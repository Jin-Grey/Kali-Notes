# 🌐 Networking Fundamentals (Cybersecurity Edition)

> These notes are focused on **practical networking for hacking & security**, not just theory.

---

# 🧠 1. What is Networking?

Networking is the process of connecting multiple systems to:
- Share data
- Communicate
- Access services

📌 In hacking:
> Networking = Understanding how targets communicate

---

# 🧱 2. OSI Model (Real Hacker View)

| Layer | Name | What Hackers Care About |
|------|------|------------------------|
| 7 | Application | HTTP, DNS attacks |
| 6 | Presentation | Encryption (SSL/TLS) |
| 5 | Session | Session hijacking |
| 4 | Transport | TCP/UDP, ports |
| 3 | Network | IP, routing |
| 2 | Data Link | MAC, ARP spoofing |
| 1 | Physical | Hardware |

---

# 🌍 3. IP Address

### Types:
- Private IP → `192.168.x.x`, `10.x.x.x`
- Public IP → Internet-facing

### Check your IP:
```bash
ip a

