# ENED 1120 Autonomous Robot for Mobile TDP Plant  
**Spring 2025 – University of Cincinnati**

## 🌍 Project Overview

This project addresses the National Academy of Engineering (NAE) Grand Challenge:  
**Develop Carbon Sequestration Methods**

Our team designed and built a **semi-autonomous robot** prototype intended for use in a **mobile Thermal Depolymerization (TDP) plant**, which processes disaster debris into usable fuel. The robot autonomously classifies, lifts, and transports bins of material to their correct processing zones—contributing to disaster recovery while promoting environmental sustainability.

> 🔗 **Watch the Final Demo**: [YouTube – Final Demo Video](https://youtu.be/uCwxQbQjLqI)

---

## 🤖 Robot Capabilities

- **Line following** using dual color sensors and a PID control system  
- **Weight-based material classification** (Light, Medium, Heavy) via lifting arm torque analysis  
- **Autonomous zone detection and drop-off** using ultrasonic sensors  
- **Touch sensor-triggered bin pickup** with dynamic arm movement  
- **Closed-loop operation** from pickup to drop-off and back

---

## 🧠 Key Features

- **PID-Controlled Navigation**: Custom LabVIEW PID code enabled reliable path tracking on solid and broken lines.
- **Dynamic Arm Control**: Motor power scaled based on error to ensure smooth and consistent lifts.
- **Weight Detection Algorithm**: Integrated into pickup sequence; identifies bin weight from accumulated motor effort.
- **Zone & Drop-off Logic**: Zone detection tracked using ultrasonic sensor pulses; triggered drop-offs based on bin class.
- **Professional Build & Documentation**: All decisions documented in an engineering notebook and tested thoroughly over multiple iterations.

---

## 🛠️ Technologies Used

- **LabVIEW 2016** for control logic and PID implementation  
- **LEGO Mindstorms EV3** for hardware architecture  
- **Desmos** for mathematical modeling of lifting curves  
- **Ultrasonic, Color, and Touch Sensors** for interaction and detection  
- **CAD & Rapid Prototyping** for custom bins and build components

---

