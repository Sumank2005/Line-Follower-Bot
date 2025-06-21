# 🤖 Line Follower Bot

An Arduino-based **line following robot** that detects and follows a black path using IR sensors. Ideal for robotics competitions and electronics learning.

---

## 🧠 Features

- Follows black lines on white surface using IR sensors
- Uses Arduino Uno for control
- Simple PID (optional) or threshold-based logic
- Can detect turns and junctions (basic logic)
- Compact design with dual motor driver (L298N / L293D)

---

## 🔌 Components Used

- Arduino UNO
- IR Sensor Module (x2 or x5)
- L298N / L293D Motor Driver
- DC Geared Motors (x2)
- Wheels + Chassis
- 12V Battery Pack
- Jumper Wires
- Breadboard or soldered PCB (optional)

---

## ⚙️ Working Principle

1. IR sensors detect the contrast between black line and white background.
2. Microcontroller reads the sensor values.
3. Based on sensor output, Arduino drives the motors:
   - If line is center → move forward
   - If line is left → turn left
   - If line is right → turn right

---

## 🛠 Circuit Diagram

![Line Follower Circuit](./images/line-follower-circuit.png)

---
