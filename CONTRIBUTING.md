# Contributing to the Sovereign AI Organism

**Thank you for considering contributing to the Aicent Stack. We are not just building a library; we are evolving a digital lifeform.**

[![Status](https://img.shields.io/badge/Status-Homeostasis-brightgreen.svg)](#)
[![Specs](https://img.shields.io/badge/Specs-RFC--001--005-blue.svg)](#)

Aicent Stack is governed by the principles of **Sub-millisecond Latency, Zero-Trust Immunity, and Economic Homeostasis.** We welcome contributions from the world's most elite protocol engineers, Rustaceans, and AI researchers.

---

## 🏛️ The RFC-First Process

Before submitting code, all major architectural changes or protocol optimizations must follow the **RFC (Request for Comments)** process.

1. **Review existing specs:** Study [RFC-001 through RFC-005](./rfcs) in the Manifesto.
2. **Propose a change:** Open an Issue titled `[RFC-PROPOSAL] <Your Feature Name>`.
3. **Design over Implementation:** We prioritize deterministic execution and metabolic consistency over "amazing features."

---

## 🦀 Engineering Standards

To maintain a sub-1ms reflex arc, all contributions must adhere to the following:

- **Language:** Performance-critical Rust (1.75+).
- **Zero Allocation:** No heap allocation in the critical path of `RTTP` and `RPKI` (Zero-allocation/Zero-copy).
- **Safety:** Every `unsafe` block must be documented with a `// SAFETY: <reason>` comment, explaining why it is necessary for nanosecond dispatch.
- **Determinism:** Logic must be side-effect free within the cognitive cycle.
- **Real-time:** We use [Embassy](https://embassy.dev/) and [Tokio](https://tokio.rs/) for high-frequency scheduling.

---

## 🔬 High-Priority Domains

We are currently seeking experts in the following "Organ" systems:

- **[RFC-002] Nerves (RTTP):** eBPF/XDP offloading and SIMD-accelerated semantic routing.
- **[RFC-003] Immunity (RPKI):** Parallel tensor watermarking and AVX-512 verification pipelines.
- **[RFC-004] Blood (ZCMK):** Nanosecond matching engines and ZK-based hybrid micro-settlement.
- **[RFC-005] Body (GTIOT):** Rust-based firmware (Embassy) for 1.2 kHz+ robotic control loops.

---

## 🛠️ Development Workflow

```bash
# 1. Clone the Unified Workspace
git clone https://github.com/Aicent-Stack/aicent-stack.git
cd aicent-stack

# 2. Build and Audit
cargo build --workspace
cargo clippy --workspace -- -D warnings
