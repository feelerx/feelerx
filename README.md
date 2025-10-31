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

I am a quantum computing researcher and software developer working at the intersection of **quantum compilation**, **systems engineering**, and **backend development**.  
I publish research on quantum-classical software stacks, contribute to quantum compiler infrastructure, and build tools that bridge theory and practice.

**Graduated (2023)** with published work in Springer and invited presentations at international quantum computing seminars.

---

## About Me

- **Research focus:** Quantum compilation, QIR-based compilation workflows, distributed quantum systems  
- **Quantum stack:** Qiskit, QIR, CUDA-Quantum, simulators, and hardware-aware compilation  
- **Backend expertise:** Django, FastAPI, PostgreSQL, Redis, Docker  
- **Systems-level work:** Memory management, performance optimization, reverse engineering (C/C++, x86 assembly)

**IBM Qiskit Developer Advocate** (Sept 2025 - Present)

---

## Publications & Presentations

**Peer-Reviewed Publication**
- Onoja, P.O. et al. (2025). "Cross-Platform Analysis of Quantum Circuit Simulators with State Collapse Mechanisms and Back-Action Tracking in C and Python." *Artificial Intelligence and Quantum Computing: Early Innovations, Volume 1.* Studies in Computational Intelligence, vol 1200. Springer, Cham.  
  [https://doi.org/10.1007/978-3-031-85614-3_16](https://doi.org/10.1007/978-3-031-85614-3_16)

**Invited Talks**
- "Integrating Quantum Intermediate Representation (QIR) into a C-Based Quantum-Classical Framework for Efficient Quantum Computing" — Seminar on AI and Quantum Computing, National Polytechnic Institute Baja California (October 2025)
- "Quantum Compilation: Optimizing Quantum Circuits for Hardware Efficiency" — Qiskit Fall Fest, University of Ibadan, Nigeria (2024)

---

## Ongoing Research

My research centers on **quantum compilation and distributed quantum systems**.  
I explore how **Quantum Intermediate Representation (QIR)** can serve as a generalized bridge between quantum programming frameworks and diverse hardware backends.

Key themes include:
- Adaptive quantum compilation using device-specific performance profiles  
- Hardware-aware circuit partitioning and task allocation in **distributed quantum networks**  
- Integration of QIR into classical-quantum hybrid runtimes for scalable execution  
- Systems-level optimization of quantum-classical interfaces for speed and reliability

This ongoing work builds on ideas from my experimental projects such as `C_qir`, `qc_simulator`, and the distributed FastAPI-based **QTask** system.

**Current research position:** Quantum Software Research Intern at QWorld (July 2025 - Present), working on optimal task-to-QPU mapping algorithms for distributed quantum systems. Manuscript in preparation for QCAMP.

---

## Open Source Contributions

I actively contribute to [qBraid/qbraid-qir](https://github.com/qBraid/qbraid-qir), focusing on QIR profile compliance and quantum circuit preprocessing.

- [#225](https://github.com/qBraid/qbraid-qir/pull/225) — Implemented Adaptive Execution Profile support with measurement state tracking, register-based output recording, and validation of post-measurement qubit operations. Added profile-based architecture enabling JSON-defined QIR profiles for different quantum execution models (Closed [#199](https://github.com/qBraid/qbraid-qir/issues/199))

- [#228](https://github.com/qBraid/qbraid-qir/pull/228) — Implemented QIR Base Profile compliance by adding measurement state tracking to prevent quantum operations on measured qubits, enforcing qubit reset requirements, and ensuring proper function usage per Base Profile specification (Closed [#224](https://github.com/qBraid/qbraid-qir/issues/224))

- [#248](https://github.com/qBraid/qbraid-qir/pull/248) — Refactored Cirq circuit preprocessing to use `optimize_for_target_gateset` with custom `QirTargetGateSet` class, fixing unnecessary gate decomposition and preserving supported gates (H, CNOT, TOFFOLI) while properly handling classically-controlled operations (Closed [#93](https://github.com/qBraid/qbraid-qir/issues/93))

**Unitary Hackathon Bounty Winner** (2024) for QIR Base & Adaptive Profile compliant QASM conversions

---

## Projects

### Quantum Computing Research

- **[C_qir](https://github.com/feelerx/C_qir)** – A compiler pipeline converting universal quantum instructions written in C to Quantum Intermediate Representation (QIR), enabling C code execution on any QIR-compatible quantum backend. This work directly led to an invited presentation at the National Polytechnic Institute Baja California (October 2025).

- **[qc_simulator](https://github.com/feelerx/qc_simulator)** – A quantum circuit simulator implementing three distinct computational approaches (matrix multiplication, tensor product, direct qubit manipulation) in both C and Python. Comparative performance analysis published in *Artificial Intelligence and Quantum Computing: Early Innovations* (Springer, 2025).

### Systems Programming & Optimization

- **[AutoFreer](https://github.com/feelerx/autofreer)** – An automatic memory management system implemented as a lightweight DLL for C, achieving 10-20% faster execution and lower memory overhead compared to the Boehm-Demers-Weiser library. Built on insights from reverse-engineering MSVC's malloc/calloc/realloc/free implementations (undergraduate thesis work).

- **[AutoGrad](https://github.com/feelerx/AutoGrad)** – A lightweight automatic differentiation system for mathematical expressions in C, enabling gradient tracking and manipulation for machine learning workflows.

### Full-Stack Development

- **[Picture Us](https://picture-us.vercel.app/)** – A social photo-sharing web app built with Django and PostgreSQL, featuring WebSocket-based real-time updates and permission management.

- **[GuesstheImpostor](https://guesstheimpostor.vercel.app/)** – A multiplayer FastAPI-based web game.

---

## Tech Stack

**Languages:** Python, C, C++, JavaScript, x86 Assembly  
**Frameworks:** Django, FastAPI, Flask  
**Databases & Tools:** PostgreSQL, Redis, Docker, Git  
**Quantum SDKs:** Qiskit, QIR, CUDA-Quantum, Cirq  
**Research Tools:** Reverse engineering (Ghidra, x64dbg), profiling, performance optimization

---

## Achievements

- IBM Qiskit Developer Advocate (Sept 2025 - Present)
- Qiskit Global Summer School Badge of Quantum Excellence (2023, 100% lab completion)
- IBM Quantum Challenge Participant (Spring 2023, 2024)
- Unitary Hackathon Bounty Winner (2024)

---

**Full CV & Publications:** [here]()

## Contact

- LinkedIn: [here](https://www.linkedin.com/in/paul-onoja-9035a0220/)  
- Email: [here](onojaopaul@gmail.com)  

I’m always open to collaborations in quantum software, compiler research, and backend systems.

