```python

from qiskit import * # import functionailty 

qc = QuantumCircuit(1,1) # make a circuit

phi=qiskit.quantum_info.random_statevector(2).data  # random state

qc.initialize(phi,0)  # initilaize 

```
