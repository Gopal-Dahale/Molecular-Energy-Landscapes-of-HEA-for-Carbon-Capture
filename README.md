# Molecular Energy Landscapes of HEA in Quantum Computing for Carbon Capture

## Team Jetix

Members: Gopal Ramesh Dahale, Tom Magorsch and Amey Bhatuse

## Abstract
One of the frontiers for the Noisy Intermediate-Scale Quantum (NISQ) era’s practical uses of quantum computers is quantum chemistry. By employing Hybrid Quantum Classical Optimisation we aim to investigate the minimum of the Ground Potential Energy Surface (PES) of the BeH2 molecule. Furthermore, we develop an algorithm that efficiently calculates the minimum of the PES for systems related to CO2 capture using MOFs. We use a Variational Quantum Eigensolver (VQE) and focus on exploring the power of hardware-efficient ansatzes to improve the convergence of finding the ground state energy of the molecules. We study the latest paper published in this domain: [Molecular Energy Landscapes of Hardware-Efficient Ansätze in Quantum Computing Boy Choy* and David J. Wales](https://pubs.acs.org/doi/pdf/10.1021/acs.jctc.2c01057) (published on 7th Feb 2023) where the authors propose a simple deparameterisation procedure that reduces the number of trainable parameters while retaining high accuracy for the global minimum, simplifying the energy landscape, and hence speeding up optimization.

## Files

1. The first is the `qhack-simulation.ipynb` which describes the problem statement and simulates the ansatzes. 
2. Based on the deparameterised circuits obtained in the previous step, `qhack-hardware.ipynb` executes them on real hardware.
3. Although, the notebooks are self contained, `report.pdf` summarizes all the problem statement, methodology, results and conclusion.
