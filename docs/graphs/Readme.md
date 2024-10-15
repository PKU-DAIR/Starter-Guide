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

### GNN basics


<details open>
<summary>

##### basic introduction

</summary>

- `⚡` 🎓 Stanford CS224W, https://www.youtube.com/watch?v=JAB_plj2rbA

</details>

<details open>
<summary>

##### GNN model

</summary>

- `⚡` 📄 Semi-supervised Classification with Graph Convolutional Networks
- `⚡` 📄 Inductive Representation Learning on Large Graphs
- `⚡` 📄 Graph Attention Networks
- `⚡` 📄 Simplifying Graph Convolutional Networks

</details>

<details open>
<summary>

##### GNN Principle

</summary>

- `💎` 📄 Convolutional Neural Networks on Graphs with Fast Localized Spectral Filtering
- `💎` 📄 Spectral Networks and Locally Connected Networks on Graphs
- `💡` 📄 The Emerging Field of Signal Processing on Graphs Extending High-Dimensional Data Analysis to Networks and Other Irregular Domains

</details>

### Heterogeneous GNN


<details open>
<summary>

##### Library

</summary>

- `⚡` 🔧 Fast Graph Representation Learning with PyTorch Geometric, https://github.com/pyg-team/pytorch_geometric
- `⚡` 🔧 Deep Graph Library: A Graph-Centric, Highly Performant Package for Graph Neural Networks, https://github.com/dmlc/dgl

</details>

<details open>
<summary>

##### Survey

</summary>

- `⚡` 📄 A Survey on Heterogeneous Graph Embedding: Methods, Techniques, Applications and Sources

</details>

<details open>
<summary>

##### Representation Learning

</summary>

- `⚡` 📄 metapath2vec: Scalable Representation Learning for Heterogeneous Networks

</details>

<details open>
<summary>

##### Relation based

</summary>

- `⚡` 📄 Relation Structure-Aware Heterogeneous Graph Neural Network
- `⚡` 📄 SCALABLE GRAPH NEURAL NETWORKS FORHETEROGENEOUS GRAPHS

</details>

<details open>
<summary>

##### Metapath-based

</summary>

> Attention

- `⚡` 📄 Heterogeneous Graph Attention Network
- `⚡` 📄 Simple and Efficient Heterogeneous Graph Neural Network

</details>

### Graph condensation (Homogeneous)


<details open>
<summary>

##### Metapath-free

</summary>

> Transformer

- `⚡` 📄 Heterogeneous Graph Transformer
- `⚡` 📄 Are we really making much progress? Revisiting, benchmarking, and refining heterogeneous graph neural networks

</details>

<details open>
<summary>

##### Towards Accuracy

</summary>

> training-based

- `⚡` 📄 GRAPH CONDENSATION FOR GRAPH NEURAL NET-WORKS

</details>

<details open>
<summary>

##### Towards Efficiency

</summary>

> training-based

- `⚡` 📄 Fast Graph Condensation with Structure-based Neural Tangent Kernel

</details>

<details open>
<summary>

##### Towards Generalization

</summary>

> training-based

- `⚡` 📄 Graph Condensation via Eigenbasis Matching

</details>

### Graph condensation (Heterogeneous)


<details open>
<summary>

##### Training-free

</summary>

- `⚡` 📄 Graph-Skeleton: ∼1% Nodes are Sufficient to Represent Billion-Scale Graph

</details>

### Graph Structure Learning


<details open>
<summary>

##### Towards Accuracy

</summary>

> training-based

- `⚡` 📄 Heterogeneous Graph Condensation

</details>

<details open>
<summary>

##### Survey

</summary>

- `⚡` 📄 Deep Graph Structure Learning for Robust Representations: A Survey

</details>

<details open>
<summary>

##### Benchmark

</summary>

> 学习开源库

- `⚡` 📄+🔧 GSLB: The Graph Structure Learning Benchmark Github：https: //github.com/GSL-Benchmark/GSLB
- `⚡` 📄+🔧 OpenGSL: A Comprehensive Benchmark for Graph Structure Learning GitHub:  https://github.com/OpenGSL/OpenGSL

</details>

<details open>
<summary>

##### Pre-training based

</summary>

- `💎` 📄 Towards Unsupervised Deep Graph Structure Learning

</details>

<details open>
<summary>

##### Heterogeneous Graph

</summary>

- `💎` 📄 Heterogeneous Graph Structure Learning for Graph Neural Networks

</details>

### Graph Data Augmentation


<details open>
<summary>

##### Scalable GSL

</summary>

- `💎` 📄 NodeFormer: A Scalable Graph Structure Learning Transformer for Node Classification

</details>

<details open>
<summary>

##### Survey

</summary>

- `⚡` 📄 Graph Data Augmentation for Graph Machine Learning: A Survey
- `⚡` 📄 Data Augmentation for Deep Graph Learning: A Survey

</details>

<details open>
<summary>

##### GDA for GCL

</summary>

- `💎` 📄 An Empirical Study of Graph Contrastive Learning

</details>

<details open>
<summary>

##### AutoML + GDA

</summary>

