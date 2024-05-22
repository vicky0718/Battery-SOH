📊 **Li-ion Battery Data for Operational Profiles and Prediction Tasks**
This repository contains data from a set of four Li-ion batteries (#5, 6, 7, and 18) run through three different operational profiles (charge, discharge, and impedance) at room temperature. The data can be used for predicting both the remaining charge (for a given discharge cycle) and the remaining useful life (RUL) of the batteries.

📂 Files
B0005.mat: Data for Battery #5
B0006.mat: Data for Battery #6
B0007.mat: Data for Battery #7
B0018.mat: Data for Battery #18
📐 Data Structure
The data is structured into cycles, each containing information on charge, discharge, and impedance operations.

Cycle Structure
cycle: Top-level structure array containing the charge, discharge, and impedance operations.
type: Operation type (charge, discharge, or impedance).
ambient_temperature: Ambient temperature (°C).
time: Start time of the cycle (MATLAB date vector format).
data: Data structure containing measurements.
Charge Data Fields
Voltage_measured: Battery terminal voltage (Volts).
Current_measured: Battery output current (Amps).
Temperature_measured: Battery temperature (°C).
Current_charge: Current measured at charger (Amps).
Voltage_charge: Voltage measured at charger (Volts).
Time: Time vector for the cycle (secs).
