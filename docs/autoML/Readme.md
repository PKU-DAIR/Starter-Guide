<p align="center">
    <h1 align="center">⏱️ AutoML方向</h1>
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

### AutoML 与超参数优化


<details open>
<summary>

##### AutoML综述

</summary>

- `⚡` 📄 AutoML: A Survey of the State-of-the-Art

</details>

<details open>
<summary>

##### 贝叶斯优化基础

</summary>

> 先通过阅读专栏了解贝叶斯优化和高斯过程的基本原理，然后阅读两篇论文了解SMBO的经典方法

- `⚡` 📄 (BO & GP) https://zhuanlan.zhihu.com/p/139605200
- `⚡` 📄 (SMAC) Sequential Model-Based Optimization for General Algorithm Configuration (extended version)
- `⚡` 📄 (TPE) Algorithms for Hyper-Parameter Optimization

</details>

<details open>
<summary>

##### 黑盒优化系统

</summary>

> 通过openbox自己搭建SMBO的基本流程
阅读openbox源代码，了解其内部实现

- `⚡` 🛠️ openbox:  https://github.com/PKU-DAIR/open-box

</details>

<details open>
<summary>

##### 多精度优化

</summary>

- `⚡` 📄 Hyperband: A Novel Bandit-Based Approach to Hyperparameter Optimization
- `⚡` 📄 BOHB: Robust and Efficient Hyperparameter Optimization at Scale

</details>

<details open>
<summary>

##### 多精度优化

</summary>

- `💎` 📄 DEHB: Evolutionary Hyperband for Scalable, Robust and Efficient Hyperparameter Optimization
- `💎` 📄 Efficient Automatic CASH via Rising Bandits
- `💎` 📄 (DyHPO) Supervising the Multi-Fidelity Race of Hyperparameter Configurations

</details>

<details open>
<summary>

##### AutoML系统

</summary>

- `⚡` 📄 Auto-WEKA: combined selection and hyperparameter optimization of classification algorithms
- `⚡` 📄 (auto-sklearn) Efficient and Robust Automated Machine Learning

</details>

<details open>
<summary>

##### AutoML系统

</summary>

> 通过开源autoML系统自行搭建自动化机器学习的完整流程，并了解其内部实现

- `⚡` 🛠️ auto-sklearn:  https://github.com/automl/auto-sklearn
- `⚡` 🛠️ MindWare:  https://github.com/thomas-young-2013/mindware

</details>

<details open>
<summary>

##### 迁移学习综述

</summary>

- `⚡` 📄 Transfer Learning for Bayesian Optimization: A Survey

</details>

<details open>
<summary>

##### 迁移学习

</summary>

- `⚡` 📄 (RGPE) Scalable Meta-Learning for Bayesian Optimization using Ranking-Weighted Gaussian Process Ensembles
- `⚡` 📄 (TAF) Scalable Gaussian process-based transfer surrogates for hyperparameter optimization

</details>

### 网络结构搜索(NAS)


<details open>
<summary>

##### 迁移学习

</summary>

- `💎` 📄 Learning Hyperparameter Optimization Initializations
- `💎` 📄 Hyperparameter Search Space Pruning – A NewComponent for Sequential Model-Based Hyperparameter Optimization
- `💎` 📄 (POGOE) Scalable Hyperparameter Optimization with Products of Gaussian Process Experts
- `💎` 📄 (TST) Two-Stage Transfer Surrogate Model for Automatic Hyperparameter Optimization
- `💎` 📄 (TransBO) TransBO: Hyperparameter Optimization via Two-Phase Transfer Learning

</details>

<details open>
<summary>

##### NAS综述

</summary>

- `⚡` 📄 Neural Architecture Search: A Survey

</details>

<details open>
<summary>

##### NAS基础

</summary>

- `⚡` 📄 Neural Architecture Search with Reinforcement Learning
- `⚡` 📄 Learning Transferable Architectures for Scalable Image Recognition

</details>

<details open>
<summary>

##### One-Shot NAS

</summary>

- `⚡` 📄 DARTS: Differentiable Architecture Search

</details>

<details open>
<summary>

##### One-Shot NAS

</summary>

- `💎` 📄 (DARTS-PT) Rethinking Architecture Selection in Differentiable NAS
- `💎` 📄 β-DARTS: Beta-Decay Regularization for Differentiable Architecture Search

</details>

### 模型压缩


<details open>
<summary>

##### Zero-Shot Proxy

</summary>

- `⚡` 📄 Accelerating Neural Architecture Search via Proxy Data
- `⚡` 📄 Zero-Cost Proxies MeetDifferentiable Architecture Search

</details>

<details open>
<summary>

##### 模型压缩综述

</summary>

> 对模型压缩感兴趣的同学可以在这一部分基础上自己查询相关论文阅读

- `💎` 📄 Model Compression for Deep Neural Networks: A Survey

</details>

<details open>
<summary>

##### 模型剪枝基础

</summary>

- `💎` 📄 Pruning Filters for Efficient ConvNets
- `💎` 📄 Learning both weights and connections for efficient neural network

</details>

<details open>
<summary>

##### 知识蒸馏基础

</summary>

- `💎` 📄 Distilling the Knowledge in a Neural Network
- `💎` 📄 Contrastive Representation Distillation

</details>

