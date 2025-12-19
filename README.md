# i3-papers

## Research on Hyper-Efficient LLM Architectures

This repository is the central hub for independent research into **i3** architectures. The core objective is to redefine computational scaling laws for Large Language Models (LLMs) by prioritizing architectural efficiency over brute-force hardware scaling, with the goal of making state-of-the-art performance accessible without large-scale infrastructure.

---

## Published Research Papers

This section lists the full technical reports available in this repository.

---

### 1. The i3-200M Report

**Title**
*The i3-200M Model: A Hybrid Architecture for Efficient and Effective Language Modeling*

**Abstract**
The pursuit of efficient and high-performing large language models (LLMs) has driven exploration beyond traditional Transformer architectures. This paper introduces the **i3-200M model** (also known as *Redherring*), a hybrid architecture designed to combine the strengths of recurrent/state-space models with attention mechanisms. The model integrates RWKV-style time-mixing and Mamba state-space dynamics in early layers for efficient sequence processing, followed by standard multi-head attention in deeper layers to capture long-range global dependencies. With approximately **170M parameters**, i3-200M achieves a final training loss of **1.6** and a perplexity of **5.2** on a diverse pre-training corpus. This hierarchical hybrid design demonstrates a strong balance between computational efficiency and modeling capacity, highlighting a promising direction for resource-conscious LLM development.

**Link**
[Read the Full Report](papers/i3-200M-12.2025.pdf)

---

### 2. The i3-80M Report

**Title**
*i3-80M: A Hybrid Architecture Language Model for Efficient Text Generation*

**Abstract**
The **i3-80M** model is an **82.77M parameter** language model designed to explore efficiency–performance trade-offs in hybrid architectures. It combines recurrent and convolutional sequence modeling—specifically RWKV-style time-mixing with Mamba state-space dynamics in early layers—with multi-head attention in deeper layers for global context modeling. Trained on a diverse multi-domain dataset, i3-80M demonstrates strong convergence and high hardware efficiency, achieving a final perplexity of approximately **6** while maintaining a low VRAM footprint. These properties make the model suitable for both training and inference on consumer-grade hardware. This report details the architecture, training methodology, and performance metrics, and highlights improvements over its predecessor, **i3-22M**.

**Link**
[Read the Full Report](papers/i3-80M-12.2025.pdf)

---

### 3. The i3-Ethan Report

**Title**
*i3-Ethan-Base: A 170M Parameter Hybrid RWKV–Attention Language Model for Efficient Text Generation*

**Abstract**
This paper presents **i3-Ethan-Base**, a compact **170M parameter** hybrid language model that combines RWKV’s linear-time attention mechanism with standard Transformer attention. The model was trained on the FineWeb dataset for several hours on a single consumer-grade NVIDIA GPU with limited VRAM. Despite its modest hardware requirements, i3-Ethan-Base achieves competitive text generation performance relative to comparable baselines. The architecture employs RWKV layers in early stages followed by standard attention layers, resulting in stable and nearly linear training loss dynamics. These results provide insights into the convergence behavior of hybrid architectures and demonstrate that high-quality language models can be trained efficiently on accessible hardware, lowering the barrier to entry for language model research and development.

**Link**
[Read the Full Report](papers/i3-Ethan-Base-12.2025.pdf)

