# Varro Companion

**Status:** Planned  
**Technologies:** Mobile Development · Bluetooth Low Energy · Audio Streaming · HTTP APIs

## Overview

Varro Companion is a mobile application that connects a portable ESP32 voice device to the self-hosted Varro assistant. I am designing it to relay audio and controls through the phone's network connection while providing a convenient interface for interactions with the assistant.

The **Varro** name references Marcus Terentius Varro, a Roman scholar whose work spanned many disciplines.

## Key Design Choices

- **Bluetooth bridge:** Connect to the voice device and transport audio and control messages.
- **Server-side processing:** Forward speech to backend services rather than running large models on the phone or microcontroller.
- **Shared conversations:** Keep authoritative chat state and memory in the orchestrator.
- **Independent client:** Develop and deploy the mobile application separately from firmware and backend services.

## Roadmap

- [ ] Select the mobile platform and define Bluetooth messages.
- [ ] Establish reliable device pairing and audio transport.
- [ ] Connect voice sessions to Varro's server APIs.
- [ ] Add basic session controls and interaction feedback.
- [ ] Validate end-to-end use over mobile networks.

## Usage

### Requirements

### Setup

### Configuration

### Operation
