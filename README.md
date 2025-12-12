# CHM 3915 Physical Chemistry Lab Notebooks

This repository contains Jupyter notebooks and materials for the Physical Chemistry Laboratory course (CHM 3915) at Eastern Illinois University.

## Course Description

CHM 3915 is a laboratory course in physical chemistry that introduces students to computational methods, data analysis, and scientific programming using Python.

## Contents

### Notebooks

- **CHM 3915 Intro to Python.ipynb** - Introduction to Python programming with chemistry-focused exercises including:
  - Variables and mathematical operations
  - Boolean logic
  - Lists and comprehensions
  - Control flow (if/else, for loops, while loops)
  - File I/O operations
  - Chemistry applications (ideal gas law, quadratic equations, radioactive decay, etc.)

- **CHM 3915 Plotting in Python - Final.ipynb** - Data visualization and analysis including:
  - Creating plots with matplotlib
  - Linear and quadratic regression
  - Error bars and confidence intervals
  - R² calculations
  - Professional figure formatting for lab reports

### Data

- **Data/test.csv** - Sample data file for exercises

## Getting Started

### Option 1: Local Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/PellizzeriLab/EIU_CHM3915_Lab_Notebooks.git
   cd EIU_CHM3915_Lab_Notebooks
   ```

2. Install required packages:
   ```bash
   conda env create -f environment.yml
   ```

3. Launch Jupyter:
   ```bash
   jupyter notebook
   ```

### Option 2: Using Binder

Click the badge below to launch the notebooks in an interactive environment without any installation:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/PellizzeriLab/EIU_CHM3915_Lab_Notebooks/main)

## Requirements

- Python 3.x
- matplotlib
- pandas
- numpy
- scikit-learn
- openpyxl

See `requirements.txt` for the complete list.

## Usage

1. Navigate to the `Intro_to_programming` folder
2. Open the desired notebook
3. Complete the exercises in the provided code cells
4. Execute cells to verify your solutions

## License

This project is licensed under the terms specified in the LICENSE file.

## Contact

For questions or issues, please contact the course instructor at Eastern Illinois University.

## Acknowledgments

Developed for the Chemistry Department at Eastern Illinois University.
