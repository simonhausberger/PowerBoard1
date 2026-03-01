# ⚡ PowerBoard v1

## Modular BLDC Motor Test Bench for Laboratory Education  
**Diploma Thesis – HTL Anichstraße**  
Department of Electrical Engineering & Mechatronics  
Class 5AHET (2025/26)

---

## ⚠️ Important Notice

This hardware revision contains known design errors.  
👉 Please use **PowerBoard v2** instead:  
https://github.com/simonhausberger/PowerBoard2

---

## 📘 Project Overview

At the energy laboratory of HTL Anichstraße, Department of Electrical Engineering and Mechatronics, there is currently no dedicated platform for the practical investigation of low-power BLDC motors.

The goal of this diploma thesis is the development of a **modular motor test bench for laboratory applications**, capable of realistically representing the operating behavior of a permanent magnet synchronous machine (PMSM) or BLDC motor.

The project is divided into three main areas:

- 💻 Software development  
- ⚡ Power and control electronics  
- 🏗 Mechanical test bench design  

---

## ⚙️ System Concept

The motor control system is developed entirely from scratch and supports multiple control strategies:

- Block commutation  
- Field-Oriented Control (FOC)  
- Sensorless control methods  

Motor loading is achieved using a mechanically coupled DC machine operating in generator mode.

The test bench is designed modularly, allowing future integration of other machine types such as:

- Induction machines  
- Synchronous machines  

instead of the BLDC motor.

---

## 📊 Measurement & Data Processing

Operating and measurement data are captured via sensors, processed by a microcontroller, and transmitted to a PC for visualization and analysis.

Both hardware and software are fully self-developed to enable a deep understanding of modern electric drive systems.

The final result is a sustainable extension of the laboratory infrastructure.

---

## 📦 Downloads

### 🔧 Hardware (Fusion Design Files)

Fusion archive including:
- Schematic  
- PCB layout  
- 3D model  

Download:  
https://github.com/simonhausberger/PowerBoard1/releases/tag/PowerBoardv1

---

### 💻 Control Software

Developed by Matthias Kleinlercher  

Repository:  
https://github.com/MatthiasKleinlercher

---

## 🤝 Cooperation

Developed in cooperation with  

**Infineon Technologies AG**

---

## 🎓 Educational Purpose

This project serves as an educational platform for:

- Power electronics  
- Gate driver design  
- Microcontroller-based motor control  
- Control engineering  
- Measurement and data acquisition  

---
