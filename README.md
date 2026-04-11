# Privacy in Recommender Systems

<div align="center">

![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)

A comprehensive collection of research papers on privacy threats and protections in recommender systems.

</div>

## 📋 Overview

This repository contains papers organized by **privacy threat types** (first-level) and **privacy protection techniques** (second-level).

## 📚 Paper Collections

## MIAs (成员推理攻击)

### differential privacy

- [Where Have You Been? A Study of Privacy Risk for Point-of-Interest Recommendation](https://arxiv.org/pdf/2310.18606)
- [Defending Against Membership Inference Attack for Counterfactual Federated Recommendation With Differentially Private Representation Learning.](https://www.researchgate.net/publication/383683847_Defending_Against_Membership_Inference_Attack_for_Counterfactual_Federated_Recommendation_with_Differentially_Private_Representation_Learning)

### 对抗学习

- [Social Relation-Level Privacy Risks and Preservation in Social Recommender Systems](https://doi.org/10.1145/3726302.3730086)
- [Physical Trajectory Inference Attack and Defense in Decentralized POI Recommendation](https://arxiv.org/abs/2401.14583)
- [Interaction-level Membership Inference Attack against Recommender Systems with Long-tailed Distribution](https://doi.org/10.1145/3627673.3679804)

### 模糊化方法

- [Membership Inference Attacks Against Recommender Systems [CCS'21]](https://arxiv.org/pdf/2109.08045)
- [Interaction-level membership inference attack against federated recommender systems](https://www.semanticscholar.org/paper/Interaction-level-Membership-Inference-Attack-Yuan-Yang/b48a8c226efb52844c9b97309a654a383f33b823)

## AIAs (属性推理攻击)

### approximate unlearning

- [Aegis: Post-Training Attribute Unlearning in Federated Recommender Systems against Attribute Inference Attacks](https://researchr.org/publication/WuJH25)
- [Post-Training Attribute Unlearning in Recommender Systems](https://arxiv.org/abs/2403.06737)
- [Defending against Attribute Inference Attacks in Post-Training of Recommendation Systems via Unlearning](https://arxiv.org/abs/2504.11510)
- [LEGO: A Lightweight and Efficient Multiple-Attribute Unlearning Framework for Recommender Systems](https://dl.acm.org/doi/abs/10.1145/3746027.3755604)
- [Plug and Play: Enabling Pluggable Attribute Unlearning in Recommender Systems.](https://openreview.net/forum?id=8LuVZOMqF6&referrer=%5Bthe%20profile%20of%20Yuyuan%20Li%5D(%2Fprofile%3Fid%3D~Yuyuan_Li1))
- [Making Users Indistinguishable: Attribute-wise Unlearning in Recommender Systems](https://arxiv.org/abs/2503.23032)

### differential privacy

- [Comprehensive Privacy Analysis on Federated Recommender System against Attribute Inference Attacks](https://doi.org/10.1109/TKDE.2023.3295601)
- [Graph Embedding for Recommendation against Attribute Inference Attacks](https://doi.org/10.1145/3442381.3449813)

### 对抗学习

- [User Consented Federated Recommender System Against Personalized Attribute Inference Attack](https://arxiv.org/abs/2312.16203)
- [Unlearning Protected User Attributes in Recommendations with Adversarial Training](https://doi.org/10.1145/3477495.3531820)
- [Privacy-Aware Recommendation with Private-Attribute Protection using Adversarial Learning](https://doi.org/10.1145/3336191.3371832)

### 模糊化方法

- [Camouflaged Variational Graph AutoEncoder against Attribute Inference Attacks for Cross-Domain Recommendation](https://doi.org/10.1109/TKDE.2025.3565793)

## SMIAs (社交关系推理攻击)

### 对抗学习

- [Social Relation-Level Privacy Risks and Preservation in Social Recommender Systems](https://doi.org/10.1145/3726302.3730086)

## MEAs (模型抽取攻击)

### 模糊化方法

- [Defense Against Model Extraction Attacks on Recommender Systems](https://arxiv.org/pdf/2310.16335)
- [Hide Your Model: A Parameter Transmission-free Federated Recommender System](https://arxiv.org/abs/2311.14968)

## Inversion Attacks (模型反演攻击)

### 对抗学习

- [Comprehensive Privacy Analysis on Recommendation With Causal Embedding Against Model Inversion Attacks](https://arxiv.org/abs/2205.11857)

## User-Plat.

### differential privacy

- [Comprehensive Privacy Analysis on Federated Recommender System against Attribute Inference Attacks](https://doi.org/10.1109/TKDE.2023.3295601)
- [Federated Heterogeneous Graph Neural Network for Privacy-preserving Recommendation](https://openreview.net/pdf/45878acfe2f8079d2cf956c574daebacd9271185.pdf)
- [Decentralized Graph Neural Network for Privacy-Preserving Recommendation](https://doi.org/10.1145/3583780.3614834)
- [Private and Utility Enhanced Recommendations With Local Differential Privacy and Gaussian Mixture Model](https://arxiv.org/abs/2102.13453)
- [PrivateRec: Differentially Private Model Training and Online Serving for Federated News Recommendation](https://doi.org/10.1145/3580305.3599889)
- [EANA: Reducing Privacy Risk on Large-scale Recommendation Models](https://dl.acm.org/doi/10.1145/3523227.3546769)
- [Fast-adapting and privacy-preserving federated recommender system [vldbj]](https://repository.kaust.edu.sa/bitstreams/ebbb3af8-57a3-441a-ba24-03eb87584ab5/download)
- [Heterogeneous Graph Neural Network for Privacy-Preserving Recommendation](https://openreview.net/forum?id=bJxS9a0TdB)
- [Novel Collaborative Filtering Recommender Friendly to Privacy Protection](https://doi.org/10.24963/ijcai.2019/668)
- [Privacy Enhanced Matrix Factorization for Recommendation with Local Differential Privacy](https://doi.org/10.1109/TKDE.2018.2805356)
- [Differential-Trust-Mechanism-Based Trade-Off Method Between Privacy and Accuracy in Recommender Systems](https://doi.org/10.1109/TIFS.2025.3566509)

### exact unlearning

- [On the Effectiveness of Unlearning in Session-Based Recommendation](https://doi.org/10.1145/3616855.3635823)
- [Federated Unlearning for On-Device Recommendation](https://doi.org/10.1145/3539597.3570463)
- [Recommendation Unlearning](https://jhliu0807.github.io/paper/IMCorrect.pdf)

### 加密化技术

- [Privacy-Preserving Orthogonal Aggregation for Guaranteeing Gender Fairness in Federated Recommendation](https://doi.org/10.1145/3701551.3703513)
- [Lightweight Privacy-Preserving Distributed Recommender System Using Tag-Based Multikey Fully Homomorphic Data Encapsulation.](https://www.researchgate.net/publication/368411528_Lightweight_Privacy-preserving_Distributed_Recommender_System_using_Tag-based_Multikey_Fully_Homomorphic_Data_Encapsulation)
- [Secure federated matrix factorization. [IEEE IS 20]](https://ieeexplore.ieee.org/abstract/document/9162459)
- [Efficient privacy-preserving recommendations based on social graphs](https://doi.org/10.1145/3298689.3347013)

### 模糊化方法

- [Privacy-Preserving Sequential Recommendation with Collaborative Confusion.](https://arxiv.org/abs/2401.04423)
- [Hide Your Model: A Parameter Transmission-free Federated Recommender System](https://arxiv.org/abs/2311.14968)
- [Discrete Federated Multi-behavior Recommendation for Privacy-Preserving Heterogeneous One-Class Collaborative Filtering](https://doi.org/10.1145/3652853)
- [A Generic Federated Recommendation Framework via Fake Marks and Secret Sharing](https://doi.org/10.1145/3548456)
- [Privacy-Preserving Synthetic Data Generation for Recommendation Systems](https://doi.org/10.1145/3477495.3532044)
- [FR-FMSS: Federated Recommendation via Fake Marks and Secret Sharing](https://dl.acm.org/doi/10.1145/3460231.3478855)
- [Privacy-Preserving Social Media Data Publishing for Personalized Ranking-Based Recommendation](https://doi.org/10.1109/TKDE.2018.2840974)

### 系统设计

- [FedCIA: Federated Collaborative Information Aggregation for Privacy-Preserving Recommendation](https://arxiv.org/abs/2504.14208)
- [Comprehensive Privacy Analysis on Federated Recommender System against Attribute Inference Attacks](https://doi.org/10.1109/TKDE.2023.3295601)
- [Towards Personalized Privacy: User-Governed Data Contribution for Federated Recommendation](https://arxiv.org/html/2508.06208v1)
- [Discrete Federated Multi-behavior Recommendation for Privacy-Preserving Heterogeneous One-Class Collaborative Filtering](https://doi.org/10.1145/3652853)
- [Federated Unlearning for On-Device Recommendation](https://doi.org/10.1145/3539597.3570463)
- [Decentralized Graph Neural Network for Privacy-Preserving Recommendation](https://doi.org/10.1145/3583780.3614834)
- [PrivateRec: Differentially Private Model Training and Online Serving for Federated News Recommendation](https://doi.org/10.1145/3580305.3599889)
- [Semi-decentralized Federated Ego Graph Learning for Recommendation](https://doi.org/10.1145/3543507.3583337)
- [Decentralized collaborative learning framework for next POI recommendation](https://www.semanticscholar.org/paper/Decentralized-Collaborative-Learning-Framework-for-Long-Chen/86427c903b0c41adc186134b7787136df318a147)
- [A Generic Federated Recommendation Framework via Fake Marks and Secret Sharing](https://doi.org/10.1145/3548456)
- [Fast-adapting and privacy-preserving federated recommender system [vldbj]](https://repository.kaust.edu.sa/bitstreams/ebbb3af8-57a3-441a-ba24-03eb87584ab5/download)
- [DeepRec: On-device Deep Learning for Privacy-Preserving Sequential Recommendation in Mobile Commerce](https://doi.org/10.1145/3442381.3449942)
- [FedRec++: Lossless Federated Recommendation with Explicit Feedback](https://doi.org/10.1609/aaai.v35i5.16546)
- [FR-FMSS: Federated Recommendation via Fake Marks and Secret Sharing](https://dl.acm.org/doi/10.1145/3460231.3478855)
- [FedGNN: Federated Graph Neural Network for Privacy-Preserving Recommendation [NC 21]](https://arxiv.org/abs/2102.04925)
- [Secure federated matrix factorization. [IEEE IS 20]](https://ieeexplore.ieee.org/abstract/document/9162459)
- [FedRec: Federated Recommendation With Explicit Feedback [IEEE IS 20]](https://www.computer.org/csdl/magazine/ex/2021/05/09170754/1motmh7q3io)
- [A Privacy-Preserving Distributed Contextual Federated Online Learning Framework with Big Data Support in Social Recommender Systems](https://doi.org/10.1109/TKDE.2019.2936565)
- [PrivateJobMatch: a privacy-oriented deferred multi-match recommender system for stable employment](https://doi.org/10.1145/3298689.3346983)
- [Privacy Preserving Point-of-Interest Recommendation Using Decentralized Matrix Factorization](https://arxiv.org/abs/2003.05610)
- [[short] Enhanced Privacy Preservation for Recommender Systems](https://www.researchgate.net/publication/373944108_Enhanced_Privacy_Preservation_for_Recommender_Systems)

## Plat.-Plat.

### differential privacy

- [P4GCN: Vertical Federated Social Recommendation with Privacy-Preserving Two-Party Graph Convolution Network](https://www.themoonlight.io/en/review/p4gcn-vertical-federated-social-recommendation-with-privacy-preserving-two-party-graph-convolution-network)
- [Reducing Item Discrepancy via Differentially Private Robust Embedding Alignment for Privacy-Preserving Cross Domain Recommendation](https://openreview.net/forum?id=rk4kmL8aOY)
- [Privacy-preserving Cross-domain Recommendation with Federated Graph Learning](https://doi.org/10.1145/3653448)
- [Enhancing Dual-Target Cross-Domain Recommendation with Federated Privacy-Preserving Learning](https://www.ijcai.org/proceedings/2024/238)
- [Win-Win: A Privacy-Preserving Federated Framework for Dual-Target Cross-Domain Recommendation](http://urban-computing.com/pdf/AAAI23_WinWin.pdf)
- [Differential Private Knowledge Transfer for Privacy-Preserving Cross-Domain Recommendation](https://openreview.net/attachment?id=i16IGbfnSL&name=pdf)

### 加密化技术

- [P4GCN: Vertical Federated Social Recommendation with Privacy-Preserving Two-Party Graph Convolution Network](https://www.themoonlight.io/en/review/p4gcn-vertical-federated-social-recommendation-with-privacy-preserving-two-party-graph-convolution-network)
- [Privacy-Preserving Social Recommendation: Privacy Leakage and Countermeasure](https://doi.org/10.1145/3705328.3748051)
- [Privacy Matters: Vertical Federated Linear Contextual Bandits for Privacy Protected Recommendation](https://doi.org/10.1145/3580305.3599475)
- [Secure Social Recommendation based on Secret Sharing](https://doi.org/10.3233/FAIA200132)

### 模糊化方法

- [Privacy-Friendly Cross-Domain Recommendation via Distilling User-irrelevant Information](https://openreview.net/pdf?id=yuzbzzekdB)
- [Enhancing Healthcare Recommendations: A Privacy-Protective and Interpretable Cross-Domain Framework](https://openreview.net/pdf?id=iT1UfkmDio)
- [PPGenCDR: A Stable and Robust Framework for Privacy-Preserving Cross-Domain Recommendation](https://openreview.net/pdf?id=yuzbzzekdB)
- [Vertical Federated Graph Neural Network for Recommender System](https://proceedings.mlr.press/v202/mai23b.html)
- [Performance Analysis of a Privacy Constrained kNN Recommendation Using Data Sketches](https://doi.org/10.1145/3159652.3159673)

### 系统设计

- [P4GCN: Vertical Federated Social Recommendation with Privacy-Preserving Two-Party Graph Convolution Network](https://www.themoonlight.io/en/review/p4gcn-vertical-federated-social-recommendation-with-privacy-preserving-two-party-graph-convolution-network)
- [Federated Semantic Learning for Privacy-preserving Cross-domain Recommendation.](https://www.researchgate.net/publication/393531092_Federated_Semantic_Learning_for_Privacy-preserving_Cross-domain_Recommendation)
- [Privacy-preserving Cross-domain Recommendation with Federated Graph Learning](https://doi.org/10.1145/3653448)
- [Enhancing Dual-Target Cross-Domain Recommendation with Federated Privacy-Preserving Learning](https://www.ijcai.org/proceedings/2024/238)
- [Federated Probabilistic Preference Distribution Modelling with Compactness Co-Clustering for Privacy-Preserving Multi-Domain Recommendation](https://doi.org/10.24963/ijcai.2023/245)
- [Win-Win: A Privacy-Preserving Federated Framework for Dual-Target Cross-Domain Recommendation](http://urban-computing.com/pdf/AAAI23_WinWin.pdf)
- [Privacy Matters: Vertical Federated Linear Contextual Bandits for Privacy Protected Recommendation](https://doi.org/10.1145/3580305.3599475)
- [Vertical Federated Graph Neural Network for Recommender System](https://proceedings.mlr.press/v202/mai23b.html)
- [FedCDR: Federated Cross-Domain Recommendation for Privacy-Preserving Rating Prediction](https://doi.org/10.1145/3511808.3557320)
- [Cross-domain Recommendation Without Sharing User-relevant Data](https://doi.org/10.1145/3308558.3313538)

---

*Last updated: 2026-04-10*

*Generated from paper-taxonomy.json*
