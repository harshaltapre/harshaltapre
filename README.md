<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1a1a2e,100:16213e&height=200&section=header&text=Embedded%20Systems%20%26%20IoT%20Engineer&fontSize=32&fontColor=00b4d8&fontAlignY=40&desc=Final-Year%20E%26TC%20Student%20%7C%20Microcontrollers%20%7C%20IoT%20Protocols%20%7C%20PCB%20Design&descSize=15&descAlignY=62&descColor=90e0ef&animation=fadeIn" width="100%" />

</div>

---

## About Me

I am a final-year Electronics and Telecommunication Engineering student with a focused interest in embedded systems, IoT automation, and hardware-software integration. My work is centered on building reliable firmware for microcontrollers, interfacing sensors and peripherals, and designing IoT pipelines that bridge hardware with cloud or mobile platforms.

Currently gaining hands-on industry experience at **Swayog Energy**, where I am developing IoT-driven automation systems for energy applications. I am actively working toward deepening my expertise in RTOS-based firmware design and Linux driver development — areas I consider critical for professional embedded engineering.

I value clean, well-structured code, correct hardware abstraction, and a disciplined approach to debugging and testing.

---

## Technical Skills

### Microcontrollers and Embedded Hardware

![ESP32](https://img.shields.io/badge/ESP32-Espressif-003B57?style=flat-square&logo=espressif&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-AVR%20%7C%20ARM-00878A?style=flat-square&logo=arduino&logoColor=white)
![STM32](https://img.shields.io/badge/STM32-ARM%20Cortex--M-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white)
![8051](https://img.shields.io/badge/8051-Assembly%20%7C%20Embedded%20C-555555?style=flat-square)

### Communication Protocols

![UART](https://img.shields.io/badge/UART-Serial-4A90D9?style=flat-square)
![I2C](https://img.shields.io/badge/I2C-Two--Wire-4A90D9?style=flat-square)
![SPI](https://img.shields.io/badge/SPI-Four--Wire-4A90D9?style=flat-square)
![MQTT](https://img.shields.io/badge/MQTT-Telemetry%20Protocol-660099?style=flat-square&logo=mqtt&logoColor=white)
![HTTP](https://img.shields.io/badge/HTTP-REST%20API-005C84?style=flat-square)

### Programming Languages

![C](https://img.shields.io/badge/C-Embedded%20%7C%20Firmware-00599C?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-Arduino%20%7C%20IDF-00427E?style=flat-square&logo=cplusplus&logoColor=white)
![Embedded C](https://img.shields.io/badge/Embedded%20C-Bare%20Metal-2C3E50?style=flat-square)
![Python](https://img.shields.io/badge/Python-IoT%20%7C%20Scripting-3776AB?style=flat-square&logo=python&logoColor=white)

### PCB and Circuit Design

![KiCad](https://img.shields.io/badge/KiCad-PCB%20Design-314CB0?style=flat-square&logo=kicad&logoColor=white)
![Proteus](https://img.shields.io/badge/Proteus-Simulation-1B2A6B?style=flat-square)
![LTspice](https://img.shields.io/badge/LTspice-Circuit%20Analysis-8B0000?style=flat-square)

### Tools and Environment

![Arduino IDE](https://img.shields.io/badge/Arduino%20IDE-Development-00878A?style=flat-square&logo=arduino&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-Editor-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)
![Git](https://img.shields.io/badge/Git-Version%20Control-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-Ubuntu%20%7C%20CLI-FCC624?style=flat-square&logo=linux&logoColor=black)
![ESP-IDF](https://img.shields.io/badge/ESP--IDF-Espressif%20Framework-E7352C?style=flat-square&logo=espressif&logoColor=white)

---

## Projects

### 1. IoT-Based Energy Parameter Monitoring System

**Stack:** ESP32, MQTT, Mosquitto Broker, Node-RED, Python  
**Protocols:** I2C, Wi-Fi, MQTT

Designed a full IoT pipeline for real-time monitoring of electrical parameters. The ESP32 node reads sensor data at configurable intervals, structures it as JSON, and publishes to an MQTT broker. Node-RED subscribes to topics and routes data to a dashboard for visualization. Implemented reconnection logic, heartbeat messages, and a retained-message strategy for last-known-state recovery.

**Key aspects:** Bare-metal sensor driver, MQTT QoS 1 delivery, structured topic design, live dashboard integration.

---

### 2. Custom PCB for Sensor Acquisition Node

**Stack:** KiCad, ESP32-WROOM, ACS712, DHT22, Voltage Divider  
**Domain:** PCB Design and Hardware Prototyping

Designed a two-layer PCB for a standalone sensor acquisition node intended for energy monitoring deployments. The board integrates power regulation (3.3V LDO), onboard ESP32 module footprint, screw terminal connectors for field wiring, and dedicated pads for current and temperature sensors. Conducted DRC and design review in KiCad before prototyping.

**Key aspects:** Schematic capture, component selection, DRC clearance, practical layout for EMI mitigation.

---

### 3. ESP32 to Mobile App Integration via REST and MQTT

**Stack:** ESP32, HTTP REST API, MQTT, Android (MIT App Inventor / Flutter basics)  
**Protocols:** Wi-Fi, HTTP POST, MQTT Publish/Subscribe

Built a dual-channel communication system where the ESP32 publishes live sensor data over MQTT for real-time display and sends periodic summaries via HTTP POST to a backend endpoint. A mobile interface subscribes to the MQTT feed for live readings and fetches historical logs via REST. Focused on designing a clean device-side API layer that decouples the hardware from the application logic.

**Key aspects:** Protocol selection rationale, payload schema design, mobile-hardware interface, modular firmware architecture.

---

## Skills in Progress

I am actively studying the following areas to grow toward professional-grade embedded engineering:

**FreeRTOS and RTOS Concepts**  
Studying task scheduling, semaphores, mutexes, queues, and interrupt-safe IPC using FreeRTOS on ESP32. Working through the official FreeRTOS documentation and ESP-IDF RTOS examples to understand preemptive multitasking in constrained systems.

**Linux Device Drivers**  
Exploring character device drivers in Linux, the driver model, and sysfs interfaces. Following LDD3 (Linux Device Drivers, 3rd ed.) and kernel documentation to understand how userspace communicates with hardware through the kernel.

**ESP-IDF (Native Framework)**  
Transitioning from Arduino abstraction to native ESP-IDF development for finer control over FreeRTOS tasks, NVS, and BLE/Wi-Fi stacks.

**Low-Level Protocol Implementation**  
Implementing I2C and SPI bit-bang drivers from scratch to understand timing constraints and hardware behavior independent of library abstractions.

---

## What I Am Building Toward

My goal is to work as an embedded firmware engineer on systems where hardware reliability and software correctness are both critical — energy electronics, industrial IoT, or automotive embedded domains. I am building toward writing production firmware that handles concurrency with RTOS, communicates through well-defined protocols, and integrates cleanly with higher-level systems.

---

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com)
[![GitHub](https://img.shields.io/badge/GitHub-Profile-181717?style=flat-square&logo=github&logoColor=white)](https://github.com)
[![Email](https://img.shields.io/badge/Email-Contact-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:your@email.com)

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:16213e,50:1a1a2e,100:0d1117&height=100&section=footer&animation=fadeIn" width="100%" />

</div>
