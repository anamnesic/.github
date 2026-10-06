<div align="center">

# Anamnesic Labs

### Open-source AI systems engineering & hardware inference R&D.

*Making modern language models run where they were never supposed to.*

---

[![ChronoKairo](https://img.shields.io/badge/Maintained%20by-ChronoKairo-blue?style=flat-square)](https://github.com/chronokairo)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=flat-square)](https://opensource.org/licenses/MIT)

</div>

---

## 🔭 About Anamnesic Labs

**Anamnesic Labs** is the open-source and applied research arm maintained by **[ChronoKairo](https://github.com/chronokairo)**. 

While enterprise products and commercial agent runtimes operate under the ChronoKairo ecosystem, Anamnesic Labs focuses on **extreme edge AI**, low-level systems engineering, and hardware democratization:

1. **AI on Constrained & Abandoned Hardware**: Exploring ways to run modern transformers and hybrid SSMs (Llama 3, SmolLM2, Qwen 3.5, DeltaNet) on legacy GPUs, integrated graphics, and memory-constrained devices.
2. **Heterogeneous Compute**: Data-movement minimization, zero-copy unified memory pooling, and tensor-tiering across dGPUs, iGPUs, and host RAM.
3. **Applied Systems R&D**: Implementations of cutting-edge literature in speculative decoding, quantization, and attention kernels.

---

## 🔬 Active Research Repositories

| Repository | Scope & Focus | Tech Stack |
| :--- | :--- | :--- |
| **[`relic`](https://github.com/anamnesic/relic)** | Minimal, high-performance GGUF LLM runtime for OpenCL 1.2 & 3.0 devices (dGPU + iGPU + CPU). Hosts the org's hardware profiling notes ([`docs/hardware`](https://github.com/anamnesic/relic/tree/main/docs/hardware)) and research backlog ([`docs/`](https://github.com/anamnesic/relic/tree/main/docs)). | Pure C, OpenCL, CMake |

> The former `surveyor` (hardware profiling & feasibility notes) and `anamnesic-labs` (applied research focus) repositories were absorbed into `relic/docs`.

---

## 🏛️ Ecosystem Alignment

Core applications and agent platforms originally incubated in Anamnesic have graduated to the ChronoKairo official suites:
- **Tool-calling scaffolding & SLM reliability (`clamp`)** → Consolidated into [`chronokairo-ai`](https://github.com/chronokairo/ai).
- **IDE LLM Bridges & local servers** → Consolidated into [`chronokairo-ai/tools/llm-server`](https://github.com/chronokairo/ai).
- **Sandboxed Agent Execution (`AegisOS`)** → Integrated into [`chronokairo-ai/tools/sandbox`](https://github.com/chronokairo/ai).
- **Agent Memory & Context Engine** → Integrated into [`chronokairo-ai/tools/context`](https://github.com/chronokairo/ai).
- **Project Intelligence & Risk Matrices** → Integrated into [`chronokairo-projects`](https://github.com/chronokairo/projects).

---

## 📜 Principles

- **Zero-Waste Hardware**: Hardware is only obsolete if the software gives up on it.
- **Data Movement is the Bottleneck**: Arithmetic is cheap; moving bytes across the bus is expensive.
- **Open Science & Open Systems**: Foundational low-level runtimes and hardware research are shared openly with the developer community.

---

<div align="center">

An open-source initiative by **[ChronoKairo](https://github.com/chronokairo)**

</div>
