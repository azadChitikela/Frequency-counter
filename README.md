# Frequency-counter
Embedded Frequency Counter using Keil uVision &amp; Embedded C  A precise digital frequency counter project built in Keil uVision, measuring real-time signal frequencies via microcontroller timers/counters. Certified project.
# ⏱️ Microcontroller-Based Frequency Counter

An embedded system project designed to measure and display signal frequencies in real-time. Built and simulated using **Keil µVision IDE** in **Embedded C**.

🏆 **Certificate of Completion / Achievement Earned**

---

## 🚀 Overview
This project implements a digital frequency counter using internal timers/counters of a microcontroller. It measures incoming digital/pulse signals over a fixed gate time window and calculates the frequency ($f = \frac{N}{t}$).

### Key Features
* **Accurate Frequency Measurement:** Measures incoming signal pulses per unit time.
* **Timer/Counter Integration:** Configured microcontroller hardware timers for pulse capture and gate-time control.
* **Keil Simulation & Debugging:** Verified timing accuracy and signal edge detection using Keil µVision logic analyzer and debugger.
* **Display Output:** Interfaces with an LCD/7-segment display (or Virtual Terminal) for live frequency readouts.

---

## 🛠️ Tech Stack & Hardware
* **IDE:** Keil µVision
* **Language:** Embedded C / Assembly
* **Microcontroller:** [e.g., LPC1768 / 8051 / STM32]
* **Simulation Tool:** [e.g., Proteus / Keil Logic Analyzer]

---

## 📊 How It Works
1. **Gate Time Setup:** Timer 0 generates a precise time window (e.g., 1 second).
2. **Pulse Counting:** Timer 1 operates as a counter in external clock mode to count incoming rising edges.
3. **Calculation:** Once the gate time expires, the total pulse count is read, processed, and formatted.
4. **Output:** Results are updated and displayed continuously.

---

## 📜 Certification
This project was completed as part of [Course/Organization Name, e.g., Embedded Systems Certification], demonstrating proficiency in hardware timers, embedded interrupts, and Keil development tools.

*(Optional: Add image/scan of certificate or project schematic in the repository assets)*
