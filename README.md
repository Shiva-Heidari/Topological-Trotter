# Trotterized Simulation of the Kitaev Chain

This repository contains a suite of quantum simulation notebooks focused on the **Kitaev chain**, i.e., a 1D model of spinless fermions that exhibits **topological superconductivity** and supports **Majorana edge modes**. The simulations implement **Trotterized time evolution** using [Qiskit](https://qiskit.org) and analyze quantum observables and entanglement growth over time.

---

## Project Goals

- Simulate fermionic models via **Jordan–Wigner mapping** to qubit operators.
- Implement **Trotterized time evolution** of the Kitaev chain.
- Track local observables, multi-site correlations, and **entanglement entropy**.
- Benchmark the accuracy of Trotter methods via **fidelity comparisons**.
- Explore physical signatures of **topological order** in small systems.

---

## Repository Structure

```bash
.
├── notebooks/
│   ├── 1_two_qubit_kitaev.ipynb              # 2-site Kitaev chain with Pauli evolution
│   ├── 2_three_qubit_kitaev.ipynb            # 3-site chain with extended observables
│   ├── 3_four_qubit_kitaev_entropy.ipynb     # 4-site chain + bipartite entanglement entropy
│   ├── 4_trotter_vs_exact_fidelity.ipynb     # Fidelity between Trotter and exact evolution
│
├── requirements.txt                          # Python dependencies
├── README.md                                 # Project overview (this file)
