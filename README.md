## Hi 👋. Here is the homepage of Intelligent Cognitive Systems Laboratory (iCOST), Beijing University of Posts and Telecommunications. test

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->

## Table of Contents

- [Introduction](#introduction)
- [Papers](#papers)
  - [2D Human Pose Estimation](#2d-human-pose-estimation)
  - [3D Human Pose Estimation](#3d-human-pose-estimation)
  - [3D Human Motion Prediction](#3d-human-motion-prediction)
  - [Early Action Prediction](#early-action-prediction)
  - [Skeleton-based Human Action Recognition](#skeleton-based-human-action-recognition)
  - [Group Activity Recognition](#group-activity-recognition)
  - [Uncertainty-aware Scene Understanding with Point Clouds](#uncertainty-aware-scene-understanding-with-point-clouds)
  - [Audio-Visual Learning](#audio-visual-learning)
  - [Audio and Speech Processing](#audio-and-speech-processing)
  - [Medical Image Segmentation](#medical-image-segmentation)
  - [Adversarial Attack](#adversarial-attack)
  - [Others](#others)

## Introduction

The Intelligent Cognitive Systems Laboratory (iCost) at BUPT (Beijing University of Posts and Telecommunications) is actively engaged in long-term research in multiple cutting-edge fields, including computer vision and embodied intelligence. Our research spans various sub-domains such as action recognition, human pose prediction and estimation, uncertainty research, multimodal and audio-visual learning, audio-visual event detection, medical image segmentation, 3D object detection, adversarial strategies, embodied navigation, and robot grasping.

Our research team has achieved substantial results, publishing numerous high-quality research papers in internationally recognized and authoritative journals such as IEEE Transactions on Image Processing (IEEE TIP), IEEE Transactions on Circuits and Systems for Video Technology (IEEE TCSVT), and top-tier conferences like AAAI.

In the Intelligent Cognitive Systems Laboratory, we encourage communication and collaboration among team members, fostering a rigorous and harmonious academic atmosphere. We warmly welcome scholars, researchers, and students who are passionate about artificial intelligence and related fields to join us or collaborate. We believe that everyone with a curiosity for science can find their stage here.

## Papers

### 2D Human Pose Estimation

[**PR 2024**] Kinematics Modeling Network for Video-based Human Pose Estimation [[paper](https://arxiv.org/pdf/2207.10971.pdf)] [[code](https://github.com/YHDang/KIMNet)]

[**TIP 2022**] Relation-Based Associative Joint Location for Human Pose Estimation in Videos [[paper](https://ieeexplore.ieee.org/document/9786543)] [[code](https://github.com/YHDang/pose-estimation)]

[**KBS 2024**] DHRNet: A Dual-Path Hierarchical Relation Network for Multi-Person Pose Estimation [[code](https://github.com/YHDang/DHRNet)]

[-] BiHRNet: A Binary high-resolution network for Human Pose Estimation [[paper](https://arxiv.org/abs/2311.10296)]

### 3D Human Pose Estimation

[**AAAI 2024**] Lifting by Image - Leveraging Image Cues for Accurate 3D Human Pose Estimation [[paper](https://arxiv.org/abs/2312.15636)]

### 3D Human Motion Prediction

[**KBS 2024**] April-GCN: Adjacency Position-velocity Relationship Interaction Learning GCN for Human motion prediction [[paper](https://authors.elsevier.com/sd/article/S0950-7051(24)00248-X)] 

[**TNNLS 2023**] Learning Constrained Dynamic Correlations in Spatiotemporal Graphs for Motion Prediction [[paper](https://ieeexplore.ieee.org/abstract/document/10138910)] [[code](https://github.com/Jaakk0F/DSTD-GCN)]

[**TCSVT 2023**] Collaborative Multi-Dynamic Pattern Modeling for Human Motion Prediction [[paper](https://ieeexplore.ieee.org/abstract/document/10025861)]

[**TCSVT 2022**] Towards more realistic human motion prediction with attention to motion coordination [[paper](https://ieeexplore.ieee.org/abstract/document/9745623/)]

[**TCSVT 2021**] TrajectoryCNN: a new spatio-temporal feature learning network for human motion prediction [[paper](https://ieeexplore.ieee.org/document/9186039)] [[code](https://github.com/lily2lab/TrajectoryCNN)]

[**Neurocomputing 2024**] Physics-constrained Attack against Convolution-based Human Motion Prediction [[paper](https://arxiv.org/abs/2306.11990)] [[code](https://github.com/ChengxuDuan/advHMP)]

[**Neurocomputing 2022**] Temporal consistency two-stream CNN for human motion prediction [[paper](https://www.sciencedirect.com/science/article/abs/pii/S0925231221014892?via%3Dihub)]

[**机器人 2022**] 面向人体动作预测的对称残差网络 [[paper](https://robot.sia.cn/cn/article/doi/10.13973/j.cnki.robot.210188#:~:text=%E6%91%98%E8%A6%81%3A%20%E4%B8%BA%E4%BA%86%E7%A0%94%E7%A9%B6%E4%B8%8D%E5%90%8C%E6%AE%8B%E5%B7%AE%E8%BF%9E%E6%8E%A5%E6%96%B9%E5%BC%8F%E5%AF%B9%E4%BA%BA%E4%BD%93%E5%8A%A8%E4%BD%9C%E9%A2%84%E6%B5%8B%E5%8D%B7%E7%A7%AF%E7%A5%9E%E7%BB%8F%E7%BD%91%E7%BB%9C%E7%9A%84%E5%BD%B1%E5%93%8D%EF%BC%8C%E6%8E%A2%E8%AE%A8%E4%BA%86%E5%9C%A8%E4%BF%9D%E6%8C%81%E7%BD%91%E7%BB%9C%E6%B7%B1%E5%BA%A6%E4%B8%80%E5%AE%9A%E7%9A%84%E6%83%85%E5%86%B5%E4%B8%8B%EF%BC%8C%E5%A6%82%E4%BD%95%E5%88%A9%E7%94%A8%E6%AE%8B%E5%B7%AE%E8%BF%9E%E6%8E%A5%E6%9E%84%E6%88%90%E4%B8%80%E4%B8%AA%E9%AB%98%E6%95%88%E6%8D%95%E6%8D%89%E4%BA%BA%E4%BD%93%E5%8A%A8%E4%BD%9C%E7%89%B9%E5%BE%81%E7%9A%84%E9%A2%84%E6%B5%8B%E6%A8%A1%E5%9E%8B%E3%80%82%20%E9%80%9A%E8%BF%87%E8%A7%82%E5%AF%9F%E4%BA%BA%E4%BD%93%E9%AA%A8%E9%AA%BC%E5%85%B3%E8%8A%82%E7%82%B9%E6%8E%92%E5%88%97%E6%96%B9%E5%BC%8F%EF%BC%8C%E6%8F%90%E5%87%BA%E4%B8%80%E7%A7%8D%E9%80%82%E7%94%A8%E4%BA%8E%E4%BA%BA%E4%BD%93%E9%AA%A8%E9%AA%BC%E5%85%B3%E8%8A%82%E7%82%B9%E9%A2%84%E6%B5%8B%E7%9A%84%E5%AF%B9%E7%A7%B0%E6%AE%8B%E5%B7%AE%E8%BF%9E%E6%8E%A5%E6%96%B9%E6%B3%95%EF%BC%8C%E5%B9%B6%E5%9F%BA%E4%BA%8E%E8%AF%A5%E6%96%B9%E6%B3%95%E8%AE%BE%E8%AE%A1%E4%BA%86%E5%AF%B9%E7%A7%B0%E6%AE%8B%E5%B7%AE%E5%9D%97,%28symmetric%20residual%20block%EF%BC%8CSRB%29%E3%80%82)]

[**MPE 2020**] A Hierarchical Static-Dynamic Encoder-Decoder Structure for 3D Human Motion Prediction with Residual CNNs [[paper](https://www.hindawi.com/journals/mpe/2020/7064910/)] [[code](https://github.com/liujin0/SDnet)]

[**Cognitive Computation and Systems 2020**] Stacked residual blocks based encoder–decoder framework for human motion prediction[[code](https://github.com/lily2lab/residual_prediction_network)]

[-]Uncertainty-aware Human Motion Prediction [[paper](https://scholar.google.com/scholar?oi=bibs&cluster=11543079145147482533&btnI=1&hl=en)]

[-] MSSL: Multi-scale Semi-decoupled Spatiotemporal Learning for 3D human motion prediction [[paper](https://arxiv.org/abs/2010.05133)][[code](https://github.com/lily2lab/MSSL)]

[-] DeepSSM: Deep State-Space Model for 3D Human Motion Prediction [[paper](https://arxiv.org/abs/2005.12155)] [[code](https://github.com/lily2lab/DeepSSM)]


### Early Action Prediction

[**TIP 2024**] Rich Action-semantic Consistent Knowledge for Early Action Prediction [[paper](https://www.semanticscholar.org/reader/7ec7b4929c73ade2c926b65e88bdefaa03148115)] [[code](https://github.com/lily2lab/RACK)]

[**ICCSIP 2022**] A discussion of data sampling strategies for early action prediction [[paper](https://link.springer.com/chapter/10.1007/978-981-16-9247-5_24)]

[**中国自动化大会 2023**] An end-to-end multi-scale network for action prediction in videos

### Skeleton-based Human Action Recognition

[**TCSVT 2024**] SiT-MLP: A Simple MLP with Point-wise Topology Feature Learning for Skeleton-based Action Recognition [[paper](https://ieeexplore.ieee.org/document/10495051)] [[code](https://github.com/BUPTSJZhang/SiT-MLP)]

[**RAS 2020**] DWnet: Deep-wide network for 3D action recognition [[paper](https://www.sciencedirect.com/science/article/abs/pii/S0921889019308176)] [[code](https://github.com/YHDang/DWnet)]

[-] Spatial-Temporal Decoupling Contrastive Learning for Skeleton-based Human Action Recognition [[paper](https://arxiv.org/abs/2312.15144)] [[code](https://github.com/BUPTSJZhang/STD-CL)]

### Group Activity Recognition
[**KBS 2024**] MLP-AIR: An effective MLP-based module for actor interaction relation learning in group activity recognition [[paper](https://www.sciencedirect.com/science/article/pii/S0950705124010876)]

### Uncertainty-aware Scene Understanding with Point Clouds

[**TGRS 2023**] Neighborhood Spatial Aggregation MC Dropout for Efficient Uncertainty-aware Semantic Segmentation in Point Clouds [[paper](https://ieeexplore.ieee.org/document/10247069/)] [[code](https://github.com/chaoqi7/Uncertainty_Estimation_PCSS)]

[**TCSVT 2023**] Instance-incremental Scene Graph Generation from Real-world Point Clouds via Normalizing Flows [[paper](https://ieeexplore.ieee.org/document/10164228/)] [[code](https://github.com/chaoqi7/GPL3D)]

[**TIM 2020**] Multigranularity Semantic Labeling of Point Clouds for the Measurement of the Rail Tanker Component With Structure Modeling [[paper](https://ieeexplore.ieee.org/document/9207911/)] [[code](https://github.com/chaoqi7/Multi-granularity-Semantic-Labeling-with-Structure-Modeling-TIM)]

[**ICRA 2021**] Neighborhood Spatial Aggregation based Efficient Uncertainty Estimation for Point Cloud Semantic Segmentation  [[paper](https://ieeexplore.ieee.org/document/9560972/)] [[code](https://github.com/chaoqi7/Uncertainty_Estimation_PCSS)]

[**Tsinghua Science and Technology 2023**] Dynamic Scene Graph Generation of Point Clouds with Structural Representation Learning [[paper](https://ieeexplore.ieee.org/document/10225283/)]

### Audio Visual Learning

[**TMM 2023**] Leveraging the Video-level Semantic Consistency of Event for Audio-visual Event Localization [[paper](https://ieeexplore.ieee.org/abstract/document/10286391)] [[code](https://github.com/Bravo5542/VSCG)]

[**EMNLP 2023**] Target-Aware Spatio-Temporal Reasoning via Answering Questions in Dynamic Audio-Visual Scenarios [[paper](https://aclanthology.org/2023.findings-emnlp.630/)] [[code](https://github.com/Bravo5542/TJSTG)]

[**计算机应用 2021**] 基于关键帧筛选网络的视听联合动作识别 [[paper](http://www.joca.cn/CN/10.11772/j.issn.1001-9081.2021060995)]

[-] Past Future Motion Guided Network for Audio Visual Event Localization [[paper](https://arxiv.org/abs/2205.03802v1)]

### Audio and Speech Processing

[**ICPR 2024**] Full-frequency dynamic convolution: a physical frequency-dependent convolution for sound event detection [[paper](https://arxiv.org/abs/2401.04976)] [[code](https://github.com/Harper812/FFDConv)]

[**Interspeech 2024**]  MFF-EINV2: Multi-scale Feature Fusion across Spectral-Spatial-Temporal Domains for Sound Event Localization and Detection [[paper](https://arxiv.org/pdf/2406.08771)] [[code](https://github.com/muuda/MFF-EINV2)]

### Medical Image Segmentation

[**IEEE-CYBER 2023**] Multi-task Learning Network for CT Whole Heart Segmentation [[paper](https://ieeexplore.ieee.org/document/10256432)]

[**Biomedical Signal Processing and Control 2022**] DC-net: Dual-Consistency Semi-Supervised Learning for 3D Left Atrium Segmentation from MRI [[paper](https://www.sciencedirect.com/science/article/abs/pii/S1746809422003858)]

### Adversarial Attack

[**Neurocomputing 2023**] Physics-constrained attack against convolution-based human motion prediction [[paper](https://www.sciencedirect.com/science/article/pii/S0925231224000432?via%3Dihub)]

### Others
[**MTAP2023**] Transfer the global knowledge for current gaze estimation [[paper](https://link.springer.com/article/10.1007/s11042-023-17484-2)]

[**TCSVT 2021**] Energy-based Periodicity Mining with Deep Features for Action Repetition Counting in Unconstrained Videos [[paper](https://ieeexplore.ieee.org/document/9339959)] [[code](https://github.com/BUPT-COST-lab/ActionCounting)]

[**ROBIO 2019**]DBNet: A New Generalized Structure Efficient for Classification [[paper](https://ieeexplore.ieee.org/abstract/document/8961680/)] [[code](https://github.com/YHDang/DBNet)]

[-] SDVRF: Sparse-to-Dense Voxel Region Fusion for Multi-modal 3D Object Detection [[paper](https://arxiv.org/abs/2304.08304)]

## Last update: August 22, 2024

Feel free to contact us at 7858833@bupt.edu.cn, or zsj@bupt.edu.cn.
