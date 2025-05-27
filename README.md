
# Quantum Ransomware Simulation with Qiskit

This project presents a conceptual demonstration of **Quantum Ransomware**, leveraging Qiskit's capabilities to simulate how malware could propagate and compromise quantum communication endpoints. The experiment showcases how single-qubit and multi-qubit operations can be used to mimic a *Man-in-the-Endpoint* attack, contrasting it with traditional *Man-in-the-Middle* vectors that risk collapsing qubit states upon measurement.

This scenario highlights the growing need for robust **Quantum Security Frameworks**, particularly as quantum computing moves closer to practical, real-world deployment.

---

## 🔬 Experiment Overview

The simulation follows these main steps:

1. **Alice and Bob Simulation**: Alice and Bob operate with their own post-NISQ quantum devices using quantum registers.
2. **Message Sharing**: Alice uses a quantum oracle to generate and send a message to Bob in plaintext.
3. **Endpoint Compromise**: Eve has already compromised Bob’s endpoint, allowing for post-exploitation techniques.
4. **Quantum Malware Deployment**: Eve simulates a Command and Control (C2) register to inject malicious quantum operations, exfiltrate Bob’s information, and encrypt it—emulating a traditional ransomware attack in quantum form.

---

## 📦 Deployment

To run this project locally:

1. **Convert the notebook to a Python script**:
   ```bash
   jupyter nbconvert --to script your_notebook.ipynb
   ```

2. **Ensure the `.py` file is created** in your working directory.

3. **Execute the script** using Python:
   ```bash
   python your_notebook.py
   ```

---

## 📚 Documentation & Resources

- [IBM Quantum Experience](https://quantum-computing.ibm.com/)
- [Awesome Qiskit Learning Resources](https://qiskit.org/learn)
- [MITRE ATT&CK Enterprise Tactics](https://attack.mitre.org/tactics/enterprise/)
- [Attacking the Quantum Internet](https://arxiv.org/abs/2005.04617)

---

## 👥 Authors

- [@fvelazquez](https://github.com/fvelazquez-X)

---

## 💬 Feedback

If you have feedback or suggestions, contact:  
📧 **jvelazquez@notlan.mx**

---

## 📝 License

This project is licensed under the [MIT License](https://choosealicense.com/licenses/mit/).
