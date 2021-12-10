# QuaCK  
Quantum Classification Kernel

## Abstract
Quantum computing is one of the most promising new technologies. Unlike classical computers, quantum computers have the peculiarity of being made up by qubits.
They permit us to exploit the properties of quantum mechanics to better the performance and computational capabilities. One of such properties is quantum entanglement, that can be obtained by applying *quantum gates* like the Hadamard and the C-NOT gate.


Furthermore, quantum computing allows us to have, instead of the classical binary state, a superposition of states like $\ket{\Psi}=\alpha \ket{0}+ \beta \ket{1}$, where $\ket{0}$ and $\ket{1}$ are the quantum states representing the qubits.


Machine learning is the branch of Artificial Intelligence that takes inspiration from the learning ability of the brain, trying to emulate it via algorithm. 
*Support vector machines* and *kernels* are used for classification problems, and they belong to the class of *supervised* machine learning methods, meaning that they learn by example. 


Support vector machines are a learning model that map a n-dimensional dataset into a space of dimension m, with $m > n$, until the data appear to be separable by a hyperplane.


The kernel function is employed to simplify and speed the operation, because the computational cost rises while m gets bigger.
This is the reason why it is convenient to use the quantum counterparts of these classification methods, like *quantum support vector machines* and *quantum kernels*.  


Qubits are fragile states, prone to error, but their usage allows a noticeable computational speed-up. Thanks to quantistic properties, quantum computing can manage faster high dimensional spaces.


In the first part of this thesis it is described the meaning of machine learning, focusing on kernel methods and support vector machines and explaining the definitions of support vector, margin and hyperplane and how they are used in data classification.
The case of separable data and overlapped data is then given and analysed, together with the fundamental statistical learning notions. 


Then, Python codes  from *scikit-learn* are shown so that we can familiarise with kernel and SVM classification methods. 


After that, quantum computers are introduced, describing the *quantum stack* and how it is possible to go from the qubit hardware to the user interface, touching on the *Qiskit* programming language.
After an introduction on quantum computing, are given examples of quantum gates and quantum circuits and their usage.

Then, *quantum machine learning* is explained together with the definitions of quantum kernel, quantum feature map and quantum SVM.
 Qiskit, a Python-based programming language, with the ```qiskit_machine_learning```, module are used through the IBM Quantum Lab platform, that lets users run code on real quantum computers.


A classification example is then given analysing the ```adhoc_dataset``` with the algorithm support vector machine classification ```SVC``` from ```scikit-learn```.
Next, the kernel matrix is computed though the class ```QuantumKernel``` and ```ZZfeaturemap```. The possibility to define a *custom* kernel is shown. Subsequently the matrixes *adhoc training kernel* and *adhoc testing kernel* are calculated.


After that, the ```breast_cancer``` dataset from ```qiskit.ml.dataset``` is analysed with the ```QSVM``` algorithm and the ```ZZfeaturemap```.


Finally for each dataset we compare for the classical and quantum case, finding the *success ratio*, the classification time and kernel matrix. This demonstrates how quantum computing can be more efficient. 
