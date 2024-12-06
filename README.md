# Project: Kalman Filter Implementation for a Nonlinear Dynamic System

This repository contains the development of a project on Kalman filters, including the simulation, implementation, and analysis of different variants of this filter for a nonlinear dynamic system with input.

## Project Content

The work is divided into the following main parts:

1. **Experimental Data Collection**
   - Simulation of a nonlinear dynamic system in Simulink.
   - Generation of experimental data with noise.

2. **Extended Kalman Filter (EKF)**
   - Implementation of the extended Kalman filter to estimate the system states.
   - Graphical analysis of results:
     - Estimated states and confidence intervals.
     - Trace of the covariance matrix.
     - Kalman gain norm.
     - Whiteness test.

3. **Joint Kalman Filter (JKF)**
   - Implementation of the joint Kalman filter to estimate states and parameters.
   - Graphical analysis of results:
     - Estimated states and parameters.
     - Condition number of the observability matrix.
     - Kalman gain norm.

4. **State Feedback Control**
   - Implementation of a state feedback controller using the EKF.
   - Simulation and analysis of results:
     - Controlled states.
     - Control action.
     - Robustness against disturbances.

## Repository Structure

This repository includes the following files and folders:

- `Informe/`  
  Contains the Live Script file in MATLAB format (`.mlx`) with results, calculations, and graphs in IMRAD format.

- `Simulaciones/`  
  Includes the Simulink (`.slx`) files for:
  1. Generating experimental data with noise.
  2. State feedback control.

- `README.md`  
  This file.

## Prerequisites

- **MATLAB** with support for Live Scripts and Simulink.
- Basic knowledge of:
  - Nonlinear dynamic systems.
  - Kalman filters (EKF and JKF).
  - System control.

## How to Execute the Project

1. **Simulation and Data Collection**
   - Open the Simulink file in `Simulaciones/`.
   - Run the simulation to generate experimental data.

2. **Kalman Filter Analysis**
   - Open the Live Script file in `Informe/`.
   - Execute the cells step by step to generate graphs and analysis.

3. **State Feedback Control**
   - Open the corresponding Simulink file in `Simulaciones/`.
   - Modify initial conditions as needed.
   - Run the simulation to observe the controlled behavior.

## Report Format

The report follows the IMRAD format (Introduction, Methods, Results, and Discussion). 

- **Introduction**: Brief description of the problem and the model used.
- **Methods**: Description of the implementation and procedures performed.
- **Results**: Graphs and analysis of the filters and control.
- **Discussion**: Interpretation and discussion of the obtained results.
