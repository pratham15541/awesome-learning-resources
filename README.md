# Quantum Computing Resource

A practical, beginner-friendly roadmap to start learning quantum computing with Python and Qiskit.

This repository is designed for self-study over 12 weeks, with a balance of reading, videos, and hands-on coding.

## Who This Is For

- Beginners with basic Python knowledge
- Students who want a clear path from fundamentals to algorithms
- Developers who want to build quantum projects step by step

## Learning Path Overview

| Phase   | Timeline  | Focus             | Output                                         |
| ------- | --------- | ----------------- | ---------------------------------------------- |
| Phase 0 | Day 1     | Setup             | Ready-to-code environment                      |
| Phase 1 | Week 1-2  | Basics            | Understand qubits, superposition, entanglement |
| Phase 2 | Week 3-5  | Circuits + coding | Build and measure multi-qubit circuits         |
| Phase 3 | Week 6-8  | Algorithms        | Implement Grover and explore Shor/QFT          |
| Phase 4 | Week 9-12 | Applications      | Build mini real-world demos                    |
| Phase 5 | Optional  | Deep theory       | Use Nielsen & Chuang as a reference            |

## Phase 0: Setup (Day 1)

### Required tools

- Python (required)
- Qiskit
- Jupyter Notebook

### Quick start

1. Install Python 3.10+.
2. Create and activate a virtual environment.
3. Install dependencies:

```bash
pip install qiskit jupyter
```

4. Start notebook environment:

```bash
jupyter notebook
```

### Platform setup

- Create an account on IBM Quantum Experience:
  https://quantum.ibm.com/

## Phase 1: Basics (Week 1-2)

### Book

- [Quantum Computing for Everyone (Chris Bernhardt)](books/quantum-computing-for-everyone.pdf)

### Free videos

- Search YouTube: Quantum Computing Full Course freeCodeCamp
- IBM Quantum beginner playlists

### Topics

- Qubits
- Superposition
- Entanglement
- Basic gates: H, X, CNOT

### Practice

- Create your first Qiskit circuits
- Try a single-qubit Hadamard circuit
- Build and measure a Bell state

## Phase 2: Circuits + Coding (Week 3-5)

### Book

- [Programming Quantum Computers: Essential Algorithms and Code Samples (Eric R. Johnston et al.)](books/programming-quantum-computers-essential-algorithms-and-code-samples.pdf)

### Videos

- IBM Qiskit tutorials (YouTube)
- Search YouTube: Qiskit full tutorial Python

### What you will learn

- Circuit construction patterns
- Measurement and result interpretation
- Multi-qubit systems

### Mini projects

- Quantum coin toss
- Bell state generator
- Quantum teleportation demo

## Phase 3: Algorithms (Week 6-8)

### Book

- [Quantum Computing: A Gentle Introduction (Eleanor Rieffel)](books/Quantum%20Computing%20A%20Gentle%20Introduction%20%E2%80%94%20Eleanor%20Rieffel.pdf)

### Videos

- Search YouTube: Grover algorithm explained
- Search YouTube: Shor algorithm simple explanation

### Topics

- Grover's algorithm
- Shor's algorithm (concept + small simulation)
- Quantum Fourier Transform (QFT)

### Projects

- Grover search implementation
- Small-number Shor simulation

## Phase 4: Advanced + Real World (Week 9-12)

### Book

- [Quantum Computing: An Applied Approach (Jack D. Hidary)](books/Quantum%20Computing%20An%20Applied%20Approach%20by%20Jack%20D.%20Hidary.pdf)

### Talks and videos

- IBM Quantum talks
- Google Quantum AI talks

### Topics

- Optimization problems
- Quantum machine learning basics
- Industry use cases

### Projects

- Basic portfolio optimization toy model
- Quantum random number generator
- Hybrid classical ML + quantum demo

## Phase 5: Deep Understanding (Optional)

### Reference text

- [Quantum Computation and Quantum Information (Nielsen & Chuang)](books/quantum-computation-and-quantum-information-nielsen-chuang.pdf)

Use this as a long-term reference while you continue building projects. Do not feel pressured to finish it in one pass.

## Weekly Time Plan

- 1-2 hours per day
- 5-6 days per week

Recommended split:

- 40% coding
- 30% videos
- 30% reading

## Suggested Project Portfolio

If you are building a portfolio, include:

1. Hadamard and measurement notebook
2. Bell state + entanglement notebook
3. Quantum teleportation notebook
4. Grover implementation notebook
5. Small Shor simulation notebook
6. One applied demo from Phase 4

## Repository Structure

- books/: Recommended reading materials used by this roadmap

## Contributing

Contributions are welcome. See CONTRIBUTING.md for how to submit:

- Code examples
- Tutorials and notebooks
- Book and learning resource recommendations
- Fixes and improvements to this roadmap
