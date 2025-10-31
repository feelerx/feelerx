<table border="0">
 <tr>
    <td>
      <br>
     <p align="center"><img src="https://readme-typing-svg.herokuapp.com/?ont=Righteous&size=35&center=true&vCenter=true&width=500&height=70&duration=4000&lines=Hi+There!+👋;"/>
    <td>
      <img alt="gif" src="./soloo.gif">
   </td>  
 </tr>  
</table>

I'm a quantum computing researcher and software developer. I work on quantum compilation, build backend systems, and explore how to bridge classical and quantum software stacks.
I graduated (2023) and I'm focused on making quantum computing more practical through better compiler infrastructure and systems-level optimization.

Recent work I'm proud of
Published paper in Springer (2025) comparing quantum circuit simulation approaches in C and Python. We analyzed the trade-offs between performance and extensibility across different implementation strategies. Read it here
Invited speaker at the National Polytechnic Institute Baja California (Oct 2025) where I presented on integrating QIR into C-based quantum-classical frameworks. Also spoke at Qiskit Fall Fest Nigeria about quantum compilation.
Won the Unitary Hackathon bounty (2024) for implementing QIR Base and Adaptive Profile compliant QASM conversions in qBraid-qir.

Open source contributions
Most of my contributions are to qBraid/qbraid-qir, where I work on QIR compilation workflows:
#225 — Built the Adaptive Execution Profile system with measurement state tracking and register-based output recording. This lets different quantum execution models be defined via JSON profiles.
#228 — Implemented QIR Base Profile compliance, adding measurement state tracking to prevent operations on measured qubits and enforce proper reset requirements.
#248 — Refactored Cirq preprocessing to use optimize_for_target_gateset, fixing issues where supported gates were being unnecessarily decomposed.

Projects
Quantum Software:

C_qir — A compiler that converts quantum instructions written in C to QIR bytecode. The goal is to enable direct quantum programming in C for any QIR-compatible backend.
qc_simulator — Quantum circuit simulator exploring different computational approaches. Implemented it in both C and Python to compare performance vs. extensibility trade-offs. This became the basis for my Springer paper.

Systems programming:

AutoFreer — Automatic memory management for C that's faster than Boehm GC. Built this after reverse-engineering MSVC's memory allocator for my undergrad thesis.
AutoGrad — Educational autodiff library in C for gradient computation experiments.

Web apps:

Picture Us — Django-based photo sharing app with real-time updates
GuesstheImpostor — Multiplayer web game built with FastAPI

Tech I work with
Quantum: Qiskit, QIR, CUDA-Quantum, Cirq
Backend: Python, Django, FastAPI, PostgreSQL, Redis, Docker
Systems: C, C++, x86 assembly, reverse engineering (Ghidra, x64dbg)

Research interests
I'm exploring how Quantum Intermediate Representation (QIR) can serve as a universal bridge between high-level quantum programming frameworks and diverse hardware backends. My current focus areas:

Adaptive quantum compilation using device-specific profiles
Hardware-aware circuit partitioning in distributed quantum networks
Systems-level optimization of quantum-classical interfaces
Making quantum compilation tooling more practical and accessible


**Full CV & Publications:** [here]()

## Contact

- LinkedIn: [here](https://www.linkedin.com/in/paul-onoja-9035a0220/)  
- Email: [here](onojaopaul@gmail.com)  

I’m always open to collaborations in quantum software, compiler research, and backend systems.

