# ZK-SNARKs_Circuit

This project is an example of using zk-SNARKs to generate a proof of computation and verify it on an Ethereum network (Sepolia or Mumbai Testnet).
Create a circuit using the circom programming language that implements the following logical gate:

#Circuit Template: Multiplication Checker

#Description:
This circuit template checks whether the output signal 'Q' is the result of multiplying input signals 'a' and 'b'. It employs custom components 'AND', 'NOT', and 'OR' gates for its logic.

#Components:
- Multiplier2: The main template for the multiplication check circuit.
- AND: A custom AND gate component.
- NOT: A custom NOT gate component.
- OR: A custom OR gate component.

#Circuit Logic:
1. The 'AND' gate calculates the logical AND of input signals 'a' and 'b' and outputs it as 'X'.
2. The 'NOT' gate calculates the logical NOT of input signal 'b' and outputs it as 'Y'.
3. The 'OR' gate calculates the logical OR of signals 'X' and 'Y' and outputs it as the final result 'Q'.

#Usage:
1. Instantiate the main component 'Multiplier2'.
2. Provide input values 'a' and 'b'.
3. The circuit will output 'Q', which indicates whether 'a * b' is the same as the provided output 'Q'.

#Note:
This circuit template is designed for demonstration purposes and might not be optimized for practical use. It showcases the basic logic of AND, NOT, and OR gates implemented using custom components.

