 Blue Team Lab 1: Windows Logon Event Analysis

**Date:** July 27, 2025  
**Tool:** Windows Event Viewer  
**Lab Goal:** Detect successful logins using Event ID 4624

---

 Steps Taken
1. Opened Event Viewer with `eventvwr.msc`
2. Navigated to **Windows Logs > Security**
3. Filtered by Event ID: `4624`
4. Found a successful system login (`Logon Type 5`)

---

 Screenshot

---

 What I Learned
- `4624` = successful logins
- `Logon Type 5` = system service
- This is how defenders detect logins

---

✅ Conclusion
I analyzed my first Windows login event using Blue Team tools.
