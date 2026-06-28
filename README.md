# Bandit OTW

## Level 0 

**Goal:** The goal of this level is to log into the game using SSH. The host is bandit.labs.overthewire.org, on port 2220. Username is bandit0 and password is bandit0.

**Commands used:** ssh

**Solution:**

```bash
ssh bandit0@bandit.labs.overthewire.org -p 2220    # SSH (Secure Shell), a way to remotely control another computer through the terminal, securely over the network.
```

**Password:** bandit0
<img width="618" height="540" alt="image" src="https://github.com/user-attachments/assets/560d691f-c0dc-42eb-8c4c-cc588b36652f" />

---

## Level 0 → Level 1

**Goal:** The password for the next level is stored in a file called readme located in the home directory. Use this password to log into bandit1 using SSH. Whenever you find a password for a level, use SSH (on port 2220) to log into that level and continue the game.

**Commands used:** ls , cd , cat , file , du , find

**Solution:**

```bash
bandit0@bandit:~$ ls    # List files and directories
readme
bandit0@bandit:~$ cat readme    # Cat prints the content of a file in terminal
```

**Password:** 6y2kwnwK6grgvwvpLaa2T1cpFEK0hNR

<img width="692" height="172" alt="image" src="https://github.com/user-attachments/assets/fd665512-7f3e-4bfa-940c-22f4e118056f" />

---
