

<div align="center">

# MMGL: Multi-Scale Multi-View Global-Local Contrastive learning for Semi-supervised Cardiac Image Segmentation

[![MICCAI2022](https://img.shields.io/badge/arXiv-2207.01883-blue)](https://arxiv.org/abs/2207.01883)
[![MICCAI2022](https://img.shields.io/badge/Conference-ICIP2022-green)](https://ieeexplore.ieee.org/document/9897591)



</div>

Pytorch implementation of our method for IEEE ICIP 2022 paper: "MMGL: Multi-Scale Multi-View Global-Local Contrastive learning for Semi-supervised Cardiac Image Segmentation". (Our code will be release soon.)

## Abstract
With large-scale well-labeled datasets, deep learning has shown significant success in medical image segmentation. However, it is challenging to acquire abundant annotations in clinical practice due to extensive expertise requirements and costly labeling efforts. Recently, contrastive learning has shown a strong capacity for visual representation learning on unlabeled data, achieving impressive performance rivaling supervised learning in many domains. In this work, we propose a novel multi-scale multi-view global-local contrastive learning (MMGL) framework to thoroughly explore global and local features from different scales and views for robust contrastive learning performance, thereby improving segmentation performance with limited annotations. Extensive experiments on the MM-WHS dataset demonstrate the effectiveness of MMGL framework on semi-supervised cardiac image segmentation, outperforming the state-of-the-art contrastive learning methods by a large margin.

<p align="center">
<img src="https://github.com/jacobzhaoziyuan/MMGL/blob/main/assets/archi_mmgl.png" width="800">
</p>







## Citation
If you find the codebase useful for your research, please cite the paper:
```
@misc{zhao2022mmgl,
    title={MMGL: Multi-Scale Multi-View Global-Local Contrastive learning for Semi-supervised Cardiac Image Segmentation},
    author={Ziyuan Zhao and Jinxuan Hu and Zeng Zeng and Xulei Yang and Peisheng Qian and Bharadwaj Veeravalli and Cuntai Guan},
    year={2022},
    eprint={2207.01883},
    archivePrefix={arXiv},
    primaryClass={eess.IV}
}

```
