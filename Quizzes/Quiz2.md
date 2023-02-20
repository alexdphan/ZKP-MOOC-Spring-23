**How are SNARKs different from IPs?**
- SNARKs are arguments and not proofs, i.e., they only provide computational soundness
- All SNARKs have sublinear proof size
- All SNARKs have sublinear verifier
- All SNARKs prove NP statements
- SNARKs are non-interactive
- SNARKs are knowledge-sound


**Which of the following are true about preprocessing SNARKs?**
- We can not construct SNARKs for general circuits without preprocessing
- If the secrets used in the trusted setup are revealed, the SNARK prover can violate soundness

**Which of the following are true about the components used to construct SNARKs?**
- Functional commitment schemes are SNARKs that support a restricted class of functions
- An unbounded prover can't break the knowledge soundness of an Interactive oracle proof (IOP)
- Functional commitments are used to instantiate the oracles in IOPs
- To make a SNARK zero-knowledge, we use a hiding functional commitment scheme

**Which of the following are true about the SNARK for polynomial equality testing?**
- The oracles in the corresponding IOP have a degree bound to ensure that any inconsistencies in the input polynomials are detected
- The corresponding IOP can be made non-interactive using the Fiat-Shamir transform because it is public-coin