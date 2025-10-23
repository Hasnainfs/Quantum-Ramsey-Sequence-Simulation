<p align="center"><b>Name: Muhammad Hasnain</b></p>

---

### 🧪 **Project Summary: Quantum Ramsey Sequence Simulation**

In this project, a **single-qubit Ramsey interferometry sequence** was implemented using **Qiskit and the Aer simulator** to estimate the effect of a magnetic field on the qubit. The quantum circuit consisted of:

1. **Initial Hadamard gate** to create a superposition.  
2. **Rz rotation** simulating the free evolution of the qubit under a magnetic field.  
3. **Second Hadamard gate** to complete the Ramsey sequence.  
4. **Measurement** in the computational basis.

---

**🔹 Simulation Results (1000 shots):**
- **Measurement counts:** `{'0': 995, '1': 5}`  
- **Probability of |0⟩ state:** `0.995`  
- **Estimated magnetic field:** `0.142` *(arbitrary units)*

---

### 🎯 **Conclusion**

These results demonstrate that the qubit remains mostly in the |0⟩ state, and the Ramsey sequence effectively encodes the magnetic field into the qubit's phase.  
This experiment validates the use of **quantum circuits for precise phase estimation**.

---

### ▶️ **Run on Google Colab**

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Hasnainfs/Quantum-Ramsey-Sequence-Simulation/blob/main/Quantum_Ramsey_Simulation.ipynb)
