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


### ML数据侧入门+选方向


<details open>
<summary>

##### 数据测基础：

**Data-Centric ML是研究使用数据生成、选择与配比等方法实现大规模，高效以及提升模型表现的研究方向。**

</summary>

- `⚡` 🗞️ [MIT DCAI 2024](https://dcai.csail.mit.edu/)
> 课程难度不大，但是涵盖了很多 DCAI 的 Topic，包括但不限于：Data Selection/Data Cleaning/Distribution Shift/Data Curation 等，每节课都有一个配套的实验，完成难度也不大，完成后可以对该topic有一个比较 general 的认识
- `⚡` 🗞️ [华盛顿大学 DCAI](https://koh.pw/cse599j/)
> 新课程，等待评测中……
- `⚡` 🗞️ 数据生成（数据生成主要是通过大语言模型，diffusion model等生成模型，生成高质量数据并用于训练模型）
- `⚡` 🗞️ 数据配比（数据配比主要是通过多个领域的数据进行配比，让大模型能够获得多个领域的能力）
- `⚡` 🗞️ 数据选择（数据选择是通过大语言模型，Metric等指标筛选高质量数据，达到Efficiency和Effectiveness）

</details>

<details open>
<summary>

##### 多模态大模型数据侧

**多模态大模型主要分为VideoLLM和ImageLLM。这里主要研究image, video的数据生成选择**

</summary>

1. 入门文档

- `⚡` 💭 [多模态大模型入门文档](https://wcny4qa9krto.feishu.cn/wiki/Lyq9wNeovivXpbkwaNVcebrCnnb?from=from_copylink)

2. ImageLLMs

- `⚡` 💭 https://arxiv.org/abs/2301.12597
- `⚡` 💭 https://arxiv.org/abs/2304.10592
- `⚡` 💭 https://arxiv.org/abs/2304.08485
- `⚡` 💭 https://arxiv.org/abs/2310.03744

3. VideoLLMs

- `⚡` 💭 https://arxiv.org/abs/2308.12966
- `⚡` 💭 https://arxiv.org/abs/2306.02858
- `⚡` 💭 https://arxiv.org/abs/2311.10122
- `⚡` 💭 https://arxiv.org/abs/2311.17005
- `⚡` 💭 https://arxiv.org/abs/2403.15377

> 可能有帮助的[文档](https://docs.google.com/document/d/13iqTmfJZVt8Mk3yt9icXQq_Nvbkf99PGIKJaKJBb_2c/edit?usp=sharing)

1. Data-Centric VLMs（主要是数据的选择、增强(recaption)，比如重写caption）
- `⚡` 💭 https://arxiv.org/abs/2310.03744
- `⚡` 💭 https://arxiv.org/abs/2311.06607
- `⚡` 💭 https://arxiv.org/abs/2311.12793
- `⚡` 💭 https://arxiv.org/abs/2311.10122
- `⚡` 💭 https://arxiv.org/abs/2311.17005
- `⚡` 💭 https://arxiv.org/abs/2404.03413
> 见这些论文使用的数据，同时这三个论文的模型和数据量可以训练，其余模型训练不出来（Datasets）

</details>

<details open>
<summary>

##### Data-Centric AI4Math

**大模型展现了强大的语言能力。但是数学能力仍有待加强，特别是计算能力。Data-Centric AI4Math主要是研究使用数据生成、选择、配比的方式加强模型的数学能力，探究数据对于模型数学能力的影响。**

</summary>

1. MathLLMs：专门为解决数学问题而设计的大语言模型

入门论文：

- `⚡` 📄+🔧 https://arxiv.org/abs/2402.03300https://arxiv.org/abs/2402.06332
- `⚡` 📄+🔧 https://arxiv.org/abs/2405.12209

数学数据集：

- `⚡` 📄+🔧 https://arxiv.org/abs/2402.03300https://arxiv.org/abs/2402.06332

> 数学知识按照难度分为小学，初中，高中和大学。大学又有很多细分，比如数学分析，高等代数以及概率论与数理统计，最优化方法，数值分析等等目前观察到的现象是说，无论是否是Math的模型，在SFT之后高中和大学数学能力都会大幅度下降，说明数据集的构建不利于高中和大学数学能力的学习

</details>

<details open>
<summary>

##### 纯语言多模态大语言模型数据侧

**1）大模型的数据生成**

**2）大模型的思考**

</summary>

> 1）大模型的数据生成大模型的生成数据和原始训练数据分布有较大差异。想要控制生成数据的分布仍然十分困难。主要是希望能够提升生成数据的可控性

> 2）大模型的思考
目前以GPT-o1为首的大模型引入了基于强化学习的思考机制，但这种思考机制仍不完全明确。
另一方面，基于统计信息的大模型无法保证全部正确，因此对于这种基于统计的模型，如何Verify模型的正确性十分重要。
最后，这可能会引出生成数据的终极形态，就是自我对抗学习，自我生产数据学习，无需再收集训练数据。类似AlphaGO

1. 大模型的数据生成调研
- `⚡` 📄+🔧 [生成数据分布、可控数据生成调研](https://wcny4qa9krto.feishu.cn/wiki/CoSywYR6gim7V2kxTTIc73FTnKe?from=from_copylink)
- `⚡` 📄+🔧 [MAGPIE: Alignment Data Synthesis from Scratch by Prompting Aligned LLMs with Nothing](https://arxiv.org/abs/2406.08464)

2. 大模型的思考调研
- `⚡` 📄+🔧 [GPT等大模型思考](https://wcny4qa9krto.feishu.cn/wiki/K8EYw6Woii9bDJkLxLGc6WXQnzg?from=from_copylink)

</details>

<details open>
<summary>

##### Data Centric工具  

**1） Data Centric AI数据侧工具开发 主要涉及到数据生成、配比、处理、抽取模块 也有辅助模块，比如数据的压缩，AutoML，数据标注等**

**2） Data Centric AI数据侧工具相关的科研 比如数据的评估模块相关的科研**

</summary>

> 1）Data Centric AI数据侧开发，主要关注Data Juicer，要求对于数据侧有比较详细的了解
> 2）Data Centric AI数据侧工具相关的科研
需要对于数据侧工具有一定的了解，阅读相关的论文
附录：数据评估相关论文

1. Image数据评估论文
- `⚡` 📄+🔧 [CLIPScore: A Reference-free Evaluation Metric for Image Captioning](https://arxiv.org/abs/2104.08718)
- `⚡` 📄+🔧 [InfoMetIC: An Informative Metric for Reference-free Image Caption Evaluation](https://aclanthology.org/2023.acl-long.178.pdf)

1. 下面两篇是follow-up的新工作
- `⚡` 📄+🔧 [leverage large multimodal model](https://arxiv.org/pdf/2406.06004)
- `⚡` 📄+🔧 [Video数据评估论文](https://arxiv.org/pdf/2407.18589)

1. EMScore
- `⚡` 📄+🔧 [EMScore: Evaluating Video Captioning via Coarse-Grained and Fine-Grained Embedding Matching](https://arxiv.org/abs/2111.08919)

1. PAC-S
- `⚡` 📄+🔧 [Positive-Augmented Contrastive Learning for Image and Video Captioning Evaluation](https://arxiv.org/abs/2303.12112)

> 1）Data Centric AI数据侧开发
涉及到数据生成、配比、处理、抽取
目前数据处理需要自己编写代码，每个公司都有自己数据处理的方式，更多事“小作坊式”数据处理。
我们想要写类似Pytorch的工具来统一数据处理

> 2）Data Centric AI数据侧工具相关的科研
在开发数据侧工具的同时，我们也需要对于其中的许多算法进行改进，比如image-caption，video-caption的评估等等

</details>

### Multimodal LLM

<details open>
<summary>

##### 入门文档

</summary>

- `⚡` 📄+🔧 [参考多模态大模型入门文档](https://wcny4qa9krto.feishu.cn/wiki/Lyq9wNeovivXpbkwaNVcebrCnnb)
- `⚡` 📄 Survey: https://arxiv.org/pdf/2306.13549

</details>

<details open>
<summary>

##### Vision-Language Model中视觉特征的提取与选择 

**1）主流的VLM普遍使用CLIP-ViT作为Vision Encoder，通过对比学习训练的视觉编码器无法提取细粒度的图像特征，单纯增加图像分辨率对输入窗口影响过大，因此不同VE的融合（比如DINO，SigLip等）与选择是必要的。**

**2）当前的高分辨率VLLM将图像编码为高分辨率的visual token，计算成本过大。如何选择特定的、问题相关的高分辨率视觉特征，设计灵活高效的注意力机制是必要的。**

</summary>

- `⚡` 📄+🔧 https://brave-vlms.epfl.ch/
- `⚡` 📄+🔧 https://arxiv.org/abs/2401.06209
- `⚡` 📄+🔧 https://arxiv.org/abs/2407.20228
- `⚡` 📄+🔧 https://arxiv.org/abs/2310.08825

> 1. 不同vision encoder的视觉特征分析与组合

> 2. Question-aware的高分辨率视觉特征的提取与注入

</details>

<details open>
<summary>

##### MLLM中Image，video，audio等不同模态之间的对齐范式设计 

**1）在当前的X-to-T多模态理解模型中，通常使用简单的模块(如MLP)作为跨模态表示的桥梁，但这些方法往往因为简单的空间映射导致不同模态的表征之间产生偏差，从而影响模型的推理和生成。**

**2）设计更复杂且高效的跨模态对齐机制，尤其是在不同模态间的对齐机制上进行优化是必要的。**

</summary>

- `⚡` 📄+🔧 https://github.com/BradyFU/Awesome-Multimodal-Large-Language-Models?tab=readme-ov-file
- `⚡` 📄+🔧 https://arxiv.org/pdf/2408.05211

> 1. 创新性的训练范式

> 2. Modality Projector / Resampler的设计（拼接后输入或llm内部注入）

> 3. 跨模态间交互的可解释性

</details>

### Multimodal & Alignment入门+选方向

<details open>
<summary>

##### llm/mllm RLHF:在强化学习和rlhf的基础上开发新的对齐范式，以及专注于XAI，可解释性alignment后和数据分布

</summary>

- `⚡` 📄+🔧 PPO, DPO, IPO, KPO, SPPO等前置工作
- `⚡` 📄+🔧 [对齐Survey](https://arxiv.org/pdf/2404.18922)

> 1. XPO新对齐范式系列工作
> 2. 重新modeling对齐范式，不拘泥于rlhf
> 3. 对齐新范式系列工作
> 4. 基于数据分布的对齐可解释性
> 5. 训练过程的可解释性

</details>

<details open>
<summary>

##### Downstream alignment

</summary>

> 1. 医疗任务对齐
> 2. AIGC对齐
> 3. benchmark/打榜

</details>

<details open>
<summary>

##### Multimodal alignment

</summary>

> 1.模态融合算法/架构
> 2.多模态对齐范式

</details>

<details open>
<summary>

##### llm/mllm Trustworthiness: 让AI系统更安全，鲁棒，可信

</summary>

- `⚡` 📄+🔧 Llm safety survey
- `⚡` 📄+🔧 Mllm safety survey
- `⚡` 📄+🔧 mllm Trustworthiness survey

> 1. llm/mllm攻防技术
> 2. 多维度alignment
> 3. 模型训练减少
> 4. hallucinattion的系列工作

</details>

##### Diffusion model

</summary>

> 1.加入encoder的diffusion

</details>

### RAG


<details open>
<summary>

##### 领域综述

</summary>

- `⚡` 📄+🔧 [组里一篇RAG的Survey供参考](https://arxiv.org/abs/2402.19473)

</details>
