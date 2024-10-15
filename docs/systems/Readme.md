<p align="center">
    <h1 align="center">💻 系统方向</h1>
    <p align="center">入门指南</p>
    <p align="center">
        <a href="https://github.com/PKU-DAIR">
            <img alt="Static Badge" src="https://img.shields.io/badge/%C2%A9-PKU--DAIR-%230e529d?labelColor=%23003985">
        </a>
        <a href="https://github.com/PKU-DAIR">
            <img alt="Static Badge" src="https://img.shields.io/badge/PKU--DAIR-black?logo=github">
        </a>
    </p>
</p>

### ML/DL系统框架

> 注:⚡为**基础必读**,💎为**基础选读**,💡为**进阶阅读**

<details open>
<summary>

##### ML/DL系统基础

</summary>

**⚡ 基础必读**

- 🎓 [CMU DL Systems 课程](https://dlsyscourse.org/)

> 学习线上课程并完成作业，了解深度学习系统的基本组成，同时要求作业不能光做完就算了，注重运行效率的优化，比如跟PyTorch对比，是更快还是更慢

**💎基础选读**

- 🎓 [System for AI](https://github.com/microsoft/AI-System)
</details>

<details open>
<summary>

##### DL系统框架⚡

</summary>

- 🛠️ [PyTorch](https://dlsyscourse.org/)
</details>

### 分布式训练

<details open>
<summary>

##### 分布式训练框架⚡

</summary>

> 调研学习现在主流的分布式训练系统，包括他们的系统框架实现，以及介绍主要技术的文章

- 🛠️ [Megatron-LM](https://github.com/NVIDIA/Megatron-LM)
- 🛠️ [DeepSpeed](https://github.com/microsoft/DeepSpeed)
</details>

<details open>
<summary>

##### 分布式训练综述⚡

</summary>

- 📄 Demystifying Parallel and Distributed Deep Learning: An In-Depth Concurrency Analysis
- 📄 Efficient Training of Large Language Models on Distributed Infrastructures: A Survey
</details>

<details open>
<summary>

##### 数据并行(All-Reduce based)⚡

</summary>

- 📄 **Horovod** | Fast and easy distributed deep learning in TensorFlow
- 📄 **PyTorch DDP** | PyTorch Distributed: Experiences on Accelerating Data Parallel Training
</details>

<details open>
<summary>

##### ZeRO/FSDP并行⚡

</summary>

- 📄 ZeRO: memory optimizations toward training trillion parameter models
- 📄 ZeRO-Offload: Democratizing Billion-Scale Model Training
</details>

<details open>
<summary>

##### 流水并行⚡

</summary>

- 📄 GPipe: Efficient Training of Giant Neural Networks using Pipeline Parallelism
- 📄 PipeDream: Fast and Efficient Pipeline Parallel DNN Training
- 📄 **PipeDream-2BW/PipeDream-Flush/1F1B-Flush** | Memory-Efficient Pipeline-Parallel DNN Training
</details>

<details open>
<summary>

##### 张量并行/算子并行⚡

</summary>

- 📄 [OWT] One weird trick for parallelizing convolutional neural networks
- 📄 [Megatron-style TP] Megatron-LM: Training Multi-Billion Parameter Language Models Using Model Parallelism
</details>

<details open>
<summary>

##### 3D并行⚡

</summary>

- 📄 Efficient Large-Scale Language Model Training on GPU Clusters Using Megatron-LM
</details>

<details open>
<summary>

##### 自动并行⚡

</summary>

- 📄 [FlexFlow] Beyond Data and Model Parallelism for Deep Neural Networks
- 📄 Galvatron: Efficient Transformer Training over Multiple GPUs Using Automatic Parallelism
- 📄 Alpa: Automating Inter- and Intra-Operator Parallelism for Distributed Deep Learning
</details>

<details open>
<summary>

##### Tensor Annotation💎

</summary>

- 📄 GSPMD: General and Scalable Parallelization for ML Computation Graphs
- 📄 Unity: Accelerating DNN Training Through Joint Optimization of Algebraic Transformations and Parallelization
</details>

<details open>
<summary>

##### 专家并行/MoE训练💎

</summary>

- 📄 GShard: Scaling Giant Models with Conditional Computation and Automatic Sharding
- 📄 A Hybrid Tensor-Expert-Data Parallelism Approach to Optimize Mixture-of-Experts Training
- 📄 FasterMoE: modeling and optimizing training of large-scale dynamic pre-trained models
</details>

<details open>
<summary>

##### 序列并行/长窗口并行💎

</summary>

- 📄 [Megatron-style SP] Reducing Activation Recomputation in Large Transformer Models
- 📄 [Ulyssys-style SP] DeepSpeed Ulysses: System Optimizations for Enabling Training of Extreme Long Sequence Transformer Models
- 📄 [RSA] Sequence parallelism: Long sequence training from system perspective
- 📄 [Ring-Attn] Ring Attention with Blockwise Transformers for Near-Infinite Context
- 📄 [LightSeq/DistFlashAttn] DISTFLASHATTN: Distributed Memory-efficient Attention for Long-context LLMs Training
</details>

<details open>
<summary>

##### 显存节约💎

</summary>

- 📄 [Activation Checkpointing/Recomputation] Training Deep Nets with Sublinear Memory Cost
- 📄 [Offloading] vDNN: Virtualized Deep Neural Networks for Scalable, Memory-Efficient Neural Network Design
</details>

<details open>
<summary>

##### 算子融合优化💎

</summary>

- 📄 FlashAttention: Fast and Memory-Efficient Exact Attention with IO-Awareness
- 📄 FlashAttention-2: Faster Attention with Better Parallelism and Work Partitioning
</details>

<details open>
<summary>

##### 长序列训练💡

</summary>

- 📄 Striped Attention: Faster Ring Attention for Causal Transformers
- 📄 USP: A Unified Sequence Parallelism Approach for Long Context Generative AI
- 📄 LoongTrain: Efficient Training of Long-Sequence LLMs with Head-Context Parallelism
</details>

<details open>
<summary>

##### 多模态训练💡

</summary>

- 📄 DistTrain: Addressing Model and Data Heterogeneity with Disaggregated Training for Multimodal Large Language Models
- 📄 Optimus: Accelerating Large-Scale Multi-Modal LLM Training by Bubble Exploitation
- 📄 Efficient Multi-Task Large Model Training via Data Heterogeneity-aware Model Management
</details>

<details open>
<summary>

##### 异构训练💡

</summary>

- 📄 HetHub: A Heterogeneous distributed hybrid training system for large-scale models
- 📄 AMP: Automatically Finding Model Parallel Strategies with Heterogeneity Awareness
- 📄 AccPar: Tensor Partitioning for Heterogeneous Deep Learning Accelerators
- 📄 Whale: Scaling Deep Learning Model Training to the Trillions
</details>

### LLM推理服务
<details open>
<summary>

##### LLM服务系统框架**
</summary>

- 🛠️ [vLLM](https://github.com/vllm-project/vllm)
</details>

<details open>
<summary>

##### 综述⚡
</summary>

- 📄 A Survey on Efficient Inference for Large Language Models
- 📄 Towards Efficient Generative Large Language Model Serving: A Survey from Algorithms to Systems
</details>

<details open>
<summary>

##### Batching⚡
</summary>

- 📄 Orca: A Distributed Serving System for Transformer-Based Generative Models
</details>

<details open>
<summary>

##### 模型并行⚡
</summary>

- 📄 AlpaServe: Statistical Multiplexing with Model Parallelism for Deep Learning Serving
</details>

<details open>
<summary>

##### 显存管理⚡
</summary>

- 📄 Efficient Memory Management for Large Language Model Serving with PagedAttention
</details>

<details open>
<summary>

##### 投机推理⚡
</summary>

- 📄 Fast Inference from Transformers via Speculative Decoding
</details>

<details open>
<summary>

##### Prefix Sharing⚡
<summary>

- 📄 SGLang: Efficient Execution of Structured Language Model Programs
</details>

<details open>
<summary>

##### PD分离💎
</summary>

- 📄 DistServe: Disaggregating Prefill and Decoding for Goodput-optimized Large Language Model Serving
- 📄 Splitwise: Efficient generative LLM inference using phase splitting
- 📄 Inference without Interference: Disaggregate LLM Inference for Mixed Downstream Workloads
- 📄 Mooncake: A KVCache-centric Disaggregated Architecture for LLM Serving
</details>

<details open>
<summary>

##### Chunked Prefill💎
</summary>

- 📄 Taming Throughput-Latency Tradeoff in LLM Inference with Sarathi-Serve
</details>

<details open>
<summary>

##### 模型压缩💎
</summary>

- 📄 GPTQ: Accurate Post-Training Quantization for Generative Pre-trained Transformers
- 📄 AWQ: Activation-aware Weight Quantization for LLM Compression and Acceleration
</details>

### Diffusion（文生图、文生视频）推理服务