### Quantum Logic Gates

#### Primitives

##### NSx Gate

Quantum computing is non-linear, however the Pauli Gates are linear, that is to say that they are deterministic gates. In order to achieve quantum computation that is more useful than classical simulation we have to introduce the element of non-linearity, or indeterministic states. To achieve this, we use modified versions of the Non-linear sign-flip gate or NSx Gate. The NSx Gate is a single-qubit operation that performs a phase-shift on one mode conditioned on two ancillary modes.


#### Measure

The measurement gate counts the number of photons in each mode for each qubit, to do this a silicon photomultiplier is used in both H and V modes.

#### Unitary Gates

##### Pauli-X Gate

The Pauli-X Gate performs a NOT operation or bit flip on a single qubit.
X|0> = |1>

##### Pauli-Y Gate

The Pauli-Y Gate rotates one qubit around the y axis, it looks similar to an X gate, but with a global phase diffrence of i or -i.
Y|0> = i|1> and Y|1> = -i|0>
Note: This Pauli gate does not invert itself.

##### Pauli-Z Gate

The Pauli-X Gate performs a NOT operation or bit flip on a single qubit, this time in the +/- basis.
Z|-> = |+>

##### Hadamard Gate

The Hadamard gate swaps basis states between 1/0 and +/-. It is often used to create a superposition.
H|1> = |+> , H|-> = |0> 

#### Controlled Gates

Controlled gates utilize nonlinear sign-flip gates to introduce non-linearity into our programs. These non-linearities are extremely difficult to simulate as they actually entangle our qubit states, whereas the Unitary qubit transformations are easy to simulate comparatively. Effectively this is what gives our quantum computer an edge over typically digital computing.
They act on two qubits, the Control and Target. If the Control is 1, the operation is carried out otherwise it isn't.

##### CX Gate

The Controlled-X Gate (shorthand: CX) performs a controlled NOT operation on two qubits. 

##### CY Gate

The Controlled-Y Gate (shorthand: CY) performs a controlled Pauli-Y operation on two qubits.

##### CZ Gate

The Controlled-Z Gate (shorthand: CZ) performs a controlled Pauli-Z operation on two qubits.



##### CH Gate

The Controlled-H Gate (shorthand: CH) performs a controlled Hadamard operation on two qubits.

