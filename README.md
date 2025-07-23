# 🔧 Arduino Projects Overview

This README provides documentation for two Arduino-based projects created on Tinkercad. Each project is described with an image, a summary of its components, functionality, and whether it uses **analog** or **digital** inputs.

---

## 📌 Project 1: Temperature Monitoring using TMP36 Sensor and LCD Display

🔗 [Tinkercad Project Link](https://www.tinkercad.com/things/cjVFzoQlCth/editel?returnTo=%2Fdashboard)

### 📸 Project Image  
![TMP36 Sensor Project](Screenshot_2025-07-23_173724.png)

### 📝 Description:
This project uses a TMP36 analog temperature sensor to read ambient temperature. The reading is then converted to voltage and displayed on a 16x2 LCD screen using the `LiquidCrystal` library.

### 🧩 Components Used:
- Arduino Uno
- TMP36 temperature sensor
- 16x2 LCD display
- Potentiometer (for adjusting LCD contrast)
- Resistor
- Breadboard and jumper wires

### 🔌 Input Type:
✅ **Analog Input**  
- The temperature sensor is connected to **A0**, which is an analog input pin.

---

## 📌 Project 2: Motion Detection with PIR Sensor, Buzzer, and LEDs

🔗 [Tinkercad Project Link](https://www.tinkercad.com/things/2cpHcDg5uLf/editel?returnTo=%2Fdashboard)

### 📸 Project Image  
![PIR Motion Sensor Project](Screenshot_2025-07-23_181341.png)

### 📝 Description:
This project utilizes a PIR motion sensor to detect movement. When motion is detected, a buzzer sounds and an LED indicator lights up. It's useful for simple intrusion or presence detection.

### 🧩 Components Used:
- Arduino Uno
- PIR motion sensor
- Red and Green LEDs
- Buzzer
- Resistors
- Breadboard and jumper wires

### 🔌 Input Type:
✅ **Digital Input**  
- The PIR sensor is connected to a **digital pin (D2)**.
