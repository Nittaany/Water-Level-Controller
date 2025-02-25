# 💧 Water Level Monitoring & Pump Control System

**Water Level Monitoring & Pump Control System** is a dynamic prototype developed as part of our **Computer Organization and Architecture** and **Design Thinking and Management** courses. This project combines both hardware and software to create a fully functional model that simulates water level detection and pump control in an innovative way.

<div align="center">
  <img src="https://drive.google.com/uc?export=view&id=192H-Mnfk8emOOqGGc8QlU_KqVA1hWBod" alt="Working Model" width="600" />
</div>



> Find Documentation & Resources! 📚 

---

## 🌟 Overview

This project employs an ultrasonic sensor to measure water level and automatically controls a pump—with the option for manual override. **Key highlights include:**

- **Accurate Measurement:** The sensor calculates water level percentage based on a calibrated value stored in EEPROM.
- **Smart Pump Control:** A motor-driven wheel (representing a water pump) starts rotating when the water level is low and stops when the level is full.
- **Prototype Innovation:** Instead of using real water, a paper blocks the ultrasonic sensor to mimic the water level in a tank.

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
> [Watch the Demo](https://drive.google.com/file/d/1TBmy9M0k2LNoWJ65NNz6bQ8MHIUsC6q0/view?usp=drive_link)

---

## 🔧 Hardware & Software

### Hardware Components

- **Ultrasonic Sensor:** Measures water level.
- **I²C LCD Display:** Shows water level, pump status, and operating mode.
- **Motor & Wheel:** Mimic a water pump; the wheel rotates when the pump is on.
- **Paper Tank Model:** Simulates water by blocking the ultrasonic sensor.

### Software Components

- **Platform:** Arduino (C/C++ programming)
- **Libraries Used:**
  - `EEPROM`
  - `Wire`
  - `LiquidCrystal_I2C`

---

## 📚 Documentation & Resources

- **Working Demo Video:** [Watch Here](https://drive.google.com/file/d/1TBmy9M0k2LNoWJ65NNz6bQ8MHIUsC6q0/view?usp=drive_link)
- **Photo of the Model:**  
  ![Model Photo]

(https://drive.google.com/uc?export=view&id=192H-Mnfk8emOOqGGc8QlU_KqVA1hWBod)
- **IEEE Paper:** [Download IEEE Paper](https://drive.google.com/file/d/10rUBdXM_WwcKP4FapUVsXkZ6iGJeymsf/view?usp=sharing)

---

## ⚙️ Getting Started

### Prerequisites

- Arduino IDE installed with required libraries.
- Basic understanding of Arduino programming and electronic circuit assembly.

### Setup Instructions

1. **Assemble the Hardware:**  
   Follow the schematic to connect the ultrasonic sensor, LCD, motor, and push buttons to your Arduino._(Refer IEEE Paper for the circuit diagram)_

2. **Upload the Code:**  
   Open the project in Arduino IDE, select the correct board and port, and upload the code.

3. **Calibrate & Run:**  
   Use the provided buttons to calibrate the system and observe real-time water level monitoring and pump control.

---

## 🙏 Acknowledgements

This project was developed during the **Computer Organization and Architecture** and **Design Thinking and Management** courses. We extend our gratitude to our mentors and team members for their invaluable support in both design and implementation.

---

## 💌 Connect

Got feedback or suggestions? Feel free to reach out!

- **LinkedIn** → [Reach ME!](https://linkedin.com/in/satyam-c)

---

## 📄 License

This project is open-source. Feel free to use.
ENJOY😎
