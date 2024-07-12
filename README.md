# Quantum Error Correction: Assignment 1 - Stabilizer Codes

## Overview
This repository contains the solutions and code for Assignment 1 on Stabilizer Codes in Quantum Error Correction (QEC). The assignment explores foundational concepts in QEC, including the construction of stabilizer codes, error detection and correction, and implementation of specific codes such as the 3-qubit code and the Shor code.


## Assignment Tasks
The assignment is structured into several questions, each focusing on different aspects of stabilizer codes in quantum error correction.

### Task 1: Stabilizers and Stabilizer Generators
- Given `n` qubits and `k` logical qubits, calculate the number of stabilizers and independent stabilizer generators required.

### Task 2: Constraints on Stabilizer Group
- Discuss the constraints on operators to form a stabilizer group.

### Task 3: Error Correction with Stabilizer Group
- Analyze the types of errors that a stabilizer code can correct.

### Task 4: 3-Qubit Repetition Code
- Identify the stabilizers for the 3-qubit repetition code.
- Implement the error correction pipeline for the 3-qubit code, including:
  - Constructing the encoder
  - Simulating a single qubit error
  - Performing non-destructive measurements of the stabilizer generators
  - Constructing a function to correct errors based on syndrome bits

### Task 5: Limitations of 3-Qubit Code
- Explain why the 3-qubit code cannot correct arbitrary errors, referencing the discretization theorem.

### Task 6: Minimum Qubits for Single Qubit Error Correction
- Determine the minimum number of qubits needed to correct any single qubit error.
- Write down the stabilizers for this code and implement the error correction pipeline.

### Task 7: Shor Code
- Study the Shor code, a composition of two 3-qubit codes.
- Write down the stabilizers for the Shor code.
- Analyze the error correction capability of the Shor code.
- Implement the Shor code in your favorite quantum computing library.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements
This assignment is based on foundational concepts in Quantum Error Correction. Special thanks to the authors of the foundational paper on QEC for their insightful contributions to the field.
