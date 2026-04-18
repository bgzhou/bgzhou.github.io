---
layout: single
title: "Research"
permalink: /research/
author_profile: true
---

# 🔎 Research

[**Research Interests**](#research-interests) | [**Research Highlights**](#research-highlights) | [**Collaborators**](#collaborators)
## <font color=MediumAquaMarine>Research Interests</font>


### <font color=CornflowerBlue>Methods</font>
- **Machine Learning**: Statistical Machine Leanring (SML), Deep Learning (DL), Graph Machine Learning (GML), Generative Artificial Intelligence (GAI), Neural Natural Language Processing (Neural NLP)

- **Data Science**: Statistical Analysis, Data Efficiency, Correlation Mining

<!-- - **Natural Language Processing**: Neural Natural Language Processing (Neural NLP); Knowledge Base/Graph -->

### <font color=CornflowerBlue>Applications</font>
- **Wireless Communications and Sensing**: Massive/Extremely Large-Scale MIMO; Beyond Diagonal Reconfigurable Intelligent Surfaces (BD-RIS); Integrated Sensing and Communications

- **Applied Data Mining**: Spatial-Temporal (Demand) Forecasting, Energy Disaggregation

- **Smart Healthcare**: Digital Health Mornitoring, Health Informatics

## <font color=MediumAquaMarine>Research Highlights</font>

### <font color=CornflowerBlue>1. Knowledge-and-Data Driven CSI Acquisition</font>

<img src='images/KDD_CSI.png' width = "1200" alt="" align=center />

Currently, mobile communications have evolved into 5G/B5G and we are now anticipating what 6G will be like. According to [1], the usage scenarios of IMT-2030 (6G) include immersive communication, hyper reliable and low-latency communication, massive communication, ubiquitous connectivity, integrated sensing and communication, etc. These usage scenarios raise **high data rate requirements**, **hyper reliability requirements**, and **massive connection requirements** to current wireless communication systems. To meet these requirements, extreme/massive MIMO has been recognized as an essential technology to provide spatial degrees of freedom, diversity or multiplexing gain, and array gain, thereby improving the spectral and energy efficiencies of wireless communication systems.

However, extreme/massive MIMO also brings out **complicated channel characteristics** and **high overhead and computational complexity**, which are significantly challenging for channel state information (CSI) acquisition. It is fortunate that by learning from extensive data, some deep learning-based algorithms have been proposed to capture the complicated channel characteristics of massive MIMO channels and further improve the spectral and energy efficiencies of massive MIMO systems. Nonetheless, the high overhead and computational complexity of massive MIMO systems are not significantly reduced by existing deep learning-based algorithms. In addition, most existing deep learning-based algorithms are purely data-driven and basically rely on extensive collected data for learning the features of complicated wireless channels, leading to unaffordable data collection costs.

To simultaneously improve spectral and energy efficiencies, reduce overhead and computational complexity, and circumvent extensive data collection towards accurate and efficient CSI acquisition, we investigate how to realize knowledge-and-data driven CSI estimation and feedback, particularly for massive MIMO systems. Both **domain knowledge**, e.g., multi-domain correlations and channel sparsity, and **learning data,** e.g., historical data and cross-domain data, are exploited for framework design, learning paradigm design, and computationally efficient design to achieve the aforementioned goals. Some frameworks and algorithms we proposed are listed above and the interested readers are referred to the following publications:

```[1] Binggui Zhou, Xi Yang, Shaodan Ma, Feifei Gao, and Guanghua Yang, “Pay less but get more: A dual-attention-based channel estimation network for massive MIMO systems with low-density pilots,” IEEE Transactions on Wireless Communications, vol. 23, no. 6, pp. 6061-6076, Jun. 2024.```

```[2] Binggui Zhou, Xi Yang, Jintao Wang, Shaodan Ma, Feifei Gao, and Guanghua Yang, “A low-overhead incorporation-extrapolation based few-shot CSI feedback framework for massive MIMO systems,” IEEE Transactions on Wireless Communications, vol. 23, no. 10, pp. 14743-14758, Oct. 2024.```

```[3] Binggui Zhou, Xi Yang, Shaodan Ma, Feifei Gao, and Guanghua Yang, “Low-overhead channel estimation via 3D extrapolation for TDD mmWave massive MIMO systems under high-mobility senarios,” IEEE Transactions on Wireless Communications, vol. 24, no. 4, pp. 2797-2813, Apr. 2025.```


### <font color=CornflowerBlue>2. Machine Learning Empowered Wireless Communications: Prototyping and Demo Systems</font>

Vision-aided multi-user sensing and communications prototyping system:

<img src='images/VisionDemo_Diagram.png' width = "1200" alt="" align=center />

Details of the prototyping system can be found in our [Lab Pages](https://www.fst.um.edu.mo/personal/shaodanma/research/) and the following publications.

```[1] Kehui Li, Binggui Zhou, Jiajia Guo, Xi Yang, Qing Xue, Feifei Gao, and Shaodan Ma, “Vision-aided Multi-user Beam Tracking for mmWave Massive MIMO System: Prototyping and Experimental Results,” in Proceedings of IEEE Vehicular Technology Conference: VTC2024-Spring, pp. 1-6, 2024.```

### <font color=CornflowerBlue>3. Pratical Verifications of Machine Learning Empowered Wireless Communications</font>

(1) Check out [Our Solution](https://mp.weixin.qq.com/s/iZAZn3NxvLZKTBuukFsbsQ) to the **First 6G AI Competition** held by the Guangdong OPPO Mobile Communications Corp., Ltd, which won the **Second Prize** and ranked **2/727 teams**.

Channel modeling is an important area of 6G pre-research. To cope with the increasingly complex wireless communication environment and make full use of data-driven/knowledge-and-data driven algorithms for complex channel modeling, we propose a generative adversarial network (GAN) for channel modeling and constructing an extensive wireless channel dataset of high-quality samples using a small number of real channel samples. The proposed GAN is based on the multi-head self-attention mechanism and convolution operations. We decouple the channel generation problem into two parts: valid (meaningful) delayed **path position generation** and valid (meaningful) delayed **path generation**. Therefore, the generator contains two sub-networks. The path generation sub-network mainly exploits Transformer layers as the backbone, while the backbone of the path position generation sub-network is with a two-layer multi-layer perceptron structure. The discriminator exploits multiple convolutional downsampling modules to distinguish between generated samples and real samples.

<img src='images/AICompetition_ChannelModeling.png' width = "1200" alt="" align=center />

(2) Our recent solution to **CSI feedback with limited samples** won the **Winning Prize (ranking 9/1252 teams)** of the **First 6G Intelligent Wireless Communication System Competition** held by the IMT-2030 (6G) Promotion Group and Guangdong OPPO Mobile Communications Corp., Ltd.

Deep learning based CSI feedback has received widespread attention from academia and industry in recent years. However, most of the existing deep learning based CSI feedback methods are purely data-driven. In addition to obtaining high-performance gains brought by data-driven, such methods also show poor generalization performance in different scenarios. Currently, to mitigate this issue, expensive data collection costs and long training time for different scenarios are inevitable, and thus poses further challenges for the implementation of such deep learning based CSI feedback methods. To address these challenges, we propose a CSI feedback method that uses only a small number of samples to obtain better generalization capabilities. Through **frequency domain data augmentation** and the advanced **dual-attention-based CSI feedback model**, the proposed CSI feedback method can achieve CSI feedback with good generalization ability in a very concise way. In addition, to mitigate quantization errors, we further propose a **quantization ensemble framework** which exploits several quantizers and dequantizers for ensemble. Specifically, constrained by 30-bit CSI feedback overhead and to balance the number of feedback bits, quantization error and the size of backbone networks, we use 27 bits for quantization and 3 bits as the quantizer index (which indicates that a total of 8 quantizers with different configurations can be utilized). Hybrid scalar quantization is considered, and each two quantizers share an Encoder backbone network to ensure that each Encoder backbone network has larger model scale and learning capabilities.

The dual-attention-based CSI feedback model (left) and the quantization ensemble framework (right):

<img src='images/6GAICompetition_CSIFeedback.png' width = "1200" alt="" align=center />


<!-- ### 3. Machine Learning and Data Science

### 4. Smart Healthcare -->

<!-- ### Other Topics, such as machine learning methodology -->

## Collaborators

I collaborate closely with [Prof. Shaodan Ma (Professor, University of Macau)](https://scholar.google.co.uk/citations?user=43edNugAAAAJ&hl=en), [Prof. Guanghua Yang (Professor, IET Fellow, Jinan University)](https://scholar.google.co.uk/citations?user=0GaD5AEAAAAJ&hl=en), [Prof. Bruno Clerckx (Professor, IEEE Fellow, Imperial College London)](https://profiles.imperial.ac.uk/b.clerckx), [Prof. Xi Yang (Professor, East China Normal University)](https://faculty.ecnu.edu.cn/_s15/yx2/main.psp), [Prof. Feifei Gao (Professor, IEEE Fellow, Tsinghua University)](https://scholar.google.com/citations?user=_VDYtKMAAAAJ&hl=en), [Prof. Zheng Shi (Professor, Jinan University)](https://scholar.google.com/citations?user=_DQ7HfQAAAAJ&hl=en), [Prof. Qing Xue (Associate Professor, Chongqing University of Posts and Telecommunications)](https://scholar.google.com/citations?user=kK2thisAAAAJ&hl=zh-CN), [Prof. Weiqiang Tan (Professor, Guangzhou University)](https://aicom.gzhu.edu.cn/info/1160/1033.htm), and [Dr. Jintao Wang (Postdoctoral Researcher, University of Macau)](https://scholar.google.com/citations?hl=zh-CN&user=dkQrb10AAAAJ) on wireless communications, and with [Prof. Yunxuan Dong (Assistant Professor, Guangxi University)](https://scholar.google.com/citations?user=dYcYJfUAAAAJ&hl=en&authuser=1) on applied data mining.

Feel free to [drop me an email](mailto:binggui.zhou@imperial.ac.uk) if you would like to collaborate with me.