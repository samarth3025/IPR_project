
# Vogel's IPR Calculator

This Python project calculates and visualizes Vogel’s Inflow Performance Relationship (IPR) for oil wells with solution gas drive. It estimates well productivity index (J), maximum flow rate (Qmax), and flow rates at different bottomhole pressures using user input parameters.

## Project Description
This project calculates and visualizes Vogel’s Inflow Performance Relationship (IPR) using Python. It estimates well productivity, maximum flow rate, and flow behavior under varying bottomhole pressures based on user inputs. The tool helped me apply reservoir engineering concepts and enhance my skills in data analysis and scientific plotting.

## Features
- Calculates Productivity Index (J) and Qmax
- Computes flow rate at different pwf values
- Generates Vogel’s IPR plot
- Presents flowrate vs pwf data in a table

## User Inputs
- Porosity
- Permeability (md)
- Pay zone thickness (ft)
- Reservoir pressure (psi)
- Formation volume factor (Bo)
- Fluid viscosity (cp)
- Drainage area (acres)
- Wellbore radius (ft)
- Skin factor

## Requirements
- Python 3.x
- numpy
- pandas
- matplotlib

Install dependencies using:

```bash
pip install numpy pandas matplotlib
```

## How to Run
Run the script using:

```bash
python vogel_ipr.py
```

You will be prompted to enter required reservoir parameters.

## Output
- Productivity Index (J)
- Maximum flow rate (Qmax)
- Flowrate vs pwf table
- Vogel’s IPR curve

## Reference
- Vogel, J.V. (1968). “Inflow Performance Relationships for Solution-Gas Drive Wells.” Journal of Petroleum Technology.
