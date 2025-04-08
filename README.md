# Nature-Inspired Quantum Circuit Optimization for IQM

This project demonstrates how Genetic Algorithms (GAs), inspired by natural evolution, can be used to **optimize quantum circuit parameters** for better fidelity and hardware alignment. It simulates a 2-qubit quantum circuit in Qiskit and evolves gate angles to maximize the probability of measuring the `'00'` state.

## Why This Matters for IQM

IQM is building **scalable, hardware-efficient quantum processors** with native topologies like IQM Crystal and Star. However, key challenges remain:
- ❌ **Quantum gate errors**
- ❌ **Crosstalk and decoherence**
- ❌ **Finding optimal circuit layouts for native gates**

This project addresses those with:
- ✅ A **non-gradient-based optimizer** suited for quantum noise and discrete search spaces
- ✅ A framework that can be extended to respect **IQM's hardware constraints** (e.g., limited qubit connectivity, tunable couplers)
- ✅ A **nature-aligned strategy** for evolving circuits that could inform smarter quantum compilers or hardware-aware transpilers

## Results
Using only 10 generations and 20 candidate circuits per generation, the algorithm evolved parameters that achieved **>99.2% probability** for the target state.

## Future Directions
- Add realistic noise models (thermal relaxation, decoherence)
- Extend to multi-qubit systems with IQM-style topologies
- Incorporate swarm-based optimization (e.g., Ant Colony, PSO)
- Apply to **hardware-in-the-loop** scenarios

---

> Inspired by biology. Built for quantum. Designed with IQM in mind.
>
> Author: Satya Mohit Rao Kamkanampati
> Email: Saka4331@colorado.edu
