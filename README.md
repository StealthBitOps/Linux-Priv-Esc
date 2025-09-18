---
## 🧱 Linux Privilege Escalation

---
#### 🧭 Objectives
- Learn how to escalate privileges on compromised Linux systems.
- Identify misconfigurations and exploitable binaries.
- Practise manual and automated enumeration techniques.

#### 🧠 Skills Explored
- File and permission analysis.
- SUID binaries and PATH manipulation.
- Exploiting cron jobs and writable scripts.
- Using automated tools to streamline escalation.

#### 🛠️ Tools Overview
- `LinPEAS`, `Linux Exploit Suggester`, `find`, `sudo`, `getcap` – for enumeration and exploitation.
- `GTFOBins` – for known binary abuse techniques.
- TryHackMe target VM – vulnerable Linux box for hands-on practice.

#### 🔄 Steps to Remember (_Privilege Escalation Flow_)
1. **Initial Enumeration** – Gather system info and user context.
2. **Check Permissions** – Look for writable files and SUID binaries.
3. **Explore Scheduled Tasks** – Identify exploitable cron jobs.
4. **Use Known Exploits** – Reference GTFOBins and suggesters.
5. **Escalate & Validate** – Gain root and confirm access.

---
### ✅ Summary
This room builds on previous exploitation skills by focusing on privilege escalation within Linux. 

Develop the ability to move from limited shell access to full system control, an essential step in real-world engagements.

---
