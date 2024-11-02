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

- `⚡` 📄 [AutoML: A Survey of the State-of-the-Art](https://www.sciencedirect.com/science/article/abs/pii/S0950705120307516)

</details>

<details open>
<summary>

##### 贝叶斯优化基础

</summary>

> 先通过阅读专栏了解贝叶斯优化和高斯过程的基本原理，然后阅读两篇论文了解SMBO的经典方法

- `⚡` 📄 [(BO & GP)](https://zhuanlan.zhihu.com/p/139605200)
- `⚡` 📄 (SMAC) [Sequential Model-Based Optimization for General Algorithm Configuration (extended version)](https://ai.dmi.unibas.ch/research/reading_group/hutter-et-al-tr2010.pdf)
- `⚡` 📄 (TPE) [Algorithms for Hyper-Parameter Optimization](https://proceedings.neurips.cc/paper_files/paper/2011/hash/86e8f7ab32cfd12577bc2619bc635690-Abstract.html)

</details>

<details open>
<summary>

##### 黑盒优化系统

</summary>

> 通过openbox自己搭建SMBO的基本流程
阅读openbox源代码，了解其内部实现

- `⚡` 🛠️ [Openbox](https://github.com/PKU-DAIR/open-box)

</details>

<details open>
<summary>

##### 多精度优化

</summary>

- `⚡` 📄 [Hyperband: A Novel Bandit-Based Approach to Hyperparameter Optimization](https://www.jmlr.org/papers/v18/16-558.html)
- `⚡` 📄 [BOHB: Robust and Efficient Hyperparameter Optimization at Scale](https://proceedings.mlr.press/v80/falkner18a.html)

</details>

<details open>
<summary>

##### 多精度优化

</summary>

- `💎` 📄 [DEHB: Evolutionary Hyperband for Scalable, Robust and Efficient Hyperparameter Optimization](https://www.ijcai.org/proceedings/2021/0296.pdf)
- `💎` 📄 [Efficient Automatic CASH via Rising Bandits](https://ojs.aaai.org/index.php/AAAI/article/view/5910)
- `💎` 📄 (DyHPO) [Supervising the Multi-Fidelity Race of Hyperparameter Configurations](https://proceedings.neurips.cc/paper_files/paper/2022/hash/57b694fef23ae7b9308eb4d46342595d-Abstract-Conference.html)

</details>

<details open>
<summary>

##### AutoML系统

</summary>

- `⚡` 📄 [Auto-WEKA: combined selection and hyperparameter optimization of classification algorithms](https://dl.acm.org/doi/abs/10.1145/2487575.2487629)
- `⚡` 📄 (auto-sklearn) [Efficient and Robust Automated Machine Learning](https://proceedings.neurips.cc/paper/2015/hash/11d0e6287202fced83f79975ec59a3a6-Abstract.html)

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

- `⚡` 📄 [Transfer Learning for Bayesian Optimization: A Survey](https://arxiv.org/abs/2302.05927)

</details>

<details open>
<summary>

##### 迁移学习

</summary>

- `⚡` 📄 (RGPE) [Scalable Meta-Learning for Bayesian Optimization using Ranking-Weighted Gaussian Process Ensembles](https://aad.informatik.uni-freiburg.de/wp-content/uploads/papers/18-AUTOML-RGPE.pdf)
- `⚡` 📄 (TAF) [Scalable Gaussian process-based transfer surrogates for hyperparameter optimization](https://link.springer.com/article/10.1007/s10994-017-5684-y)

- `💎` 📄 [Learning Hyperparameter Optimization Initializations](https://ieeexplore.ieee.org/abstract/document/7344817)
- `💎` 📄 [Hyperparameter Search Space Pruning – A NewComponent for Sequential Model-Based Hyperparameter Optimization](https://link.springer.com/chapter/10.1007/978-3-319-23525-7_7)
- `💎` 📄 (POGOE) [Scalable Hyperparameter Optimization with Products of Gaussian Process Experts](https://link.springer.com/chapter/10.1007/978-3-319-46128-1_3)
- `💎` 📄 (TST) [Two-Stage Transfer Surrogate Model for Automatic Hyperparameter Optimization](https://link.springer.com/chapter/10.1007/978-3-319-46128-1_13)
- `💎` 📄 (TransBO) [TransBO: Hyperparameter Optimization via Two-Phase Transfer Learning](https://dl.acm.org/doi/abs/10.1145/3534678.3539255)

</details>

### 网络结构搜索(NAS)

<details open>
<summary>

##### NAS综述

</summary>

- `⚡` 📄 [Neural Architecture Search: A Survey](https://www.jmlr.org/papers/v20/18-598.html)

</details>

<details open>
<summary>

##### NAS基础

</summary>

- `⚡` 📄 [Neural Architecture Search with Reinforcement Learning](https://arxiv.org/abs/1611.01578)
- `⚡` 📄 [Learning Transferable Architectures for Scalable Image Recognition](https://openaccess.thecvf.com/content_cvpr_2018/html/Zoph_Learning_Transferable_Architectures_CVPR_2018_paper.html)

</details>

<details open>
<summary>

##### One-Shot NAS

</summary>

- `⚡` 📄 [DARTS: Differentiable Architecture Search](https://arxiv.org/abs/1806.09055)

</details>

<details open>
<summary>

##### One-Shot NAS

</summary>

- `💎` 📄 (DARTS-PT) [Rethinking Architecture Selection in Differentiable NAS](https://arxiv.org/abs/2108.04392)
- `💎` 📄 [β-DARTS: Beta-Decay Regularization for Differentiable Architecture Search](https://openaccess.thecvf.com/content/CVPR2022/html/Ye_b-DARTS_Beta-Decay_Regularization_for_Differentiable_Architecture_Search_CVPR_2022_paper.html)

</details>

<details open>
<summary>

##### Zero-Shot Proxy

</summary>

- `⚡` 📄 [Accelerating Neural Architecture Search via Proxy Data](https://arxiv.org/abs/2106.04784)
- `⚡` 📄 [Zero-Cost Operation Scoring in Differentiable Architecture Search](https://arxiv.org/abs/2106.06799)
- `⚡` 📄 [ProxyBO: Accelerating Neural Architecture Search via Bayesian Optimization with Zero-Cost Proxies](https://ojs.aaai.org/index.php/AAAI/article/view/26169)

</details>

### 模型压缩

<details open>
<summary>

##### 模型压缩综述

</summary>

> 对模型压缩感兴趣的同学可以在这一部分基础上自己查询相关论文阅读

- `💎` 📄 [Model Compression for Deep Neural Networks: A Survey](https://www.mdpi.com/2073-431X/12/3/60)

</details>

<details open>
<summary>

##### 模型剪枝基础

</summary>

- `💎` 📄 [Pruning Filters for Efficient ConvNets](https://arxiv.org/abs/1608.08710)
- `💎` 📄 [Learning both weights and connections for efficient neural network](https://proceedings.neurips.cc/paper/2015/hash/ae0eb3eed39d2bcef4622b2499a05fe6-Abstract.html)

</details>

<details open>
<summary>

##### 知识蒸馏基础

</summary>

- `💎` 📄 [Distilling the Knowledge in a Neural Network](https://arxiv.org/abs/1503.02531)
- `💎` 📄 [Contrastive Representation Distillation]()https://arxiv.org/abs/1910.10699

</details>

<details open>
<summary>

##### 参数量化基础

</summary>

- `💎` 📄 [ZeroQ: A Novel Zero Shot Quantization Framework](https://openaccess.thecvf.com/content_CVPR_2020/html/Cai_ZeroQ_A_Novel_Zero_Shot_Quantization_Framework_CVPR_2020_paper.html)
- `💎` 📄 [Post-Training Sparsity-Aware Quantization](https://proceedings.neurips.cc/paper/2021/hash/9431c87f273e507e6040fcb07dcb4509-Abstract.html)

</details>

### 大语言模型与AutoML

<details open>
<summary>

##### LLM for AutoML

</summary>

> 使用大模型帮助AutoML的流程执行

- `💎` 📄 [Large Language Models to Enhance Bayesian Optimization](https://arxiv.org/abs/2402.03921)
- `💎` 📄 [Large Language Models for Automated Data Science: Introducing CAAFE for Context-Aware Automated Feature Engineering](https://proceedings.neurips.cc/paper_files/paper/2023/hash/8c2df4c35cdbee764ebb9e9d0acd5197-Abstract-Conference.html)

</details>