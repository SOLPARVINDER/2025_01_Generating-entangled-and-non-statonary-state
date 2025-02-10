# 2025/01 Entanglement Generation and Non-Stationary States

This repository contains the codes associated with the work:

**"Generation of Entanglement and Non-Stationary States via Competing Coherent and Incoherent Bosonic Hopping"**

by *Parvinder Solanki, Albert Cabot, Matteo Brunelli, Federico Carollo, Christoph Bruder, and Igor Lesanovsky.*

## Dependencies

### Python (Version 3.12.3)
The following libraries and their respective versions are required:
- **QuTiP**: 4.7.5  
- **NumPy**: 1.26.4  
- **Matplotlib**: 3.6.3  
- **SciPy**: 1.11.4  

### Julia (Version 1.10.5)
The following libraries are required:
- **DiffEqBase** v6.155.1  
- **QuadGK** v2.11.1  
- **DiffEqCallbacks** v3.9.1  
- **OrdinaryDiffEq** v6.89.0  
- **LinearAlgebra**  
- **Distributed**  

## Folder Structure
All the codes are contained in the following directories:

### 1) `Correlations`
- Contains the code for calculating entanglement, quantum discord, and classical discord.
- Relevant figures: **Fig. 3(a,c) (main text), Fig. S2, S3 (supplemental material).**

### 2) `Eigenspectra`
- Contains the code for computing the eigenspectra of the Liouville superoperator for different system sizes.
- Relevant figures: **Fig. 2(g-i) (main text).**

### 3) `Mean-field_Dynamics`
- Contains the code for generating data and plots related to the mean-field dynamics of the system.
- Relevant figures: **Fig. 2, Fig. 3(d) (main text), Fig. S1 (supplemental material).**

### 4) `Exact_Dynamics`
- Contains the code for evolving the master equation for different system sizes.
- Relevant figures: **Fig. 2(d-f) (main text).**

### 5) `Spin_equivalent_model`
- Contains the code for evolving the spin-equivalent model of the Bose-Hubbard model.
- Includes both mean-field equations and exact time evolution of the master equation for different system sizes.


---
For any questions or clarifications, please refer to the manuscript or contact the authors.

