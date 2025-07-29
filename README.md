# EmoCapCLIP

<a href="https://arxiv.org/abs/2507.21015"><img src="https://img.shields.io/badge/arXiv-paper-<color>"></a>


>[**Learning Transferable Facial Emotion Representations from Large-Scale Semantically Rich Captions**](https://arxiv.org/abs/2507.21015)<br>
> [Licai Sun∗](https://sunlicai.github.io/), [Xingxun Jiang∗](https://jiangxingxun.github.io/), [Haoyu Chen](https://mikecheninoulu.github.io/), [Yante Li](https://scholar.google.com/citations?user=zYCz89sAAAAJ&hl=en&oi=ao), [Zheng Lian](https://zeroqiaoba.github.io/Homepage/), [Biu Liu](https://scholar.google.com/citations?user=UEB_5QEAAAAJ&hl=en), [Yuan Zong](https://scholar.google.com/citations?user=rv14ap4AAAAJ&hl=en&oi=ao), [Wenming Zheng†](https://scholar.google.com/citations?user=k5fqIogAAAAJ&hl=en), [Jukka M. Leppänen](https://scholar.google.com/citations?user=dNRRUIsAAAAJ&hl=en&oi=ao), [Guoying Zhao†](https://scholar.google.com/citations?user=hzywrFMAAAAJ&hl=en&oi=ao)<br>
University of Oulu, Southeast University, University of Turku, Institute of Automation, Chinese Academy of Sciences

## ✨ Overview


<p align="center">
  <img src="figs/Overview.png" width=80%> <br>
  Conceptual overview of our EmoCapCLIP
</p>


Abstract: Current facial emotion recognition systems are predominately trained to predict a fixed set of predefined categories or abstract dimensional values. This constrained form of supervision hinders generalization and applicability, as it reduces the rich and nuanced spectrum of emotions into oversimplified labels or scales. In contrast, natural language provides a more flexible, expressive, and interpretable way to represent emotions, offering a much broader source of supervision. Yet, leveraging semantically rich natural language captions as supervisory signals for facial emotion representation learning remains relatively underexplored, primarily due to two key challenges: 1) the lack of large-scale caption datasets with rich emotional semantics, and 2) the absence of effective frameworks tailored to harness such rich supervision. To this end, we introduce EmoCap100K, a large-scale facial emotion caption dataset comprising over 100,000 samples, featuring rich and structured semantic descriptions that capture both global affective states and fine-grained local facial behaviors. Building upon this dataset, we further propose EmoCapCLIP, which incorporates a joint global-local contrastive learning framework enhanced by a cross-modal guided positive mining module. This design facilitates the comprehensive exploitation of multi-level caption information while accommodating semantic similarities between closely related expressions. Extensive evaluations on over 20 benchmarks covering five tasks demonstrate the superior performance of our method, highlighting the promise of learning facial emotion representations from large-scale semantically rich captions.


## 🛠️ Train & Evaluate

Stay tuned! The code will be released soon.


## ☎️ Contact 

If you have any questions, please feel free to reach me out at `licai.sun@oulu.fi`.

## ✏️ Citation

If you think this project is helpful, please feel free to leave a star⭐️ and cite our paper:

```
@article{sun2025learning,
  title={Learning Transferable Facial Emotion Representations from Large-Scale Semantically Rich Captions},
  author={Licai Sun, Xingxun Jiang, Haoyu Chen, Yante Li, Zheng Lian, Biu Liu, Yuan Zong, Wenming Zheng, Jukka M. Leppänen, Guoying Zhao},
  journal={arXiv preprint arXiv:2507.21015},
  year={2025}
}
```

