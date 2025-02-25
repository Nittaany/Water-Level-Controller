# Water Level Monitoring & Pump Control System

This mini project was developed as part of our **Computer Organization and Architecture** and **Design Thinking and Management** courses. It’s a fun, practical project that integrates both hardware and software, featuring a working model that monitors water levels and controls a pump automatically—with a manual override option.

---

## Overview

The project uses an ultrasonic sensor to measure the water level in a container and displays the level as a percentage on an I²C LCD. A pump is controlled based on the water level: it automatically turns on when the water level drops below a threshold (30%) and turns off when nearly full (above 99%). Users can also calibrate the system and manually override the pump status using buttons. The calibration data is stored in EEPROM.

---

## Features

- **Water Level Measurement:**  
  Measures water level with an ultrasonic sensor and converts the readings into a percentage based on a user-defined calibration value.
  
- **Automatic & Manual Pump Control:**  
  - **Automatic Mode:** The pump is activated when water level is low and deactivated when near capacity.  
  - **Manual Mode:** Allows users to toggle the pump on/off regardless of water level.

- **Calibration:**  
  Users can calibrate the maximum water level, with the value saved in EEPROM for persistence.

- **Real-Time Feedback:**  
  Displays water level percentage, pump status (ON/OFF), and mode (MANUAL/AUTO) on an I²C LCD.

---

## Hardware & Software

### Hardware Components

- Ultrasonic Sensor (for water level measurement)
- Arduino (or compatible microcontroller)
- I²C LCD Display
- Water Pump (controlled via a relay)
- Push Buttons (for manual control and calibration)
- Supporting hardware for the working model

### Software Components

- **Programming Language:** C/C++ (Arduino)
- **Libraries:**  
  - `EEPROM`
  - `Wire`
  - `LiquidCrystal_I2C`

---

## Demo & Documentation

- **Working Demo Video:**  
  [Watch the Demo](https://link-to-demo-video.com)  
  *(Replace with your actual demo video link)*

- **Photo of the Model:**  
  ![Model Photo](https://link-to-model-photo.com)  
  *(Replace with your actual photo link)*

- **Project Report:**  
  [Download Project Report](https://link-to-project-report.com)  
  *(Replace with your actual report link)*

- **IEEE Paper:**  
  [Download IEEE Paper](https://link-to-ieee-paper.com)  
  *(Replace with your actual IEEE paper link)*

---

## Getting Started

### Prerequisites

- Arduino IDE installed on your computer.
- Required Arduino libraries (use the Library Manager in Arduino IDE to install if not already available).

### How to Upload

1. **Connect** your Arduino board to your computer.
2. **Open** the project file in the Arduino IDE.
3. **Select** the correct board and port under the Tools menu.
4. **Verify** the code to check for errors.
5. **Upload** the code to your Arduino board.

---

## Acknowledgements

This project was developed as part of the **Computer Organization and Architecture** and **Design Thinking and Management** courses. Special thanks to our mentors and team members for their support and contributions in building the working hardware model.

---

## License

This project is open-source. Feel free to use, modify, and share it under your preferred license.


# Water-Level-Controller
