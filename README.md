# Measurement-Error-Mitigation-with-Qiskit
Measurement Error Mitigation is an important tool for Error correction given that it does not make use of extra quantum hardware sources. Here, we have implemented the Calibration matrix of the standard quantum teleportation protocol.

The main procedure considers the three qubits which are used to teleport the input qubit state and the gates that construct this circuit. For this, we can check that the code possesses the usual direction in which the gates are applied and their reversal, given that we can use the Unitary condition that they are supposed to accomplish. Then, we can see that we are changing the basis on which they are being measured. 

As it is commented at the end of the notebook, it is important to check that the corrected data correctly accomplish a probability density distribution. It could be implementation, for example, making use of the Least Squares method.
