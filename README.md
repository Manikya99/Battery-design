# Manual Tuning of ESC Model

## Overview
This project involves manually tuning an Equivalent Circuit Model (ESC) of a battery cell. The goal was to achieve a high degree of accuracy in voltage prediction with minimal error.

## Features
- **Thévenin Model:** Used for the ESC model.
- **Manual Tuning:** Fine-tuned parameters to achieve an RMS voltage-prediction error of 4.97821 mV.
- **MATLAB Implementation:** MATLAB was used for tuning and simulation.

## Project Structure
- **/scripts**: MATLAB scripts for tuning the ESC model.
- **/results**: Contains the results and performance metrics of the tuned model.
- **README.md**: This file.

## Requirements
- MATLAB with the Curve Fitting Toolbox
- Basic knowledge of battery modeling

## How to Run
1. Clone the repository.
2. Navigate to the `scripts` folder in MATLAB.
3. Run the tuning scripts and observe the results in the `results` folder.

## Results
The tuning resulted in an RMS voltage-prediction error of 4.97821 mV, indicating a highly accurate model. Detailed results are available in the `results` folder.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
