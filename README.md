# A Modular Quantum Compilation Framework for Distributed Quantum Computing

I have tried to implement various parts of the Research Paper - "A Modular Quantum Compilation Framework for Distributed Quantum Computing". 
### 1. Qubits assignment 
  - Representing the Monolithic Quantum Circuit / sub-circuit in the form of a weighted undirected Graph
  - Perform K-way Partitioning of the Graph to minimize the cost of qubit assignment using Metis's Algo or Louvain Community Detection Algo as Provided by the NetworkX Library
### 2. Remote Gate Scheduler 
  - Ordering the execution of Remote Gates
  - Minimize the utilization of communication qubits
