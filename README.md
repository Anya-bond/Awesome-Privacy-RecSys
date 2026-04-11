# Awesome Privacy-Preserving Recommender Systems
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

> 隐私保护推荐系统资源汇总 | A curated collection of awesome resources for privacy-preserving recommender systems.

## Table of Contents

- [Papers](#papers)
- [Frameworks \& Libraries](#frameworks--libraries)
- [Datasets](#datasets)
- [Surveys \& Books](#surveys--books)
- [Tools \& Platforms](#tools--platforms)
- [Awesome Lists](#awesome-lists)

---

## Papers

### Differential Privacy in Recommender Systems
- **Deep Learning with Differential Privacy** (2016) - Abadi et al. [[Paper]](https://arxiv.org/abs/1607.00133)
- **Privacy-Preserving Recommender Systems with Neural Network** (2020) - Jiang et al. [[Paper]](https://arxiv.org/abs/2006.14755)
- **Locally Differentially Private Recommender Systems** (2019) - Shin et al. [[Paper]](https://ieeexplore.ieee.org/document/8803581)

### Federated Learning for Recommender Systems
- **FedRec: Federated Recommendation** (2019) - Ammad et al. [[Paper]](https://arxiv.org/abs/1905.10469)
- **FedML: A Benchmark for Federated Learning** (2020) - Chaoyang He et al. [[Paper]](https://arxiv.org/abs/2007.13518)
- **Personalized Federated Recommendation** (2021) - Chen et al. [[Paper]](https://arxiv.org/abs/2106.15342)

### Secure Multi-Party Computation
- **Secure Recommender Systems** (2018) - Badsha et al. [[Paper]](https://dl.acm.org/10.1145/3243734)
- **Privacy-Preserving POI Recommendation** (2020) - Li et al. [[Paper]](https://ieeexplore.ieee.org/document/9127958)

### On-Device Learning
- **RecSys'droid** (2021) - Liu et al. [[Paper]](https://dl.acm.org/10.1145/3460231)
- **EdgeRec: Recommender System on Edge Devices** (2020) - Chen et al. [[Paper]](https://arxiv.org/abs/2002.02890)

---

## Frameworks & Libraries

| Framework | Language | Description |
|-----------|----------|-------------|
| [PySyft](https://github.com/OpenMined/PySyft) | Python | Privacy-preserving machine learning |
| [TensorFlow Privacy](https://github.com/tensorflow/privacy) | Python | DP ML with TensorFlow |
| [Opacus](https://github.com/pytorch/opacus) | Python | Differential privacy for PyTorch |
| [FedML](https://github.com/FedML-AI/FedML) | Python | Federated learning & ML infrastructure |
| [Flower](https://github.com/adap/flower) | Python | Federated learning framework |
| [PyVertical](https://github.com/dssg/pyvertical) | Python | Vertical federated learning |

---

## Datasets

| Dataset | Domain | Size | Privacy Type |
|---------|--------|------|--------------|
| [MovieLens-DP](https://grouplens.org/datasets/movielens/) | Movies | 27M ratings | Synthetic DP |
| [Netflix Prize (modified)](https://www.kaggle.com/datasets/netflix-inc/netflix-prize-data) | Movies | 100M ratings | Anonymized |
| [Last.fm-DP](https://www.last.fm/) | Music | 360K users | LDP noise |
| [Amazon Review Data](https://jmcauley.ucsd.edu/data/amazon/) | E-commerce | 233M reviews | Anonymized |

---

## Surveys & Books

- **Privacy-Preserving Recommender Systems: A Survey** (2022) - Zhang et al. [[Paper]](https://arxiv.org/abs/2205.07617)
- **Federated Recommendation Systems** (2021) - Kim et al. [[Paper]](https://ieeexplore.ieee.org/document/9555206)
- **Differential Privacy: From Theory to Practice** (2022) - Apple [[Book]](https://www.apple.com.cn)
- **Private Recommender Systems: How to Build Privacy-Preserving Recommendation Engines** (2021) - Vinterbo et al. [[Paper]](https://arxiv.org/abs/2105.01239)

---

## Tools & Platforms

- **Google DP Library**: Implements differential privacy mechanisms [[Link]](https://github.com/google/differential-privacy)
- **OpenMined**: Privacy-preserving AI ecosystem [[Link]](https://www.openmined.org)
- **SecretFlow**: Secure computation platform [[Link]](https://github.com/secretflow/secretflow)
- **PyPI Privacy**: Privacy-preserving package recommendations [[Link]](https://pypi.org)

---

## Awesome Lists

- [Awesome Differential Privacy](https://github.com/ryan112358/awesome-differential-privacy)
- [Awesome Federated Learning](https://github.com/woacross/awesome-federated-learning)
- [Awesome Privacy](https://github.com/pluja/awesome-privacy)
- [Awesome Privacy on Mobile](https://github.com/AsmithSoftware/awesome-mobile-privacy)

---

## Contributing

Contributions welcome! Please read [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