- `💎` 📄 Learning Graph Augmentations to Learn Graph Representations

</details>

<details open>
<summary>

##### Scalable GDA

</summary>

- `💎` 📄 Robust Optimization as Data Augmentation for Large-scale Graphs

</details>

<details open>
<summary>

##### Edge-level GDA

</summary>

- `💎` 📄 Learning to Drop: Robust Graph Neural Network via Topological Denoising

</details>

### GNN System


<details open>
<summary>

##### GDA for graph-level task

</summary>

> ICML outstanding paper

- `💎` 📄 G-Mixup: Graph Data Augmentation for Graph Classification

</details>

<details open>
<summary>

##### Survey

</summary>

- `⚡` 📄 Parallel and Distributed Graph Neural Networks An In-Depth Concurrency Analysis

</details>

<details open>
<summary>

##### Single machine

</summary>

- `⚡` 📄+🛠️ PaGraph Scaling GNN Training on Large Graphs via Computation-aware Caching
- `💎` 📄+🛠️ Large Graph Convolutional Network Training with GPU-oriented Data Communication Architecture

</details>

<details open>
<summary>

##### Multi machine

</summary>

- `⚡` 📄+🛠️ DistDGL Distributed Graph Neural Network Training for Billion-Scale Graphs
- `💎` 📄+🛠️ P3 Distributed Deep Graph Learning at Scale

</details>

<details open>
<summary>

##### Out-of-core training

</summary>

- `💎` 📄+🛠️ Ginex SSD-enabled Billion-scale Graph Neural Network Training on a Single Machine via Provably In-memory Caching

</details>

<details open>
<summary>

##### Inference

</summary>

- `💎` 📄+🛠️ DGI An Easy and Efficient Framework for GNN Model Evaluation

</details>

### GNN+LLM


<details open>
<summary>

##### Compiler

</summary>

- `💎` 📄+🛠️ Graphiler Optimizing Graph Neural Networks with Message Passing Data Flow Graph

</details>

<details open>
<summary>

##### Survey

</summary>

- `⚡` 📄 Large Language Models on Graphs A Comprehensive Survey

</details>

<details open>
<summary>

##### GNN-centric

</summary>

- `⚡` 📄 Harnessing Explanations LLM-to-LM Interpreter for Enhanced Text-Attributed Graph Representation Learning
- `⚡` 📄 Empowering Text-Attributed Graph Learning with Large Language Models (LLMs)
- `⚡` 📄 One For All Towards Training One Graph Model for All Classification Tasks

</details>

### GNN 数据标注


<details open>
<summary>

##### LLM-centric

</summary>

- `⚡` 📄 GPT4Graph Can Large Language Models Understand Graph Structured Data An Empirical Evaluation and Benchmarking
- `⚡` 📄 Language is All a Graph Needs
- `⚡` 📄 GraphGPT Graph Instruction Tuning for Large Language Models
- `💎` 📄 LLaGA Lage Language and Graph Assistant

</details>

<details open>
<summary>

##### Graph active learning

</summary>

- `⚡` 📄 Active Learning for Graph Embedding
- `⚡` 📄 Grain Improving Data Efficiency of Graph Neural Networks via Diversified Influence Maximization
- `⚡` 📄 ALG Fast and Accurate Active Learning Framework for Graph Convolutional Networks

</details>

<details open>
<summary>

##### Noise-aware

</summary>

- `💎` 📄 RIM Reliable Influence-based Active Learning on Graphs

</details>

### Scalable GNN (GNN Acceleration)


<details open>
<summary>

##### LLM as oracle

</summary>

- `⚡` 📄 Label-free Node Classification on Graphs with Large Language Models (LLMs)

</details>

<details open>
<summary>

##### Training Acceleration

</summary>

- `⚡` 📄 Inductive Representation Learning on Large Graphs
- `⚡` 📄 FASTGCN: FAST LEARNING WITH GRAPH CONVOLU-TIONAL NETWORKS VIA IMPORTANCE SAMPLING
- `⚡` 📄 GraphSAINT: GRAPH SAMPLING BASED INDUCTIVELEARNING METHOD
- `⚡` 📄 Simplifying Graph Convolutional Networks
- `⚡` 📄 Graph Attention Multi-Layer Perceptron
- `💎` 📄 PREDICT THEN PROPAGATE: GRAPH NEURALNETWORKS MEET PERSONALIZED PAGERANK

</details>

<details open>
<summary>

##### Inference Acceleration

</summary>

- `⚡` 📄 Distilling Knowledge from Graph Convolutional Networks
- `💎` 📄 GRAPH-LESS NEURAL NETWORKS: TEACHING OLDMLPS NEW TRICKS VIA DISTILLATION
- `💎` 📄 NOSMOG: Learning Noise-robust and Structure-aware MLPs on Graphs
- `⚡` 📄 DEGREE-QUANT: QUANTIZATION-AWARE TRAINING FOR GRAPH NEURAL NETWORKS
- `💎` 📄 THE LOTTERY TICKET HYPOTHESIS: FINDING SPARSE, TRAINABLE NEURAL NETWORKS

</details>

