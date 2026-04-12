# Amplitude Modulation (DSB-LC)

An educational Double-Sideband Large Carrier (DSB-LC) Amplitude Modulation circuit designed for laboratory testing and signal analysis.

## Project Overview
This project demonstrates the generation of AM waves using a diode-based switching modulator. It is optimized for a 20 kHz carrier frequency and includes a passive LC band-pass filter to extract the desired AM envelope. The PCB is routed for DIY fabrication (acid/toner transfer method) with a robust trace width (25 mil) and an extensive ground plane for noise reduction.

## Operating Specifications
* Target Carrier Frequency (fc): 20 kHz (Tuned via 1mH Inductor & 68nF Capacitor)
* Max Message Frequency (fm): <= 2 kHz
* Maximum Input Voltage: 15 Vpp
* Modulation Type: DSB-LC

## Simulation & Signal Analysis
The mathematical foundation of the circuit is based on the standard AM equation:

s(t) = Ac [1 + ka m(t)] \cos(2pifct)



## Hardware Design
The schematic and PCB were designed using EasyEDA. 



* Components: 1N4148 fast-switching diode, 1/4W THT resistors, radial inductors/capacitors.
* PCB Features: Teardrop routing for mechanical stress relief, bottom-layer silkscreen mirroring for DIY etching, and robust ground pours.

## About the Designer
Designed by Barış Erişen.
Electrical and Electronics Engineering Student.
