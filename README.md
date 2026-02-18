# Monocular-depth-estimation-paper-list
A personal list of papers and resources for monocular depth estimation (not complete yet)

---
- [Survey](#survey)
- [Models](#Models)
   - [Metric Monocular depth estimation](#Metric-Monocular-depth-estimation)
   - [Relative Monocular depth estimation](#Relative-Monocular-depth-estimation)
- [Datasets](#datasets)
- [Challenges and workshops](#challenges-and-workshops)

---

## Survey
   * Monocular Depth Estimation: A Thorough Review [[IEEE TPAMI 2024](https://www.computer.org/csdl/journal/tp/2024/04/10313067/1RUgtl8jBAI)] [[]()]
   * Deep Learning-based Depth Estimation Methods from Monocular Image and Videos: A Comprehensive Survey [[ACM Computing Surveys, 2024](https://arxiv.org/pdf/2406.19675)] [[]()]
   * Survey on Monocular Metric Depth Estimation [[arXiv 2025](https://arxiv.org/pdf/2501.11841)] [[]()]

---

## Models
### Metric-Monocular-depth-estimation
   * InfiniDepth: Arbitrary-Resolution and Fine-Grained Depth Estimation with Neural Implicit Fields [[arXiv 2026](https://arxiv.org/pdf/2601.03252)] [[repo](https://github.com/zju3dv/InfiniDepth)]
   * UniDepthV2: Universal Monocular Metric Depth Estimation Made Simpler [[IEEE TPAMI 2026](https://arxiv.org/pdf/2502.20110)] [[repo](https://github.com/lpiccinelli-eth/UniDepth)]
   * Depth Pro: Sharp Monocular Metric Depth in Less Than a Second [[ICLR 2025](https://arxiv.org/pdf/2410.02073)] [[repo](https://github.com/apple/ml-depth-pro)]
   * MoGe-2: Accurate Monocular Geometry with Metric Scale and Sharp Details [[NeurIPS 2025](https://arxiv.org/pdf/2507.02546) [[]()]
   * MoGe: Unlocking Accurate Monocular Geometry Estimation for Open-Domain Images with Optimal Training Supervision [[CVPR 2025](https://arxiv.org/pdf/2410.19115)] [[repo](https://github.com/microsoft/MoGe)]
     
     
   * Depth Anything V2 [[NeurIPS 2024](https://arxiv.org/pdf/2406.09414)] [[repo](https://github.com/DepthAnything/Depth-Anything-V2)]
   * UniDepth: Universal Monocular Metric Depth Estimation [[CVPR 2024](https://arxiv.org/pdf/2403.18913)] [[repo](https://github.com/lpiccinelli-eth/UniDepth/tree/main)]
   * DUSt3R: Geometric 3D Vision Made Easy [[CVPR 2024](https://arxiv.org/pdf/2312.14132)] [[repo](https://github.com/naver/dust3r)]
   * Depth Anything: Unleashing the Power of Large-Scale Unlabeled Data [[CVPR 2024](https://arxiv.org/pdf/2401.10891)] [[repo](https://github.com/LiheYoung/Depth-Anything)]
   * Metric3dv2 [[TPAMI 2024](https://arxiv.org/pdf/2404.15506)][[repo](https://github.com/YvanYin/Metric3D)]
   * PatchFusion: An End-to-End Tile-Based Framework for High-Resolution Monocular Metric Depth Estimation [[CVPR 2024](https://arxiv.org/pdf/2312.02284)][[repo](https://github.com/zhyever/PatchFusion)]

     
   * ZoeDepth: Zero-shot Transfer by Combining Relative and Metric Depth [[CVPR 2023](https://arxiv.org/pdf/2302.12288)] [[rep](https://github.com/isl-org/ZoeDepth)]
   * Metric3D: Towards Zero-shot Metric 3D Prediction from A Single Image [[ICCV 2023](https://arxiv.org/pdf/2307.10984)] [[repo](https://github.com/YvanYin/Metric3D)]
   * iDisc: Internal Discretization for Monocular Depth Estimation [[CVPR 2023](https://arxiv.org/pdf/2304.06334)] [[repo](https://github.com/SysCV/idisc)]
   * ZeroDepth: Towards Zero-Shot Scale-Aware Monocular Depth Estimation [[ICCV 2023](https://arxiv.org/pdf/2306.17253)] [[repo](https://github.com/tri-ml/vidar)]

     
   * Vision Transformers for Dense Prediction (DPT) [[IEEE TPAMI 2021](https://arxiv.org/pdf/2103.13413)] [[repo](https://github.com/isl-org/DPT)]
   * AdaBins: Depth Estimation Using Adaptive Bins [[CVPR 2021](https://arxiv.org/pdf/2011.14141)] [[repo](https://github.com/shariqfarooq123/AdaBins)]

     

### Relative-Monocular-depth-estimation
   * Marigold: Affordable Adaptation of Diffusion-Based Image Generators for Image Analysis [[CVPR 2024](https://arxiv.org/pdf/2505.09358)] [[repo](https://github.com/prs-eth/Marigold)]
   * G2-MonoDepth [[IEEE TPAMI 2024](https://arxiv.org/pdf/2310.15422)] [[repo](https://github.com/Wang-xjtu/G2-MonoDepth)]
   * Towards Robust Monocular Depth Estimation: Mixing Datasets for Zero-shot Cross-dataset Transfer (MiDaS) [[IEEE TPAMI 2020](https://arxiv.org/pdf/1907.01341)] [[repo](https://github.com/isl-org/MiDaS)]
   * Boosting Monocular Depth Estimation Models to High-Resolution via Content-Adaptive Multi-Resolution Merging [[CVPR 2021](https://arxiv.org/pdf/2105.14021)] [repo](https://github.com/compphoto/BoostingMonocularDepth)
   
---

## Datasets
### Monocular-Real-Indoor

  * [ARKitScenes](https://github.com/apple/ARKitScenes?tab=readme-ov-file) [[NeurIPS 2021](https://openreview.net/pdf?id=tjZjv_qh_CE)]
  * [iBims-v1](https://www.kaggle.com/datasets/patiencechewyeecheah/ibims-1) [[ECCV 2018](https://openaccess.thecvf.com/content_ECCVW_2018/papers/11131/Koch_Evaluation_of_CNN-based_Single-Image_Depth_Estimation_Methods_ECCVW_2018_paper.pdf)]
  * [ScanNet](http://www.scan-net.org/) [[CVPR 2017](https://openaccess.thecvf.com/content_cvpr_2017/papers/Dai_ScanNet_Richly-Annotated_3D_CVPR_2017_paper.pdf)]
  * [SUN RGB-D: A RGB-D Scene Understanding Benchmark Suite](https://rgbd.cs.princeton.edu/) [[CVPR 2015](https://rgbd.cs.princeton.edu/paper.pdf)]
  * [NYU Depth Dataset V2](https://cs.nyu.edu/~fergus/datasets/nyu_depth_v2.html) [[ECCV 2012](https://cs.nyu.edu/~fergus/datasets/indoor_seg_support.pdf)]
  * [RGB-D SLAM Dataset and Benchmark](https://cvg.cit.tum.de/data/datasets/rgbd-dataset) [[IROS 2012](https://ieeexplore.ieee.org/document/6385773)]
  * [Taskonomy](http://taskonomy.stanford.edu/) [[CVPR 2018](http://taskonomy.stanford.edu/taskonomy_CVPR2018.pdf)]


### Monocular-Real-Indoor-and-Outdoor
  * [DIODE: A Dense Indoor and Outdoor DEpth Dataset](https://diode-dataset.org/) [[CoRR 2019](https://arxiv.org/pdf/1908.00463)]
    
### Monocular-Real-Outdoor

### Monoular-Synthetic-Indoor

### Monoular-Synthetic-Outdoor

### Stereo-Real-Indoor
   * [Booster Dataset](https://cvlab-unibo.github.io/booster-web/) [[CVPR 2022](https://arxiv.org/pdf/2206.04671)]

### Stereo-Real-Outdoor

### Stereo-Synthetic-Indoor

### Stereo-Synthetic-Outdoor

---

## Challenges-and-workshops




