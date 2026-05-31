Centre of Innovation in IoT (COI) – Project Description
1. Project Overview
Project Title

Smart Heart Sound Monitoring System Using Adaptive Notch Filtering and Bluetooth Connectivity

Description

The Smart Heart Sound Monitoring System is an IoT-enabled healthcare solution designed to improve the quality of Phonocardiogram (PCG) signals by removing power-line interference and environmental noise using an Adaptive Notch Filter. The system processes heart sound signals, validates the filtering algorithm through Verilog HDL implementation, and wirelessly transmits monitoring data using Bluetooth Low Energy (BLE).

The project is intended for healthcare monitoring applications where clean heart sound signals are required for accurate analysis. The solution provides a low-cost, portable, and scalable platform that can be further extended with AI-based heart abnormality prediction and cloud-based healthcare monitoring.

Target Users
Healthcare professionals
Medical researchers
Students and researchers in Biomedical Engineering
Remote patient monitoring systems
Motivation

Heart sound signals are often affected by 50 Hz power-line interference, making diagnosis difficult. This project aims to provide a low-cost IoT-based solution for signal conditioning and wireless monitoring of cardiac signals.

2. Technical Architecture
System Architecture
<img width="553" height="2041" alt="mermaid-diagram" src="https://github.com/user-attachments/assets/05fa431b-5941-406b-9fd0-4923c3df4994" />
Future Architecture
<img width="522" height="1148" alt="mermaid-diagram2" src="https://github.com/user-attachments/assets/7bfe49e1-0081-46f4-a80a-678caabd0d4f" />

4. Technologies Used
Wireless Technologies
Bluetooth Low Energy (BLE)
Signal Processing Technologies
Fast Fourier Transform (FFT)
Adaptive Frequency Detection
Adaptive Notch Filtering
Digital Signal Processing (DSP)
Hardware Design Technologies
Verilog HDL
Fixed-Point Arithmetic
Programming Languages
MATLAB
Verilog HDL
C (for Silicon Labs firmware)
Silicon Labs Software
Simplicity Studio
Gecko SDK (GSDK)
Development Tools
MATLAB
GTKWave
GitHub
VS Code
5. Hardware Components
Silicon Labs Hardware
Development Board
Silicon Labs xG24 Explorer Kit
Wireless Technology
Bluetooth Low Energy (BLE)
Processor
EFR32MG24 Wireless SoC
External Hardware
Required Hardware
Smartphone (BLE Receiver)
PC/Laptop
Digital Stethoscope (Optional)
PCG Sensor (Future Implementation)
Development Tools
Logic Analyzer (Optional)
Oscilloscope (Optional)
6. Software Components / Dependencies
Silicon Labs Dependencies
Gecko SDK
Gecko SDK Suite (GSDK) v4.x
Simplicity Studio
Simplicity Studio 5
Bluetooth Stack
Silicon Labs Bluetooth SDK
External Software Dependencies
MATLAB

Used for:

PCG Signal Processing
FFT Analysis
Adaptive Notch Filter Design
Result Visualization
Signal Processing Toolbox

Used for:

FFT Computation
IIR Notch Filter Design
Frequency Analysis
Verilog HDL Simulation
Icarus Verilog
Waveform Analysis
GTKWave
Version Control
GitHub

Project Features
Adaptive Noise Removal
FFT-Based Frequency Detection
Adaptive Notch Filtering
Verilog HDL Implementation
Bluetooth Low Energy Connectivity
Wireless Healthcare Monitoring
Low-Cost IoT Architecture
Real-Time Signal Processing Capability

Expected Outcomes

Removal of 50 Hz power-line interference from PCG signals.
Improved heart sound signal quality.
Successful Verilog-based digital filter implementation.
Wireless transmission of monitoring information through BLE.
Foundation for future AI-based cardiac abnormality detection systems.

Future Scope

AI-Based Heart Abnormality Prediction
TinyML on Silicon Labs Devices
Cloud Database Integration
Mobile Healthcare Application
Hospital Monitoring Dashboard
FPGA Acceleration
Wearable Heart Monitoring Device
