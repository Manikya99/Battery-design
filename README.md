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


# Thermal Modeling of the Battery Pack

## Overview
This project involves the thermal modeling of a 10-cell series lithium-ion battery pack. The objective is to simulate the thermal effects and compare life cycle performance at various temperatures and charge/discharge rates using MATLAB.

## Features
- **Simulation of thermal behavior:** Analyze the temperature impact on the State of Charge (SoC) and overall battery performance.
- **Temperature variation:** Test the battery at different operating temperatures ranging from 300K to 390K.
- **MATLAB Implementation:** Utilize MATLAB Simscape for thermal modeling and simulation.

## Project Structure
- **/images**: Contains all images and diagrams related to the project.
- **/simulink_model**: MATLAB Simulink files for the battery pack model.
- **/results**: Output graphs and analysis at different temperatures.
- **README.md**: This file.

## Requirements
- MATLAB with Simscape and Simulink
- Basic understanding of battery management systems

## How to Run
1. Clone the repository.
2. Open MATLAB and navigate to the `simulink_model` folder.
3. Open the Simulink model and run the simulation.
4. Observe the results in the `results` folder.

## Results
The results indicate that the State of Charge (SoC) decreases as the temperature increases, leading to faster discharge and reduced battery life. Detailed graphs and data can be found in the `results` folder.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.



