<p align="right"><strong>English</strong> · <a href="contactless-vitals.zh-CN.md">简体中文</a></p>

# Contactless vital-sign monitoring prototype

**Student project · North University of China · 2023**

This project explored how to observe respiration and heart-rate signals without attaching electrodes to the subject. We built a demonstration device around a millimeter-wave radar, an ESP32, a network connection, and a remote viewing interface.

## System flow

```mermaid
flowchart LR
    A[Millimeter-wave radar] --> B[ESP32 processing]
    B --> C[MQTT transmission]
    C --> D[Remote viewing interface]
```

The prototype combined sensing, data handling, and remote display in one workflow. My role was project lead: I organized the work and participated in integrating the device connection and viewing path. This was collaborative student work, not a solo build.

## What the records show

- A physical prototype and its device connection were presented in my 2026 personal portfolio.
- The team received a **second prize in the 2023 Beidou Cup regional contest** for a related contactless respiration and heart-rate device that included Beidou short-message communication.
- The team received a **third prize in the 2023 Chinese Collegiate Computing Competition, Shanxi round**, for the contactless monitoring device.

The contest titles describe the submitted versions. The system diagram above describes the ESP32, radar, and MQTT demonstration documented in my later portfolio; it should not be read as a complete schematic for every competition version.

## Current boundary

This is a student demonstration prototype. The available project record does not establish clinical performance or a measurement accuracy figure, and no medical-use claim is made here. A reproducible public release would need circuit files, firmware, test conditions, and measurement data.

[← Back to profile](../README.md)
