# APFC_System
IoT-Based Smart Automatic Power Factor Correction System with Dynamic Capacitor Switching for Energy Efficiency

# IoT-Based APFC System with Dynamic Capacitor Switching

This repository contains the MATLAB/Simulink models and final report for an IoT-based Automatic Power Factor Correction (APFC) system that uses dynamic capacitor switching to improve energy efficiency under varying load conditions.

---

## 📌 Overview

The project implements an APFC system that:

- Continuously measures the real-time power factor (PF) of a three-phase load.
- Dynamically switches capacitor banks to maintain PF near unity.
- Uses IoT for remote monitoring (data logging to ThingSpeak, if expanded).

---

## 📂 Repository Structure

├── capacitor_bank.slx # Simulink model with dynamic capacitor switching logic
├── fixed_load_capacitor_bank.slx # Simulink model for a fixed-load capacitor bank scenario
├── working_final_model.slx # Final integrated Simulink model used for testing
└── Report.pdf # Detailed project report


---

## ⚙️ Model Descriptions

1. **capacitor_bank.slx**  
   - Simulink model implementing dynamic capacitor bank switching based on PF readings.  
   - Contains PF measurement blocks and switching logic to engage/disengage individual capacitor sections.

2. **fixed_load_capacitor_bank.slx**  
   - Simulink model of a fixed-load scenario with a static capacitor bank for baseline comparison.  
   - Used to evaluate performance against the dynamic switching approach.

3. **working_final_model.slx**  
   - Final integrated Simulink model combining the dynamic switching controller, PF sensor blocks, and three-phase load.  
   - Serves as the master model for simulations and result generation.

---

## 📄 Report

- **Report.pdf**  
  - Explains system architecture, control algorithms, and simulation results.  
  - Includes performance analysis showing improved PF, reduced reactive power, and transient response under load changes.



## 🔗 License

This project is intended for academic and educational use only.  

