<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1a1a2e,100:16213e&height=190&section=header&text=Embedded%20Systems%20%26%20IoT%20Engineer&fontSize=30&fontColor=00b4d8&fontAlignY=40&desc=Final-Year%20E%26TC%20%7C%20Microcontrollers%20%7C%20IoT%20Protocols%20%7C%20PCB%20Design&descSize=14&descAlignY=62&descColor=90e0ef&animation=fadeIn" width="100%" />

</div>

---

## Profile

Final-year Electronics and Telecommunication Engineering student focused on embedded firmware, IoT automation, and hardware-software integration. I build reliable firmware for microcontrollers, interface sensors and peripherals, and design IoT pipelines that connect hardware to cloud and mobile platforms.

Currently working at **Swayog Energy** on IoT-driven solar energy monitoring and automation systems. Actively studying RTOS and Linux drivers to grow toward production-grade embedded engineering.

---

## Engineering Focus

- Embedded firmware development for microcontroller-based systems
- Sensor interfacing and data acquisition over I2C, SPI, and UART
- IoT communication pipelines using MQTT and REST
- Real-world automation logic for energy and monitoring applications
- Hardware-software integration from bare-metal to cloud dashboard

---

## Skills

<table>
<tr>
<td valign="top" width="50%">

### Embedded and Electronics

![ESP32](https://img.shields.io/badge/ESP32-003B57?style=flat-square&logo=espressif&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00878A?style=flat-square&logo=arduino&logoColor=white)
![STM32](https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white)
![8051](https://img.shields.io/badge/8051-555555?style=flat-square)

![UART](https://img.shields.io/badge/UART-4A90D9?style=flat-square)
![I2C](https://img.shields.io/badge/I2C-4A90D9?style=flat-square)
![SPI](https://img.shields.io/badge/SPI-4A90D9?style=flat-square)
![MQTT](https://img.shields.io/badge/MQTT-660099?style=flat-square&logo=mqtt&logoColor=white)
![HTTP REST](https://img.shields.io/badge/HTTP%20REST-005C84?style=flat-square)

![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00427E?style=flat-square&logo=cplusplus&logoColor=white)
![Embedded C](https://img.shields.io/badge/Embedded%20C-2C3E50?style=flat-square)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

![KiCad](https://img.shields.io/badge/KiCad-314CB0?style=flat-square&logo=kicad&logoColor=white)
![Proteus](https://img.shields.io/badge/Proteus-1B2A6B?style=flat-square)
![LTspice](https://img.shields.io/badge/LTspice-8B0000?style=flat-square)

![ESP-IDF](https://img.shields.io/badge/ESP--IDF-E7352C?style=flat-square&logo=espressif&logoColor=white)
![Arduino IDE](https://img.shields.io/badge/Arduino%20IDE-00878A?style=flat-square&logo=arduino&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

</td>
<td valign="top" width="50%">

### Data and Automation

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)

![Node-RED](https://img.shields.io/badge/Node--RED-8F0000?style=flat-square&logo=nodered&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

**Applied in embedded and IoT context:**
- Sensor data cleaning and preprocessing
- Time-series analysis for energy parameter trends
- Anomaly detection on telemetry streams
- Automating decisions from sensor thresholds via Node-RED
- Visualizing MQTT payload logs with Python

</td>
</tr>
</table>

---

## Projects

### IoT-Based Solar Energy Monitoring and Automation System

`ESP32` `MQTT` `Mosquitto` `Node-RED` `I2C` `Python`

ESP32-based system designed for real-world solar installations.

- Acquired voltage, current, and environmental sensor data
- Implemented MQTT-based telemetry using Mosquitto broker
- Built Node-RED flows for real-time monitoring and automation
- Designed logic for automated solar panel cleaning triggers
- Ensured reliable communication using reconnect handling and QoS mechanisms

Focus: reliability, real-time monitoring, and deployable automation

---

### Custom PCB — Sensor Acquisition Node

`KiCad` `ESP32-WROOM` `ACS712` `DHT22` `LDO Regulation`

Two-layer PCB designed for standalone field deployment. Integrates 3.3V power regulation, ESP32 module footprint, screw terminal connectors, and sensor pads for current and temperature measurement. Full DRC clearance with EMI-conscious layout before prototyping.

---

### ESP32 to Mobile App via REST and MQTT

`ESP32` `HTTP POST` `MQTT` `Android`

Dual-channel communication system — ESP32 publishes live sensor readings over MQTT for real-time display and sends periodic summaries via HTTP POST to a backend endpoint. Mobile interface consumes both channels. Emphasis on a clean device-side API layer that decouples hardware from application logic.

---

## What I Build

- Embedded firmware for ESP32-based systems
- Sensor-driven data acquisition systems
- IoT telemetry pipelines using MQTT and REST
- Automation systems for real-world applications — energy monitoring, control, and remote management
- Hardware-software integrated solutions with cloud dashboards

---

## Skills in Progress

| Area | What I am studying |
|---|---|
| FreeRTOS | Task scheduling, semaphores, queues, interrupt-safe IPC on ESP32 via ESP-IDF |
| Linux Drivers | Character device model, sysfs, kernel-userspace interface — following LDD3 |
| ESP-IDF Native | Moving beyond Arduino abstraction for direct RTOS and BLE/Wi-Fi stack control |
| Bare-Metal Protocols | Bit-bang I2C and SPI to understand hardware timing without library abstraction |

---

## Engineering Approach

- Prefer structured firmware over quick scripts
- Focus on system reliability and communication stability
- Design with real deployment constraints in mind
- Separate hardware logic and communication layers for scalability
- Continuously improving toward RTOS-based and production-grade systems

---

## Goal

To work as an embedded firmware engineer on systems where hardware reliability and software correctness are both critical — energy electronics, industrial IoT, or automotive embedded. Building toward production firmware with RTOS concurrency, clean protocol design, and solid hardware abstraction.

---

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:your@email.com)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:16213e,50:1a1a2e,100:0d1117&height=100&section=footer&animation=fadeIn" width="100%" />

</div>
