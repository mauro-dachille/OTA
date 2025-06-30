# Optical Time Algorithm (OTA)

In "Configurable photonic simulator for quantum fields", we propose the Optical Time Algorithm (OTA) as a unified framework capable of simulating efficiently a large class of free quantum field dynamics using a single optical circuit design that separates the time from the Hamiltonian's structure.
More precisely, while a fixed array of beam splitters followed by a single layer of squeezers implements a largely arbitrary coupling geometry, the dynamics is entirely encoded in a single layer of phase shifters. This facilitates the simulation of the non-equilibrium dynamics of various quantum field theories without the need to ever alter the experimental design. 

This repository includes two Mathematica notebooks:
1. OTA.nb: it generates the optical parameters needed for a physical realization of the circuit (the only input needed for the script is the Hamiltonian matrix).
2. Figures.nb: it contains the scripts producing figures 4 and 5 of the paper. 

If you want to add new features to these notebooks, feel free to suggest pull requests!
