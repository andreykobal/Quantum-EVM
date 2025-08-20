# Quantum EVM: Proof-of-Coherence Consensus

**Author:** Andrew Kobal (AILAND Group)  
**Date:** August 2025  

## Overview
Quantum EVM explores the idea of a blockchain consensus protocol that we describe as  
**Quantum-Native Consensus via Proof-of-Coherence (PoC)**.  

The protocol combines quantum randomness from physical QRNG devices with AI-based verification of coherence fingerprints.  
The goal is to provide randomness that is both physically generated and verifiable,  
which can be used in distributed systems such as blockchains.  

## Whitepaper
A more detailed description is provided in the accompanying document:  
[Quantum_EVM_Academic_v1.pdf](./Quantum_EVM_Academic_v1.pdf)

## Key Ideas
- **Proof-of-Coherence (PoC):** randomness is linked to coherence fingerprints of quantum processes.  
- **AI-based verification:** a frozen model checks that data corresponds to quantum sources rather than classical simulation.  
- **Consensus rule:** a block is considered valid if the coherence metric `C` meets or exceeds the network difficulty `D_net`.  
- **Applications:** fair transaction ordering, randomized liquidations, and new DeFi mechanisms that depend on trustworthy randomness.  

## Roadmap
1. **Proof-of-concept:** software simulation of coherence verification.  
2. **MVP:** integration with real QRNG hardware and training of a verifier AI model.  
3. **Mainnet candidate:** deployment as an Ethereum Layer 2 rollup with appchain support.  

## Public Claim
This repository serves as a **public disclosure (anti-patent)** of the idea of  
**Quantum-Native Consensus via Proof-of-Coherence (PoC)**.  

The main concept — combining quantum random number generators (QRNG) with AI-based coherence verification  
to provide verifiable physical randomness in blockchain consensus —  
was described here in **August 2025** by Andrew Kobal (AILAND Group).  

The purpose of this disclosure is to make the idea public so it remains part of the public domain  
and cannot be patented in a restrictive way.  

## License
This project is released under the MIT License. See [LICENSE.md](./LICENSE.md).
