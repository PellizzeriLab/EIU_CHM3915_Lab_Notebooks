# CHM 3915 Physical Chemistry Lab Notebooks

Jupyter notebooks and data for the Physical Chemistry Laboratory course (CHM 3915) at Eastern Illinois University.

## Course Description

CHM 3915 introduces computational methods, data analysis, and scientific programming applied to physical chemistry experiments.

## Repository Structure

- **Intro_to_programming/** — Introductory Python and plotting notebooks
  - CHM 3915 Intro to Python.ipynb — Python fundamentals with chemistry applications
  - CHM 3915 Plotting in Python - Final.ipynb — Data visualization and linear/quadratic regression

- **Phase_Diagram/** — Refractive Index (RI) calibration and composition analysis
  - RI-Fitting.ipynb — Interactive tool to predict cyclohexane mole fraction in cyclohexane:ethanol solutions based on measured RI
  - Data/ — Supporting data files for calibration
  
- **Bomb_Calorimetry/**
- **NO2_Dimerization/**
- **Phenolphthalein_Kinetics/**
- **Polymer_Viscosity/**
- **Speed_of_Sound/**

- environment.yml — Conda environment specification
- LICENSE

## Binder (no install)

Launch an interactive session in the cloud (uses the repository environment):

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/PellizzeriLab/EIU_CHM3915_Lab_Notebooks/HEAD)

## Environment (conda)

1) Clone the repository
```bash
git clone https://github.com/PellizzeriLab/EIU_CHM3915_Lab_Notebooks.git
cd EIU_CHM3915_Lab_Notebooks
```

2) Create the course environment (name: eiu-pchem-env)
```bash
conda env create -f environment.yml
conda activate eiu-pchem-env
```

3) Launch Jupyter
```bash
jupyter lab
# or
jupyter notebook
```

To update the environment after changes to environment.yml:
```bash
conda env update -f environment.yml --prune
```
## Key Packages

Core tools from environment.yml (see file for full list and versions):

### Intro to Programming
- Open the notebook for your experiment inside its folder (e.g., Intro_to_programming/ for the intro materials).
- Run cells in order; fill in exercise cells where indicated.
- Save your completed notebook before submission.

### Phase Diagram - RI Fitting Tool
The RI-Fitting notebook provides an interactive tool for analyzing cyclohexane-ethanol mixtures:

1. Launch the notebook and run all cells
2. The interactive predictor will display:
   - Input field for refractive index (RI) measurement
   - Calibration range showing safe interpolation vs. extrapolation regions
   - Predict button to calculate cyclohexane mole fraction
   - Export button to save prediction log to file
3. Enter measured RI values and click "Predict Cyclohexane Mole Fraction"
4. Results show:
   - Estimated cyclohexane mole fraction (x_C6H12)
   - Status (interpolated/extrapolated)
   - Warning flags for out-of-range predictions
   - Running log of all predictions

**Note:** Interpolated values (within calibration range) are more reliable. Extrapolated values have higher uncertainty
- quantum/chemistry: psi4, psi4-rt, fortecubeview, ase, libint, dftd3-python

## Usage

- Open the notebook for your experiment inside its folder (e.g., Intro_to_programming/ for the intro materials).
- Run cells in order; fill in exercise cells where indicated.
- Save your completed notebook before submission.

## License

This project is licensed under the terms specified in the LICENSE file.

## Contact

For questions or issues, please contact the course instructor at Eastern Illinois University.

## Acknowledgments

Developed for the Chemistry Department at Eastern Illinois University.
