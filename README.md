# Class AB Audio Amplifier – First Fabricated PCB (Designed in Altium Designer)


## 🔧 Project Overview

This repository documents my **first fabricated PCB** project — a **Class AB audio amplifier** designed using **Altium Designer**.  
The goal of this project was to explore a complete **industry-standard PCB design workflow**, from schematic to fabrication.

---

## 🎯 Objectives

- Learn and apply a standard hardware design process
- Gain proficiency with Altium Designer's interface and features
- Understand Gerber file structure and PCB manufacturing constraints
- Prototype and validate a basic analog amplifier circuit
- Handle real-world DFM (Design for Manufacturability) issues

---

## 📐 Design Overview

- **Op-Amp**: LM4562
- **Output Stage**: Push-pull Class AB using NPN/PNP transistors
- **Topology**: DC-coupled two-stage amplifier
- **Power Supply**: Dual ±12V DC
- **Output Load**: 8Ω speaker

---

## 🛠️ Workflow Summary

1. **System Planning**: Block diagram to define functional sections  
2. **Schematic Design**: Created in Altium Designer  
3. **Simulation**: Validated gain and stability in LTspice  
4. **Prototyping**: Breadboarded for real-world testing  
5. **PCB Layout**: Top and bottom layers designed with proper grounding and clearance  
6. **Gerber Generation**: Exported manufacturing-ready files  
7. **Fabrication**: Ordered and received fabricated boards  
8. **DFM Issue**: Encountered and fixed misplaced NC drill file

---

## 📂 Files Included

- `/Schematic/` – Altium schematic files  
- `/PCB/` – PCB layout files (.PcbDoc, .PrjPcb)  
- `/Gerbers/` – Gerber and NC drill files for fabrication  


---

## 🧠 Key Learnings

- The importance of correct **NC drill file alignment**
- How simulation and prototyping help in catching early-stage design flaws
- The significance of **layer management** and **grounding techniques**
- How to read and verify **Gerber files** for fabrication readiness

---

## 🚀 Next Steps

- Improve routing for noise reduction and thermal dissipation
- Add an onboard voltage regulator
- Test frequency response and harmonic distortion
