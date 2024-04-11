# Stress-Strain Curve Analysis

## Introduction
This Python script is designed to analyze stress-strain curves for rubber materials. It calculates the linear limit, ultimate stress, and fracture stress from experimental data and annotates these points on the stress-strain curves.

## Requirements
- Python 3.x
- Matplotlib
- NumPy

## Usage
1. Ensure you have Python installed on your system.
2. Install the required dependencies using `pip install matplotlib numpy`.
3. Prepare your experimental data in a suitable format. The data should include elongation (in meters) and force (in Newtons).
4. Update the script with your data and run it.

## Instructions
- Replace the `data_1`, `data_2`, and `data_3` variables with your experimental data.
- Adjust the parameters such as `L_0` (initial length) and `A` (cross-sectional area) according to your experimental setup.
- If needed, modify the threshold value in the script to adjust the sensitivity of the linear limit detection.
- Run the script. It will generate a plot with annotations indicating the linear limit, ultimate stress, and fracture stress for each dataset.

## File Descriptions
- `stress_strain_analysis.py`: Python script for stress-strain curve analysis.
- `README.md`: This file providing instructions and information about the script.

## Example
Below is an example of how to use the script:

```bash
python stress_strain_analysis.py
