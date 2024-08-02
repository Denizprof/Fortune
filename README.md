# Fortune Programming Language

Fortune is a programming language designed for future quantum computers. Created by Daniel Deniz Akıncı, Fortune aims to make quantum computing more accessible and understandable by combining quantum and classical code blocks. This facilitates the writing of complex quantum algorithms in a more efficient manner.

## Key Features

- **Quantum Code Blocks**: For defining quantum operations.
- **Classical Code Blocks**: For defining traditional operations.
- **I/O Code Blocks**: For handling user input and output.

## Example Fortune Code

```plaintext
#("Fortune")#

(quantum=
# Define quantum operations
CREATE QUBITS 2;
HADAMARD QUBIT 0;
CNOT QUBIT 0, QUBIT 1;
MEASURE QUBIT 0, QUBIT 1;
)

(classical=
# Define classical operations
PRINT "Qubit measurements are complete";
)

(io=
# Define I/O operations
READ INPUT "Enter the number of qubits:";
WRITE OUTPUT "Results have been calculated";
)
