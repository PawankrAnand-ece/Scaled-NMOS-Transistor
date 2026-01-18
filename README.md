Scaled NMOS TransistorImplementation and Performance Analysis of Scaled NMOS Transistor
Project Overview
This project focuses on the design, fabrication simulation, and electrical characterization of a scaled NMOS transistor using Silvaco TCAD2222. It explores how miniaturization affects transistor performance, specifically focusing on short-channel effects
Simulation Workflow
The project is divided into two main simulation phases:
1.	Process Simulation (ATHENA): Defines the fabrication steps, including substrate initialization, gate oxide growth, polysilicon deposition, and source/drain implantation4.
2.	Device Simulation (ATLAS): Extracts the electrical characteristics of the simulated structure5.
Key Performance Metrics
The following parameters were extracted to analyze the device performance6:
•	Threshold Voltage ($V_t$): The voltage at which the transistor turns on7.
•	$I_D-V_{GS}$ & $I_D-V_{DS}$ Characteristics: Current-voltage relationships8.
•	$I_{on}/I_{off}$ Ratio: The efficiency of the transistor as a switch9.
•	Subthreshold Behavior: Evaluation of leakage current10.
•	DIBL (Drain-Induced Barrier Lowering): Analysis of short-channel degradation11.
Scaling Analysis
To study technology scaling, the channel length was systematically varied12. As the channel length decreased, the following observations were made:
•	Threshold Voltage Roll-off: A reduction in $V_t$ as dimensions decreased13.
•	Increased Leakage: Higher off-state current due to short-channel effects14.
How to Run
1.	Open DeckBuild in Silvaco.
2.	Run the nmos_fab.in script to generate the structure file.
3.	Run the nmos_test.in script to perform electrical characterization and view plots in TonyPlot
