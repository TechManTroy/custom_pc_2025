# 🖥️ Custom PC Build Log – Troy Edmonds (2025)

## 🛠️ Overview

This is a documentation of my first custom-built PC. The goal of this project was to build a reliable, high-performance workstation for Linux, home lab work, virtualization, and occasional gaming — all while learning PC hardware inside and out.

---

## 🔧 Final Specs

| Component         | Details                                                                 |
|------------------|-------------------------------------------------------------------------|
| **CPU**          | AMD Ryzen 7 5700G (8-core, 16-thread APU)                               |
| **CPU Cooler**   | Thermalright Assassin X 120R SE V2                                      |
| **Motherboard**  | ASUS Prime B550M-A WiFi II (mATX, WiFi 6, PCIe 4.0, ECC support)        |
| **RAM**          | 32GB DDR4 (4×8GB 2666MHz DIMMs)                                         |
| **Storage**      | 1TB NVMe M.2 SSD                                                        |
| **Case**         | STGAUBRON ABR0922 Mid-Tower w/ 6 ARGB fans                              |
| **PSU**          | Thermaltake Smart BM3 750W (Modular, 80+ Bronze)                        |
| **OS**           | Ubuntu Linux                                                            |

---

## 🎯 Goals

- Learn how to build a desktop PC from scratch
- Understand hardware compatibility, installation, and cable management
- Install and optimize Linux
- Prepare for use in my home lab environment (virtualization, media server, networking)

---

## 🪛 Build Notes

### ✅ Pre-Build Checklist
- Verified CPU and cooler compatibility
- Confirmed RAM and SSD from previous OptiPlex build were compatible
- Reviewed motherboard layout and front panel header map
- Got extra thermal paste and double-sided tape for SSD mount

### 🔌 Fan + RGB Controller Setup
- Case included 6x ARGB fans with 6-pin proprietary connectors
- Used included fan/RGB controller (picked up from store after realizing it was missing)
- **Mapped Reset SW to RGB controller**, allowing front panel reset button to cycle RGB modes
- Fans powered via SATA from PSU

### 💡 Power Supply Orientation
- PSU fan mounted facing downward for airflow (case has vent and dust filter)
- Modular PSU cables used:
  - 24-pin ATX to motherboard
  - 8-pin EPS to CPU (EATX12V)
  - SATA power to fans/controller
  - Additional SATA for SSD

### ⚙️ BIOS & Temps
- Entered BIOS successfully
- CPU idle temp: ~40°C
- Motherboard temp: ~31°C
- Verified boot order and secure boot settings
- Voltage readings within normal range

---

## 🧪 Linux + Post-Build

- Booted into Linux from USB → installed Ubuntu to NVMe SSD
- All hardware detected successfully (CPU, RAM, NVMe, case fans, onboard WiFi)
- Fan controller does **not** show up in BIOS (expected — it’s standalone)
- System stable with no errors or thermal issues

---

## 💡 Lessons Learned

- Always install the I/O shield **before** the motherboard 😅
- Double-check standoff alignment to avoid shorting the board
- Modular PSUs make cable management **so much cleaner**
- RGB/fan controllers often hijack Reset SW — plan wiring ahead
- Not all fans connect directly to the motherboard — especially pre-installed ARGB

---

## 🎮 What It Can Handle

- Great for Linux multitasking, virtualization (KVM, VirtualBox), and DevOps testing
- With APU graphics (5700G), light gaming is possible:
  - ✅ League of Legends, Valorant, Minecraft
  - ✅ Older Call of Duty titles at low/med settings
  - ❌ AAA games will require dedicated GPU (e.g. RX 6600, RTX 3060)

---

## 💰 Estimated Resale Value (2025)

| Part             | Est. Value |
|------------------|------------|
| Full System      | $450–$600  |
| With GPU (e.g., RX 6600) | $650–$800+ |

---

## 📷 Photos (To Upload)
- [ ] Completed build (side panel on/off)
- [ ] BIOS screen
- [ ] Cable management
- [ ] Fan controller

---

## 📁 Repository Structure 

├── PC-Build-Log.md

├── photos/

│ ├── front-view.jpg

│ ├── side-panel-open.jpg

│ └── bios-screen.jpg

└── parts-list.txt


---

## ✅ Status

🟢 Build complete  
🟢 Stable temps and voltage  
🟢 Linux installed  
🟢 RGB fans working via controller  
🟢 Ready for home lab, testing, and media projects!

---

# #Linux 🐧 #PCBuild 🛠️ #ITSupport 📞 #HomeLab 🔬 #TechJourney 🚀 #SystemAdmin 🖥️


