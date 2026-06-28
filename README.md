# Bandit OTW

## Level 0 → Level 1

**Goal:** The goal of this level is to log into the game using SSH. The host is bandit.labs.overthewire.org, on port 2220. Username is bandit0 and password is bandit0.

**Commands used:** ssh

**Solution:**

```bash
ssh bandit0@bandit.labs.overthewire.org -p 2220
```

**Password:** bandit0

---

**SSH — Secure Shell**

A way to remotely control another computer through the terminal, securely over the network.

**Syntax:**

```bash
ssh username@ipaddress -p portnumber
```

**Why SSH matters in cybersecurity?**
- Pentesting and CTFs — connect to target machines using found credentials
- Privilege escalation — SSH keys stored with wrong permissions are vulnerable
- Brute forcing — attackers try common passwords against SSH
- Tunneling — bypass firewalls by routing traffic through SSH
---
