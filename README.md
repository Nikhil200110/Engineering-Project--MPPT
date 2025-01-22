# Engineering-Project--MPPT
Expanding this research to hybrid MPPT techniques and integrating machine learning for adaptive performance under dynamic weather conditions.
Project Overview:
This project investigates the control of Maximum Power Point Tracking (MPPT) in grid-connected photovoltaic (PV) systems, aiming to enhance power efficiency and ensure stable voltage output. Using advanced simulation and hardware prototypes, the study compares two key MPPT techniques—Incremental Conductance (InC) and Perturb & Observe (P&O)—to identify the optimal method for maximum power transfer under varying environmental conditions.
![Without S Full_page-0001](https://github.com/user-attachments/assets/280c8ce7-cedc-4637-b211-386d7862fbc7)

Problem Statement:
Grid-connected PV systems face efficiency issues due to nonlinear I-V characteristics, voltage instability, and weather-dependent performance. Despite modifications like advanced panels and additional batteries, challenges like voltage fluctuation and low power transfer persist. The project seeks to address these issues by implementing and evaluating different MPPT algorithms.

Research Question:
Which MPPT technique provides better performance for maximum power transfer and stable voltage in grid-connected PV systems?

Tools and Libraries Used:

Simulation Software: MATLAB (R2022a)
Hardware Components: PIC16F886 Microcontroller, Boost Converter, Solar Panel, LCD Display, H-Bridge Inverter.
Dataset Description:
Simulated and real-world data for solar irradiation, temperature, and PV panel parameters in Nagpur conditions. The dataset includes parameters like open circuit voltage (Voc), short circuit current (Isc), and voltage/current at MPP.

Steps Undertaken:

Data Preparation:

Modeled PV array characteristics using MATLAB.
Simulated environmental variations (irradiance and temperature).

Exploratory Analysis:

Analyzed I-V and P-V curves for PV arrays to identify MPP.
Evaluated system performance with and without MPPT under varying conditions.

Hypothesis Testing:

Hypothesis: Incremental Conductance provides better performance than P&O.
Results showed Incremental Conductance achieves higher efficiency (above 98%) and accurate tracking under changing conditions.

Simulation Analysis:

Developed models for P&O and Incremental Conductance MPPT.
Results confirmed better power transfer with Incremental Conductance.

Hardware Testing:

Created dual-mode MPPT kit with P&O and Incremental Conductance algorithms.
Compared outputs for accuracy and response time under controlled lab conditions.

Key Findings:

Incremental Conductance surpasses P&O in accuracy, efficiency, and adaptability to varying irradiance.
P&O is faster but less stable under fluctuating conditions.
Optimal settings for maximum efficiency were identified for practical implementation.

Business Impact:

Improved efficiency and stability of grid-connected PV systems.
Reduced power losses and operational costs.
Enhanced adaptability for residential and industrial applications.

Conclusion:
This project emphasizes the importance of choosing the right MPPT algorithm to maximize power transfer and efficiency in grid-connected PV systems. Incremental Conductance proved superior, offering better performance in real-world conditions.
