# RF Signal Interference Analysis Using 433 MHz ASK Modules
## Overview

This project investigates RF signal interference behavior using 433 MHz ASK (Amplitude Shift Keying) transmitter and receiver modules with a Raspberry Pi Pico W microcontroller.

The system was designed to analyze how interference affects wireless communication in the 433 MHz ISM band by operating two transmitters simultaneously and measuring the receiver response under multiple experimental conditions.

The project also explores the limitations of bare ASK modules for structured digital communication without encoding and decoding circuitry.

---

## Objectives

- Set up a 433 MHz ASK RF communication link
- Simulate RF interference using a secondary transmitter
- Analyze signal degradation under interference conditions
- Perform pattern-based signal detection experiments
- Study the limitations of unencoded ASK communication
- Propose improvements for reliable RF analysis systems

---

## Hardware Used

- Raspberry Pi Pico W
- 433 MHz ASK RF Transmitter Modules
- 433 MHz ASK RF Receiver Module
- LED Indicator
- 330 Ω Resistor
- Quarter-wave wire antennas (~17 cm)
- USB Power Supply

---

## Topics Covered

- ASK Modulation
- RF Interference
- Noise in Digital RF Systems
- Pattern Detection
- Signal Stability Analysis
- Carrier-to-Interference Concepts
- Wireless Communication Limitations

---

## Experimental Modes

### 1. Clean Link Mode
Simulates ideal transmission conditions with minimal interference.

### 2. Co-channel Noise Mode
Introduces interference from another transmitter operating at the same frequency.

### 3. Burst Interference Mode
Simulates sudden short-duration interference spikes.

### 4. Multipath Fading Mode
Studies signal fluctuations caused by reflections and propagation effects.

### 5. Thermal Drift Mode
Analyzes slow signal variations caused by temperature-related drift.

---

## Key Findings

- Receiver output fluctuated significantly even under clean conditions.
- Bare ASK modules produced pseudo-random outputs without encoding.
- Interference effects were difficult to distinguish statistically.
- Pattern detection accuracy remained close to random chance.
- Reliable RF communication requires structured protocols and synchronization.

---

## Future Improvements

- HT12E / HT12D Encoder-Decoder Integration
- NRF24L01 Transceiver Upgrade
- Manchester Encoding
- SDR-Based Spectrum Analysis
- Improved Antenna Matching
- Shielded RF Testing Environment
