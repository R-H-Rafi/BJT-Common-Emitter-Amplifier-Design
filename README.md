# BJT Common Emitter Amplifier Design and Simulation

![Electronics](https://img.shields.io/badge/Electronics-Analog%20Design-blue)
![BJT](https://img.shields.io/badge/Circuit-BJT%20Amplifier-green)
![Simulation](https://img.shields.io/badge/Software-TINA--TI-orange)
![Status](https://img.shields.io/badge/Status-Completed-success)

## Project Overview

This project focuses on the design, simulation, and analysis of a BJT (Bipolar Junction Transistor) Common Emitter Amplifier using TINA-TI simulation software.

The objective was to study transistor biasing, signal amplification, voltage gain characteristics, and output waveform behavior of a single-stage common emitter amplifier circuit.

The project was completed as part of the Electronics-II laboratory coursework.

---

## Objectives

- Design a Common Emitter Amplifier using an NPN transistor
- Establish proper DC biasing conditions
- Analyze AC signal amplification
- Observe input and output waveforms
- Evaluate amplifier performance
- Understand the role of coupling and bypass capacitors

---

## Circuit Components

| Component | Purpose |
|------------|------------|
| BC547C Transistor | Main amplifying device |
| R1, R2 | Voltage divider bias network |
| Rc (Collector Resistor) | Controls collector current and voltage gain |
| Re (Emitter Resistor) | Provides thermal stability |
| C1 | Input coupling capacitor |
| C2 | Output coupling capacitor |
| C3 | Emitter bypass capacitor |
| VCC | DC Power Supply |
| AC Source | Input signal source |

---

## Circuit Operation

The amplifier operates in the active region of the transistor.

### Biasing Network

R1 and R2 form a voltage divider network that provides the required base bias voltage to maintain proper transistor operation.

### Signal Amplification

A small AC signal is applied through the input coupling capacitor (C1).

The transistor amplifies the signal, producing a larger output voltage across the collector resistor (Rc).

### Capacitor Functions

- C1 blocks DC while allowing the AC input signal to pass.
- C2 isolates the DC collector voltage from the output load.
- C3 bypasses the emitter resistor for AC signals, increasing voltage gain.

---

## Simulation Results

The simulation was performed using TINA-TI.

### Observations

- Stable transistor biasing was achieved.
- AC input signal was successfully amplified.
- Output waveform remained periodic and continuous.
- Proper operation of coupling and bypass capacitors was verified.
- The amplifier demonstrated expected Common Emitter characteristics.

### Waveform Analysis

The simulation graph displays:

- X-axis → Time (s)
- Y-axis → Voltage (V)

The periodic waveform confirms successful amplification of the input AC signal.

The output signal exhibits the characteristic behavior of a Common Emitter amplifier.

---

## Key Concepts Demonstrated

- Transistor Biasing
- Small Signal Amplification
- Common Emitter Configuration
- Voltage Gain
- Capacitive Coupling
- Frequency Response Fundamentals
- Analog Circuit Design
- Electronic Circuit Simulation

---

## Software Used

- TINA-TI
- Electronic Circuit Analysis Tools

---

## Project Files

```text
.
├── BJT Circuit Design.TSC
├── Circuit Screenshot.png
├── Calculation Report.pdf
└── README.md
```

---

## Learning Outcomes

Through this project, I gained practical experience in:

- BJT transistor operation
- Amplifier circuit design
- Analog electronics fundamentals
- Circuit simulation techniques
- Biasing network calculations
- Waveform analysis
- Electronic circuit troubleshooting

---

## Author

### Md. Redowanul Haq Rafi

Computer Science & Engineering Student

### Areas of Interest

- Cybersecurity
- Ethical Hacking
- Penetration Testing
- Network Security
- Routing & Switching
- Cloud Security
- Security Operations

---

## Academic Note

This project was developed as part of Electronics-II laboratory coursework for educational purposes. The design and simulation were performed to understand the practical operation of BJT-based amplifier circuits and analog electronic systems.
