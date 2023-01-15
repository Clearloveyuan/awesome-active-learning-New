# Awesome Active Learning [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<p align="center">
      <a href="https://img.shields.io/badge/version-v0.1.0-blue">
      <img alt="version" src="https://img.shields.io/badge/version-v0.1.0-blue?color=FF8000?color=009922" />
    </a>
  <a >
       <img alt="Status-building" src="https://img.shields.io/badge/Status-building-blue" />
      </a>
  <a >
       <img alt="PRs-Welcome" src="https://img.shields.io/badge/PRs-Welcome-red" />
      </a>
       <a href="https://github.com/Clearloveyuan/Awesome-Active-Learning/stargazers">
       <img alt="stars" src="https://img.shields.io/github/stars/Clearloveyuan/Awesome-Active-Learning" />
      </a>
      <a href="https://github.com/Clearloveyuan/Awesome-Active-Learning/network/members">
       <img alt="FORK" src="https://img.shields.io/github/forks/Clearloveyuan/Awesome-Active-Learning?color=FF8000" />
      </a>
    <a href="https://github.com/Clearloveyuan/Awesome-Active-Learning/issues">
      <img alt="Issues" src="https://img.shields.io/github/issues/Clearloveyuan/Awesome-Active-Learning?color=0088ff"/>
    </a>
    <br />
</p>

___TODO: Modify Introduction___

🤩 A curated list of awesome Active Learning ! 🤩

<font size=5><b> Background </b></font>


