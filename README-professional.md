# YaJie Li

**Embedded Systems Developer — STM32 firmware, IoT sensing & connected devices**

I design and build firmware for sensor-driven devices — from bare-metal STM32 code to MQTT cloud connectivity.

---

## About

Embedded developer focused on STM32-based sensing devices. My main work is a smart bracelet system on STM32F103 that fuses heart-rate / SpO2 sensing (MAX30102), motion, step counting and fall detection (MPU6050), and environmental sensing (DHT11, ADC), with ESP8266 + MQTT connectivity to the OneNET cloud. I also build battery management firmware for 18650 cells, experiment with vision on Raspberry Pi 5, and maintain AI-assisted coding tooling.

## Core Competencies

| Area | Skills |
| --- | --- |
| Firmware | C · STM32F103 · STM32 HAL / CMSIS · STM32CubeMX · Keil MDK-ARM · ST-Link |
| Sensors & IoT | MAX30102 (heart rate / SpO2) · MPU6050 (motion / fall detection) · DHT11 · ESP8266 · MQTT · OneNET |
| Edge & Systems | Raspberry Pi 5 · Linux · Python |
| Tools & Workflow | Git / GitHub · TypeScript · Node.js |

## Featured Projects

### [Smart Bracelet System](https://github.com/Lgun-code/stm32-)

智能手环系统 — a multi-sensor smart bracelet built on STM32F103, developed as my graduation project.

- Multi-sensor fusion: heart rate and SpO2 (MAX30102), steps, calories and fall detection (MPU6050), temperature / humidity (DHT11), smoke and light via ADC
- Four-page OLED UI with key interaction, configurable thresholds and buzzer alarm
- ESP8266 + MQTT connection to OneNET, with cloud attribute reporting and downlink parameter control

`C` `STM32F103` `HAL` `Keil MDK-ARM` `MQTT / OneNET`

*Also: [a lightweight variant](https://github.com/Lgun-code/888money-final) with a reduced sensor set and the same OneNET data model.*

### [STM32 18650 Battery Management System](https://github.com/Lgun-code/-)

基于 STM32 的 18650 锂电池充放电管理系统 — charge / discharge management and testing firmware for 18650 lithium cells.

- STM32-based monitoring and control for lithium battery charge and discharge
- CubeMX-generated configuration with a Keil MDK-ARM project structure

`C` `STM32` `STM32CubeMX` `Keil MDK-ARM`

### [Codex ChatGPT Bridge](https://github.com/Lgun-code/codex-chatgpt-bridge)

A compatibility distribution I maintain of Codex with ChatGPT — ChatGPT web acts as the planning and review layer, while Codex keeps full control of local execution.

- Read-only by design: ChatGPT inspects the workspace through eight read-only tools; it cannot write, delete, or run shell commands
- Quick Tunnel compatibility fixes for ordinary HTTP-proxy networks on Windows
- OAuth 2.1 + PKCE security model, with credentials and secrets denied by default

`TypeScript` `Node.js` `Cloudflare Tunnel`

*Based on the original [XiaoDuoYa/codex-with-chatgpt](https://github.com/XiaoDuoYa/codex-with-chatgpt) project, released under the MIT License.*

## Learning Lab

- **[rpi5_vision_project](https://github.com/Lgun-code/rpi5_vision_project)** — my first Linux project on Raspberry Pi 5, and the starting point for edge vision experiments. In progress.

## GitHub Stats

<img height="160" src="https://github-readme-stats.vercel.app/api?username=Lgun-code&show_icons=true" alt="GitHub stats" />

## Contact

- GitHub: [@Lgun-code](https://github.com/Lgun-code)
