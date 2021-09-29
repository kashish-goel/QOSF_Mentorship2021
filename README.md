# QOSF_Mentorship2021
### Task 1 

Design a quantum circuit that considers as input the following vector of integers numbers: [1,5,7,10], returns a quantum state which is a superposition of indices of the target solution, obtaining in the output the indices of the inputs where two adjacent bits will always have different values. In this case the output should be: 1/sqrt(2) * (|01> + |11>), as the correct indices are 1 and 3.

### Approach
Created a circuit using X-Gate and CNOT-Gate to perform computation on the qubits and used the Logic behind the XOR gate to find if all the pairs of consecutive bitstrings in the binary number are '0' and '1'
The Approach works for the Bonus Task as well.
