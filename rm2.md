# DCzilla - DC DIY UPS Documentation

⚠️ Important Notice

**Personal Documentation:** This document is created for my personal use as a reminder and guide for the DCzilla DC UPS assembly procedure.

**No Liability:** I assume no responsibility for any components, modules, procedures described herein, or any resulting damage or injury.

**Use at Your Own Risk:** Users must verify all information independently and follow proper safety procedures.

For full disclaimer, see Legal Notice section at the end of this document.

# Overview

DCzilla is a custom DC UPS (Uninterruptible Power Supply) solution designed to provide multiple configurable DC outputs without the inefficiency of multiple voltage conversions (AC→DC, DC→AC, AC→DC). The system can simultaneously output different voltages (5V, 9V, 12V, 15V, 19V) to power various devices such as routers, switches, mini-PCs, and single-board computers.

The primary use case is to ensure uninterrupted power to home network infrastructure, including devices like Dell Optiplex Micro, Raspberry Pi, routers, and network switches.

# Key Features

- **Multiple outputs**: Up to 3 independent DC outputs, each configurable to 5V, 9V, 12V, 15V, or 19V
- **Smart battery management**: User-defined high/low voltage thresholds for automatic output control
- **Configurable timing**: Customizable power-up and power-down delays for safe shutdown sequences
- **Status monitoring**: Real-time status messages via COM port (Node-RED compatible)
- **Battery voltage monitoring**: Continuous battery voltage tracking
- **Modular design**: Uses pre-assembled DC-DC buck/boost converters and battery charging modules
- **Standard DC input**: 19-20V AC/DC supply (standard notebook adapter)
- **Lead-acid battery**: 12V, 7-9Ah SLA/VRLA battery (standard UPS type)
- **Fanless operation**: Silent operation without cooling fan
- **Compact design**: Width matches Dell Optiplex Micro (182mm)

# System Architecture

**Block Diagram**
