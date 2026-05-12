---
title: "Expert as Prompt: Emotion-Prototype-Routed Mixture of Experts for Multimodal Sentiment Analysis"
collection: publications
category: journals
permalink: /publication/2025-09-01-expert-as-prompt
excerpt: 'First-author research paper proposing a novel prototype-routed MoE architecture for sample-adaptive multimodal fusion in sentiment analysis. Under review at Information Fusion (SCI Q1, IF=15.5).'
---

## 📄 研究概述 | Research Overview

本论文提出了一种基于情感原型指导的MoE（Mixture of Experts）网络架构，用于实现样本自适应的多模态融合。通过学习一组可学习的情感原型，动态路由多模态特征至不同的专家进行处理，并通过对比损失和负载均衡损失优化模型，显著增强了模型对复杂情感模式的理解与鲁棒性。

This paper proposes a novel emotion-prototype-guided Mixture of Experts (MoE) network for sample-adaptive multimodal fusion. By introducing learnable emotion prototypes for dynamic expert routing and incorporating contrastive and load-balancing losses, the method achieves substantial improvements in model robustness and interpretability for complex sentiment patterns.

## 🔬 核心贡献 | Key Contributions

![方法框架图]({{ site.baseurl }}/images/EaP.png)
*Expert as Prompt 方法架构 | Expert as Prompt Method Framework*

1. **Novel Architecture**: 设计了情感原型驱动的MoE架构，实现动态专家路由
2. **Comprehensive Evaluation**: 包括消融研究、参数分析等系统性实验
3. **Enhanced Robustness**: 在多个基准数据集上取得显著的效果提升
4. **Interpretability**: 通过原型可视化增强了模型的可解释性

## 📊 实验结果 | Experimental Results

- Improved accuracy on multiple benchmark datasets (CMU-MOSI, CMU-MOSEI, etc.)
- Superior robustness against distribution shifts
- Effective ablation studies demonstrating each component's contribution
- Visualization of learned emotion prototypes showing semantic coherence

## 🎓 研究意义 | Research Significance

This work advances multimodal sentiment analysis by combining the principles of prototype learning and mixture-of-experts approaches, offering new insights into how multiple modalities can be effectively fused for emotion understanding. The proposed method has potential applications in affective computing, human-computer interaction, and psychological assessment.

---

**Status**: 论文投稿中 | Paper Under Review  
**Journal**: Information Fusion (SCI Q1, IF=15.5)  
**Author**: Kexin Wang (First Author)  
