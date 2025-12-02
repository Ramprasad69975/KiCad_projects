# UJT LED Flasher PCB Design

This project implements a simple LED flasher circuit using a **UJT (Unijunction Transistor)** as a relaxation oscillator.  
The PCB was fully designed and routed as a learning project to understand real-world PCB design fundamentals.

---

## 🔍 Project Overview

This circuit uses the switching behavior of a UJT to generate periodic pulses that flash an LED.  
The frequency of blinking is controlled by an RC network connected to the emitter of the UJT.

---

## ⚙️ Working Principle

- The capacitor charges through a resistor from the supply voltage.
- When the capacitor voltage reaches the intrinsic standoff voltage (ηVp) of the UJT:
  - The UJT turns ON.
  - The capacitor discharges rapidly through B1.
  - This sudden current causes the LED to flash.
- After discharge, the UJT turns OFF and the cycle repeats.

---

## 🧰 Components Used

| Component | Description |
|-----------|-------------|
| UJT | Unijunction Transistor |
| R | Timing Resistor |
| C | Timing Capacitor |
| LED | Visual indicator |
| Power Source | DC supply |
| PCB | 2-layer board |

---

## 🖥️ Design Tools

- **KiCad** for schematic and PCB layout
- Gerber files generated for fabrication
- 3D view rendered inside KiCad

---

## 📁 Repository Contents

| Folder | Description |
|--------|-------------|
| `schematic/` | Circuit diagram |
| `pcb_layout/` | PCB screenshots (top, bottom, 3D) |
| `gerber_files/` | Manufacturing-ready Gerber files |
| `documents/` | Theory and explanation (optional) |

---

## 📸 PCB Views

### Top Layer
![Top View](pcb_layout/top_view.png)

### Bottom Layer
![Bottom View](pcb_layout/bottom_view.png)

### 3D Model
![3D View](pcb_layout/3d_view.png)

---

## ✅ Features

- Correct routing and placement
- Complete Gerber output
- Proper silkscreen labeling
- Optimized copper routing
- Clean PCB layout

---

## 🚀 What I Learned

- PCB layout fundamentals
- UJT working principle
- Component placement
- Routing rules (45° routing, trace width control)
- Gerber generation
- Design rule checking

---

## 🏁 Author

Designed by **Your Name**

---

## 📜 License

Open-source project for learning and educational purposes.
