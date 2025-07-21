# TryHackMe Solutions Repository

Welcome to my TryHackMe solutions repository! This contains my writeups, scripts, and notes from various rooms and challenges on [TryHackMe](https://tryhackme.com/).

**Profile:** [KUN2001](https://tryhackme.com/p/KUN2001)

## 📋 Repository Structure

```
├── README.md
├── beginner/
│   ├── room-name/
│   │   ├── README.md
│   │   ├── writeup.md
│   │   ├── scripts/
│   │   └── screenshots/
├── intermediate/
├── advanced/
├── ctf/
├── tools/
│   ├── custom-scripts/
│   └── useful-commands.md
└── resources/
    ├── cheatsheets/
    └── references.md
```

## 🎯 Progress Tracker

### Completed Rooms

#### Beginner Level
- [ ] **Room Name** - Brief description
  - **Difficulty:** Easy
  - **Date Completed:** DD/MM/YYYY
  - **Key Learnings:** Brief note about what you learned
  - **Files:** [Link to folder](./beginner/room-name/)

#### Intermediate Level
- [ ] **Room Name** - Brief description
  - **Difficulty:** Medium
  - **Date Completed:** DD/MM/YYYY
  - **Key Learnings:** Brief note about what you learned
  - **Files:** [Link to folder](./intermediate/room-name/)

#### Advanced Level
- [ ] **Room Name** - Brief description
  - **Difficulty:** Hard
  - **Date Completed:** DD/MM/YYYY
  - **Key Learnings:** Brief note about what you learned
  - **Files:** [Link to folder](./advanced/room-name/)

### CTF Challenges
- [ ] **CTF Name** - Brief description
  - **Date Completed:** DD/MM/YYYY
  - **Rank/Score:** Your ranking or score
  - **Files:** [Link to folder](./ctf/ctf-name/)

## 🛠️ Tools and Resources

### Custom Scripts
- **Script Name** - Brief description of what it does
  - Location: [./tools/custom-scripts/script-name.py](./tools/custom-scripts/)
  - Usage: `python3 script-name.py [arguments]`

### Favorite Tools Used
- **Nmap** - Network scanning and enumeration
- **Burp Suite** - Web application security testing
- **Metasploit** - Exploitation framework
- **Gobuster** - Directory/file brute-forcer
- **John the Ripper** - Password cracking
- **Hydra** - Login brute-forcer
- **Wireshark** - Network protocol analyzer

## 📚 Learning Paths Progress

### Complete Beginner
- [ ] Learning Cyber Security
- [ ] Intro to Offensive Security
- [ ] Linux Fundamentals 1
- [ ] Linux Fundamentals 2
- [ ] Linux Fundamentals 3
- [ ] Windows Fundamentals 1
- [ ] Windows Fundamentals 2
- [ ] Windows Fundamentals 3

### Web Fundamentals
- [ ] How websites work
- [ ] HTTP in detail
- [ ] Burp Suite: The Basics
- [ ] OWASP Top 10
- [ ] OWASP Juice Shop

### Network Security
- [ ] Intro to Networking
- [ ] Nmap
- [ ] Network Services
- [ ] Network Services 2
- [ ] Protocols and Servers
- [ ] Protocols and Servers 2

## 📊 Statistics

- **Total Rooms Completed:** 0
- **Current Streak:** 0 days
- **Favorite Categories:** [Update based on your interests]
- **Current Rank:** [Your current THM rank]

## 📝 Notes and Tips

### General Methodology
1. **Reconnaissance** - Always start with thorough enumeration
2. **Vulnerability Assessment** - Identify potential attack vectors
3. **Exploitation** - Carefully execute attacks with proper documentation
4. **Post-Exploitation** - Maintain access and gather information
5. **Documentation** - Record everything for future reference

### Common Commands Cheatsheet
```bash
# Network Scanning
nmap -sC -sV -oN nmap_initial.txt <target_ip>
nmap -p- -oN nmap_all_ports.txt <target_ip>

# Web Enumeration
gobuster dir -u http://<target_ip> -w /usr/share/wordlists/dirb/common.txt
nikto -h http://<target_ip>

# File Transfers
python3 -m http.server 8000
wget http://<your_ip>:8000/file.txt
```

## 🏆 Achievements and Badges

- [ ] **7 Day Streak** - Complete a room every day for 7 days
- [ ] **30 Day Streak** - Complete a room every day for 30 days
- [ ] **100 Days** - Be active for 100 days
- [ ] **Cat Linux** - Complete the Linux Fundamentals path
- [ ] **Mr. Robot** - Complete the Mr. Robot CTF

## 🤝 Contributing

This repository is primarily for my personal learning, but feel free to:
- Suggest improvements to my writeups
- Share alternative solutions
- Point out any errors or better approaches

## ⚠️ Disclaimer

These solutions are for educational purposes only. The writeups and scripts in this repository are intended to help others learn cybersecurity concepts. Please:

- Use this knowledge responsibly and ethically
- Only test on systems you own or have explicit permission to test
- Follow TryHackMe's guidelines and terms of service
- Respect the learning process - try to solve challenges yourself before looking at solutions

## 📞 Contact

- **TryHackMe Profile:** [KUN2001](https://tryhackme.com/p/KUN2001)
- **GitHub:** [Your GitHub Profile]
- **LinkedIn:** [Your LinkedIn Profile] (optional)

---

**Last Updated:** [Current Date]

*Happy Hacking! 🚀*