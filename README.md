# Quantum Catalyst Discovery Project
Electrolysis Simulation Project for QUAC 605, based on the ***"Challenge 1: Characterizing Candidate Materials for Electrolysis Catalysts for Water Splitting."***

## Glossary

- **Catalyst:** A substance that speeds up a chemical reaction without being consumed or changed in the process. In water splitting, catalysts lower the energy required to produce hydrogen[1].
- **Electrolysis:** Using electricity to split water (H₂O) into hydrogen (H₂) and oxygen (O₂)[1].
- **Water Splitting:** The process of decomposing water into hydrogen and oxygen gases, essential for clean hydrogen production[1].
- **Ground-state Energy:** The lowest possible energy that a material or molecule can have, important for determining its stability and efficiency as a catalyst[1].
- **Hamiltonian:** A mathematical function that represents the total energy of a system, including kinetic and potential energies. In quantum computing, Hamiltonians are mapped so computers can simulate molecular behaviors[1].
- **Fermion:** A particle, such as an electron, that follows the Pauli exclusion principle (two cannot occupy the same state)—essential in modeling materials at the atomic level[1].
- **Qubit:** The basic unit of quantum information, similar to a bit in classical computing, but can represent more complex states for powerful calculations[1].
- **Fermion-Qubit Mapping:** Mathematical techniques that convert the behavior of electrons (fermions) in molecules into a format that quantum computers (which use qubits) can understand—Jordan-Wigner, Bravyi-Kitaev, and Parity Mapping are common methods[1].
- **Variational Quantum Eigensolver (VQE):** A quantum algorithm used to estimate the ground-state energy of a molecule, making it possible to simulate which catalyst materials are most efficient[1].
- **Hybrid Quantum-Classical Algorithm:** An approach that combines quantum and traditional computing methods to solve challenging problems, often used in early practical quantum applications[1].
- **Adsorption Energy:** The energy required for a molecule (like hydrogen or oxygen) to attach to a catalyst, which influences the efficiency of the reaction[1].

## Project Description: Setup, Development, and Testing

This project uses quantum computing to identify and optimize catalyst materials for water splitting, focusing on clear stepwise processes, small models, and reproducible comparisons[1].

### 1. Setup

- Select a simple, representative catalyst material (a basic molecule relevant to water splitting)[1].
- Build a mathematical model (Hamiltonian) for the material and catalytic environment[1].
- Use classical chemistry tools to extract model parameters (one- and two-electron integrals)[1].
- Map quantum states describing electron behaviors into qubit representations using Jordan-Wigner or Bravyi-Kitaev mappings[1].

### 2. Development

- Implement a Variational Quantum Eigensolver (VQE) or a similar quantum-classical algorithm to estimate ground-state energy and adsorption energies[1].
- Incorporate classical pre-processing (e.g., geometry optimization) and post-processing (e.g., data visualization)[1].
- Use open-source tools like Qiskit Nature, OpenFermion, PySCF, or Psi4 to build and execute simulations[1].
- Clearly document every step to ensure ease of understanding and reproducibility[1].

### 3. Testing

- Benchmark results against reference catalysts such as platinum or iridium oxide[1].
- Repeat the pipeline for other candidates and compare their performance[1].
- Visualize and interpret results, highlighting which materials show practical promise[1].
- Identify workflow challenges and note future improvements possible as quantum technologies advance[1].

## References

QAI Ventures Canada, Quantum City, University of Calgary. (2025). Challenge 1: Characterizing Candidate Materials for Electrolysis Catalysts for Water Splitting. In GenQ Hackathon Challenge Set, Calgary[1].

Sources
[1] [QAI Ventures MQUAC Project 1 Materials for Energy](docs/QAI_Ventures_MQUAC_Project_1_Materials_for_Energy.pdf)