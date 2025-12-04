# 🔐 C++ Cybersecurity Study Planner — 30 Days

This repository contains a structured **30-day learning roadmap** focused on applying C++ in cybersecurity domains such as **malware development concepts, exploit fundamentals, system programming, reverse engineering, and defensive security tool development**.

The planner is designed for:
- Cybersecurity beginners learning low-level programming  
- Students preparing for SOC / Malware Analysis / DFIR roles  
- Developers transitioning into systems security  
- Anyone wanting hands-on experience with OS-level security tools  

---

# 📊 Visual Overview — Learning Flowchart

```mermaid
flowchart TD
    A[Week 1: C++ Foundations] -->|Syntax, Memory, I/O| B[Week 2: System Programming]
    B -->|WinAPI, Syscalls, Networking| C[Week 3: Offensive C++]
    C -->|Reverse Shells, Injection, Exploits| D[Week 4: Defensive & Reversing]
    D -->|AV, EDR, Malware Toolkit| E[Final: Portfolio + Review]

    A --> A1[Day 1–7 Projects:\nPort Scanner]
    B --> B1[Day 8–14 Projects:\nKeylogger]
    C --> C1[Day 15–21 Projects:\nReverse Shell + RAT]
    D --> D1[Day 22–30 Projects:\nAV Scanner + EDR Tool]
