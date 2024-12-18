# 🎵 MP3 Player Design Project

## 📝 Project Overview

This repository contains the design and implementation details of an **MP3 player with power bank functionality**, developed as part of the **EN2160 - Electronic Design Realization** course at the **University of Moratuwa**. The project incorporates multiple features including music playback from an SD card, volume control, an OLED display, and a high-capacity battery pack for extended use and device charging.

---

## 📌 Table of Contents

1. **[Introduction](#introduction)**
2. **[Design Specifications](#design-specifications)**
   - [Display](#display)
   - [Control IC](#control-ic)
   - [SD Card Storage](#sd-card-storage)
   - [Battery](#battery)
   - [Boost Converter](#boost-converter)
   - [Charging and Regulation Circuit](#charging-and-regulation-circuit)
3. **[Functionality Description](#functionality-description)**
4. **[PCB Design](#pcb-design)**
5. **[Components/BOM](#componentsbom)**
6. **[Enclosure Design](#enclosure-design)**
7. **[Soldering and Testing](#soldering-and-testing)**
8. **[Final Prototype](#final-prototype)**
9. **[Instruction to Use](#instruction-to-use)**
10. **[Appendices](#appendices)**
    - [Appendix I: BOM](#appendix-i-bom)
    - [Appendix II: Design Files](#appendix-ii-design-files)
    - [Appendix III: Final Product Assembly](#appendix-iii-final-product-assembly)
    - [Appendix IV: Display Code](#appendix-iv-display-code)
    - [Appendix V: Preliminary Design Approach](#appendix-v-preliminary-design-approach)

---

## 📄 Introduction

The MP3 player is designed to:

- Play music from an SD card.
- Output audio via a 3.5mm audio jack.
- Provide power bank functionality using a high-capacity battery pack.
- Include user controls and an OLED display for easy navigation.

---

## 🔧 Design Specifications

### Display

- **Type:** 0.96-inch OLED display  
- **Purpose:** Displays track number and volume level.

### Control IC

- **Microcontroller:** ATmega328p (SMD version)  
- **Features:** Supports display control and navigation buttons.

### SD Card Storage

- **Module:** DFPlayer Mini  
- **Functionality:** Decodes audio and outputs analog signals.

### Battery

- **Type:** Three 18650 Li-ion batteries (3600mAh each)  
- **Feature:** Provides extended music playback and power bank functionality.

### Boost Converter

- **Function:** Converts 3.7V to 5V for charging external devices.

### Charging and Regulation Circuit

- **Components:**  
  - **TC4056:** Charging management IC  
  - **DW01:** Battery protection IC  
  - **FS8205:** Dual MOSFET for efficient power switching

---

## ⚙️ Functionality Description

- **Inputs:**  
  - `Prev`: Go to the previous track  
  - `Next`: Go to the next track  
  - `Select`: Play/pause music and control volume  
- **Audio Output:** 3.5mm audio jack  
- **Power Bank:** Capable of charging external devices via USB.

---

## 🖨️ PCB Design

The design includes:

- **Power Management:** Handles battery charging and protection.
- **Control Circuit:** Manages user inputs and display output.
- **Audio Output:** Interfaces with the DFPlayer Mini for music playback.

---

## 📋 Components/BOM

A detailed **Bill of Materials (BOM)** is available in **[Appendix I](#appendix-i-bom)**.

---

## 🏗️ Enclosure Design

- **Software Used:** SolidWorks  
- **Design:** Two-part enclosure with lip and groove fitting and screw mounts.  
- **Features:** Openings for buttons, audio jack, SD card, and USB ports.

---

## 🔧 Soldering and Testing

- **Process:**  
  - Soldered SMD and through-hole components onto the PCB.  
  - Tested the power management and audio playback functionality.  
- **Issues:** Resolved overheating issues with the boost converter.

---

## ✅ Final Prototype

The final assembled prototype includes:

- MP3 player with OLED display.  
- High-capacity battery pack.  
- Enclosure with user-friendly controls.

---

## 📖 Instruction to Use

1. **First-Time Setup:** Connect to an external power source to reset the IC’s logic levels.
2. **Playback:** Insert an SD card with preloaded songs and use the buttons to navigate tracks.
3. **Charging:** Use the USB ports to charge external devices.

---

## 📎 Appendices

### Appendix I: BOM

Refer to the detailed **Bill of Materials (BOM)** for component specifications and costs.

### Appendix II: Design Files

Includes **schematics**, **PCB layouts**, and **fabrication files**.

### Appendix III: Final Product Assembly

Step-by-step assembly process with images of the prototype.

### Appendix IV: Display Code

Arduino code for controlling the OLED display and MP3 playback.

### Appendix V: Preliminary Design Approach

Initial sketches, design iterations, and user-centered design feedback.

---

## 🚀 Developed by

- **Bandara D.M.D.V.**  
  **University of Moratuwa**  
  **Department of Electronic & Telecommunication Engineering**  
  **July 14, 2023**

---

📂 **[Project Documentation and Design Files](#)**  
For detailed design files and schematics, explore the repository contents.
