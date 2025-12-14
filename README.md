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

2. The i3-80M Report
>i3-80M: A Hybrid Architecture Language Model for Efficient Text Generation
>
>Abstract:The i3-80M model is an 82.77 million parameter language model designed to explore the 
efficiency and performance trade-offs of a novel hybrid architecture [1] [2]. This model 
uniquely combines the strengths of recurrent/convolutional sequence modeling, specifically 
integrating RWKV-style time-mixing with Mamba state-space dynamics in its initial 
layers, with the global context capabilities of Multi-Head Attention in its deeper layers. 
Trained on a diverse, multi-domain dataset, i3-80M demonstrates strong convergence and 
exceptional hardware efficiency, achieving a final perplexity of approximately 6 [2] while 
maintaining a low VRAM footprint, making it highly suitable for training and inference on 
consumer-grade hardware [2]. This paper details the architecture, training methodology, and 
performance metrics of the i3-80M, highlighting its advancements over its predecessor, i3
22M. 
>
>Link: [Read the Full Report](papers/i3-80M-12.2025.pdf)
