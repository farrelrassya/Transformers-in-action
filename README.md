# Transformers in Action

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebooks-orange.svg)](https://jupyter.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

> A practical guide for data scientists and ML engineers on transformer models and Large Language Models (LLMs)

<p align="center">
  <img src="https://github.com/farrelrassya/Transformers-in-action/blob/main/cover.png" alt="Book Cover" width="300">
</p>

---

## About This Book

**Transformers in Action** provides hands-on guidance for applying transformer models beyond text—into vision, audio, and production environments. This book covers architecture fundamentals, practical applications including RAG and multimodal models, optimization techniques, and ethical considerations through executable Jupyter notebooks.

<p align="center">
  <img src="https://github.com/farrelrassya/Transformers-in-action/blob/main/architecture.png" alt="Transformer Architecture" width="600">
</p>

---

## Who Is This Book For?

- **Intermediate to advanced machine learning engineers** looking to master transformer architectures
- **Data scientists** seeking practical applications of LLMs in production
- **Researchers** exploring multimodal models and advanced alignment techniques
- Readers with **intermediate Python skills** and a basic understanding of ML fundamentals

---

## Key Topics Covered

| Area | Topics |
|------|--------|
| **Fundamentals** | Mathematical and theoretical foundations of transformer architecture |
| **Practical Applications** | Text, image, and audio processing with transformers |
| **LLM Mastery** | Prompt engineering, sampling strategies, decoding methods, preference alignment |
| **Optimization** | Training optimization, performance tuning, GPU utilization |
| **Production** | Model deployment and monitoring strategies |
| **Advanced Concepts** | RAG, multimodal models, AI ethics and responsible AI |

<p align="center">
  <img src="https://github.com/farrelrassya/Transformers-in-action/blob/main/usecase.png" alt="Transformer Use Cases" width="600">
</p>

---

## Table of Contents

### Part 1: Foundations of Modern Transformer Models

| Chapter | Title | Topics |
|---------|-------|--------|
| 1 | **The Need for Transformers** | The transformers breakthrough, attention mechanism, multihead attention, when and why to use transformers |
| 2 | **A Deeper Look into Transformers** | Seq-2-seq to transformers, encoder/decoder stacks, positional encoding, attention mechanisms, position-wise FFNs |

### Part 2: Generative Transformers

| Chapter | Title | Topics |
|---------|-------|--------|
| 3 | **Model Families and Architecture Variants** | Decoder-only models, encoder-only models, embeddings, RAG fundamentals, Mixture of Experts (MoE) |
| 4 | **Text Generation Strategies and Prompting Techniques** | Greedy search, beam search, top-k sampling, nucleus sampling, temperature, zero/few-shot prompting, CoT, ToT, ThoT |
| 5 | **Preference Alignment and RAG** | RLHF, Direct Preference Optimization (DPO), GRPO, MixEval benchmark, RAG architecture and design |

### Part 3: Specialized Models

| Chapter | Title | Topics |
|---------|-------|--------|
| 6 | **Multimodal Models** | Visual embeddings, image/video analysis, audio embeddings, multimodal RAG |
| 7 | **Efficient and Specialized Small Language Models** | SLMs as agents, classification with SLMs, fine-tuning Gemma 3 for empathy and translation |
| 8 | **Training and Evaluating LLMs** | Hyperparameter optimization, experiment tracking, LoRA, QLoRA, DoRA, LoftQ |
| 9 | **Optimizing and Scaling LLMs** | Pruning, distillation, sharding, inference optimization, FlashAttention, RoPE, YaRN |
| 10 | **Ethical and Responsible LLMs** | Bias identification, interpretability with Captum and LIME, responsible AI, safeguarding against jailbreaks |

---

## Key Features

- **🔬 Hands-on Approach** — Executable Jupyter notebooks for every major concept
- **📚 Comprehensive Coverage** — From foundational theory to production deployment
- **🎯 Practical Focus** — Real-world applications across text, vision, and audio
- **⚡ Optimization Techniques** — GPU-level optimizations and efficient fine-tuning methods
- **🛡️ Responsible AI** — Dedicated coverage of ethics, bias, and model safety

---

## Getting Started

### Prerequisites

```bash
Python >= 3.8
PyTorch >= 2.0
Transformers >= 4.30
```

### Installation

```bash
# Clone the repository
git clone https://github.com/farrelrassya/Transformers-in-action.git
cd Transformers-in-action

# Install dependencies
pip install -r requirements.txt
```

### Running the Notebooks

```bash
jupyter notebook
```

Navigate to the chapter folder and open the corresponding notebook.

---

## Repository Structure

```
Transformers-in-action/
├── ch01_need_for_transformers/
├── ch02_deeper_look_transformers/
├── ch03_model_families/
├── ch04_text_generation/
├── ch05_alignment_rag/
├── ch06_multimodal_models/
├── ch07_small_language_models/
├── ch08_training_evaluating/
├── ch09_optimizing_scaling/
├── ch10_ethics_responsible_ai/
├── requirements.txt
└── README.md
```

---

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgments

- The transformer research community
- Open-source contributors to Hugging Face Transformers
- All readers and practitioners applying these concepts

---

<p align="center">
  <i>Happy learning! 🚀</i>
</p>
