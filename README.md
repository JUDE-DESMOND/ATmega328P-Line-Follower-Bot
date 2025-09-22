# Smart Line Follower Car using ATmega328P

A dual-mode autonomous robot car that follows a black line using IR sensors and avoids obstacles using an ultrasonic sensor. This project was developed as part of the **Microcontroller Laboratory** during the **2nd Year, 2nd Semester**.

---

## 🚗 Project Overview

This smart car operates in two modes:

- **Mode 01 (Line Following):**  
  - Uses 3 IR sensors to follow a calibrated black line.
  - Green LED blinks when this mode is active.

- **Mode 02 (Line Following + Obstacle Detection):**  
  - Follows the line using IR sensors.
  - Ultrasonic sensor checks for obstacles.
  - Car stops if an obstacle is detected.
  - Blue LED blinks when this mode is active.
  - Red LED blinks when an obstacle is detected.

---

## 🔧 Hardware Components

| Component              | Description                                 |
|------------------------|---------------------------------------------|
| Microcontroller        | ATmega328P (via Arduino UNO or bare chip)   |
| IR Sensors (x3)        | For line detection                          |
| Ultrasonic Sensor      | For obstacle detection                      |
| Motor Driver           | L298N Dual H-Bridge                         |
| DC Motors              | N20 High Torque Motors (x2)                 |
| Power Supply           | 12V Lithium Battery                         |
| LEDs                   | Red, Blue, Green (Status Indicators)        |
| Chassis                | 2-Wheel Drive Platform                      |

---

## ⚙️ Working Principle

1. **Power ON**: Car activates automatically using the 12V battery.
2. **Mode Selection**:
   - Mode 01: Line following only.
   - Mode 02: Line following + obstacle detection.
3. **IR Sensors** detect the line and direct the car.
4. **Ultrasonic Sensor** (in Mode 02) checks for obstacles.
5. LEDs provide visual feedback:
   - 🟢 Green: Mode 01 active
   - 🔵 Blue: Mode 02 active
   - 🔴 Red: Obstacle detected

---

## 🧠 Skills Gained

- Embedded C / Arduino Programming
- Sensor Integration
- Motor Control using PWM
- Power Management
- Real-time Decision Making
- Project Debugging & Testing

---


