<p align="center">
    <h1 align="center">💻 AI系统方向</h1>
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

> 注:⚡为**基础必读**,💎为**基础选读**,💡为**进阶阅读**

### AI基础入门

<details open>
<summary>

##### ML/DL、AIGC大模型基础

</summary>

> 面向之前没有 ML/DL、AIGC大模型 相关基础的同学

- `⚡` 📔 [李宏毅机器学习](https://www.bilibili.com/video/BV1Wv411h7kN/?share_source=copy_web&vd_source=f5a7a6bc8935280a6ac3bbea7f7740eb)
- `⚡` 📔 [动手学深度学习](https://zh.d2l.ai/)
- `⚡` 📦 [复旦大学LLM教材](https://intro-llm.github.io/chapter/LLM-TAP.pdf)

</details>

### ML/DL系统框架

<details open>
<summary>

##### ML/DL系统基础

</summary>

> 学习线上课程并完成作业，了解深度学习系统的基本组成，同时要求作业不能光做完就算了，注重运行效率的优化，比如跟PyTorch对比，是更快还是更慢

- `⚡` 🎓 [CMU DL Systems课程](https://dlsyscourse.org/)
- `💎` 🎓 [System for AI](https://github.com/microsoft/AI-System)

</details>

<details open>
<summary>

##### DL系统框架

</summary>

- `⚡` 🛠️ [PyTorch](https://pytorch.org/)
- `💡` 🛠️ [Jax](https://jax.readthedocs.io/en/latest/)
- `💡` 🛠️ [Hetu](https://github.com/PKU-DAIR/Hetu)

</details>

### 分布式训练

<details open>
<summary>

##### （分布式）训练框架

</summary>

> 调研学习现在主流的分布式训练系统，包括他们的系统框架实现，以及介绍主要技术的文章

- `⚡` 🛠️ [Megatron-LM](https://github.com/NVIDIA/Megatron-LM)
- `⚡` 🛠️ [DeepSpeed](https://github.com/microsoft/DeepSpeed)
- `💡` 🛠️ [Galvatron](https://github.com/PKU-DAIR/Hetu-Galvatron)

</details>

<details open>
<summary>

##### 分布式训练综述

</summary>

> 介绍分布式训练的blog post有很多，可以上网搜索其他相关内容进行初步了解，有一定基础知识储备后再看这两篇综述会更合适

- `💎` 📄 [Demystifying Parallel and Distributed Deep Learning: An In-Depth Concurrency Analysis](https://arxiv.org/abs/1802.09941)
- `💎` 📄 [Efficient Training of Large Language Models on Distributed Infrastructures: A Survey](https://arxiv.org/abs/2407.20018)

</details>

<details open>
<summary>

##### 数据并行（All-Reduce based）

</summary>

- `⚡` 📄 [(Horovod) Fast and easy distributed deep learning in TensorFlow](https://arxiv.org/abs/1802.05799)
- `⚡` 📄 [(PyTorch DDP) PyTorch Distributed: Experiences on Accelerating Data Parallel Training](https://www.vldb.org/pvldb/vol13/p3005-li.pdf)

</details>

<details open>
<summary>

##### ZeRO/FSDP并行

</summary>

- `⚡` 📄 [ZeRO: memory optimizations toward training trillion parameter models](https://dl.acm.org/doi/10.5555/3433701.3433727)
- `⚡` 📄 [PyTorch FSDP: Experiences on Scaling Fully Sharded Data Parallel](https://www.vldb.org/pvldb/vol16/p3848-huang.pdf)
- `⚡` 📄 [ZeRO-Offload: Democratizing Billion-Scale Model Training](https://www.usenix.org/system/files/atc21-ren-jie.pdf)

</details>

<details open>
<summary>

##### 流水并行

</summary>

- `⚡` 📄 [GPipe: Efficient Training of Giant Neural Networks using Pipeline Parallelism](https://dl.acm.org/doi/abs/10.5555/3454287.3454297)
- `⚡` 📄 [PipeDream: Fast and Efficient Pipeline Parallel DNN Training](https://dl.acm.org/doi/10.1145/3341301.3359646)
- `⚡` 📄 [(PipeDream-2BW/PipeDream-Flush/1F1B-Flush) Memory-Efficient Pipeline-Parallel DNN Training](https://proceedings.mlr.press/v139/narayanan21a/narayanan21a.pdf)

</details>

<details open>
<summary>

##### 张量并行/算子并行

</summary>

- `⚡` 📄 [(OWT) One weird trick for parallelizing convolutional neural networks](https://arxiv.org/abs/1404.5997)
- `⚡` 📄 [(Megatron-style TP) Megatron-LM: Training Multi-Billion Parameter Language Models Using Model Parallelism](https://arxiv.org/abs/1909.08053)

</details>

<details open>
<summary>

##### 3D并行

</summary>

- `⚡` 📄 [Efficient Large-Scale Language Model Training on GPU Clusters Using Megatron-LM](https://dl.acm.org/doi/10.1145/3458817.3476209)

</details>

<details open>
<summary>

##### 自动并行

</summary>

- `⚡` 📄 [(FlexFlow) Beyond Data and Model Parallelism for Deep Neural Networks](https://proceedings.mlsys.org/paper_files/paper/2019/file/b422680f3db0986ddd7f8f126baaf0fa-Paper.pdf)
- `⚡` 📄 [Galvatron: Efficient Transformer Training over Multiple GPUs Using Automatic Parallelism](https://www.vldb.org/pvldb/vol16/p470-miao.pdf)
- `⚡` 📄 [Alpa: Automating Interand Intra-Operator Parallelism for Distributed Deep Learning](https://www.usenix.org/system/files/osdi22-zheng-lianmin.pdf)

</details>

<details open>
<summary>

##### Tensor Annotation

</summary>

- `💎` 📄 [GSPMD: General and Scalable Parallelization for ML Computation Graphs](https://arxiv.org/abs/2105.04663)
- `💎` 📄 [Unity: Accelerating DNN Training Through Joint Optimization of Algebraic Transformations and Parallelization](https://www.usenix.org/system/files/osdi22-unger.pdf)

</details>

<details open>
<summary>

##### 专家并行/MoE训练

</summary>

- `💎` 📄 [GShard: Scaling Giant Models with Conditional Computation and Automatic Sharding](https://arxiv.org/abs/2006.16668)
- `💎` 📄 [A Hybrid Tensor-Expert-Data Parallelism Approach to Optimize Mixture-of-Experts Training](https://dl.acm.org/doi/10.1145/3577193.3593704)
- `💎` 📄 [FasterMoE: modeling and optimizing training of large-scale dynamic pre-trained models](https://dl.acm.org/doi/10.1145/3503221.3508418)
- `💎` 📄 [FlexMoE: Scaling Large-scale Sparse Pre-trained Model Training via Dynamic Device Placement](https://dl.acm.org/doi/10.1145/3588964)

</details>

<details open>
<summary>

##### 序列并行/长窗口并行

</summary>

- `💎` 📄 [(Megatron-style SP) Reducing Activation Recomputation in Large Transformer Models](https://proceedings.mlsys.org/paper_files/paper/2023/file/80083951326cf5b35e5100260d64ed81-Paper-mlsys2023.pdf)
- `💎` 📄 [(Ulyssys-style SP) DeepSpeed Ulysses: System Optimizations for Enabling Training of Extreme Long Sequence Transformer Models](https://arxiv.org/abs/2309.14509)
- `💎` 📄 [(RSA) Sequence parallelism: Long sequence training from system perspective](https://aclanthology.org/2023.acl-long.134.pdf)
- `💎` 📄 [(Ring-Attn) Ring Attention with Blockwise Transformers for Near-Infinite Context](https://openreview.net/pdf?id=WsRHpHH4s0)
- `💎` 📄 [(LightSeq/DistFlashAttn) DISTFLASHATTN: Distributed Memory-efficient Attention for Long-context LLMs Training](https://openreview.net/pdf?id=pUEDkZyPDl)

</details>

<details open>
<summary>

##### 通信压缩

</summary>

- `💎` 📄 [QSGD: Communication-Efficient SGD via Gradient Quantization and Encoding](https://proceedings.neurips.cc/paper_files/paper/2017/file/6c340f25839e6acdc73414517203f5f0-Paper.pdf)
- `💎` 📄 [Deep Gradient Compression: Reducing the Communication Bandwidth for Distributed Training](https://openreview.net/pdf?id=SkhQHMW0W)
- `💎` 📄 [Don't Waste Your Bits! Squeeze Activations and Gradients for Deep Neural Networks via TinyScript](https://proceedings.mlr.press/v119/fu20c/fu20c.pdf)
- `💎` 📄 [PowerSGD: Practical Low-Rank Gradient Compression for Distributed Optimization](https://proceedings.neurips.cc/paper_files/paper/2019/file/d9fbed9da256e344c1fa46bb46c34c5f-Paper.pdf)

</details>

<details open>
<summary>

##### 显存节约

</summary>

- `💎` 📄 [(Activation Checkpointing/Recomputation) Training Deep Nets with Sublinear Memory Cost](https://arxiv.org/abs/1604.06174)
- `💎` 📄 [(Offloading) vDNN: Virtualized Deep Neural Networks for Scalable, Memory-Efficient Neural Network Design](https://dl.acm.org/doi/10.5555/3195638.3195660)

</details>

<details open>
<summary>

##### 算子融合优化

</summary>

- `💎` 📄 [FlashAttention: Fast and Memory-Efficient Exact Attention with IO-Awareness](https://openreview.net/pdf?id=H4DqfPSibmx)
- `💎` 📄 [FlashAttention-2: Faster Attention with Better Parallelism and Work Partitioning](https://openreview.net/pdf?id=mZn2Xyh9Ec)

</details>

<details open>
<summary>

##### 长序列训练

</summary>

- `💡` 📄 [Striped Attention: Faster Ring Attention for Causal Transformers](https://arxiv.org/abs/2311.09431)
- `💡` 📄 [USP: A Unified Sequence Parallelism Approach for Long Context Generative AI](https://arxiv.org/abs/2405.07719)
- `💡` 📄 [LoongTrain: Efficient Training of Long-Sequence LLMs with Head-Context Parallelism](https://arxiv.org/abs/2406.18485)
- `💡` 📄 [Efficiently Training 7B LLM with 1 Million Sequence Length on 8 GPUs](https://arxiv.org/abs/2407.12117)


</details>

<details open>
<summary>

##### 多模态训练

</summary>

- `💡` 📄 [DistTrain: Addressing Model and Data Heterogeneity with Disaggregated Training for Multimodal Large Language Models](https://arxiv.org/abs/2408.04275)
- `💡` 📄 [Optimus: Accelerating Large-Scale Multi-Modal LLM Training by Bubble Exploitation](https://arxiv.org/abs/2408.03505)
- `💡` 📄 [Efficient Multi-Task Large Model Training via Data Heterogeneity-aware Model Management](https://arxiv.org/abs/2409.03365)

</details>

<details open>
<summary>

##### 异构训练

</summary>

- `💡` 📄 [HetHub: A Heterogeneous distributed hybrid training system for large-scale models](https://arxiv.org/abs/2405.16256)
- `💡` 📄 [AMP: Automatically Finding Model Parallel Strategies with Heterogeneity Awareness](https://proceedings.neurips.cc/paper_files/paper/2022/file/2b4bfa1cebe78d125fefd7ea6ffcfc6d-Paper-Conference.pdf)
- `💡` 📄 [AccPar: Tensor Partitioning for Heterogeneous Deep Learning Accelerators](https://ieeexplore.ieee.org/document/9065574)
- `💡` 📄 [Whale: Scaling Deep Learning Model Training to the Trillions](https://www.usenix.org/system/files/atc22-jia-xianyan.pdf)

</details>

### LLM推理服务

<details open>
<summary>

##### LLM服务系统框架

</summary>

- `⚡` 🛠️ [vLLM](https://github.com/vllm-project/vllm)

</details>

<details open>
<summary>

##### 综述

</summary>

- `⚡` 📄 [A Survey on Efficient Inference for Large Language Models](https://arxiv.org/abs/2404.14294)
- `⚡` 📄 [Towards Efficient Generative Large Language Model Serving: A Survey from Algorithms to Systems](https://arxiv.org/abs/2312.15234)

</details>

<details open>
<summary>

##### Batching

</summary>

- `⚡` 📄 [Orca: A Distributed Serving System for Transformer-Based Generative Models](https://www.usenix.org/system/files/osdi22-yu.pdf)

</details>

<details open>
<summary>

##### 模型并行

</summary>

> 分布式推理中也有用到很多并行策略，建议对前面关于并行策略的内容也进行阅读了解

- `⚡` 📄 [AlpaServe: Statistical Multiplexing with Model Parallelism for Deep Learning Serving](https://www.usenix.org/system/files/osdi23-li-zhuohan.pdf)

</details>

<details open>
<summary>

##### 显存管理

</summary>

- `⚡` 📄 [Efficient Memory Management for Large Language Model Serving with PagedAttention](https://dl.acm.org/doi/10.1145/3600006.3613165)

</details>

<details open>
<summary>

##### 投机推理

</summary>

- `⚡` 📄 [Fast Inference from Transformers via Speculative Decoding](https://openreview.net/pdf?id=C9NEblP8vS)

</details>

<details open>
<summary>

##### Prefix Sharing

</summary>

- `⚡` 📄 [SGLang: Efficient Execution of Structured Language Model Programs](https://arxiv.org/abs/2312.07104)

</details>

<details open>
<summary>

##### PD分离

</summary>

- `💎` 📄 [DistServe: Disaggregating Prefill and Decoding for Goodput-optimized Large Language Model Serving](https://www.usenix.org/system/files/osdi24-zhong-yinmin.pdf)
- `💎` 📄 [Splitwise: Efficient generative LLM inference using phase splitting](https://www.computer.org/csdl/proceedings-article/isca/2024/265800a118/1Z3pCOHPSuc)
- `💎` 📄 [Inference without Interference: Disaggregate LLM Inference for Mixed Downstream Workloads](https://arxiv.org/abs/2401.11181)
- `💎` 📄 [Mooncake: A KVCache-centric Disaggregated Architecture for LLM Serving](https://arxiv.org/abs/2407.00079)

</details>

<details open>
<summary>

##### Chunked Prefill

</summary>

- `💎` 📄 [Taming Throughput-Latency Tradeoff in LLM Inference with Sarathi-Serve](https://www.usenix.org/system/files/osdi24-agrawal.pdf)

</details>

<details open>
<summary>

##### 模型压缩

</summary>

- `💎` 📄 [GPTQ: Accurate Post-Training Quantization for Generative Pre-trained Transformers](https://openreview.net/pdf?id=tcbBPnfwxS)
- `💎` 📄 [AWQ: Activation-aware Weight Quantization for LLM Compression and Acceleration](https://proceedings.mlsys.org/paper_files/paper/2024/file/42a452cbafa9dd64e9ba4aa95cc1ef21-Paper-Conference.pdf)
- `💎` 📄 [SmoothQuant: Accurate and Efficient Post-Training Quantization for Large Language Models](https://proceedings.mlr.press/v202/xiao23c/xiao23c.pdf)


</details>

### Diffusion（文生图、文生视频）推理服务

<details open>
<summary>

##### DiT系统框架

</summary>

- `⚡` 🛠️ [xDiT](https://github.com/xdit-project/xDiT)
- `⚡` 🛠️ [VideoSys](https://github.com/NUS-HPC-AI-Lab/VideoSys)

</details>

<details open>
<summary>

##### 分布式推理

</summary>

- `⚡` 📄 [DistriFusion: Distributed Parallel Inference for High-Resolution Diffusion Models](https://openaccess.thecvf.com/content/CVPR2024/papers/Li_DistriFusion_Distributed_Parallel_Inference_for_High-Resolution_Diffusion_Models_CVPR_2024_paper.pdf)
- `⚡` 📄 [PipeFusion: Displaced Patch Pipeline Parallelism for Inference of Diffusion Transformer Models](https://arxiv.org/abs/2405.14430)
</details>

