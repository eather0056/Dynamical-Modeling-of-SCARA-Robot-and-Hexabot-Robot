# Dynamical Modeling of SCARA Robot and Hexabot Robot

## Overview
This project focuses on the dynamical modeling of two distinct robotic systems: the SCARA Robot and the Hexabot Robot, under the guidance of Prof. Cédric Anthierens at the University of Toulon. Utilizing MATLAB and Simulink, the project delves into the kinematic and dynamic analyses of these robots, employing Denavit-Hartenberg (DH) parameters, Homogeneous Transformation Matrices, Jacobians, and the identification of singularities for the SCARA Robot, as well as the Hexabot Robot's frame analysis and Jacobian calculations.

## Project Components

### SCARA Robot
- **Robot Frame**: Analysis and definition of the SCARA robot's frame structure.
- **DH Parameters**: Application of Denavit-Hartenberg parameters to model the robot's joints and links.
- **Homogeneous Transformation Matrix**: Development of matrices to describe the robot's kinematics.
- **First Two DOF Analysis**: Special focus on the homogeneous transformation matrix for the first two degrees of freedom (DOF) from base to the third joint.
- **Jacobian Matrix**: Calculation of the Jacobian for the first two DOF links to analyze velocities and forces.
- **Singularities**: Identification and analysis of singular configurations of the SCARA robot.

### Hexabot Robot
- **Robot Frame**: Development of the Hexabot Robot frame with 3 DOF per leg.
- **DH Parameters**: Implementation of Denavit-Hartenberg parameters for the Hexabot's unique structure.
- **Homogeneous Transformation Matrix**: Construction of matrices to define leg kinematics.
- **First Two DOF Analysis**: Examination of the transformation matrix from the base to the third joint for the first two DOF.
- **Jacobian Matrix**: Derivation of the Jacobian matrix, with an emphasis on its application to the Hexabot's locomotion.
- **Translation Matrix**: Exploration of the translation matrix as part of the Jacobian analysis for understanding the Hexabot's translational movements.

## Project Structure
- `SCARA/`: MATLAB scripts and Simulink models specific to the SCARA Robot analysis.
- `Hexabot/`: MATLAB scripts and Simulink models for the Hexabot Robot modeling.
- `docs/`: Documentation including theory, model derivations, and project findings.
- `experiments/`: Experimental setup and results for both robots.
- `results/`: Visualizations, plots, and analysis outcomes from simulations.
- `README.md`: Project overview and instructions.

## Setup
Ensure MATLAB and Simulink are installed on your system to run the project.

1. Clone the repository to your local machine:
   ```
   git clone https://github.com/eather0056/Hexapod-Robot.git
   ```
2. Navigate to the project directory:
   ```
   cd Dynamical_Modeling_SCARA_Hexabot
   ```
3. Open MATLAB and set the project directory as your working directory.

## Usage
Navigate to either `SCARA/` or `Hexabot/` directories to access the relevant scripts and models:

1. Open the desired MATLAB scripts or Simulink models.
2. Execute MATLAB scripts directly or run Simulink models to perform the analyses and simulations.
3. Review the `docs/` and `results/` directories for detailed explanations and outcomes.

## Results
This project provides comprehensive dynamical models for both the SCARA and Hexabot robots, offering insights into their kinematic behaviors, control strategies, and potential singularities. Detailed results and discussions are available in the `results/` directory.

## Acknowledgments
This project was made possible through the guidance of Prof. Cédric Anthierens and the collaborative efforts of the robotics research group at the University of Toulon.
