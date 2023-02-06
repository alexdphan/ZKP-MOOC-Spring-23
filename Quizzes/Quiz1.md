**Which of the following are true about Interactive Proofs (IP)?**
- IP verifier runs in probabilistic polynomial time


**How is IP different from NP?**
- There is interaction between prover and verifier in IP
IP Verifier is randomized
- Soundness guarantee in IP is probabilistic

**The lecture discussed an IP for Quadratic Residuosity (QR), where the proof was divided into two parts. Which of the following are true about this IP proof?**
- Given both parts of a proof, the verifier is convinced that y is a quadratic residue with 100% certainty
- The verifier never learns both parts of a proof but the ability of the prover to show either part eventually convinces the verifier that the claim is correct
- This IP proof is actually a proof of knowledge

**Which of the following are true for the Graph 3-coloring IP discussed in the lecture?**
- The protocol only offers computational zero-knowledge due to the use of commitments
- Due to NP-completeness of graph 3-coloring, this protocol implies all of NP has a zero-knowledge IP


**Which of the following are true for simulation and extraction?**
- The simulator can simulate the view without the prover because it can sample the view out of order
- The extractor can extract the witness only from successful provers