(`An illustrative example of pool-based active learning`. image source: [Settles, Burr](https://minds.wisconsin.edu/handle/1793/60660))

<font size=5><b> What is Active Learning? </b></font>

Active learning is a special case of machine learning in which a learning algorithm can interactively query a oracle (or some other information source) to label new data points with the desired outputs.

(`The pool-based active learning cycle`. image source: [Settles, Burr](https://minds.wisconsin.edu/handle/1793/60660))

There are situations in which unlabeled data is abundant but manual labeling is expensive. In such a scenario, learning algorithms can actively query the oracle for labels. This type of iterative supervised learning is called active learning. Since the learner chooses the examples, the number of examples to learn a concept can often be much lower than the number required in normal supervised learning. With this approach, there is a risk that the algorithm is overwhelmed by uninformative examples. Recent developments are dedicated to multi-label active learning, hybrid active learning and active learning in a single-pass (on-line) context, combining concepts from the field of machine learning (e.g. conflict and ignorance) with adaptive, incremental learning policies in the field of online machine learning.

(source: [Wikipedia](https://en.wikipedia.org/wiki/Active_learning_(machine_learning)))

<font size=5><b> Contributing </b></font>

If you find the awesome paper/code/book/tutorial or have some suggestions, please feel free to [pull requests](https://github.com/baifanxxx/awesome-active-learning/pulls) or contact <baifanxxx@gmail.com> or <chenliangyudavid@gmail.com> to add papers using the following Markdown format:

```txt
| Year | [Title](link) | Author | Publication | [Code](link) | Tags | Notes |
```

<font size=4><b> Tags </b></font>

___TODO: Use Our Tags___

`Sur.`: survey |  `Cri.`: critics |
`Pool.`: pool-based sampling |  `Str.`: stream-based sampling |  `Syn.`: membership query synthesize |
`Semi.`: semi-supervised learning |  `Self.`: self-supervised learning |  `RL.`: reinforcement learning |
`FS.`: few-shot learning |  `Meta.`: meta learning |

Thanks for your valuable contribution to the research community. 😃

---

# Conferences

| Conference |           2019 and before            |                 2020                 |                 2021                 |                 2022                 | 2023 | 2024 | 2025 |
|:----------:|:------------------------------------:|:------------------------------------:|:------------------------------------:|:------------------------------------:|:----:|:----:|:----:|
|    ACL     |   [2019](Paper_Summary/ACL2019.md)   |   [2020](Paper_Summary/ACL2020.md)   |   [2021](Paper_Summary/ACL2021.md)   |   [2022](Paper_Summary/ACL2022.md)   | 2023 | 2024 | 2025 |
|    CVPR    |  [2019](Paper_Summary/CVPR2019.md)   |  [2020](Paper_Summary/CVPR2020.md)   |  [2021](Paper_Summary/CVPR2021.md)   |  [2022](Paper_Summary/CVPR2022.md)   | 2023 | 2024 | 2025 |
|    NIPS    |  [2019](Paper_Summary/NIPS2019.md)   |  [2020](Paper_Summary/NIPS2020.md)   |  [2021](Paper_Summary/NIPS2021.md)   |  [2022](Paper_Summary/NIPS2022.md)   | 2023 | 2024 | 2025 |
|    ICML    |  [2019](Paper_Summary/ICML2019.md)   |  [2020](Paper_Summary/ICML2020.md)   |  [2021](Paper_Summary/ICML2021.md)   |  [2022](Paper_Summary/ICML2022.md)   | 2023 | 2024 | 2025 |
|   EMNLP    |  [2019](Paper_Summary/EMNLP2019.md)  |  [2020](Paper_Summary/EMNLP2020.md)  |  [2021](Paper_Summary/EMNLP2021.md)  |                 2022                 | 2023 | 2024 | 2025 |
|    ECCV    |  [2019](Paper_Summary/ECCV2019.md)   |  [2020](Paper_Summary/ECCV2020.md)   |                 2021                 |  [2022](Paper_Summary/ECCV2022.md)   | 2023 | 2024 | 2025 |
|    ICCV    |  [2019](Paper_Summary/ICCV2019.md)   |                 2020                 |  [2021](Paper_Summary/ICCV2021.md)   |                 2022                 | 2023 | 2024 | 2025 |
|    AAAI    |  [2019](Paper_Summary/AAAI2019.md)   |  [2020](Paper_Summary/AAAI2020.md)   |  [2021](Paper_Summary/AAAI2021.md)   |  [2022](Paper_Summary/AAAI2022.md)   | 2023 | 2024 | 2025 |
|   IJCAI    |  [2019](Paper_Summary/IJCAI2019.md)  |  [2020](Paper_Summary/IJCAI2020.md)  |  [2021](Paper_Summary/IJCAI2021.md)  |                 2022                 | 2023 | 2024 | 2025 |
|    ICLR    |  [2019](Paper_Summary/ICLR2019.md)   |  [2020](Paper_Summary/ICLR2020.md)   |  [2021](Paper_Summary/ICLR2021.md)   |  [2022](Paper_Summary/ICLR2022.md)   | 2023 | 2024 | 2025 |
|    KDD     |   [2019](Paper_Summary/KDD2019.md)   |                 2020                 |                 2021                 |   [2022](Paper_Summary/KDD2022.md)   | 2023 | 2024 | 2025 |
|    ACMM    |  [2019](Paper_Summary/ACMM2019.md)   |  [2020](Paper_Summary/ACMM2020.md)   |                 2021                 |  [2022](Paper_Summary/ACMM2022.md)   | 2023 | 2024 | 2025 |
|   ICASSP   | [2019](Paper_Summary/ICASSP2019.md)  | [2020](Paper_Summary/ICASSP2020.md)  | [2021](Paper_Summary/ICASSP2021.md)  |                 2022                 | 2023 | 2024 | 2025 |
|  AISTATS   | [2019](Paper_Summary/AISTATS2019.md) | [2020](Paper_Summary/AISTATS2020.md) | [2021](Paper_Summary/AISTATS2021.md) | [2022](Paper_Summary/AISTATS2022.md) | 2023 | 2024 | 2025 |
|   SIGIR    |  [2019](Paper_Summary/SIGIR2019.md)  |  [2020](Paper_Summary/SIGIR2020.md)  |                 2021                 |                 2022                 | 2023 | 2024 | 2025 |
|    ICDM    |  [2019](Paper_Summary/ICDM2019.md)   |  [2020](Paper_Summary/ICDM2020.md)   |  [2021](Paper_Summary/ICDM2021.md)   |                 2022                 | 2023 | 2024 | 2025 |
|   COLING   | [2019](Paper_Summary/COLING2019.md)  | [2020](Paper_Summary/COLING2020.md)  |                 2021                 |                 2022                 | 2023 | 2024 | 2025 |
|    COLT    |  [2019](Paper_Summary/COLT2019.md)   |  [2020](Paper_Summary/COLT2020.md)   |  [2021](Paper_Summary/COLT2021.md)   |                 2022                 | 2023 | 2024 | 2025 |
|   NAACL    |  [2019](Paper_Summary/NAACL2019.md)  |                 2020                 |  [2021](Paper_Summary/NAACL2021.md)  |  [2022](Paper_Summary/NAACL2022.md)  | 2023 | 2024 | 2025 |
|    WACV    |                 2019                 |                 2020                 |  [2021](Paper_Summary/WACV2021.md)   |                 2022                 | 2023 | 2024 | 2025 |
|   NLPCC    |                 2019                 |  [2020](Paper_Summary/NLPCC2020.md)  |                 2021                 |                 2022                 | 2023 | 2024 | 2025 |
|   SIGMOD   | [2019](Paper_Summary/SIGMOD2019.md)  | [2020](Paper_Summary/SIGMOD2020.md)  |                 2021                 |                 2022                 | 2023 | 2024 | 2025 |
|    ICDE    |                 2019                 |  [2020](Paper_Summary/ICDE2020.md)   |  [2021](Paper_Summary/ICDE2021.md)   |                 2022                 | 2023 | 2024 | 2025 |
|    CIKM    |                 2019                 |  [2020](Paper_Summary/CIKM2020.md)   |  [2021](Paper_Summary/CIKM2021.md)   |  [2022](Paper_Summary/CIKM2022.md)   | 2023 | 2024 | 2025 |


# Journals

|        Journal         |          2019 and before           |                2020                |                2021                |                2022                | 2023 | 2024 | 2025 |
|:----------------------:|:----------------------------------:|:----------------------------------:|:----------------------------------:|:----------------------------------:|:----:|:----:|:----:|
|          AIJ           |  [2019](Paper_Summary/AIJ2019.md)  |                2020                |                2021                |                2022                | 2023 | 2024 | 2025 |
|         TPAMI          | [2019](Paper_Summary/TPAMI2019.md) | [2020](Paper_Summary/TPAMI2020.md) | [2021](Paper_Summary/TPAMI2021.md) | [2022](Paper_Summary/TPAMI2022.md) | 2023 | 2024 | 2025 |
|          JMLR          | [2019](Paper_Summary/JMLR2019.md)  |                2020                | [2021](Paper_Summary/JMLR2021.md)  | [2022](Paper_Summary/JMLR2022.md)  | 2023 | 2024 | 2025 |
|          CVIU          | [2019](Paper_Summary/CVIU2019.md)  |                2020                |                2021                |                2022                | 2023 | 2024 | 2025 |
|          DKE           |  [2019](Paper_Summary/DKE2019.md)  |                2020                |                2021                |                2022                | 2023 | 2024 | 2025 |
|         TASLP          | [2019](Paper_Summary/TASLP2019.md) | [2020](Paper_Summary/TASLP2020.md) | [2021](Paper_Summary/TASLP2021.md) |                2022                | 2023 | 2024 | 2025 |
|  Pattern Recognition   |  [2019](Paper_Summary/PR2019.md)   |                2020                |  [2021](Paper_Summary/PR2021.md)   |  [2022](Paper_Summary/PR2022.md)   | 2023 | 2024 | 2025 |
|    Neural Networks     |  [2019](Paper_Summary/NN2019.md)   |                2020                |  [2021](Paper_Summary/NN2021.md)   |  [2022](Paper_Summary/NN2022.md)   | 2023 | 2024 | 2025 |
|   Neural Computation   |                2019                |  [2020](Paper_Summary/NC2020.md)   |                2021                |                2022                | 2023 | 2024 | 2025 |
|    Machine Learning    |  [2019](Paper_Summary/ML2019.md)   |  [2020](Paper_Summary/ML2020.md)   |  [2021](Paper_Summary/ML2021.md)   |  [2022](Paper_Summary/ML2022.md)   | 2023 | 2024 | 2025 |
|       IEEE TNNLS       | [2019](Paper_Summary/TNNLS2019.md) |                2020                | [2021](Paper_Summary/TNNLS2021.md) | [2022](Paper_Summary/TNNLS2022.md) | 2023 | 2024 | 2025 |
| IEEE Trans. Fuzzy Sys. |  [2019](Paper_Summary/TFS2019.md)  |  [2020](Paper_Summary/TFS2020.md)  |                2021                |  [2022](Paper_Summary/TFS2022.md)  | 2023 | 2024 | 2025 |
|        IEEE CYB        |  [2019](Paper_Summary/CYB2019.md)  |  [2020](Paper_Summary/CYB2020.md)  |                2021                |  [2022](Paper_Summary/CYB2022.md)  | 2023 | 2024 | 2025 |
|   IEEE Trans. Affect   |                2019                |                2020                |                2021                |  [2022](Paper_Summary/TAC2022.md)  | 2023 | 2024 | 2025 |
|        IEEE TIP        |  [2019](Paper_Summary/TIP2019.md)  |  [2020](Paper_Summary/TIP2020.md)  |  [2021](Paper_Summary/TIP2021.md)  |  [2022](Paper_Summary/TIP2022.md)  | 2023 | 2024 | 2025 |


# Preprint

[arXiv](Paper_Summary/arXiv.md)

# Disclaimer

___TODO___

Some results come from [DBLP](https://dblp.org/), [ACL](https://aclanthology.org/), [NIPS](https://papers.nips.cc/), [OpenReview](https://openreview.net/),  [paperwithcode](https://paperswithcode.com/), if this violates your copyright, you can contact us at any time, we will delete it as soon as possible, thank you :-)

# Contributers

___TODO___

# Acknowledgement

___TODO___
