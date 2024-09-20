# [Analog-Digital conversion circuit with an interface to a FPGA development board for an X-ray detector module of a 3D breast CT prototype.]


## Project Overview
This project focuses on the design and development of an ADC electronic circuit for a CMOS sensor coupled with CsI:Tl scintillating crystals to detects X-rays. The circuit samples analog pixels data from the sensor, crucial for analyzing beam geometry and sensor-scintillator response. An FPGA interfaces with the circuit to process the digital data from three sensor channels and store it on a host computer for image processing and analysis.

## Features
- High-gain audio amplification for home audio systems
- Low-noise design with optimized component selection
- PCB layout and design using EAGLE
- Circuit simulation and analysis using LTSpice


## Tools and Technologies
- **LTSpice** for circuit simulation
- **KiCad** for schematic capture and PCB layout
- **Arduino** for microcontroller integration (if applicable)
- **Oscilloscope** for signal testing
- **Resistors, capacitors, transistors**, and other components
## Circuit Schematic
Here is the circuit schematic designed in KiCad:

![Circuit Schematic](Images/circuit_schematic.png)
## How to Build and Test
1. Download the schematic and PCB files from the `Schematics/` and `PCB-Layouts/` folders.
2. Order or manufacture the PCB from the provided Gerber files.
3. Assemble the components as per the schematic.
4. Run the simulation files in **LTSpice** to verify the circuit's performance.
5. Test the assembled circuit using an oscilloscope or a signal generator for verification.
## Simulation Results
The following simulations were conducted using LTSpice. The circuit shows stable gain across the audio frequency range.

![Simulation Output](Images/simulation_output.png)
## PCB Layout
The PCB layout was created using KiCad. Below is a preview of the PCB design:

![PCB Layout](Images/pcb_layout.png)
## Bill of Materials (BOM)
- **R1, R2** - 10kΩ Resistor
- **C1** - 100nF Capacitor
- **Q1** - 2N2222 Transistor
- **Op-Amp** - LM358
## Future Improvements
- Implement feedback control for better signal stability.
- Improve power efficiency by optimizing transistor biasing.
- Add digital control for adjustable gain.
## Contact
For any questions, feel free to contact me at: [your-email@example.com](mailto:your-email@example.com).
