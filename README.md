# Print Shelver 3D
### Robot for the automatic storage of 3D printed parts  
*(a.k.a. Coloca3D)*  

---

## 📝 Description / Descripción

**English**  
**Print Shelver 3D** is a cartesian robot that automates the removal of 3D printed parts from a printer and places them into storage shelves.  
Designed for post-processing automation in FDM printers, it reduces manual intervention, improves workflow efficiency, and enables 24/7 printing cycles.  

**Español**  
**Print Shelver 3D** es un robot cartesiano que automatiza la extracción de piezas impresas en 3D y las coloca en estantes de almacenamiento.  
Diseñado para la automatización del post-proceso en impresoras FDM, reduce la intervención manual, mejora la eficiencia del flujo de trabajo y habilita ciclos de impresión 24/7.  

Alias local / creativo: **Coloca3D** 🎉

---

## ⚙️ Features / Características

- Cartesian XYZ gantry system for precise pick & place.  
- Automatic detection of print completion (signal, camera, or sensor).  
- Configurable shelving positions and storage logic.  
- Modular design: firmware, motion planning, and UI separated.  
- Open-source hardware and software.  

---

## 🛠️ Hardware Overview

- **Structure:** aluminum profiles + linear rails (gantry).  
- **Actuators:** stepper motors with drivers (TMC/DRV).  
- **End-effector:** gripper/vacuum tool for part picking.  
- **Electronics:** ESP32 / microcontroller.  
- **Optional:** sensors or camera for part detection.  

---

## 💻 Software

- `firmware/` → code for microcontroller (ESP32, Arduino, STM32, etc.).  
- `controller/` → motion planning, scheduling, and logic.  
- `ui/` → web/app interface for monitoring and control.  
- `docs/` → wiring diagrams, CAD, and setup guides.  

---

## 🚀 Quick Start

1. Clone repository:  
   ```bash
   git clone https://github.com/<user>/print-shelver-3d.git
   cd print-shelver-3d
