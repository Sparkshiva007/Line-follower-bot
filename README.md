# Line Following Robot on Perfboard

This project demonstrates a **line-following robot** designed with all components mounted on a single **perfboard**, making it compact, cost-effective, and easy to replicate. The robot can intelligently follow a black line on a white surface using onboard sensors and a control algorithm.

---

## 🔧 Features

- Smooth and responsive line tracking
- Lightweight and highly compact design
- Entire circuitry assembled on a single perfboard
- Low-cost and beginner-friendly design
- Built with commonly available electronic parts
- uses PID algorithm to detect and perform perfect turns
  
---

## 🧠 How It Works

The robot uses an array of reflectance sensors to detect the path (black line). Based on the position of the line, the robot adjusts the speed of its motors to stay on track. The main controller processes the sensor data and calculates the required motor response using a simple PID algorithm.

---

## 🛠️ Hardware Used

| Component            | Purpose                               |
|---------------------|----------------------------------------|
| Arduino Nano         | Core controller (brain of the robot)   |
| QTR Sensor Array     | To detect line position                |
| N20 Gear Motors      | For movement and turning               |
| TB6612FNG Motor Driver   | To drive and control the motors        |
| 7.4V Battery Pack    | Power supply for motors and logic      |
| Voltage Regulator    | To provide stable power to controller  |
| Perfboard            | Base for assembling all components     |
| Male/Female Headers  | For modular connections                |
| Enameled Copper Wire | For giveing connections                |
---

## 🪛 Assembly Overview

- The Arduino Nano is mounted on the perfboard alongside the QTR sensor array.
- The motors are connected via a motor driver and are powered by a rechargeable battery.
- Wires are routed through the underside of the perfboard for a clean finish.
- All sensor and motor connections are soldered directly to the board.

> Note: No additional chassis or PCB is used — the perfboard serves as both the structure and the circuit base.

---

## 💡 Credits

**Project by:** Shiva Projects  
If you recreate, remix, or improve this project, give credit to the creator.

---

## ⚠️ License

This project is licensed under the MIT License - you are free to use, modify, and distribute it with attribution.
