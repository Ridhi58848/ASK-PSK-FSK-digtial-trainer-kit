ASK–FSK–PSK Modulation Kit
📌 Overview

The ASK–FSK–PSK Modulation Kit is an educational hardware project designed to demonstrate the fundamental digital modulation techniques used in communication systems. The kit enables practical understanding of Amplitude Shift Keying (ASK), Frequency Shift Keying (FSK), and Phase Shift Keying (PSK) using standard ICs and analog circuits.

This project is primarily intended for engineering students and laboratories to bridge the gap between theoretical concepts and real-world signal modulation.

🎯 Objectives

To design and implement ASK, FSK, and PSK modulation circuits

To generate carrier and data signals using standard ICs

To understand the role of analog switches in modulation

To provide a hands-on learning platform for digital communication concepts

⚙️ System Description

The modulation kit consists of the following functional blocks:

Power Supply Unit – Provides regulated dual voltages

Input Data Generator – Generates binary data and its inverted form

Carrier Signal Generator – Generates sine waves of different frequencies

Modulation Circuit – Implements ASK, FSK, and PSK using analog switches

Each modulation technique is generated independently and available at separate output terminals.

🧩 Components Used

IC 8038 – Precision waveform generator

IC 4016 – Quad bilateral analog switch

IC 4017 – Decade counter

IC 7414 – Schmitt trigger inverter

IC 741 – Operational amplifier

IC 555 – Timer IC

Voltage regulators: 7805, 7812, 7905, 7915

Resistors and capacitors

Diodes (1N4007)

DIP switches

Banana sockets

🔌 Power Supply

A regulated dual power supply provides:

+5V

–5V

+12V

–12V

These voltages support both digital and analog sections of the circuit, ensuring stable and noise-free operation.

📥 Input Data Circuit

A 555 timer generates clock pulses

A 4017 decade counter sequentially scans DIP switch inputs

NOT gates generate both data and inverted data

This allows controlled switching in modulation circuits

📈 Carrier Signal Generator

Uses IC 8038 to generate sine waves

Multiple carrier signals (normal, inverted, and half-frequency) are produced

Operational amplifiers condition signals for modulation

🔄 Modulation Techniques
🔹 ASK (Amplitude Shift Keying)

Carrier is switched ON/OFF based on data input

Implemented using analog switches

Output amplitude varies with binary data

🔹 FSK (Frequency Shift Keying)

Two sine waves of different frequencies are selected

Frequency changes according to input data

🔹 PSK (Phase Shift Keying)

Normal and inverted sine waves are switched

Produces a 180° phase shift based on data transitions

✅ Features

Demonstrates three major digital modulation schemes

Clear separation of ASK, FSK, and PSK outputs

Uses commonly available ICs

Suitable for lab demonstrations and learning

🏭 Applications

Digital communication laboratories

Engineering education and training

Demonstration of modulation techniques

Signal processing experiments

⚠️ Limitations

Educational purpose only

Not suitable for high-frequency or real-time communication systems

Manual configuration required

🚀 Future Enhancements

Addition of demodulation circuits

Integration with CRO / PC interface

Digital control using microcontroller

Compact PCB-based design

J.C. Bose University of Science & Technology,
YMCA, Faridabad

Project Supervisor: Ms. Kusum Arora

📄 License

This project is developed for academic and educational purposes only.
