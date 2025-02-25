# 💧 Water Level Monitoring & Pump Control System

<div align="center">
  <img src="https://link-to-your-model-photo.com" alt="Working Model" width="600" />
</div>

**Water Level Monitoring & Pump Control System** is a dynamic prototype developed as part of our **Computer Organization and Architecture** and **Design Thinking and Management** courses. This project combines both hardware and software to create a fully functional model that simulates water level detection and pump control in an innovative way.

---

## 🌟 Overview

This project employs an ultrasonic sensor to measure water level and automatically controls a pump—with the option for manual override. **Key highlights include:**

- **Accurate Measurement:** The sensor calculates water level percentage based on a calibrated value stored in EEPROM.
- **Smart Pump Control:** A motor-driven wheel (representing a water pump) starts rotating when the water level is low and stops when the level is full.
- **Prototype Innovation:** Instead of using real water, a paper model blocks the ultrasonic sensor to mimic the water level in a tank.

> **Check the image above for our working model!**

---

## 🚀 Features

- **Real-Time Monitoring:**  
  The ultrasonic sensor provides continuous water level readings, which are displayed on an I²C LCD.

- **Automatic & Manual Modes:**  
  The system switches to automatic pump control when water is low and allows manual override via push buttons.

- **Prototype Simulation:**  
  Our model uses a motor and wheel to simulate a water pump—when activated, the wheel spins (indicating water pumping), and it stops when the simulated tank is full.

> **Working Model Video Demo:**  
> [Watch the Demo](https://link-to-demo-video.com)

---

## 🔧 Hardware & Software

### Hardware Components

- **Ultrasonic Sensor:** Measures water level.
- **I²C LCD Display:** Shows water level, pump status, and operating mode.
- **Motor & Wheel:** Mimic a water pump; the wheel rotates when the pump is on.
- **Push Buttons & Switches:** Facilitate manual calibration and pump control.
- **Paper Tank Model:** Simulates water by blocking the ultrasonic sensor.

### Software Components

- **Platform:** Arduino (C/C++ programming)
- **Libraries Used:**
  - `EEPROM`
  - `Wire`
  - `LiquidCrystal_I2C`

---

## 📚 Documentation & Resources

- **Working Demo Video:** [Watch Here](https://link-to-demo-video.com)
- **Photo of the Model:**  
  ![Model Photo](https://link-to-your-model-photo.com)
- **Project Report:** [Download Report](https://link-to-project-report.com)
- **IEEE Paper:** [Download IEEE Paper](https://link-to-ieee-paper.com)

---

## ⚙️ Getting Started

### Prerequisites

- Arduino IDE installed with required libraries.
- Basic understanding of Arduino programming and electronic circuit assembly.

### Setup Instructions

1. **Assemble the Hardware:**  
   Follow the schematic to connect the ultrasonic sensor, LCD, motor, and push buttons to your Arduino.

2. **Upload the Code:**  
   Open the project in Arduino IDE, select the correct board and port, and upload the code.

3. **Calibrate & Run:**  
   Use the provided buttons to calibrate the system and observe real-time water level monitoring and pump control.

---

## 🙏 Acknowledgements

This project was developed during the **Computer Organization and Architecture** and **Design Thinking and Management** courses. We extend our gratitude to our mentors and team members for their invaluable support in both design and implementation.

---

## 📄 License

This project is open-source. Feel free to use, modify, and share it under your preferred license.
