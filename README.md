# two-stage-CMOS-operational-amplifier-design
Explanation video link (Indonesian): https://youtu.be/kwhLM6c_WrE  
This project presents the design and simulation of a two-stage CMOS operational amplifier (Op-Amp).  
The design targeted key performance specifications including:  
Open-loop gain: 120 dB  
Gain Bandwidth Product (GBW): 78 MHz  
Phase Margin: ≥ 60°  
Slew Rate (SR): > 7 V/µs  
Power Dissipation: < 10 mW  
Supply Voltage: ±3.8 V  
Load Capacitance: 17 pF    
![schematic diagram](https://github.com/izzudin01/two-stage-CMOS-operational-amplifier-design/blob/main/Screenshot%202025-09-03%20164952.png)  
## Project Outcomes
Simulation Results:  
Open-loop gain: 80.43 dB  
GBW: 90.18 MHz  
Phase Margin: 64.47°  
Slew Rate: 3.49 V/µs  
Power Dissipation: 35.69 mW  
![schematic diagram](https://github.com/izzudin01/two-stage-CMOS-operational-amplifier-design/blob/main/Screenshot%202025-09-03%20165018.png)  
Conducted mathematical modeling, bias current analysis, and AC/DC/transient simulations to evaluate circuit performance.  
Identified trade-offs between gain, bandwidth, power dissipation, and slew rate, providing insight for further optimization in CMOS Op-Amp design.  

## Tools & Methods
Technology: CMOS design parameters (0.13 µm technology reference)  
Analysis: Theoretical calculations, small-signal modeling, and SPICE-based circuit simulation (LTSPICE) 
Verification: AC analysis, transient analysis, DC sweep, and stability checks (Phase Margin, ICMR)  
