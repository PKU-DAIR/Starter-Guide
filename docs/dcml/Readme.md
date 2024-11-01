<p align="center">
    <h1 align="center">🔥 Data-Centric ML方向</h1>
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


### Data Centric ML Basic

<details open>
<summary>

##### 数据侧基础：

**Data-Centric ML是研究使用数据生成、选择与配比等方法实现大规模，高效以及提升模型表现的研究方向。**

</summary>

- `⚡` 🗞️ [MIT DCAI 2024](https://dcai.csail.mit.edu/)
> 课程难度不大，但是涵盖了很多 DCAI 的 Topic，包括但不限于：Data Selection/Data Cleaning/Distribution Shift/Data Curation 等，每节课都有一个配套的实验，完成难度也不大，完成后可以对该topic有一个比较 general 的认识
- `⚡` 🗞️ [华盛顿大学 DCAI](https://koh.pw/cse599j/)

</details>

### LLM and VLM Basic

<details open>
<summary>

##### Quick Start

</summary>

- `⚡` 📄+🔧 [多模态大模型入门文档](https://wcny4qa9krto.feishu.cn/wiki/Lyq9wNeovivXpbkwaNVcebrCnnb)
- `⚡` 📄 [Survey](https://arxiv.org/pdf/2306.13549)

</details>

<details open>
<summary>

##### ImageLLMs

</summary>

- `⚡` 💭 [BLIP-2: Bootstrapping Language-Image Pre-training with Frozen Image Encoders and Large Language Models](https://arxiv.org/abs/2301.12597)
- `⚡` 💭 [MiniGPT-4: Enhancing Vision-Language Understanding with Advanced Large Language Models](https://arxiv.org/abs/2304.10592)
- `⚡` 💭 [Visual Instruction Tuning](https://arxiv.org/abs/2304.08485)
- `⚡` 💭 [Improved Baselines with Visual Instruction Tuning](https://arxiv.org/abs/2310.03744)

</details>

<details open>
<summary>

##### VideoLLMs

</summary>

- `⚡` 💭 [Qwen-VL: A Versatile Vision-Language Model for Understanding, Localization, Text Reading, and Beyond](https://arxiv.org/abs/2308.12966)
- `⚡` 💭 [Video-LLaMA: An Instruction-tuned Audio-Visual Language Model for Video Understanding](https://arxiv.org/abs/2306.02858)
- `⚡` 💭 [Video-LLaVA: Learning United Visual Representation by Alignment Before Projection](https://arxiv.org/abs/2311.10122)
- `⚡` 💭 [MVBench: A Comprehensive Multi-modal Video Understanding Benchmark](https://arxiv.org/abs/2311.17005)
- `⚡` 💭 [InternVideo2: Scaling Foundation Models for Multimodal Video Understanding](https://arxiv.org/abs/2403.15377)

> 可能有帮助的[文档](https://docs.google.com/document/d/13iqTmfJZVt8Mk3yt9icXQq_Nvbkf99PGIKJaKJBb_2c/edit?usp=sharing)

</details>

<details open>
<summary>

##### Data-Centric VLMs（主要是数据的选择、增强(recaption)，比如重写caption）
</summary>

- `⚡` 💭 [Improved Baselines with Visual Instruction Tuning](https://arxiv.org/abs/2310.03744)
- `⚡` 💭 [Monkey: Image Resolution and Text Label Are Important Things for Large Multi-modal Models](https://arxiv.org/abs/2311.06607)
- `⚡` 💭 [ShareGPT4V: Improving Large Multi-Modal Models with Better Captions](https://arxiv.org/abs/2311.12793)
- `⚡` 💭 [Video-LLaVA: Learning United Visual Representation by Alignment Before Projection](https://arxiv.org/abs/2311.10122)
- `⚡` 💭 [MVBench: A Comprehensive Multi-modal Video Understanding Benchmark](https://arxiv.org/abs/2311.17005)
- `⚡` 💭 [MiniGPT4-Video: Advancing Multimodal LLMs for Video Understanding with Interleaved Visual-Textual Tokens](https://arxiv.org/abs/2404.03413)
> 见这些论文使用的数据，同时这三个论文的模型和数据量可以训练，其余模型训练不出来（Datasets）
</details>

<details open>
<summary>

##### Vision-Language Model Visual Information Extraction
</summary>

**1）主流的VLM普遍使用CLIP-ViT作为Vision Encoder，通过对比学习训练的视觉编码器无法提取细粒度的图像特征，单纯增加图像分辨率对输入窗口影响过大，因此不同VE的融合（比如DINO，SigLip等）与选择是必要的。**

**2）当前的高分辨率VLLM将图像编码为高分辨率的visual token，计算成本过大。如何选择特定的、问题相关的高分辨率视觉特征，设计灵活高效的注意力机制是必要的。**

- `⚡` 📄+🔧 [BRAVE: Broadening the visual encoding of vision-language models](https://brave-vlms.epfl.ch/)
- `⚡` 📄+🔧 [Eyes Wide Shut? Exploring the Visual Shortcomings of Multimodal LLMs](https://arxiv.org/abs/2401.06209)
- `⚡` 📄+🔧 [FlexAttention for Efficient High-Resolution Vision-Language Models](https://arxiv.org/abs/2407.20228)
- `⚡` 📄+🔧 [From CLIP to DINO: Visual Encoders Shout in Multi-modal Large Language Models](https://arxiv.org/abs/2310.08825)

> 1. 不同vision encoder的视觉特征分析与组合

> 2. Question-aware的高分辨率视觉特征的提取与注入

</details>

<details open>
<summary>

##### Modality Alignment
</summary>

**1）在当前的X-to-T多模态理解模型中，通常使用简单的模块(如MLP)作为跨模态表示的桥梁，但这些方法往往因为简单的空间映射导致不同模态的表征之间产生偏差，从而影响模型的推理和生成。**

**2）设计更复杂且高效的跨模态对齐机制，尤其是在不同模态间的对齐机制上进行优化是必要的。**

- `⚡` 📄+🔧 https://github.com/BradyFU/Awesome-Multimodal-Large-Language-Models?tab=readme-ov-file
- `⚡` 📄+🔧 https://arxiv.org/pdf/2408.05211

> 1. 创新性的训练范式

> 2. Modality Projector / Resampler的设计（拼接后输入或llm内部注入）

> 3. 跨模态间交互的可解释性

</details>

### Data Centric LLM and VLM Algorithms

- `⚡` 💭 [A Survey of Multimodal Large Language Model from A Data-centric Perspective](https://arxiv.org/abs/2405.16640)

<details open>
<summary>

##### Data Processing
</summary>

</details>

<details open>
<summary>


##### Data Evaluation
</summary>

- `⚡` 💭 [Awesome Data Evaluation](https://github.com/Open-DataFlow/Open-DataFlow-Eval/blob/main/Awesome_Data_Evaluation.md)
  
</details>

<details open>
<summary>

##### Data Generation
</summary>

- `⚡` 💭 [Comprehensive Exploration of Synthetic Data Generation: A Survey](https://arxiv.org/abs/2401.02524)
-  `⚡` 💭 [On LLMs-Driven Synthetic Data Generation, Curation, and Evaluation: A Survey](https://arxiv.org/abs/2406.15126)
  
</details>

<details open>
<summary>

##### Data Extraction(RAG)
</summary>

- `⚡` 💭 [Retrieval-Augmented Generation for AI-Generated Content: A Survey](https://arxiv.org/abs/2402.19473)
- `⚡` 💭 [GraphRAG](https://github.com/microsoft/graphrag)
- `⚡` 💭 [Raptor](https://arxiv.org/abs/2401.18059v1)
- `⚡` 💭 [QAEncoder: Towards Aligned Representation Learning in Question Answering System](https://arxiv.org/abs/2409.20434)

</details>

### Data Centric LLM and VLM Systems
> 1）Data Centric AI数据侧开发，主要关注Data Juicer，要求对于数据侧有比较详细的了解
> 2）Data Centric AI数据侧工具相关的科研
需要对于数据侧工具有一定的了解，阅读相关的论文
附录：数据评估相关论文

<details open>
<summary>

##### Image数据评估论文

</summary>

- `⚡` 📄+🔧 [CLIPScore: A Reference-free Evaluation Metric for Image Captioning](https://arxiv.org/abs/2104.08718)
- `⚡` 📄+🔧 [InfoMetIC: An Informative Metric for Reference-free Image Caption Evaluation](https://aclanthology.org/2023.acl-long.178.pdf)
- `⚡` 📄+🔧 [leverage large multimodal model](https://arxiv.org/pdf/2406.06004)
- `⚡` 📄+🔧 [Video数据评估论文](https://arxiv.org/pdf/2407.18589)

- `⚡` 📄+🔧 [EMScore: Evaluating Video Captioning via Coarse-Grained and Fine-Grained Embedding Matching](https://arxiv.org/abs/2111.08919)

- `⚡` 📄+🔧 [Positive-Augmented Contrastive Learning for Image and Video Captioning Evaluation](https://arxiv.org/abs/2303.12112)

</details>


### Data-Centric Domain-Specific LLMs
<details open>
<summary>

##### MathLLMs
</summary>

- `⚡` 📄+🔧 [DeepSeekMath: Pushing the Limits of Mathematical Reasoning in Open Language Models](https://arxiv.org/abs/2402.03300)
- `⚡` 📄+🔧 [InternLM-Math: Open Math Large Language Models Toward Verifiable Reasoning](https://arxiv.org/abs/2402.06332)
- `⚡` 📄+🔧 [MathBench: Evaluating the Theory and Application Proficiency of LLMs with a Hierarchical Mathematics Benchmark](https://arxiv.org/abs/2405.12209)

</details>

<details open>
<summary>

##### Math Datasets：

</summary>

- `⚡` 📄+🔧 [DeepSeekMath: Pushing the Limits of Mathematical Reasoning in Open Language Models](https://arxiv.org/abs/2402.03300)
- `⚡` 📄+🔧 [InternLM-Math: Open Math Large Language Models Toward Verifiable Reasoning](https://arxiv.org/abs/2402.06332)

> 数学知识按照难度分为小学，初中，高中和大学。大学又有很多细分，比如数学分析，高等代数以及概率论与数理统计，最优化方法，数值分析等等目前观察到的现象是说，无论是否是Math的模型，在SFT之后高中和大学数学能力都会大幅度下降，说明数据集的构建不利于高中和大学数学能力的学习

</details>