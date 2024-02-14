---
title: "Projects"
date: 2024-02-14
layout: "projects"
slug: "projects"
menu:
    main:
        weight: -70
        params: 
            icon: archives
---


#### Complete List of  Projects
- [8080 Emulator](https://github.com/WaywardPhoton/Emulator8080) (Software - 2022). Creating an emulator of the 8080 chip in C++. Researching and implementing opcodes, creating a method for simulating and handling interrupts. Implementing graphics using OpenGL. Currently in progress.

- [Superconducting Circuit Design](/Superconducting_Report.pdf) (Hardware - 2021). Term project for a course on superconducting circuit design. A circuit containing multiple co-planar waveguide resonators operating within a range of 4-8 GHz with and without SQUID arrays is designed and laid out for fabrication. The SQUIDs are used to shift the resonance frequency of the resonator when added in series with them
and the lone resonators are used as fail-safe designs. The fabricated design will be tested in a cryostat at 4K and probed with a VNA to determine whether the resonance shift is detectable. If successful, circuit will provide a future way to multiplex and readout superconducting nanowire single photon detectors. 

- [Quantum Fourier Transform Kata](https://github.com/microsoft/QuantumKatas/tree/main/QFT) (Software - 2021). Contributed to open-source Q# quantum computing programming repo. Developed workbook solutions to increasingly challenging set of exercises. Made use of both my teachign and math backgrounds to develop clean, concise, and simple solitions to the problems. My contributions were succesfully integrated into the Quantum Katas repository.  

- [Spin Qubits Simulation](/ENGR_542_Term_Paper.pdf) (Software - 2021). In this term project, important properties of hole spins in single and double quantum dots (QDs) were investigated using a scripted Kohn-Luttinger solver and Hamiltonian based on [Mutter and Burkard](https://journals.aps.org/prresearch/abstract/10.1103/PhysRevResearch.3.013194). Fascinating properties of spin-flip and spin-conserving tunneling in double quantum dots were discovered.

- [Variational Quantum Eigensolver](https://github.com/WaywardPhoton/QSciTech-QuantumBC-Workshop-Team4-Solution) (Software - 2021). As part of a Quantum BC workshop team, we created a variational quantum eigensolver (VQE) that finds the ground state energy of the hydrogen (H2) molecule on IBM's quantum computer. We use Jordan-Wigner mapping to map the fermionic operators to Pauli matrices. Noise mitigation is also applied to give a better solution. We won third place in the competition. 

- [1 GHz Amplifier Design and Testing](/ENGR470_Lab5-Report_Group1.pdf) (Hardware - 2020). Designed a 1GHz amplifier in AWR using an NXP BFR520 NPN microwave transistor. The design was be implemented on a Rogers RO4350 substrate. 
Mathcing circuits were designed and implemented using microstrip transmission lines. The amplifier was required have a gain of >10dB at the centre frequency, a bandwidth of 200MHz, and a input return loss of no greater than -11dB. After fabrication the amplifier was tested and met these specifications. 

- [FDTD Simulation](https://github.com/WaywardPhoton/2-D-FDTD) (Software - 2020). A 2-D Finite-Difference Time Domain simulator was built (Matlab) to simulate the propagation of EM waves originating from a gaussian beam source. A perfectly matched layer (PML) is implemented based on the description in Computational Electrodynamics by Taflove (2005). 
The simulator can be configured to incorporated transmission and reflection across a variety of materials. In this case, a sphere with a refractive index of 1.5 was simulated (below). At the end, the maximum of the E and H-fields obtained can be plotted as a heat map. This code was used in research to facilitate the design of retro-reflecting spheres. 

![image](FDTD.PNG)


- [3-Phase DC Motor](https://youtu.be/joJTcCTw8yg) (Hardware - 2019). A 3-Phase DC motor was designed using 3-D printed magnetized plastic and neodymium magnets. Chassis designed in Solidworks and printed at UBCO. Enameled copper wire was used for the wiring. The motor was contolled using a cheap ESC module. 

![image](Dr3Phase.jpg)

