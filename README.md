# GFD Simulations

This project contains Geophysical Fluid Dynamics simulation code and experiments.

## Structure

- `src/` — Numerical solvers and model code
- `notebooks/` — Exploratory analysis and visualization
- `data/` — Input/output data files
- `environment.yml` — Conda environment for reproducibility

## How to Run

```bash
conda env create -f environment.yml
conda activate gfd 

1. Create a new empty repo at: [github.com/new](https://github.com/new)
2. Then link it from terminal:

git remote add origin https://github.com/GuerryThomas/gfd-simulations.git
git branch -M main
git add .
git commit -m "Initial commit for GFD simulations project"
git push -u origin main ```
