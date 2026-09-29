# Connor Carlisle

**Electrical Engineering, University of Mississippi (B.S. expected May 2028)** · Honors College · GPA 3.7

Audio DSP · Embedded Systems · Hardware Design

Seeking a **Summer 2027 internship** in DSP, embedded firmware, or hardware design.

📬 carlisleconnor2@gmail.com · [LinkedIn](https://www.linkedin.com/in/connor-carlisle) · [Handshake](https://app.joinhandshake.com/profiles/connorcarlisle)

---

## Featured Projects

### 🎧 LMS Adaptive Noise Canceller — *in progress*
Python/NumPy simulation → fixed-point real-time port on STM32F446RE

- Simulation harness tests LMS convergence rate, misadjustment, and weight-error floor against closed-form theory
- **Phase 1 (white noise): 8/8 gates passed · Phase 2 (colored noise): 7/7 gates passed**
- Per-eigenmode analysis of the 64-tap input autocorrelation matrix; log-linear fits misestimate colored-noise time constants by 37–47%, replaced with projection onto the λ<sub>min</sub> eigenvector
- Next: two-channel recorded-audio analysis, then real-time on STM32 with two SPH0645 I²S MEMS mics and a UDA1334A I²S DAC in a 1 m duct rig
- Precursor to a senior-year FxLMS active noise control capstone

➡️ [Repository](https://github.com/connor-carlisle/lms-noise-canceller)

### ⚡ Synchronous Buck Converter — TI LM5145 · *prototype built, bench validation next*
- 24 V → 5 V, 3 A, 500 kHz, voltage-mode control, Type III compensation
- 4-layer board (Top / GND / PWR / Bottom), hot loop placed first
- Predicted efficiency ~82%

➡️ [Repository](https://github.com/connor-carlisle/Synchronous-Buck-DC-Converter)

### 🔊 Stereo Bluetooth Amplifier — Microchip BM83 + TI TPA3116D2 · *prototype built, bench validation next*
- 2 × 50 W into 4 Ω class-D, BTL LC output filters, hierarchical schematic
- Mixed-signal star grounding and RF keep-out for the BM83 antenna

➡️ [Repository](https://github.com/connor-carlisle/bm83-tpa3116-bluetooth-speaker)

---

## Tools

**Languages:** Python (NumPy) · C (embedded) · C++ · MATLAB · SystemVerilog
**Embedded:** STM32 (F4) · I²S audio
**EDA & Hardware:** Altium Designer · Xilinx Vivado · LTspice · KiCad · Oscilloscope · Logic Analyzer · Hand SMD assembly
**DSP:** LMS/NLMS adaptive filtering · FIR filters · autocorrelation eigen-analysis

---

## Outside the Lab
Classical cellist, 10+ years (first chair, LOU Orchestra; Memphis Youth Symphony). Electronic music producer and performer as **LEDGXR**.
