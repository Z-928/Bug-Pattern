# BUG-PARTTENS

## Type:    

&emsp;__IG__: Incorrect uses of quantum gates    
&emsp;__MI__: Measurement related issue   
&emsp;__IS__: Incorrect initial state   
&emsp;__PE__: Parameters error   
&emsp;__CM__: Command misuse   
&emsp;__CE__: Call error  
&emsp;__QE__: QASM error   
&emsp;__DO__:Discarded orders




## 1.[Initialize](./Initialize/README.md)   
&emsp;[__IIS__:The number of qubits used in the Qobj is higher than the number of quantum registers defined in the Qobj](https://github.com/Z-928/BUG-PARTTENS/blob/main/Initialize/Examples/The%20number%20of%20qubits%20used%20in%20the%20Qobj%20is%20higher%20than%20the%20number%20of%20quantum%20registers%20defined%20in%20the%20Qobj.ipynb)  
&emsp;[__IIS__:Insufficient number of qubits](https://github.com/Z-928/BUG-PARTTENS/blob/main/Initialize/Examples/Number%20of%20registers%20exceed%20the%20number%20of%20qubits.ipynb)  
&emsp;[__IIS__:Insufficient length of classical registers](https://github.com/Z-928/BUG-PARTTENS/blob/main/Initialize/Examples/Qubits%20and%20classical%20bits%20do%20not%20have%20equal%20lengths.ipynb)   
&emsp;[__CM__:Wrong use of command leads to unrecognized parameters](https://github.com/Qiskit/qiskit-terra/issues/7032)  
&emsp;[__CE__:Object call error](https://github.com/Qiskit/qiskit-experiments/issues/302)  

## 2.[Gate Operation](./Gate-Operation/README.md)   

&emsp;[__IG__: The Qobj uses gates that are not among the backend’s basis gates.](https://github.com/Z-928/BUG-PARTTENS/blob/main/Gate-Operation/Examples/The%20Qobj%20uses%20gates%20that%20are%20not%20among%20the%20backend%E2%80%99s%20basis%20gates.ipynb)   
&emsp;[__PE__ :Instruction not in basis gates: instruction: {}, qubits: {}, params: {}](https://github.com/Z-928/BUG-PARTTENS/blob/main/Gate-Operation/Examples/Instruction%20not%20in%20basis%20gates.%20instruction%2C%20qubits%2C%20params.ipynb)   
&emsp;[__IG__: handle custom multi-qubit gates](https://github.com/Z-928/BUG-PARTTENS/blob/main/Gate-Operation/Examples/Gate%20%7B%7Din%20line%20%7B%7Ds%20not%20understood%20(%7B%7D).ipynb)   
&emsp;[__PE__:Incorrect qubit parameters in gates](https://stackoverflow.com/questions/64707625/visualizing-circuits-in-qiskit-with-matplotlib)  
&emsp;[__PE__:Using classical bits for entanglement](https://quantumcomputing.stackexchange.com/questions/9871/achieve-a-control-gate-with-2-hadamard-coins)     
&emsp;[__IG__:Random gate is not define](https://quantumcomputing.stackexchange.com/questions/9943/how-to-make-circuit-for-randomly-selected-gate)     
&emsp;[__CM__:Qiskit distinguishes operations in Gates which are misunderstood](https://github.com/Qiskit/qiskit-terra/issues/6540)  
&emsp;[__PE__:Same physical qubit used in one operation](https://quantumcomputing.stackexchange.com/questions/12076/real-device-error-mitigation-with-qiskit)  


## 3.[Uncompntation](./Deallocation/README.md) 

&emsp;[__PE__:Parameter error during decontrol operation](https://github.com/Qiskit/qiskit-terra/issues/3799)   
&emsp;[__IG__:Wrong uses of gates leads to incorrect reset](https://quantumcomputing.stackexchange.com/questions/5959/grovers-algorithm-returns-skewed-probability-distribution)  

## 4.[Measurement](./Measurement/README.md) 

&emsp;[__IM__:Ignoring the effects of measurement](https://github.com/Z-928/BUG-PARTTENS/blob/main/Measurement/Examples/Qubit%20measurement%20is%20followed%20by%20instructions.ipynb)   
&emsp;[__CM__:Redundant classical registers are created when measuring](https://github.com/Qiskit/qiskit-terra/issues/6571)  

## 5.Other Positions
&emsp;[__CE__: Import error](https://quantumcomputing.stackexchange.com/questions/6697/creating-and-running-parallel-circuits-in-qiskit)    
&emsp;[__CE__: Backends error](https://quantumcomputing.stackexchange.com/questions/7129/how-to-obtain-qubits-amplitude-in-qiskit)  
&emsp;[__CE__: Translate error](https://github.com/Qiskit/qiskit/issues/1337)  
&emsp;[__QE__: Issue with new from_qasm_str() method](https://github.com/Qiskit/qiskit-terra/issues/1446)  
&emsp;[__CM__: Wrong command used](https://github.com/Qiskit/qiskit-terra/issues/5249)  
&emsp;[__PE__: Not giving lists for coupling_map](https://github.com/Qiskit/qiskit/issues/1119) &emsp; [...](https://github.com/Qiskit/qiskit/issues/193)    
