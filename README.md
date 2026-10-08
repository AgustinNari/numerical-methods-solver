# Numerical Methods Solver

Interactive Streamlit application for exploring numerical methods, numerical integration, interpolation, Monte Carlo simulation, root finding, and ordinary differential equations.

The project was developed collaboratively and combines numerical computation with interactive visualizations and step-by-step result analysis.

## Methods

The application includes tools for:

- Bisection
- Newton-Raphson
- Fixed-point iteration
- Aitken acceleration
- Lagrange interpolation
- Central differences
- Midpoint rule
- Trapezoidal rule
- Simpson's 1/3 rule
- Simpson's 3/8 rule
- Monte Carlo integration
- Double Monte Carlo integration
- Euler method
- Runge-Kutta methods

## Tech Stack

- Python
- Streamlit
- NumPy
- Pandas
- SciPy
- SymPy
- Plotly

## Features

- Interactive mathematical-function input
- Numerical-method configuration
- Step-by-step calculations
- Error analysis
- Convergence visualization
- Function and solution plots
- Monte Carlo visualizations
- ODE solution analysis
- Symbolic support through SymPy

## Running Locally

Create and activate a Python virtual environment, then install the dependencies:

```bash
pip install -r requirements.txt
```

Start the application with:

```bash
streamlit run app.py
```

Streamlit will display the local application URL in the terminal.

## Additional React Simulator

This repository also includes a separate [Dynamic Systems Simulator](Simulador2/) built with React and Vite.

It provides interactive simulations of 1D, 2D, and 3D dynamical systems, including phase diagrams, trajectories, equilibrium analysis, and mathematical visualizations.

To run it locally:

```bash
cd Simulador2
npm ci
npm run dev
```

See the [React simulator README](Simulador2/README.md) for additional details.

## Scope

The application is intended as an educational and analytical tool for exploring numerical methods and their behavior through interactive examples.
