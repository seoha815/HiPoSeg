# HiPoSeg 🦛: Hierarchical Prototype Learning for Semantic Segmentation
**The Fourteenth International Conference on Learning Representations (ICLR) 2026**

[Project Page](https://iclr.cc/virtual/2026/poster/10006745) | [Paper](https://openreview.net/forum?id=wHMuQ9HgUo)

<p align="center">
  <img src="fig1_v4_1.png" width="70%">
</p>

## Hierarchical Prototype Learning for Semantic Segmentation  
**The Fourteenth International Conference on Learning Representations (ICLR) 2026**  

Seoha Lim*, Jinmyeong Kim*, Jieun Kim, Sung-Bae Cho  
Yonsei University  
{seoha815, jmkim_, lilly9928, sbcho}@yonsei.ac.kr

## 💡 Abstract

Conventional semantic segmentation methods often fail to distinguish fine-grained parts within the same object because of missing links between part-level cues and object-level semantics. Inspired by how humans recognize objects, which involves first identifying them as a whole and then distinguishing their parts, we propose a hierarchical prototype-based segmentation method called Hierarchical Prototype Segmentation (HiPoSeg). This builds a structured prototype space that captures both abstract object-level representations and detailed part-level features, enabling consistent alignment between levels. HiPoSeg leverages a hierarchical contrastive learning strategy to structure semantic representations across levels, encouraging both intra-level discrimination and cross-level consistency. Experiments on standard benchmarks such as Cityscapes, ADE20K, Mapillary Vistas 2.0, and PASCAL-Part-108 demonstrate that HiPoSeg produces consistent performance improvement with an average gain of +3.07%p mIoU without any additional inference cost.

## 💻 Code

Code will be released soon.

## 📌 Citation

If you find **HiPoSeg** useful in your research, please consider citing:

```bibtex
@inproceedings{limhierarchical,
  title={Hierarchical Prototype Learning for Semantic Segmentation},
  author={Lim, Seoha and Kim, Jinmyeong and Kim, Jieun and Cho, Sung-Bae},
  booktitle={The Fourteenth International Conference on Learning Representations}
}
