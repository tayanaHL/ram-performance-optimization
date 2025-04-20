# ram-performance-optimization
# 🧪 Project 3 – RAM & Performance Optimization

### 🔧 Goal  
Simulate a slow system scenario in a Windows 10 virtual machine and optimize performance using built-in Windows tools like Task Manager and System Configuration. This project demonstrates how to monitor RAM usage, tune startup settings, and perform light system diagnostics—essential help desk troubleshooting tasks.

---

### 🛠️ Tools Used  
- Windows 10 (VirtualBox VM)  
- Task Manager  
- System Configuration (`msconfig`)  
- Startup Settings  
- On-screen Keyboard (used during initial troubleshooting phase)

---

### 📋 Tasks Completed  

- ✅ Launched Windows 10 VM and let background apps load  
- ✅ Opened **Task Manager > Performance** tab to monitor RAM usage  
- ✅ Navigated to the **Startup** tab to identify and disable non-critical boot programs  
- ✅ Launched `msconfig` and explored **Boot > Advanced Options**  
  - Set processor count to "1" (only 1 available due to VM settings)  
- ✅ Restarted the VM to simulate post-optimization performance  
- ✅ Compared memory usage and confirmed reduced startup activity

---


#### Task Manager – Memory Usage Before Optimization  
![Memory Usage](Insert your GitHub image URL here or upload via repo)

> RAM usage was at ~57% on a 4GB VM. Used Task Manager to analyze which processes were consuming memory and viewed system commit.

---

#### `msconfig` Boot Settings  
![Boot Config](Insert your GitHub image URL here or upload via repo)

> Explored advanced boot settings. Only 1 processor was available due to VM limitations.

---

### 🧠 Reflections & Learnings  

- I learned how to monitor live memory usage and identify RAM-heavy processes  
- Explored startup management through Task Manager and `msconfig`  
- Understood the role of system optimization in Tier 1 help desk scenarios  
- Noticed improved responsiveness after disabling background services  

---

### 📦 Project Outcome  
This project demonstrates my ability to troubleshoot a “slow PC” scenario and apply standard support tools to investigate system performance issues. I gained comfort using Task Manager, exploring `msconfig`, and making low-risk performance adjustments—all crucial skills for entry-level IT support roles.

---

### 🔗 Related Tools & Commands  
- `Ctrl + Shift + Esc` → Task Manager  
- `msconfig` → System Configuration  
- `Windows + R` → Run dialog  
- Startup tab → Boot optimization  
