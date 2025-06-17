# Quantum State Preparation

This Python file defines a Qiskit function called <em>qsp_circuit</em> which, given a complex vector of dimension 2^n, creates a circuit that produces the corresponding quantum state. It also includes some examples and an explanation of the construction. 

The construction is based on induction. For small values of $n$ such as $1$ and $2$, $R_Y$ rotation gates and their controlled versions with angles obtained from the vector are used to produce the desired circuit.

This was a mini project that I completed during the Quantum Computing Bootcamp at [the Erdős Institute](https://www.erdosinstitute.org/) in summer 2025. The project was proposed by [Dr. Ákos Nagy](https://akosnagy.com/).  
