# Quantum Awesome 🌌

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome resources, tools, frameworks, papers, and learning materials for **Quantum Computing**, **Post-Quantum Cryptography**, **Quantum Sensing**, **Quantum Radar**, **Quantum Key Distribution**, and related quantum technologies.

> Inspired by the [awesome list](https://github.com/sindresorhus/awesome) format. Contributions welcome — see [Contributing](#contributing).

## Contents

- [Quantum Computing](#quantum-computing)
- [Post-Quantum Cryptography (PQC)](#post-quantum-cryptography-pqc)
- [Quantum Key Distribution (QKD)](#quantum-key-distribution-qkd)
- [Quantum Sensing](#quantum-sensing)
- [Quantum Radar](#quantum-radar)
- [Quantum Communication & Networking](#quantum-communication--networking)
- [Quantum Error Correction](#quantum-error-correction)
- [Quantum Algorithms](#quantum-algorithms)
- [Quantum Software & Frameworks](#quantum-software--frameworks)
- [Quantum Hardware & Companies](#quantum-hardware--companies)
- [Learning Resources](#learning-resources)
- [Journals, Conferences & Communities](#journals-conferences--communities)
- [Contributing](#contributing)
- [License](#license)

---

## Quantum Computing

General resources, foundational papers, and overviews of quantum computing.

- [Quantum Computing Report](https://quantumcomputingreport.com/) — News, company directory, and roadmap tracking for the quantum industry.
- [Qiskit Textbook](https://qiskit.org/learn) — Free, interactive textbook covering quantum computing theory and practice.
- [Nielsen & Chuang — *Quantum Computation and Quantum Information*](https://www.cambridge.org/highereducation/books/quantum-computation-and-quantum-information/01E10196D0A682A6AEFFEA52D53BE9AE) — The standard graduate-level textbook ("Mike & Ike").
- [arXiv quant-ph](https://arxiv.org/list/quant-ph/recent) — Preprint archive for quantum physics/computing research.
- [Quantum Computing Stack Exchange](https://quantumcomputing.stackexchange.com/) — Q&A community for theory and implementation questions.
- [John Preskill's "Quantum Computing in the NISQ era and beyond"](https://arxiv.org/abs/1801.00862) — Landmark paper coining the term NISQ.

## Post-Quantum Cryptography (PQC)

Cryptographic algorithms believed to be secure against quantum adversaries.

- [NIST Post-Quantum Cryptography Project](https://csrc.nist.gov/projects/post-quantum-cryptography) — Official NIST standardization effort and selected algorithms.
- [CRYSTALS-Kyber](https://pq-crystals.org/kyber/) — NIST-selected lattice-based key encapsulation mechanism (ML-KEM).
- [CRYSTALS-Dilithium](https://pq-crystals.org/dilithium/) — NIST-selected lattice-based digital signature scheme (ML-DSA).
- [SPHINCS+](https://sphincs.org/) — Stateless hash-based signature scheme.
- [Open Quantum Safe (liboqs)](https://openquantumsafe.org/) — Open-source C library and integrations for prototyping PQC.
- [PQClean](https://github.com/PQClean/PQClean) — Clean, portable reference implementations of PQC schemes.
- [Cloudflare: "The state of the post-quantum internet"](https://blog.cloudflare.com/pq-2024/) — Practical overview of PQC deployment on the internet.

## Quantum Key Distribution (QKD)

Protocols and systems for quantum-secure key exchange.

- [BB84 Protocol (original paper)](https://www.sciencedirect.com/science/article/pii/S0304397514004241) — Bennett & Brassard's foundational 1984 QKD protocol.
- [ID Quantique](https://www.idquantique.com/) — Commercial QKD systems and quantum-safe security products.
- [Toshiba Quantum Key Distribution](https://www.toshiba.eu/quantum/) — Long-distance QKD research and commercial systems.
- [China's Micius Satellite (QUESS)](https://en.wikipedia.org/wiki/Quantum_Experiments_at_Space_Scale) — First satellite-based QKD demonstration.
- [ETSI QKD Industry Specification Group](https://www.etsi.org/committee/1430-qkd) — Standardization body for QKD interoperability.
- [European Quantum Communication Infrastructure (EuroQCI)](https://digital-strategy.ec.europa.eu/en/policies/european-quantum-communication-infrastructure-euroqci) — EU initiative to build a pan-European QKD network.

## Quantum Sensing

Using quantum phenomena for high-precision measurement.

- [NIST Quantum Sensing overview](https://www.nist.gov/quantum-information-science/quantum-sensing) — Introduction to quantum sensing principles and applications.
- [Degen, Reinhard & Cappellaro — "Quantum Sensing" (Rev. Mod. Phys.)](https://journals.aps.org/rmp/abstract/10.1103/RevModPhys.89.035002) — Widely cited review paper on the field.
- [NV Centers in Diamond](https://en.wikipedia.org/wiki/Nitrogen-vacancy_center) — A leading platform for room-temperature quantum sensors (magnetometry, thermometry).
- [Atomic Clocks & Optical Lattice Clocks](https://www.nist.gov/programs-projects/optical-lattice-clocks) — Ultra-precise timekeeping using quantum systems.
- [Quantum Gravimetry](https://www.nature.com/articles/s41586-021-04315-3) — Using atom interferometry for precision gravity measurement.
- [AOSense](https://www.aosense.com/) / [Q-CTRL](https://q-ctrl.com/) — Companies building quantum sensing and control hardware/software.

## Quantum Radar

Emerging research on quantum-enhanced radar and target detection.

- [Lloyd — "Enhanced Sensitivity of Photodetection via Quantum Illumination"](https://www.science.org/doi/10.1126/science.1160627) — Foundational quantum illumination paper underlying quantum radar concepts.
- [Quantum Illumination for Target Detection (survey)](https://arxiv.org/abs/1910.01669) — Overview of theoretical and experimental progress.
- [University of Waterloo Quantum Radar research](https://uwaterloo.ca/institute-for-quantum-computing/) — Academic group active in quantum radar demonstrations.
- [IEEE Spectrum: "China's Claim of Quantum Radar Détente"](https://spectrum.ieee.org/chinas-quantum-radar) — Accessible overview of claims and skepticism around quantum radar.
- [Microwave Quantum Illumination Experiments (Barzanjeh et al., Sci. Adv.)](https://www.science.org/doi/10.1126/sciadv.1501966) — Early experimental microwave quantum illumination demonstration.

## Quantum Communication & Networking

- [Quantum Internet Alliance](https://quantum-internet.team/) — European consortium building quantum network infrastructure.
- [Wehner, Elkouss & Hanson — "Quantum internet: A vision..." (Science)](https://www.science.org/doi/10.1126/science.aam9288) — Roadmap paper for quantum network development stages.
- [QuTech](https://qutech.nl/) — Delft-based research center for quantum computing and networking.
- [Quantum Repeaters overview](https://en.wikipedia.org/wiki/Quantum_repeater) — Key technology for extending quantum communication distance.

## Quantum Error Correction

- [Surface Codes: A Review (Fowler et al.)](https://arxiv.org/abs/1208.0928) — Widely used introduction to the leading QEC approach.
- [Shor Code (original paper)](https://journals.aps.org/pra/abstract/10.1103/PhysRevA.52.R2493) — The first quantum error-correcting code.
- [Google Quantum AI — Logical qubit breakthroughs](https://blog.google/technology/research/google-willow-quantum-chip/) — Recent experimental results on error correction below threshold.
- [QEC Simulation: Stim](https://github.com/quantumlib/Stim) — Fast stabilizer circuit simulator for QEC research.

## Quantum Algorithms

- [Shor's Algorithm (original paper)](https://arxiv.org/abs/quant-ph/9508027) — Polynomial-time algorithm for integer factorization.
- [Grover's Algorithm (original paper)](https://arxiv.org/abs/quant-ph/9605043) — Quantum search algorithm with quadratic speedup.
- [Quantum Algorithm Zoo](https://quantumalgorithmzoo.org/) — Comprehensive catalog of known quantum algorithms with speedups.
- [Variational Quantum Eigensolver (VQE) overview](https://arxiv.org/abs/2111.05176) — Near-term hybrid algorithm for chemistry/optimization.
- [QAOA (original paper)](https://arxiv.org/abs/1411.4028) — Quantum Approximate Optimization Algorithm.

## Quantum Software & Frameworks

- [Qiskit](https://github.com/Qiskit/qiskit) — IBM's open-source quantum computing SDK.
- [Cirq](https://github.com/quantumlib/Cirq) — Google's Python framework for NISQ circuits.
- [PennyLane](https://github.com/PennyLaneAI/pennylane) — Cross-platform library for quantum machine learning and differentiable quantum programming.
- [Q# / Azure Quantum Development Kit](https://github.com/microsoft/qsharp) — Microsoft's quantum programming language and toolkit.
- [PyQuil / Forest SDK](https://github.com/rigetti/pyquil) — Rigetti's Python library for quantum programming.
- [tket](https://github.com/CQCL/tket) — Quantinuum's retargetable compiler for quantum circuits.

## Quantum Hardware & Companies

- [IBM Quantum](https://www.ibm.com/quantum) — Superconducting qubit systems, cloud access via Qiskit.
- [Google Quantum AI](https://quantumai.google/) — Superconducting processors (Sycamore, Willow).
- [IonQ](https://ionq.com/) — Trapped-ion quantum computers.
- [Quantinuum](https://www.quantinuum.com/) — Trapped-ion systems, formed from Honeywell Quantum + Cambridge Quantum.
- [Rigetti Computing](https://www.rigetti.com/) — Superconducting quantum processors.
- [PsiQuantum](https://www.psiquantum.com/) — Photonic approach to fault-tolerant quantum computing.
- [D-Wave](https://www.dwavesys.com/) — Quantum annealing systems for optimization.
- [Pasqal](https://www.pasqal.com/) — Neutral-atom quantum computing.

## Learning Resources

- [IBM Qiskit Global Summer School materials](https://qiskit.org/events/summer-school) — Free lecture videos and labs.
- [MIT 8.370x — Quantum Information Science (edX)](https://www.edx.org/learn/quantum-computing/massachusetts-institute-of-technology-quantum-information-science-i) — University-level online course.
- [Quantum Country](https://quantum.country/) — Essay-style interactive introduction using spaced repetition.
- [Microsoft Quantum Katas](https://github.com/microsoft/QuantumKatas) — Self-paced Q# programming exercises.
- [Awesome Quantum Computing (GitHub list)](https://github.com/desireevl/awesome-quantum-computing) — A broader, general-purpose curated list.

## Journals, Conferences & Communities

- [Quantum (journal)](https://quantum-journal.org/) — Open-access, community-run journal for quantum science.
- [npj Quantum Information](https://www.nature.com/npjqi/) — Nature-published journal on quantum information science.
- [QIP — Quantum Information Processing conference](https://qipconference.org/) — Leading annual academic conference.
- [Q2B — Qubits to Business](https://q2b.qcware.com/) — Industry-focused quantum computing conference.
- [r/QuantumComputing](https://www.reddit.com/r/QuantumComputing/) — Active community discussion forum.

---

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) before submitting a pull request. Make sure:

- The resource is relevant to one of the listed categories.
- Links are working and point to primary/official sources when possible.
- Entries follow the existing format: `[Name](link) — Short description.`

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

This list is released under [CC0](https://creativecommons.org/publicdomain/zero/1.0/) — to the extent possible under law, all copyright and related rights have been waived.
