# LTC-Model-with-Transfer-Learning

## Overview

This repository provides the Python implementation of a **Liquid Time-Constant (LTC)** neural network integrated with a **Transfer Learning (TL)** framework for predicting the dynamic behavior of a modified **CIGRE Active Distribution Network (ADN)** interconnected with the **IEEE 9-bus Transmission System (TS)**.

The repository also includes the datasets used in this study. These datasets were generated using **MATLAB R2024b**, where the source-domain dataset consists of extensive measurements collected under normal operating conditions, while the target-domain dataset comprises a limited number of samples obtained when the transmission system is subjected to a three-phase short-circuit fault at Bus 8 as a case study. Together, these datasets support the implementation, validation, and reproducibility of the proposed transfer learning framework.

This repository accompanies the manuscript entitled **"Adaptive Liquid Time-Constant Equivalent Dynamic Model with Transfer Learning for Active Distribution Networks with Grid-Forming IBRs,"** submitted to **IEEE Transactions on Smart Grid**, by **Moetasem Ali** and **Yasser Abdel-Rady I. Mohamed**.



## Software Requirements

The proposed LTC-based Transfer Learning framework was developed and tested using the following software environment:

### Operating System
- Windows 11 (64-bit)

### Programming Environment
- Python 3.11 (recommended)
- Jupyter Notebook or Google Colab

### Development Environment
- Visual Studio Code (recommended) or any Python IDE

### MATLAB
- MATLAB R2024b (used only for dataset generation)
