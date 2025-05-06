# Gobuster Web Directory Enumeration – TryHackMe Lab

This lab was part of my TryHackMe Web Fundamentals path. I used **Gobuster**, a command-line tool, to brute-force and discover hidden directories and pages on a simulated banking website (`http://fakebank.thm`).

## 🔧 Tools Used
- Gobuster v2.0.1
- Linux terminal (Ubuntu VM from TryHackMe)

## 📚 Learning Objectives
- Understand directory brute-forcing with wordlists
- Learn how status codes reveal accessible pages (e.g., 200 OK, 301 Redirect)
- Explore potential security risks of exposed admin endpoints

## 💻 Command Used
```bash
gobuster -u http://fakebank.thm -w wordlist.txt dir
![Gobuster Output Screenshot] https://github.com/serenalindquist99/web-dir-enumeration-gobuster/commit/e35c11c4d572527b0d5fc10cf96a29f869bc90d0
