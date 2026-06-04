# Quantum Computing Fundamentals with Qiskit

1st notebook demonstrates the fundamental quantum gates and quantum states used in quantum computing.

Topics Covered:

- Hadamard (H) Gate
- Pauli-X Gate
- Pauli-Y Gate
- Pauli-Z Gate
- Phase Gates (S and T)
- CNOT Gate
- Controlled-Z Gate
- Controlled-S Gate
- SWAP Gate
- Bell State
- GHZ State


2nd notebook demonstrates two of the most famous quantum communication protocols:

## Topics Covered

### Quantum Teleportation

Transfer an unknown quantum state from Alice to Bob without physically sending the qubit.

Concepts:

* Entanglement
* Bell States
* Measurement
* Classical Communication
* Conditional Operations

### Superdense Coding

Send two classical bits of information by transmitting only one qubit.

Concepts:

* Entanglement
* Quantum Encoding
* Bell Basis Measurement
* Information Compression


3rd notebook demonstrates two historic quantum algorithms:

## Algorithms Covered

### Deutsch Algorithm

Problem:

Determine whether a function:

f(x)

is:

* Constant
* Balanced

using only ONE oracle call.

Classically:

Up to 2 evaluations required.

Quantum:

Only 1 oracle evaluation.

---

### Deutsch-Jozsa Algorithm

Generalization of Deutsch Algorithm.

Determine whether a function:

f(x)

is:

* Constant
* Balanced

for n-bit inputs.

Classically:

Requires up to 2^(n-1)+1 evaluations.

Quantum:

Requires only ONE oracle evaluation.

---


## Requirements

pip install qiskit qiskit-aer matplotlib pylatexenc

---


Author: Muhammad Saad
