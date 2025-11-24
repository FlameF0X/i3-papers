# i3-papers: Research on Hyper-Efficient LLM Architectures

This repository serves as the central hub for independent research into i3 (Innovative, Intelligent, Inherently Efficient) architectures. Our core mission is to redefine the computational scaling laws for Large Language Models (LLMs) by prioritizing architectural efficiency over brute-force hardware scale, proving that SOTA performance is accessible to all.

# 📄 Published Research Papers

This section lists the full technical reports available in this repository.

1. The i3-200M Technical Report
>Title: Project i3-RedHerring: Efficient Sequence Modeling via Hybrid GRU-Mamba and Multi-Pattern Attention Architectures
>
>Abstract: As Large Language Models (LLMs) continue to grow in size, the computational barrier to entry has heightened. This paper introduces i3-200m (codename: i3-redherring), a 200-million parameter hybrid language model designed for high-efficiency training on consumer-grade hardware. By combining a novel GRU-Mamba recurrent block with Multi-Pattern Attention and Sparse Mixture of Experts (MoE), the model achieves training stability and convergence comparable to GPT-2 baselines in under 5 hours on a single NVIDIA Tesla P100 GPU. The architecture demonstrates that strategic layer hybridization can significantly reduce memory footprint (peaking at ~2.7GB allocated) while maintaining perplexity scores competitive with standard Transformers.
>
>Link: [Read the Full Technical Report](papers/i3-RedHerring_Technical_Report.pdf)
