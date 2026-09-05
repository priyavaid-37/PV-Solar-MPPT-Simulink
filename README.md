# PV Solar Power Generation with P&O MPPT

## Overview

This project presents a MATLAB/Simulink model of a photovoltaic (PV) solar power generation system with Maximum Power Point Tracking (MPPT).

A Perturb and Observe (P&O) algorithm is implemented to adjust the converter duty cycle based on the measured PV voltage and current. The system uses a MOSFET-based DC-DC boost converter with PWM control.

## System Components

- PV Array
- Voltage and Current Measurement
- Perturb and Observe (P&O) MPPT Controller
- PWM Generator
- MOSFET-based DC-DC Boost Converter
- Inductor
- Diode
- Capacitors
- Resistive Load
- Voltage, Current and Power Monitoring

## Simulation

The system is modeled and simulated in MATLAB/Simulink under different irradiance and temperature conditions.

The P&O MPPT controller continuously adjusts the converter duty cycle based on changes in PV voltage and power.
## System Model

The overall PV system is modeled in MATLAB/Simulink, including the PV array, P&O MPPT controller, PWM generator, and DC-DC boost converter.

![PV Solar Simulink Model](simulink_model.png)
## Simulation Results

### PV Power Response

![PV Power Response](pv_power_response.png)

### PV Voltage Response

![PV Voltage Response](pv_voltage_response.png)

### MPPT Duty Cycle

![MPPT Duty Cycle](mppt_duty_cycle.png)

## Tools Used

- MATLAB
- Simulink
- MATLAB Function
- Power Electronics
- MPPT Control
- DC-DC Boost Converter
