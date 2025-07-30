
# 🛠️ IT Support Troubleshooting Ticket

**Issue Type:** Hardware – Physical Inspection & Reassembly  
**User:** Thomas Kemp (Self-directed project)  
**Device:** Custom Desktop PC  
**Location:** Home Office, Corsham  
**Date:** July 2025  

---

## 🎯 Problem Description

User reported boot instability and inconsistent device detection. A physical inspection was required to confirm correct internal cable connections, component seating, and possible loose wiring after moving the PC.

---

## 🔍 Troubleshooting Actions Taken

1. **Full disassembly of PC case**  
   - Removed side panels and inspected motherboard, drives, and PSU  
   - Verified presence of all standoff screws and grounding

2. **Cable verification and reseating:**  
   - Reseated SATA data and power cables  
   - Reconnected HD Audio header (to COM header on motherboard)  
   - Ensured USB front panel header was securely connected (USB34 slot)  
   - Inspected CPU cooler, RAM seating, and GPU alignment

3. **Dust removal and airflow check**  
   - Cleared dust from fan filters and CPU heatsink  
   - Verified fan spin-up and case airflow

4. **Powered system on and entered BIOS**  
   - Verified POST success  
   - BIOS recognized both SSD and USB boot media  
   - Confirmed boot order matches Ventoy setup

5. **Tested multiboot USB (Ventoy)**  
   - Loaded bootloader menu successfully  
   - Confirmed working ISOs for:
     - Ubuntu 24.04.2
     - Windows 10  
     - Windows 11 (bypassing TPM/CPU checks)

---

## ✅ Resolution

System fully reassembled and tested. All cables were reconnected correctly. Multiboot environment worked as expected. No further errors found.

---

## 🧠 Skills Demonstrated

- PC disassembly/reassembly  
- BIOS configuration  
- Boot order management  
- Internal cable identification (USB, HD Audio)  
- ISO boot testing (Ventoy)

---

*Photos of setup and Ventoy boot menu available upon request or included in full portfolio.*
