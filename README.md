# Varro Companion

**Status:** Planned  
**Technologies:** ESP32 · Embedded C/C++ · Bluetooth · I²S Audio · Battery Power

## Overview

Varro Companion is a portable, battery-powered microphone and speaker device for the Varro assistant. I am designing it as a lightweight voice accessory that connects over Bluetooth to Varro Mobile, which relays audio and commands to the backend.

The **Varro** name honors Marcus Terentius Varro, a Roman scholar known for collecting and organizing knowledge.

## Key Design Choices

- **Phone-assisted networking:** Use the mobile app as the network gateway rather than connecting the device directly to Varro services.
- **Minimal on-device processing:** Handle audio capture, playback, and possible wake-word or voice-activity detection locally; offload transcription and synthesis.
- **Battery-first hardware:** Prioritize low-power operation, sleep/wake behavior, and responsive activation.
- **Separate firmware:** Keep the portable device's firmware and hardware design independent of the networked Voice Station.

## Roadmap

- [ ] Select the microcontroller, battery, and audio components.
- [ ] Prototype microphone capture and speaker playback.
- [ ] Establish Bluetooth audio and control communication with Varro Mobile.
- [ ] Add activation and power-management behavior.
- [ ] Validate latency, reliability, and battery life.

## Usage

### Requirements

### Setup

### Configuration

### Operation
