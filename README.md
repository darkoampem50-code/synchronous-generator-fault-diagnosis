# Synchronous Generator Fault Diagnosis using Machine Learning

Final-year project applying machine learning to fault classification and predictive
maintenance in synchronous generators, combining a MATLAB/Simulink electrical
simulation with Python-based model development.

## Overview

A synchronous generator was simulated in MATLAB/Simulink to generate operating data
under healthy conditions and under two common fault types (rotor and stator faults).
This data was then used to train and compare four machine learning models for
automated fault classification, with the goal of supporting predictive maintenance
in power system operations.

## Models Compared

- Artificial Neural Network (ANN)
- Support Vector Machine (SVM)
- Random Forest
- Decision Tree

**Best result:** up to 90% classification accuracy.

## Repository Contents

| File | Description |
|---|---|
| `GEN2.slx` | MATLAB/Simulink model of the synchronous generator |
| `healthy_gen.csv` | Simulated data — healthy operating condition |
| `rotor_fault.csv` | Simulated data — rotor fault condition |
| `stator_fault.csv` | Simulated data — stator fault condition |
| `bearing_fault.csv` | Simulated data — bearing fault condition |
| `project_work1.ipynb` | Python notebook — data processing, model training, and evaluation |

## Tools & Libraries

- MATLAB/Simulink (generator simulation)
- Python — NumPy, Pandas, scikit-learn, Matplotlib

## Approach

1. Simulated a synchronous generator under healthy and faulty operating conditions in
   MATLAB/Simulink
2. Exported simulation outputs as labeled datasets (healthy, rotor fault, stator fault)
3. Preprocessed and prepared the data for classification in Python
4. Trained and evaluated ANN, SVM, Random Forest, and Decision Tree classifiers
5. Compared model performance to identify the most effective approach for fault
   classification

## Author

Darko Ampem Yeboah
Final-Year Electrical & Electronics Engineering Student, University of Mines and
Technology, Tarkwa
