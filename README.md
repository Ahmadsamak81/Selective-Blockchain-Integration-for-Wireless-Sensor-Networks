# Selective Blockchain Integration for WSN

Hybrid On-Chain/Off-Chain blockchain framework for Wireless Sensor Networks (WSNs) with dynamic criticality-based routing and Merkle anchoring.

---

## 📌 Overview

This project implements a **selective blockchain integration strategy** that balances data integrity and energy efficiency in resource-constrained WSNs.

Instead of storing all data on-chain (high energy cost) or relying solely on databases (weak integrity), the proposed hybrid approach:

- Routes high-criticality packets to blockchain  
- Protects normal readings using Merkle-anchored off-chain storage  
- Adapts routing decisions based on real-time energy and data semantics  

---

## 🚀 Key Results (S1 Scenario)

- 🔐 **92.2% tamper detection**
- ⚡ **43.1% energy reduction** vs. full blockchain
- 🔄 **91.1% reduction in on-chain transactions**
- ⏳ **1.78× network lifetime extension**

---

## ⚙️ Technical Highlights

- Proof-of-Authority (PoA) consensus (3 validators)
- 8:1 Merkle batch compression
- 8-component detailed energy model
- Strict post-commit tampering attack model
- 100-node WSN simulation (3000 rounds, 10 Monte Carlo runs)

---

## 🎯 Purpose

This implementation supports research on **energy-aware blockchain integration in WSNs**, demonstrating that selective integration achieves **Pareto-optimal security-efficiency trade-offs**.

