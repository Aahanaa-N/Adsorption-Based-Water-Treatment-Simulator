Project Overview
This Python project models an adsorption-driven wastewater treatment process using classical chemical engineering principles. The system simulates batch adsorption of a dissolved contaminant onto a solid adsorbent and evaluates treatment performance using Langmuir and Freundlich isotherm models. The goal is to maximize contaminant removal while optimizing adsorbent usage from an economic perspective.

The project demonstrates how equilibrium relationships, mass balances, and numerical methods are applied to separation processes commonly used in environmental and chemical engineering.

Chemical Engineering Concepts
Adsorption Equilibrium: Langmuir and Freundlich isotherms
Separation Processes: Batch adsorption modeling
Mass Balances: Contaminant removal calculations
Process Economics: Cost versus treatment benefit optimization
Numerical Methods: Nonlinear equation solving and sensitivity analysis

Features
Models batch adsorption for varying adsorbent masses
Compares Langmuir and Freundlich adsorption behavior
Calculates equilibrium concentrations and removal efficiency
Incorporates economic analysis for optimal adsorbent selection
Includes visualization of removal efficiency and profitability trends
Easily adjustable parameters for different contaminants and adsorbents

Results
The program determines:

Equilibrium contaminant concentration after treatment
Percent removal as a function of adsorbent mass
Net profit based on treatment value and adsorbent cost
Optimal adsorbent mass for maximum economic return
Comparative performance of Langmuir and Freundlich models

Technologies Used
Python – Core programming language
NumPy – Numerical computations
SciPy – Nonlinear equation solving
Matplotlib – Data visualization

Installation & Usage

Clone the repository

git clone https://github.com/your-username/adsorption-water-treatment.git

Install required packages

pip install numpy scipy matplotlib

Run the simulation

python adsorption_optimizer.py
