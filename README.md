# 💧 Water Tank Control System - HMI Simulation

## 📘 Overview

This project demonstrates an **automated Water Tank Control System** designed and simulated using **TIA Portal**, **PLCSIM**, and **WinCC HMI Runtime Advanced**. It showcases real-time monitoring and control of tank water levels using inlet and outlet pumps, visual indicators, and interactive control elements.

## 🛠 Tools Used

- **TIA Portal** – for PLC programming and HMI design.
- **PLCSIM** – for simulating the PLC logic without physical hardware.
- **WinCC Runtime Advanced** – for running the HMI simulation interface.
- **SIMTABLE** – for linking HMI tags to the PLC program.

## 🧩 System Features

- **Start/Stop Push Buttons** – Activate or stop the inlet pump.
- **Visual Indicators**:
  - 🔵 Tank Full
  - ⚪ Tank Empty
  - 🟡 Draining in Progress
  - ⚪ Filling in Progress
- **Pump Status Lamps**:
  - 🟢 Running
  - ⚪ Stopped
- **Live Tank Level Display** – Real-time numeric and graphical level feedback.
- **Touch-Friendly HMI Interface** – Designed for touchscreen interaction.

## ⚙️ System Logic

- When the system is started, the inlet pump begins filling the tank.
- If the tank reaches the high level (`H`), the inlet pump stops and the system marks it as **Tank Full**.
- If the level exceeds the high mark or manual drain is triggered, the outlet pump activates.
- The outlet pump drains until the low level (`L`) is reached, after which it stops and shows **Tank Empty**.

## 🖥️ Simulation Instructions

1. Open the project in **TIA Portal**.
2. Run the PLC logic using **PLCSIM**.
3. Launch the HMI screen using **WinCC Runtime Advanced**.
4. Use the Start/Stop buttons on the HMI to control the system and observe the simulation.

## Variables
![Variables in SIMTable](./Variables%20in%20SIMTable.png)

## HMI Screen
![HMI Display](./HMI%20Display.png)

## ✅ Applications

- Demonstrates principles of SCADA/HMI in industrial automation.
- Ideal for learning PLC-HMI integration.
- Suitable for fluid control simulation labs or academic projects.

---

*This simulation offers a simplified view of real industrial tank control systems using Siemens automation tools.*

