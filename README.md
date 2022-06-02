
# A simple representation of a Quantum Ransomware

The following qiskit experiment presents a conceivable new technique of deploying malware into a Quantum System, using the advantages offered by Single-Qubit and Multi-Qubit operations on Quantum registers. It will examine the possibility of executing a Man-in-the-Endpoint vector using a Quantum Ransomware propagated during a conversation between two peers (Alice and Bob) showing an achievable way for exploiting Bob's endpoint and at the same time avoiding the measurement constraint of a Man-in-the-Middle attack, in which an eavesdropper can potentially collapse the qubit's state before its arrival. For the implementation of the communication schema and the attack scenario, Qiskit in the IBM Quantum Experience will be used to show accurately the feasibility of these techniques in future developments of Quantum Systems; hence from a practical perspective, the creation of a Quantum Security framework is thus becoming, urgent.

The main experiment is developed in the following steps (each piece of the code clarifies the points enumerated below):

1) Alice and Bob are being represented to have their particular post-NISQ device, (Alice and Bob registers)
2) A quantum oracle will be used by Alice to generate a message which will be shared to Bob in clear text.
3) Eve has already compromised Bob's device, therefore post-exploitation techniques are feasible. Eve's register is going to mimic the Command and Control deploying the malware.
4) Eve will upload a Quantum Malware to compromise the information Bob is suppose to receive. She will extract it and then encrypt it like a “traditional” Ransomware attack.





## Authors

- [@fvelazquez](https://www.github.com/fvelazquez-X)


## Acknowledgements

 - [Awesome qiskit learning resources]( https://qiskit.org/learn)
 - [Atacking the quantum internet](https://arxiv.org/abs/2005.04617)
 - [Enterprise tactics. ATT&CK](https://attack.mitre.org/tactics/enterprise/)


## Deployment

To run this project from a terminal using jupyter notebook:

- Firstly, you need to convert the jupyter notebook file which is in the format .ipynb to .py format using the jupyter nbconvert tool.
```bash
jupyter nbconvert --to <output format> <input notebook>
```

 Whereas, the <output format> is the desired output format. And the <input notebook> is the jupyter notbook filename.

- Verify whether .py file is created in your working directory.

- Finally, you could run a jupyter notebook .ipynb file from command prompt using the converted .py file as shown below.

```bash
   python MyFirstNotebook.py
```

## Documentation

[IBM Quantum Experience](https://quantum-computing.ibm.com/)


## Feedback

If you have any feedback, please reach out to us at jvelazqu@redhat.com


## 🚀 About Me

- 🔭 I’m an offensive security passionate working at [Red Hat](https://www.redhat.com/en)  
  

-  🔎 I’m currently learning more about [Quantum Technologies](https://quantum-explore.com/en/master/)   
  

- 📖 I recently wrote a book on Offensive Quantum Computing. Available at [Amazon](https://www.amazon.com/Introduction-Adversarial-Quantum-Computing-Practice-ebook/dp/B09YMJXQTX/ref=sr_1_1?crid=3VZONRJBAP2G3&keywords=fernando+velazquez+quantum&qid=1654154138&sprefix=%2Caps%2C138&sr=8-1)!!  
  

- ⚡ I publish articles on technology topics at  [Meer](https://www.meer.com/en/authors/390-fernando-velazquez)  


## License

[MIT](https://choosealicense.com/licenses/mit/)

