<p align="center">
    <h1 align="center">🧬 Graph方向</h1>
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

### GNN基础


<details open>
<summary>

##### 基础介绍

</summary>

- `⚡` 🎓 [Stanford CS224W](https://www.youtube.com/watch?v=JAB_plj2rbA)

</details>

<details open>
<summary>

##### GNN基础模型

</summary>

- `⚡` 📄 [Semi-supervised Classification with Graph Convolutional Networks](https://openreview.net/forum?id=SJU4ayYgl)
- `⚡` 📄 [Inductive Representation Learning on Large Graphs](https://proceedings.neurips.cc/paper/2017/hash/5dd9db5e033da9c6fb5ba83c7a7ebea9-Abstract.html)
- `⚡` 📄 [Graph Attention Networks](https://openreview.net/forum?id=rJXMpikCZ)
- `⚡` 📄 [Simplifying Graph Convolutional Networks](https://proceedings.mlr.press/v97/wu19e)

</details>

<details open>
<summary>

##### GNN原理

</summary>

- `💎` 📄 [Convolutional Neural Networks on Graphs with Fast Localized Spectral Filtering](https://proceedings.neurips.cc/paper_files/paper/2016/hash/04df4d434d481c5bb723be1b6df1ee65-Abstract.html)
- `💎` 📄 [Spectral Networks and Locally Connected Networks on Graphs](https://arxiv.org/abs/1312.6203)
- `💡` 📄 [The Emerging Field of Signal Processing on Graphs Extending High-Dimensional Data Analysis to Networks and Other Irregular Domains](https://ieeexplore.ieee.org/abstract/document/6494675/)

</details>

<details open>
<summary>

##### GNN流行工具包

</summary>

- `⚡` 🔧 [Fast Graph Representation Learning with PyTorch Geometric](https://github.com/pyg-team/pytorch_geometric)
- `⚡` 🔧 [Deep Graph Library: A Graph-Centric, Highly Performant Package for Graph Neural Networks](https://github.com/dmlc/dgl)

</details>

### 异构图GNN

<details open>
<summary>

##### 综述

</summary>

- `⚡` 📄 [A Survey on Heterogeneous Graph Embedding: Methods, Techniques, Applications and Sources](https://ieeexplore.ieee.org/abstract/document/9780569)

</details>

<details open>
<summary>

##### 基于Relation

</summary>

- `⚡` 📄 [Relation Structure-Aware Heterogeneous Graph Neural Network](https://ieeexplore.ieee.org/abstract/document/8970828)
- `⚡` 📄 [Scalable Graph Neural Networks for Heterogeneous Graphs](https://arxiv.org/abs/2011.09679)

</details>

<details open>
<summary>

##### 基于Metapath (Attention)

</summary>

- `⚡` 📄 [metapath2vec: Scalable Representation Learning for Heterogeneous Networks](https://dl.acm.org/doi/abs/10.1145/3097983.3098036)
- `⚡` 📄 [Heterogeneous Graph Attention Network](https://dl.acm.org/doi/abs/10.1145/3308558.3313562)
- `⚡` 📄 [Simple and Efficient Heterogeneous Graph Neural Network](https://ojs.aaai.org/index.php/AAAI/article/view/26283)

</details>

<details open>
<summary>

##### 无需Metapath (Transformer)

</summary>


- `⚡` 📄 [Heterogeneous Graph Transformer](https://dl.acm.org/doi/abs/10.1145/3366423.3380027)
- `⚡` 📄 [Are we really making much progress? Revisiting, benchmarking, and refining heterogeneous graph neural networks](https://dl.acm.org/doi/abs/10.1145/3447548.3467350)

</details>

### 以数据为中心的图学习

<details open>
<summary>

##### 图压缩

</summary>

- `⚡` 📄 [Graph Condensation for Graph Neural Networks](https://openreview.net/forum?id=WLEx3Jo4QaB)
- `⚡` 📄 [Heterogeneous Graph Condensation](https://ieeexplore.ieee.org/abstract/document/10423255)
- `⚡` 📄 [Fast Graph Condensation with Structure-based Neural Tangent Kernel](https://dl.acm.org/doi/abs/10.1145/3589334.3645694)
- `⚡` 📄 [Graph Condensation via Eigenbasis Matching](https://arxiv.org/abs/2310.09202)
- `⚡` 📄 [Graph-Skeleton: ∼1% Nodes are Sufficient to Represent Billion-Scale Graph](https://dl.acm.org/doi/abs/10.1145/3589334.3645452)
- `⚡` 📄 [Heterogeneous Graph Condensation](https://ieeexplore.ieee.org/abstract/document/10423255)

</details>


<details open>
<summary>

##### 图结构学习

</summary>

- `⚡` 📄 [Deep Graph Structure Learning for Robust Representations: A Survey](https://arxiv.org/abs/2103.03036)
- `⚡` 📄+🔧 [GSLB: The Graph Structure Learning Benchmark](https://github.com/GSL-Benchmark/GSLB)
- `⚡` 📄+🔧 [OpenGSL: A Comprehensive Benchmark for Graph Structure Learning](https://github.com/OpenGSL/OpenGSL)
- `💎` 📄 [Towards Unsupervised Deep Graph Structure Learning](https://dl.acm.org/doi/abs/10.1145/3485447.3512186)
- `💎` 📄 [Heterogeneous Graph Structure Learning for Graph Neural Networks](https://ojs.aaai.org/index.php/AAAI/article/view/16600)
- `💎` 📄 [NodeFormer: A Scalable Graph Structure Learning Transformer for Node Classification](https://proceedings.neurips.cc/paper_files/paper/2022/hash/af790b7ae573771689438bbcfc5933fe-Abstract-Conference.html)

</details>



<details open>
<summary>

##### 图数据增强

</summary>

- `⚡` 📄 [Graph Data Augmentation for Graph Machine Learning: A Survey](https://arxiv.org/abs/2202.08871)
- `⚡` 📄 [Data Augmentation for Deep Graph Learning: A Survey](https://dl.acm.org/doi/abs/10.1145/3575637.3575646)
- `💎` 📄 [An Empirical Study of Graph Contrastive Learning](https://openreview.net/forum?id=UuUbIYnHKO)
- `💎` 📄 [Learning Graph Augmentations to Learn Graph Representations](https://arxiv.org/abs/2201.09830)
- `💎` 📄 [Robust Optimization as Data Augmentation for Large-scale Graphs](https://openaccess.thecvf.com/content/CVPR2022/html/Kong_Robust_Optimization_As_Data_Augmentation_for_Large-Scale_Graphs_CVPR_2022_paper.html)
- `💎` 📄 [Learning to Drop: Robust Graph Neural Network via Topological Denoising](https://dl.acm.org/doi/abs/10.1145/3437963.3441734)
- `💎` 📄 [G-Mixup: Graph Data Augmentation for Graph Classification](https://proceedings.mlr.press/v162/han22c.html)

</details>


<details open>
<summary>

##### 图数据标注

</summary>

- `⚡` 📄 [Active Learning for Graph Embedding](https://arxiv.org/abs/1705.05085)
- `⚡` 📄 [Grain Improving Data Efficiency of Graph Neural Networks via Diversified Influence Maximization](https://dl.acm.org/doi/abs/10.14778/3476249.3476295)
- `⚡` 📄 [ALG Fast and Accurate Active Learning Framework for Graph Convolutional Networks](https://dl.acm.org/doi/abs/10.1145/3448016.3457325)
- `⚡` 📄 [Label-free Node Classification on Graphs with Large Language Models (LLMs)](https://openreview.net/forum?id=hESD2NJFg8)
- `💎` 📄 [RIM Reliable Influence-based Active Learning on Graphs](https://proceedings.neurips.cc/paper/2021/hash/eb86d510361fc23b59f18c1bc9802cc6-Abstract.html)

</details>



### GNN加速

<details open>
<summary>

##### 综述

</summary>

- `⚡` 📄 [Parallel and Distributed Graph Neural Networks An In-Depth Concurrency Analysis](https://ieeexplore.ieee.org/abstract/document/10443519/)
- `⚡` 📄 [Acceleration Algorithms in GNNs: A Survey](https://arxiv.org/abs/2405.04114)



</details>

<details open>
<summary>

##### 系统层面单机加速

</summary>

- `⚡` 📄+🛠️ [PaGraph Scaling GNN Training on Large Graphs via Computation-aware Caching](https://dl.acm.org/doi/abs/10.1145/3419111.3421281)
- `💎` 📄+🛠️ [Large Graph Convolutional Network Training with GPU-oriented Data Communication Architecture](https://dl.acm.org/doi/abs/10.14778/3476249.3476264)

</details>

<details open>
<summary>

##### 系统层面分布式加速

</summary>

- `⚡` 📄+🛠️ [DistDGL Distributed Graph Neural Network Training for Billion-Scale Graphs](https://ieeexplore.ieee.org/abstract/document/9407264/)
- `💎` 📄+🛠️ [P3 Distributed Deep Graph Learning at Scale](https://www.usenix.org/conference/osdi21/presentation/gandhi)

</details>

<details open>
<summary>

##### 其他系统层面加速技术

</summary>

- `💎` 📄+🛠️ [Ginex SSD-enabled Billion-scale Graph Neural Network Training on a Single Machine via Provably In-memory Caching](https://dl.acm.org/doi/abs/10.14778/3551793.3551819)
- `💎` 📄+🛠️ [OUTRE: An OUT-of-Core De-REdundancy GNN Training Framework for Massive Graphs within A Single Machine](https://dl.acm.org/doi/abs/10.14778/3681954.3681976)
- `💎` 📄+🛠️ [DGI An Easy and Efficient Framework for GNN Model Evaluation](https://dl.acm.org/doi/abs/10.1145/3580305.3599805)
- `💎` 📄+🛠️ [Graphiler Optimizing Graph Neural Networks with Message Passing Data Flow Graph](https://proceedings.mlsys.org/paper_files/paper/2022/hash/a1126573153ad7e9f44ba80e99316482-Abstract.html)

</details>

<details open>
<summary>


##### 算法层面训练阶段加速技术

</summary>

- `⚡` 📄 [Inductive Representation Learning on Large Graphs](https://proceedings.neurips.cc/paper/2017/hash/5dd9db5e033da9c6fb5ba83c7a7ebea9-Abstract.html)
- `⚡` 📄 [FastGCN: Fast Learning with Graph Convolutional Networks via Importance Sampling](https://openreview.net/forum?id=rytstxWAW)
- `⚡` 📄 [GraphSAINT: Graph Sampling Based Inductive Learning Method](https://openreview.net/forum?id=BJe8pkHFwS)
- `⚡` 📄 [Simplifying Graph Convolutional Networks](http://proceedings.mlr.press/v97/wu19e)
- `⚡` 📄 [Graph Attention Multi-Layer Perceptron](https://dl.acm.org/doi/abs/10.1145/3534678.3539121)
- `💎` 📄 [Predict Then Propagate: Graph Neural Networks Meet Personalized PageRank](https://openreview.net/forum?id=H1gL-2A9Ym)

</details>


<details open>
<summary>


##### 算法层面推理阶段加速技术

</summary>

- `⚡` 📄 [Distilling Knowledge from Graph Convolutional Networks](http://openaccess.thecvf.com/content_CVPR_2020/html/Yang_Distilling_Knowledge_From_Graph_Convolutional_Networks_CVPR_2020_paper.html)
- `⚡` 📄 [Degree-Quant: Quantization-Aware Training for Graph Neural Networks](https://openreview.net/forum?id=NSBrFgJAHg)
- `💎` 📄 [Graph-Less Neural Networks: Teaching Old MLPs New Tricks via Distillation](https://openreview.net/forum?id=4p6_5HBWPCw)
- `💎` 📄 [NOSMOG: Learning Noise-robust and Structure-aware MLPs on Graphs](https://openreview.net/forum?id=nT897hw-hHD)
- `💎` 📄 [The Lottery Ticket Hypothesis: Finding Sparse, Trainable Neural Networks](https://openreview.net/forum?id=rJl-b3RcF7)

</details>




### GNN与LLM结合

<details open>
<summary>

##### 综述

</summary>

- `⚡` 📄 [Large Language Models on Graphs A Comprehensive Survey](https://ieeexplore.ieee.org/abstract/document/10697304/)
- `⚡` 📄 [Towards Graph Foundation Models: A Survey and Beyond](https://arxiv.org/abs/2310.11829)


</details>

<details open>
<summary>

##### 以GNN为中心

</summary>

- `⚡` 📄 [Harnessing Explanations LLM-to-LM Interpreter for Enhanced Text-Attributed Graph Representation Learning](https://openreview.net/forum?id=RXFVcynVe1)
- `⚡` 📄 [Empowering Text-Attributed Graph Learning with Large Language Models (LLMs)](https://arxiv.org/abs/2310.09872)
- `⚡` 📄 [One For All Towards Training One Graph Model for All Classification Tasks](https://openreview.net/forum?id=4IT2pgc9v6)

</details>


<details open>
<summary>

##### 以LLM为中心

</summary>

- `⚡` 📄 [GPT4Graph Can Large Language Models Understand Graph Structured Data An Empirical Evaluation and Benchmarking](https://arxiv.org/abs/2305.15066)
- `⚡` 📄 [Language is All a Graph Needs](https://aclanthology.org/2024.findings-eacl.132/)
- `⚡` 📄 [GraphGPT Graph Instruction Tuning for Large Language Models](https://dl.acm.org/doi/abs/10.1145/3626772.3657775)
- `💎` 📄 [LLaGA Large Language and Graph Assistant](https://openreview.net/forum?id=B48Pzc4oKi)

</details>



