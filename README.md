# Implementation and Performance Analysis of Scaled NMOS Transistor using TCAD Silvaco

## 📌 Project Overview
This project presents the implementation and performance analysis of a scaled NMOS transistor. The device is designed and simulated using **ATHENA** for process simulation and **ATLAS** for device simulation to provide a realistic representation of fabrication and electrical behavior.

## 🛠️ Design & Fabrication (ATHENA)
The transistor structure was implemented by defining key process steps
**Substrate Initialization:** Defining the initial silicon wafer properties.
**Gate Oxide Formation:** Growing the thin insulating layer.
**Source/Drain Implantation:** Adding dopants to create the active regions.
**Diffusion:** Finalizing the junction depths.



## 📊 Performance Metrics & Analysis (ATLAS)
The project systematically varied the channel length to study the effects of technology scaling. The following parameters were extracted and analyzed:
**Threshold Voltage (Vt):** Analyzed for Vt roll-off as dimensions decreased.
**ID–VGS & ID–VDS Characteristics:** Typical drain current curves.
**On-current (Ion) vs. Off-current (Ioff):** Evaluation of the switching efficiency.
**Subthreshold Behavior:** Monitoring how the device turns off.
**DIBL (Drain-Induced Barrier Lowering):** Measuring the impact of high drain voltage on the threshold.



## 📉 Key Findings
1. **Scaling Impact:** As the channel length decreases, short-channel effects (SCE) become more prominen.
2. **Short-Channel Effects:** Miniaturization leads to a reduced threshold voltage and increased leakage current.
3. **Trade-offs:** The results highlight the fundamental trade-offs between high performance and power consumption in modern CMOS devices.

## 🚀 How to Use
1. **Simulation:** Run the `nmos_fab.in` file in Silvaco DeckBuild to generate the structure.
2. **Analysis:** Run the `nmos_test.in` file to perform the electrical characterization.
3. **Visualization:** Use **TonyPlot** to view the resulting `.str` and `.log` files.

## 📚 Conclusion
This work serves as a practical foundation for understanding device-level behavior in VLSI design and semiconductor engineering. It illustrates the critical role of TCAD tools in optimizing transistor performance for advanced technology nodes.
