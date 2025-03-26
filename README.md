# Master Thesis Project Hub

Welcome to the central hub for my master thesis work, maintained by **amir0135**. This repository serves as the main access point for all supplementary code, resources, and documentation related to the project. The thesis explores the integration of machine learning models with FPGA hardware to achieve high-performance computing.

> **Note:** The full master thesis document (the written research and findings) is maintained in a separate repository.  
> You can find the master thesis itself at:  
> [https://github.com/amir0135/Master-thesis/tree/main](https://github.com/amir0135/Master-thesis/tree/main)

## Repository Structure

- **README.md:** This file provides an overview, setup instructions, and navigation details.
- **docs/**: Contains additional documentation, presentations, and supplementary materials.
- **ML_SME_FPGA-main/**: (Submodule) Contains the FPGA integration code and environment setup.
- **Feedforward-Network/**: (Submodule) Implements the feedforward neural network used in the project.

## Step-by-Step Setup Instructions

### Step 1: Cloning the Repository with Submodules

To clone this repository along with its submodules, run:


git clone --recurse-submodules https://github.com/amir0135/Master-Thesis-Project-Hub.git

This command ensures that both the hub and the linked projects (submodules) are cloned together.

### Step 2: Initializing and Updating Submodules (If Already Cloned Without Them)

If you’ve already cloned the repository without using the --recurse-submodules flag, initialize and update the submodules with:

git submodule update --init --recursive

### Step 3: Exploring the Components

ML_SME_FPGA-main
	•	Location: ML_SME_FPGA-main/
	•	Purpose: Contains the code for FPGA integration, including the setup for deploying machine learning models on FPGA hardware.
	•	Next Steps: Navigate to this directory and follow the README within it for FPGA-specific instructions, simulation, and deployment.

Feedforward-Network
	•	Location: Feedforward-Network/
	•	Purpose: Houses the implementation of the feedforward neural network used in the thesis.
	•	Next Steps: Navigate to this directory and check its README for details on running simulations and testing the neural network.

Master Thesis Document
	•	The complete written master thesis (research, analysis, and findings) is hosted separately.
	•	Access it here: Master-thesis Repository

### Step 4: Accessing Additional Documentation

Additional thesis documentation, experimental results, and presentations are available in the docs/ directory of this repository.

Project Overview

This thesis project aims to:
	•	Integrate Machine Learning with FPGA: Leverage FPGA hardware to accelerate machine learning computations.
	•	Implement a Feedforward Neural Network: Develop and simulate neural network models, then evaluate their performance in a hardware-accelerated environment.
	•	Evaluate and Document Performance: Provide detailed evaluations, challenges, and optimizations achieved through the integration of ML and FPGA.

Contributing

Contributions, suggestions, or improvements are welcome! If you’d like to contribute:
	1.	Fork the repository.
	2.	Create your feature branch.
	3.	Commit your changes with clear documentation.
	4.	Submit a pull request for review.

License

This project is licensed under the MIT License. See the LICENSE file for more details.

Acknowledgments

Special thanks to my advisors, colleagues, and everyone who supported this research. For questions or further information, please contact me at [your.email@example.com].



