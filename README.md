# Quadrature Down Converter

This project presents the design and analysis of a **Quadrature Down Converter**, a critical component in modern wireless communication systems. It is used to extract in-phase (I) and quadrature-phase (Q) components from a received RF signal, facilitating efficient demodulation of complex modulation schemes.

## Overview

A Quadrature Down Converter consists of the following primary components:

- **Quadrature Oscillator**: Generates two sine waves 90° out of phase (I/Q components).
- **Mixer**: Multiplies the received RF signal with each of the oscillator signals.
- **Low Pass Filter**: Filters out high-frequency components to isolate baseband signals.

The full circuit was simulated using **LTSpice** and implemented using basic analog components such as op-amps and NMOS transistors.

---

## Features

- Accurate 90° phase shift using a phase shift oscillator.
- NMOS switch-based mixer implementation.
- RC-based low-pass filters with ~2kHz cutoff for clean baseband signal extraction.
- Functional integration of I and Q branches for full down-conversion.

---

## Repository Contents

- `Final Report.pdf` – Full documentation and results of simulations & hardware tests.
- `Mid Eval Report.pdf` – Intermediate evaluation insights.

---

## Key Results

- Oscillator frequency: ~96–100 kHz
- FFT analysis confirmed correct extraction of I/Q signals.
- -3dB cutoff at 2kHz achieved in low-pass filter.
- Verified both simulated and hardware outputs for all components.

---

## Applications

Quadrature Down Converters are widely used in:
- **Wireless Receivers (LTE, Wi-Fi, 5G)**
- **Software Defined Radios (SDRs)**
- **IQ Demodulation**
- **Digital Signal Processing Pipelines**

---

> *For simulation files, circuit schematics, or questions, feel free to raise an issue or reach out directly.*
