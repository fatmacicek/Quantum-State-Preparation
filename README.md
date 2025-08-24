# Quantum State Preparation

In this Python code, I defined a Qiskit function called <em>qsp_circuit</em> which takes a complex vector of dimension 2^n as its input, and creates a circuit that produces a corresponding quantum state with coordinates of the vector as its coefficients. I also included some examples and provided an explanation of the construction. 

The construction is based on induction on the number of qubits $n$. For small values of $n$ such as $1$ and $2$, I used $R_Z$ rotation gates and their controlled versions, with the phases obtained from the inverse cosine function and the coordinates of the vector. 

This was a mini project that I completed during the Quantum Computing Bootcamp at [the Erdős Institute](https://www.erdosinstitute.org/) during summer 2025. The project was proposed by [Dr. Ákos Nagy](https://akosnagy.com/).  
