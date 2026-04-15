<h1 align="center">Arundhathi Dev</h1>

<p align="center">
  <b>LLM Inference Systems • CUDA/Triton • vLLM • Distributed Serving • KV Cache Optimization</b><br/>
</p>

<div align="center">

[<img src="https://img.shields.io/badge/LinkedIn-0077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/devaru-ai/) 
[<img src="https://img.shields.io/badge/Inference%20at%20Scale-000000.svg?&style=for-the-badge&logo=none&logoColor=white" />](https://devaru-ai.github.io/inference-at-scale/posts/llm-serving.html)
[<img src="https://img.shields.io/badge/Substack-FF6719.svg?&style=for-the-badge&logo=substack&logoColor=white" />](https://inferenceatscale.substack.com/)
[<img src="https://img.shields.io/badge/Google%20Scholar-4285F4.svg?&style=for-the-badge&logo=google&logoColor=white" />](https://scholar.google.com/citations?user=mrtOLIQAAAAJ&hl=en)

</div>

<!--I'm a Graduate Student Researcher at the University of Cincinnati with a focus on **LLM inference, Model optimization, and high-performance computing**.-->

## Adaptive Sparse Attention (Ongoing Research)

*Self-tuning sparsity as a control problem for efficient long-context and multimodal inference.*

- **AdaSparge: Self-Tuning Sparse Attention for Scalable AI Inference and Deployment**  
A feedback-driven sparse attention framework treating sparsity and skip decisions as adaptive control variables, achieving up to 5.5× speedup with <0.03 L1 error and 85–95% sparsity across LLaMA 3.1, CogVideoX, and Stable Diffusion 3.5.

## Publications
- **Self-Tuning Sparse Attention: Multi-Fidelity Hyperparameter Optimization for Transformer Acceleration (Accepted at MiTA 2026)**
    Self-optimizing sparse attention framework using Bayesian optimization and multi-fidelity search, achieving 3.4× faster tuning and 8.8× fewer evaluations for transformer acceleration.
  [[arXiv](https://arxiv.org/abs/2603.18417)]
- **Efficient Domain Adaptation for Text Line Recognition via Decoupled Language Models (Accepted at MiTA 2026)**  
  Modular detection-and-correction framework enabling annotation-free domain adaptation with ~95% compute reduction via decoupled visual and language models.  
  [[arXiv](https://arxiv.org/abs/2603.28028)] 
  
## Decoding Systems & vLLM-Style Inference

- **High-Throughput LLM Inference System (vLLM-inspired)**  
  Built a scalable inference engine focused on KV cache management, batching efficiency, and high-throughput LLM serving.  
  Repo: https://github.com/devaru-ai/recreating-vllm-core

- **Hardware-Aware Sparse Attention Kernel (Triton)**  
  Developed a Triton kernel for sparse attention with improved memory bandwidth utilization and practical performance gains.  
  Repo: https://github.com/devaru-ai/triton-sparse-attention

- **Fused GPU Kernel (GEMM + Bias + GELU)**  
  Implemented a custom CUDA kernel fusing matrix multiplication, bias addition, and GELU activation for reduced memory overhead and higher throughput.  
  Repo: https://github.com/devaru-ai/fused-gemm-activation


## Inference at Scale (Blog)
- **Serving LLMs in Production: vLLM vs TensorRT-LLM vs SGLang**  
  Comparison of dominant LLM serving frameworks focusing on KV cache management, batching strategies, and throughput tradeoffs.
  [[Read 🛠️](https://devaru-ai.github.io/inference-at-scale/posts/llm-serving.html)]

- **Scaling LLMs in Practice: Parallelism Strategies and MoE**  
  Breakdown of data, tensor, and pipeline parallelism in large-scale training, and the real cost of Mixture-of-Experts systems.
  [[Untangle the parallelism 🧵](https://devaru-ai.github.io/inference-at-scale/posts/parallelism-moe.html)]

- **From Prefill to Decode: How Modern LLM Inference Actually Works**  
  End-to-end view of LLM inference pipelines including KV caching, continuous batching, chunked prefill, and speculative decoding.
  [[Read 🚀](https://devaru-ai.github.io/inference-at-scale/posts/inference-pipeline.html)]

- **From FlashAttention to PagedAttention: How Memory Shapes LLM Inference**  
  Explores attention compute optimizations and KV cache memory fragmentation solutions across modern inference systems.
  [[Peek into memory layers ⚙️](https://devaru-ai.github.io/inference-at-scale/posts/memory-attention.html)] 
<!--
**devaru-ai/devaru-ai** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
