# Modeling and Analyzing a Battery Profile
### Jarren Wilson, Kenda Kattash, James Tan, Christopher Khaing

## Meet the Team
- Jarren Wilson: Project Manager, EE @ UCSD
- Kenda Kattash: Documentation & Visualization Lead, EE @ UCLA
- James Tan: Analysis/Validation Lead, EE @ UCI
- Christopher Khaing: Modeling Lead, EECS @ UCB

## Project Overview
This project uses MATLAB to model and analyze the charging profile of a lithium-ion battery. The program imports charging data and displays how voltage, current, and power change overtime.

## Features
- Plot voltage vs. time
- Plot current vs. time
- Calculate power
- Plot power vs. time

## Matlab Dependencies
Curve Fitting Toolbox
## How to Run
### Running with Matlab Online
1. Click this button: [![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=TheB2D/Mathworks_Team1_BatteryProfiling)
2. Click the following checkbox then save and open the repository.
3. Open "BatteryCharging_StudentProjectTemplate.mlx".
4. Click "Run".
### Running with the Matlab application
1. Download or copy this repository.
2. Open MATLAB. 
3. Set the MATLAB Current Folder to project folder.
4. Open "BatteryCharging_StudentProjectTemplate.mlx".
5. Make sure the battery data is in the same folder.
6. Install required Matlab Toolboxes
   - In the Matlab Application click "Home" and then "Add-ons".
   - On the "Add-ons" popup search & install "Curve Fitting Toolbox"
7. Click "Run".
## Expected Results
### Task 1
- 5 data points should be loaded and displayed on a table in the program.
- A graph of Current (Blue) and Voltage (Red) over time should be displayed.
- Values of vMin (Voltage minimum) vMax (Voltage maximum) and vTau_thy (Voltage when T = Tau) should be displayed.
- A graph or the RC-Circuit Model comparing Measured voltage and Fitted Model of the battery for Cycle 1 should be shown.
- Display of Goodness-of-fit statistics
### Task 2
- 3 Graphs should be displayed **Voltage vs Time**, **Current vs Time**, and **Power vs Time** that are based on the given battery charging data
### Task 3
- A table with 10 diffetent time intervals should show with voltage rate of change. 
- The graph Voltage vs Time with Key Rate-of-Change Points should be displayed with 9 key points plotted along the line.
- Values of the time to reach 80% charge and time to reach 100% charge should be calculated and shown.
- Calculate the total energy delivered to the battery during the charging
- Estimate the resistive energy loss
- A summary table showing a small summary of all the values should be displayed.

## Resources Used
- [Curve Fitting Onramp](https://matlabacademy.mathworks.com/details/curve-fitting-onramp/orcf)
- [Example MathWorks Lithium Ion Battery Data](https://www.mathworks.com/help/predmaint/ug/data-analysis-and-feature-extraction-for-battery-raw-cycling-data.html)
- [Curve Fitting Workflow](https://www.mathworks.com/help/curvefit/fit.html)
- [Numerical Integration and Differentiation with MATLAB](https://www.mathworks.com/help/matlab/numerical-integration-and-differentiation.html)


