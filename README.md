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

---

I'm a **software developer**.  
I work on **quantum software**, build **backend systems**, and explore how to **bridge classical and quantum software stacks**.  

I **graduated (2023)** and I'm focused on **making quantum computing more practical** through better **compiler infrastructure** and **systems-level optimization**.

---

## **Projects**

### **Quantum Software**

- [**C_qir**](https://github.com/feelerx/C_qir) — A compiler that converts quantum instructions written in **C to QIR bytecode**. The goal is to enable direct quantum programming in C for any QIR-compatible backend. This work led to my invited presentation at **NPI Baja California**.

- [**qc_simulator**](https://github.com/feelerx/qc_simulator) — Quantum circuit simulator exploring different computational approaches. Implemented it in both **C and Python** to compare **performance vs. extensibility trade-offs**. This became the basis for my **Springer paper**.

---

### **Systems Programming & Optimization**

- [**AutoFreer**](https://github.com/feelerx/autofreer) — Automatic memory management for **C**. Built this after reverse-engineering **MSVC's memory allocator** for my undergrad thesis.

- [**AutoGrad**](https://github.com/feelerx/AutoGrad) — **Autodiff library in C** for gradient computation experiments.

---

## **Open Source Contributions**

Most of my contributions are to **qBraid/qbraid-qir**, where I work on **QIR compilation workflows**:

- [**#225**](https://github.com/qBraid/qbraid-qir/pull/225) — Built the **Adaptive Execution Profile** system with measurement state tracking and register-based output recording.  
  This lets different quantum execution models be defined via JSON profiles. *Closed [#199](https://github.com/qBraid/qbraid-qir/issues/199)*

- [**#228**]() — Implemented **QIR Base Profile compliance**, adding measurement state tracking to prevent operations on measured qubits and enforce proper reset requirements. *Closed [#224](https://github.com/qBraid/qbraid-qir/issues/224)*

- [**#248**](https://github.com/qBraid/qbraid-qir/pull/248) — Refactored **Cirq preprocessing** to use `optimize_for_target_gateset`, fixing issues where supported gates were being unnecessarily decomposed. *Closed [#93](https://github.com/qBraid/qbraid-qir/issues/93)*


---

## **Current Interests**

I'm exploring how Quantum Intermediate Representation (QIR) can serve as a universal bridge between high-level quantum programming frameworks and diverse hardware backends, alongside deepening my understanding of distributed systems (both classical and quantum).

**Current focus areas:**
- Hardware-aware circuit partitioning in distributed quantum networks  
- Practical quantum compilation tooling and Quantum-classical interface optimization
- Classical distributed systems: consensus protocols, fault tolerance, and scalability patterns

---

## **Recent Work I'm Proud Of**

- **Published paper in Springer (2025)** comparing quantum circuit simulation approaches in **C and Python**. We analyzed the trade-offs between **performance** and **extensibility** across different implementation strategies.[https://doi.org/10.1007/978-3-031-85614-3_16](https://doi.org/10.1007/978-3-031-85614-3_16)

- **Invited speaker** at the **National Polytechnic Institute Baja California (Oct 2025)** — presented on integrating **QIR** into **C-based quantum-classical frameworks**.  
  Also spoke at **Qiskit Fall Fest Nigeria** about quantum compilation.

- **Won Unitary Hackathon bounty (2024)** for implementing **QIR Base and Adaptive Profile compliant QASM conversions** in **qBraid-qir**.

**Full CV & Publications:** [here]()

---
## **Achievements**

- **IBM Qiskit Developer Advocate (Sept 2025 - Present)**  
- **Qiskit Global Summer School Badge of Quantum Excellence (2023)** — 100% lab completion  
- **IBM Quantum Challenge Participant** (Spring 2023, 2024)  
- **Unitary Hackathon Bounty Winner (2024)**  
---

### **Other Projects**

- [**Picture Us**](https://picture-us.vercel.app) — **Django-based photo sharing app** with real-time updates.  
- [**GuesstheImpostor**](https://guesstheimpostor.vercel.app) — **Multiplayer web game** built with **FastAPI**.

---

## **Tech Stack**

**Languages:** Python, C, C++, JavaScript  
**Frameworks:** Django, FastAPI  
**Databases & Tools:** PostgreSQL, Redis, Docker, Git  
**Quantum SDKs:** Qiskit, QIR, CUDA-Quantum, Cirq, qasm 
**Research Tools:** Reverse engineering (Ghidra, x64dbg), profiling, performance optimization  

---

## **Contact**

- **LinkedIn:** [here](https://www.linkedin.com/in/paul-onoja-9035a0220/)  
- **Email:** [here](mailto:onojaopaul@gmail.com)  

I’m always open to collaborations in **quantum software**, **compiler research**, and **distributed backend systems**.


