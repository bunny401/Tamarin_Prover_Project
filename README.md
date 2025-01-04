# Tamarin Prover Models

This repository contains formal security models and proofs developed using the **Tamarin Prover**, a tool for analyzing and verifying cryptographic protocols. The models in this repository focus on demonstrating security properties such as secrecy, authentication, and integrity for various protocols.

---

## 🔍 What is Tamarin Prover?

The **Tamarin Prover** is a formal verification tool for cryptographic protocols. It allows researchers and developers to:
- Analyze the security of protocols in the presence of adversaries.
- Verify properties like secrecy, authentication, and integrity.
- Explore both honest and adversarial scenarios in protocol interactions.

---

## 📂 Repository Structure

- **Models/**:  
  Contains `.spthy` files that define cryptographic protocols, actions, and security properties.
  
- **Examples/**:  
  Includes sample protocols with comments for learning and experimentation.

- **Proofs/**:  
  Contains lemmas and restrictions to demonstrate protocol correctness and security properties.

- **Documentation/**:  
  Provides detailed explanations of the models, use cases, and protocol assumptions.

---

## 🚀 Getting Started

### Prerequisites
- Install the [Tamarin Prover](https://tamarin-prover.github.io/).
- Familiarity with formal methods and cryptographic protocol analysis is helpful.

### Running a Model
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/tamarin-prover
