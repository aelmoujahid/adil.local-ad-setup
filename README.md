# adil.local-ad-setup
Manual installation of Active Directory Domain Services on Windows Server 2019 using Server Manager.
## ✅ Project Summary

- Server OS: *Windows Server 2019*
- Installation method: *Graphical interface (Server Manager)*
- Domain Name: *adil.local*
- Forest Type: New forest
- DNS Server: Installed automatically
- DSRM Password: Set during configuration

## 📸 Steps Performed (Manual GUI)

1. Open *Server Manager*
2. Click on "Add Roles and Features"
3. Select:
   - *Role-based or feature-based installation*
   - Choose local server
4. Select role: ✅ *Active Directory Domain Services*
5. Complete installation and click "Promote this server to a domain controller"
6. Choose:
   - "Add a new forest"
   - Domain name: adil.local
7. Set a *DSRM password*
8. Leave default paths and options
9. Click *Install* – the server will reboot after promotion.
## 🎥 Video Demo

Watch the full step-by-step video of this project on LinkedIn:  
👉 [Watch here](https://www.linkedin.com/posts/adil-el-moujahid-6a24ba334_activedirectory-windowsserver-it-activity-7349374779071610882-Ryb_?utm_source=share&utm_medium=member_desktop&rcm=ACoAAFQUcloBbNaRkxmp867ZAQVDynUPvIk6AZE)

> 📌 Demonstrated by Adil EL-MOUJAHID    
## 📁 Project Structure

This project does not contain a script. It is a *documentation-based project* describing a real-world AD DS deployment done manually.

---

## 📝 Notes

- This setup was performed manually for training/documentation purposes.
- Future version of this project will include a PowerShell script for automation.
- Recommended for beginners learning Windows Server administration.

---

## 👤 Author

*Adil EL-MOUJAHID*  
Windows Server 2019 – July 2025
