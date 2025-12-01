# Multiscale Materials Modelling Workshop

Welcome to the Uppsala University - UFF collaborative workshop on multiscale materials modelling! This repository contains Jupyter notebooks and resources for the Niteroi 2026 workshop.

## Overview

This workshop covers computational methods for materials and molecular simulations, focusing on:

1. **DFTB Parameterization**: Density Functional Tight Binding (DFTB) method and its parameterization techniques
2. **ML-based Force Fields**: Machine Learning approaches for force field development in materials science

## Repository Structure

```
├── notebooks/
│   ├── dftb/                    # DFTB parameterization notebooks
│   │   └── 01_dftb_intro.ipynb  # Introduction to DFTB
│   └── ml_force_fields/         # ML force field notebooks
│       └── 01_ml_ff_intro.ipynb # Introduction to ML force fields
├── requirements.txt             # Python dependencies
└── README.md
```

## Getting Started

### Prerequisites

- Python 3.8 or higher
- Jupyter Notebook or JupyterLab

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/peterbmob/Niteroi2026.git
   cd Niteroi2026
   ```

2. Create a virtual environment (recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Launch Jupyter:
   ```bash
   jupyter notebook
   ```

## Contents

### DFTB Parameterization

The notebooks in `notebooks/dftb/` cover:
- Introduction to DFTB theory
- Parameter fitting procedures
- Applications to materials systems

### ML-based Force Fields

The notebooks in `notebooks/ml_force_fields/` cover:
- Introduction to machine learning potentials
- Training ML force fields
- Applications in molecular dynamics simulations

## Contributing

This is a collaborative project between Uppsala University and UFF. Contributions and feedback are welcome!

## License

This project is for educational purposes as part of the Uppsala University - UFF collaboration.
