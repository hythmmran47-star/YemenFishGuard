# YemenFish Guard

**Systems project for cold-chain monitoring and seafood traceability**

YemenFish Guard explores how seafood transport conditions can be monitored and recorded to support cold-chain integrity and traceability.

## System Overview

The design connects sensor telemetry from an ESP32-based monitoring unit to an MQTT broker, Node-RED processing flows, a monitoring dashboard, event alerts, and a QR-accessible seafood record.

## Main Components

- Temperature and humidity monitoring
- Load measurement and handling signals
- Door-state monitoring
- MQTT message transport
- Node-RED processing and alert workflows
- Local data logging and dashboard visualization
- QR-based digital seafood record

## Analysis and Design Focus

The project demonstrates requirements decomposition, system-component boundaries, telemetry flow design, event handling, operational monitoring, and traceability concepts.

## Repository Contents

- `YemenFishGuard.pdf` — project documentation.
- `YemenFish_SourceCode.zip` — source-code archive.

This repository documents a project prototype. Sensor readings and dashboard indicators should be validated against calibrated hardware and real operating conditions before operational use.
