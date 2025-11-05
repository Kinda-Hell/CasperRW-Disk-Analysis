# CasperRW-Disk-Analysis  
Digital Forensic Examination of *ubnist1.casper-rw.gen3.E01* (NPS 2009 Casper-RW)

This repository contains the forensic analysis conducted on the **NPS 2009 Casper-RW USB drive image**, obtained from **Digital Corpora**.  
The goal of this analysis was to identify and recover **government-related files** and to reconstruct the context of system usage on the device.

The investigation was performed using both **Autopsy** (GUI-based forensic suite) and **The Sleuth Kit (TSK)** (command-line forensic toolkit), focusing on file system examination, deleted file recovery, and metadata interpretation.

---

## 🔍 **Key Objectives**
- Analyze the EXT3 filesystem structure of the USB disk image  
- Identify and list **deleted and allocated files**  
- Recover **government-related documents**, spreadsheets, and official statements  
- Validate findings using both GUI and CLI forensic workflows  
- Document the process and results transparently and reproducibly  

---

## 🧰 Tools Used
| Tool | Purpose |
|------|---------|
| **Autopsy** | GUI-based forensic analysis & file metadata inspection |
| **The Sleuth Kit (TSK)** | Low-level file system analysis and file recovery (`fls`, `icat`, `mmls`) |
| **strings (Sysinternals/Unix)** | To extract readable content from recovered data |

---

## 🧾 **Summary of Findings**
The investigation resulted in the **successful recovery of multiple U.S. Government documents**, including:

- **FCC DTV Transition spreadsheets and reports**
- **Formal FCC commissioner statements (SAFER Act)**
- **Government operational workflow spreadsheets**
- **System-level metadata about Ubuntu/KDE software environment**

Recovered documents appear to originate from official **Federal Communications Commission** (FCC) sources, indicating that the device was used to store or review government documents related to public communications infrastructure.

---
## 🎯 Key Learning Outcomes

- Gained hands-on experience working with **both GUI and command-line forensic tools**.
- Understood how **deleted files can still exist in unallocated disk space**.
- Learned how to **systematically document evidence** following forensic process standards.
- Improved skills in extracting, analyzing, and interpreting **real-world recovered data**.
- Recognized the importance of maintaining **integrity, chain of custody, and ethical handling** of digital evidence.

---

## 🏁 **Conclusion**
This project demonstrates a full workflow of forensic disk examination —  
from file system mapping to deleted file recovery, cross-verification between tools, and interpretation of digital artifacts.  
It also highlights how recovered documents can provide insight into **real operational contexts**, such as government communications and transition planning workflows.





