📊 Vogel's Inflow Performance Relationship (IPR) Calculator
This Python script calculates and visualizes the Inflow Performance Relationship (IPR) using Vogel's Equation for a solution-gas drive reservoir. It allows users to compute the Productivity Index (J), Maximum Flow Rate (Qmax), and the flow rate at various bottomhole pressures.

✅ Features
Takes user input for key reservoir and fluid parameters.

Calculates:

Productivity Index (J)

Maximum flow rate (Qmax)

Flow rate at various flowing bottomhole pressures (pwf)

Displays results in a Pandas DataFrame.

Plots Vogel’s IPR curve using Matplotlib.

📥 User Inputs
You will be prompted to enter the following parameters:

Parameter	Unit	Description
Porosity	fraction	Rock porosity (e.g., 0.21)
Permeability (K)	md	Rock permeability
Pay zone thickness (h)	feet	Thickness of the producing zone
Reservoir Pressure (P)	psi	Static reservoir pressure
Formation Vol. Factor (Bo)	RB/STB	Oil formation volume factor
Fluid Viscosity	cp	Viscosity of reservoir fluid
Drainage Area (A)	acres	Area drained by the well
Wellbore Radius (rw)	feet	Radius of the wellbore
Skin Factor (S)	-	Accounts for formation damage or stimulation

📈 Output
Productivity Index (J) in stb/day/psi

Maximum Flow Rate (Qmax) in stb/day

Flowrate vs. Bottomhole Pressure (pwf) table

Vogel's IPR Curve (Flowrate vs pwf)

📦 Requirements
Python 3.x

NumPy

Pandas

Matplotlib

Install dependencies using:

bash
Copy
Edit
pip install numpy pandas matplotlib
▶️ How to Run
Run the script using:

bash
Copy
Edit
python vogel_ipr.py
You will be prompted to input the parameters interactively.

📌 Note
This model assumes solution gas drive (saturated oil reservoir).

The flow equation used is Vogel’s empirical IPR model, which is applicable when the well is producing at pressures below the bubble point.

📚 Reference
Vogel, J.V. (1968). “Inflow Performance Relationships for Solution-Gas Drive Wells.” Journal of Petroleum Technology.
