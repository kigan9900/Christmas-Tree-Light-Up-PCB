# 🎄 Christmas-Tree-Light-Up-PCB

![License](https://img.shields.io/badge/License-MIT-green.svg)
![Made With KiCad](https://img.shields.io/badge/Made%20With-KiCad-blue)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)
![Version](https://img.shields.io/badge/Version-1.0.0-red)
![Holiday Project](https://img.shields.io/badge/Project-Holiday%20PCB-gold)

A clean, professional holiday-themed PCB designed in the shape of a Christmas tree.  
This board uses perimeter LEDs to create a simple, festive flashing pattern, making it a perfect soldering project, desk decoration, or small electronics gift.

---

## 🌲 3D Render
A polished 3D preview to highlight the final aesthetic and how the board will look once manufactured and assembled.

<img width="1025" height="775" alt="image" src="https://github.com/user-attachments/assets/dd74afa0-25db-4606-9ed5-a38b98f8bec3" />

---

## ✨ Inspiration
Inspired by classic seasonal DIY electronics kits and tabletop holiday displays. The design was driven by three goals:
- Create a visually balanced, display-worthy PCB silhouette.  
- Keep the electronics simple and accessible for beginners.  
- Ensure the board is optimized for fabrication (clearances, solder masks, panelization-friendly).

<p align="center"><em>“Small projects make the holidays shine. -Me ”</em></p>

<p align="center">
  <img width="520" alt="PCB Layout (inspiration close-up)" src="https://github.com/user-attachments/assets/386af5fa-76b8-4248-8d7e-9b9a7f38c846" />
</p>

---

## 🛠 Project Overview
A succinct look at what this project provides and why it’s useful.

- Elegant Christmas-tree PCB silhouette with cutout edges  
- Even LED placement around the perimeter for smooth, continuous patterns  
- Beginner-friendly circuit designed for reliable assembly and testing  
- Optimized for PCB fabrication: proper clearances, silk labeling, and test points  
- Ideal for learning soldering, demonstrating KiCad skills, or gifting as a small, hand-made present

<p align="center">
  <img width="700" alt="Schematic preview" src="https://github.com/user-attachments/assets/3111c2fd-e47a-4a73-854b-1e04f8166388" />
</p>

---

## 📄 Bill of Materials (BOM)

| ID | Designator(s) | Footprint | Quantity | Value / Part | Notes |
|----|---------------|-----------|----------|--------------|-------|
| 1 | U1 | DIP-8_W7.62mm | 1 | NE555P | Timer IC |
| 2 | RV3 | R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm | 1 | 50K Potentiometer | Flash speed control |
| 3 | Ce1 | CP_Radial_D5.0mm_P2.00mm | 1 | 0.01 µF | Timing capacitor |
| 4 | D12, D10, D6, D2, D8, D7, D11, D5, D9, D1 | LED_D3.0mm | 10 | LEDs | Perimeter lighting |
| 5 | U2 | N16 | 1 | 4017 | Decade counter |
| 6 | R2 | R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm | 1 | 470 Ω | LED resistor |
| 7 | R3 | R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm | 1 | 1 kΩ | Timing resistor |
| 8 | C3 | CP_Radial_D5.0mm_P2.00mm | 1 | 1 µF | Timing capacitor |


