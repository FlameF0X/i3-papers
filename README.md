# i3-papers: Research on Hyper-Efficient LLM Architectures

This repository serves as the central hub for independent research into i3 (Innovative, Intelligent, Inherently Efficient) architectures. Our core mission is to redefine the computational scaling laws for Large Language Models (LLMs) by prioritizing architectural efficiency over brute-force hardware scale, proving that SOTA performance is accessible to all.

# 📄 Published Research Papers

This section lists the full technical reports available in this repository.

1. The i3-200M Report
>The i3-200M Model: A Hybrid Architecture for Efficient and Effective Language Modeling
>
>Abstract: The pursuit of efficient and high-performing large language models (LLMs) has led to the exploration of novel architectures beyond the traditional Transformer. This paper introduces the i3-200M Model (also known as Redherring), a novel hybrid architecture designed to leverage the strengths of both recurrent/state-space models and attention mechanisms. The i3-200M uniquely combines RWKV-style time-mixing with Mamba state-space dynamics in its initial layers for efficient sequence processing, followed by standard multi-head attention in deeper layers for complex global dependency capture. With approximately 170 million parameters, the model achieves a final training loss of 1.6 and a perplexity of 5.2 on its diverse pre-training corpus. This hierarchical hybrid approach demonstrates a compelling balance between computational efficiency and modeling capacity, offering a promising direction for developing resource-conscious LLMs.
>
>Link: [Read the Full Report](papers/i3-200M-12.2025.pdf)
