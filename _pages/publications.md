---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


# 📝 Publications

[**Representative Publications (by Topic)**](#representative-publications-by-topic) | [**List of Publications (by Topic)**](#list-of-publications-by-topic)
## <font color=MediumAquaMarine>Representative Publications (by Topic)</font>

(&dagger; for Equal Contribution; * for Corresponding Authorship.)

### <font color=CornflowerBlue>Wireless Communications</font>

<div class='paper-box'><div class='paper-box-image'><div><div class='badge'>IEEE TWC</div><img src='images/SFTCE.png' alt='sym' width='100%'></div></div>
<div class='paper-box-text' markdown='1'>

[Low-Overhead Channel Estimation via 3D Extrapolation for TDD mmWave Massive MIMO Systems Under High-Mobility Scenarios](https://ieeexplore.ieee.org/document/10836149)

**Binggui Zhou**, Xi Yang, Shaodan Ma, Feifei Gao, and Guanghua Yang, “Low-Overhead Channel Estimation via 3D Extrapolation for TDD mmWave Massive MIMO Systems Under High-Mobility Scenarios,” **IEEE Transactions on Wireless Communications**, vol. 24, no. 4, pp. 2797-2813, Apr. 2025. **(JCR Q1, IF: 8.9)**
 
[Preprint](https://arxiv.org/abs/2406.08887) \| <strong><span class='show_paper_citations' data='2RwBacMAAAAJ:tOudhMTPpwUC'></span></strong>

- In this work, we propose a **three-domain (3D) channel extrapolation framework** across spatial, frequency, and temporal domains to reduce pilot training overhead for TDD mmWave massive MIMO systems under high mobility. The proposed method first realizes uplink channel estimation with the **knowledge-and-data driven spatial-frequency channel extrapolation network (KDD-SFCEN)** to reduce the spatial-frequency domain pilot training overhead $C_{sl}$, and then conducts accurate slot-level channel extrapolation with the **temporal uplink-downlink channel extrapolation network (TUDCEN)** to reduce the times of uplink channel estimations $\frac{T}{T_p}$, thereby systematically reducing the pilot training overhead $C_o$.
- Numerical results demonstrate the superiority of the proposed framework in significantly **reducing the pilot training overhead by 16 times** and **improving the system's spectral efficiency under high-mobility scenarios** compared with state-of-the-art channel estimation/extrapolation methods.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class='badge'>IEEE TWC</div><img src='images/IEFSF.png' alt='sym' width='100%'></div></div>
<div class='paper-box-text' markdown='1'>

[A Low-Overhead Incorporation-Extrapolation Based Few-Shot CSI Feedback Framework for Massive MIMO Systems](https://ieeexplore.ieee.org/document/10600118)

**Binggui Zhou**, Xi Yang, Jintao Wang, Shaodan Ma, Feifei Gao, and Guanghua Yang, “A Low-Overhead Incorporation-Extrapolation Based Few-Shot CSI Feedback Framework for Massive MIMO Systems,” **IEEE Transactions on Wireless Communications**, vol. 23, no. 10, pp. 14743-14758, Oct. 2024.  **(JCR Q1, IF: 8.9)**
 
[Preprint](https://arxiv.org/abs/2312.04062) \| <strong><span class='show_paper_citations' data='2RwBacMAAAAJ:nb7KW1ujOQ8C'></span></strong>

- In this work, we propose the **Incorporation-Extrapolation based Few-Shot CSI feedback Framework (IEFSF)** for massive MIMO systems to enable low-overhead CSI feedback with reduced data collection cost. An incorporation-extrapolation scheme for eigenvector-based CSI feedback is proposed to reduce the feedback overhead. Then, to alleviate the necessity of extensive collected samples and enable few-shot CSI feedback, we further propose a **knowledge-driven data augmentation (KDDA) method** and an **artificial intelligence-generated content (AIGC) -based data augmentation method** by exploiting the domain knowledge of wireless channels and by exploiting a novel generative model, respectively.
- Experimental results based on the DeepMIMO dataset demonstrate that the proposed IEFSF significantly reduces CSI feedback overhead by **64 times** compared with existing methods while maintaining higher feedback accuracy using **only several hundred collected samples**.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class='badge'>IEEE TWC</div><img src='images/DACEN.png' alt='sym' width='100%'></div></div>
<div class='paper-box-text' markdown='1'>

[Pay Less But Get More: A Dual-Attention-based Channel Estimation Network for Massive MIMO Systems with Low-Density Pilots](https://ieeexplore.ieee.org/document/10315065)

**Binggui Zhou**, Xi Yang, Shaodan Ma, Feifei Gao, and Guanghua Yang, “Pay Less But Get More: A Dual-Attention-based Channel Estimation Network for Massive MIMO Systems with Low-Density Pilots,” **IEEE Transactions on Wireless Communications**, vol. 23, no. 6, pp. 6061-6076, Jun. 2024. **(JCR Q1, IF: 8.9)**
 
[Preprint](https://arxiv.org/abs/2303.00986) \| [Code](https://github.com/bgzhou/DACEN) \| <strong><span class='show_paper_citations' data='2RwBacMAAAAJ:UxriW0iASnsC'></span></strong>

- In this work, we propose the **dual-attention-based channel estimation network (DACEN)** to realize accurate channel estimation via low-density pilots, by jointly learning the spatial-temporal domain features of massive MIMO channels with the temporal attention module and the spatial attention module. To further improve the estimation accuracy, we propose a **parameter-instance transfer learning approach** to transfer the channel knowledge learned from the high-density pilots pre-acquired during the training dataset collection period.
- Experimental results reveal that the proposed DACEN-based method can reduce up to **92% of pilot overhead** by reducing the pilot density **from 26/52 to 2/52** than traditional channel estimation methods. Additionally, with the proposed parameter-instance transfer learning approach, the DACEN-based method achieves **additional performance gain**, thereby further demonstrating the effectiveness and superiority of the proposed method.
</div>
</div>

### <font color=CornflowerBlue>Machine Learning and Data Science</font>

<div class='paper-box'><div class='paper-box-image'><div><div class='badge'>KBS</div><img src='images/HSTGANet.png' alt='sym' width='100%'></div></div>
<div class='paper-box-text' markdown='1'>

[A Graph-Attention Based Spatial-Temporal Learning Framework for Tourism Demand Forecasting](https://www.sciencedirect.com/science/article/pii/S0950705123000254)

**Binggui Zhou**, Yunxuan Dong, Guanghua Yang, Fen Hou, Zheng Hu, Suxiu Xu, and Shaodan Ma, “A Graph-Attention Based Spatial-Temporal Learning Framework for Tourism Demand Forecasting,” **Knowledge-Based Systems**, vol. 263, p. 110275, Mar. 2023. **(JCR Q1, IF: 7.2)**
 
<strong><span class='show_paper_citations' data='2RwBacMAAAAJ:p2g8aNsByqUC'></span></strong>

- In this paper, we propose a graph-attention based spatial–temporal learning framework for tourism demand forecasting. A **weight-dynamic multi-dimensional graph** is organized to embed multiple explicit dynamic spatial connections and provide a node attribute sequence for learning implicit dynamic spatial connections. We further propose a **heterogeneous spatial–temporal graph-attention network (HSTGANet)**, which is effective in handling both explicit and implicit dynamic spatial connections, learning high-dimensional spatial–temporal features, and forecasting tourism demand.
- Experimental results demonstrate the **effectiveness of the proposed model** over baseline models in forecasting the tourism demand for six regions of Wanshan Archipelago in Zhuhai, China, and indicate that the proposed spatial–temporal learning framework may provide **useful insights for developing more effective models** for other spatial–temporal forecasting problems.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class='badge'>ASOC</div><img src='images/ITANet.png' alt='sym' width='100%'></div></div>
<div class='paper-box-text' markdown='1'>

[Interpretable Temporal Attention Network for COVID-19 Forecasting](https://www.sciencedirect.com/science/article/pii/S1568494622001545)

**Binggui Zhou**, Guanghua Yang, Zheng Shi, and Shaodan Ma, “Interpretable Temporal Attention Network for COVID-19 Forecasting,” **Applied Soft Computing**, vol. 120, p. 108691, May 2022. **(JCR Q1, IF: 7.2)**
 
<strong><span class='show_paper_citations' data='2RwBacMAAAAJ:OU6Ihb5iCvQC'></span></strong>

- In this work, we propose the **Interpretable Temporal Attention Network (ITANet)** for COVID-19 forecasting and inferring the importance of government interventions. The proposed model is with an encoder–decoder architecture and employs long short-term memory (LSTM) for temporal feature extraction and multi-head attention for long-term dependency caption. The model simultaneously takes historical information, a priori known future information, and pseudo future information into consideration, where the pseudo future information is learned with the **covariate forecasting network (CFN)** and **multi-task learning (MTL)**. In addition, we also propose the **degraded teacher forcing (DTF) method** to train the model efficiently. 
- Compared with other models, the ITANet is more effective in the forecasting of COVID-19 new confirmed cases.
- The importance of government interventions against COVID-19 is further inferred by the **Temporal Covariate Interpreter (TCI)** of the model.
</div>
</div>

### <font color=CornflowerBlue>Smart Healthcare</font>

<div class='paper-box'><div class='paper-box-image'><div><div class='badge'>IEEE RBME</div><img src='images/FeaturedArticlePromotion.png' alt='sym' width='100%'></div></div>
<div class='paper-box-text' markdown='1'>

[Natural Language Processing for Smart Healthcare](https://ieeexplore.ieee.org/abstract/document/9904944)

**Binggui Zhou**, Guanghua Yang, Zheng Shi, and Shaodan Ma, “Natural Language Processing for Smart Healthcare,” **IEEE Reviews in Biomedical Engineering**, vol. 17, pp. 4-18, Jan. 2024. **(JCR Q1, IF: 17.2, <font color=Red>ESI Hot Paper</font>, <font color=Red>ESI Highly Cited Paper</font>, and <font color=Red>Popular Article</font> & <font color=Red>Featured Article</font> of <font color=Red>IEEE RBME</font>)**
 
[Preprint](https://arxiv.org/abs/2110.15803) \| <strong><span class='show_paper_citations' data='2RwBacMAAAAJ:K3LRdlH-MEoC'></span></strong>

- In this work, we review existing studies that concern NLP for smart healthcare from the perspectives of technique and application.
- We first elaborate on different **NLP approaches** and the **NLP pipeline for smart healthcare** from the technical point of view. Then, in the context of smart healthcare applications employing NLP techniques, we introduce several **representative smart healthcare scenarios**. We further discuss two **specific medical issues**, i.e., the coronavirus disease 2019 (COVID-19) pandemic and mental health, in which NLP-driven smart healthcare plays an important role. Finally, we discuss the **limitations** of current works and identify the **directions for future works**.

<!-- - **Academic Impact**: This work is included by many famous speech synthesis open-source projects, such as [ESPNet ![](https://img.shields.io/github/stars/espnet/espnet?style=social)](https://github.com/espnet/espnet). Our work are promoted by more than 20 media and forums, such as [机器之心](https://mp.weixin.qq.com/s/UkFadiUBy-Ymn-zhJ95JcQ)、[InfoQ](https://www.infoq.cn/article/tvy7hnin8bjvlm6g0myu).
- **Industry Impact**: FastSpeech has been deployed in [Microsoft Azure TTS service](https://techcommunity.microsoft.com/t5/azure-ai/neural-text-to-speech-extends-support-to-15-more-languages-with/ba-p/1505911) and supports 49 more languages with state-of-the-art AI quality. It was also shown as a text-to-speech system acceleration example in [NVIDIA GTC2020](https://resources.nvidia.com/events/GTC2020s21420). -->
</div>
</div>

## <font color=MediumAquaMarine>List of Publications (by Topic)</font>

(&dagger; for Equal Contribution; * for Corresponding Authorship; **J** for Journal Publications; **C** for Conference Publications; **P** for Patent Grants/Applications.)

<!-- [<font color=Blue>\[Paper\]</font>](https://ieeexplore.ieee.org/abstract/document/9475482) 【公式形式显示】 -->

### <font color=CornflowerBlue>Wireless Communications</font>

**[J16]** Yiyang Peng, **Binggui Zhou**, Yutong Zheng, Danilo Mandic, and Bruno Clerckx, “Joint Training Scattering Matrix Learning and Channel Estimation for Beyond-Diagonal Reconfigurable Intelligent Surfaces,” submitted to **IEEE Transactions on Wireless Communications**. [Preprint](https://arxiv.org/abs/2603.25299)

**[J15]** Qikai Xiao&dagger;, Kehui Li&dagger;, **Binggui Zhou**, and Shaodan Ma, “Deep Learning Based Channel Extrapolation for Dual-Band Massive MIMO Systems,” submitted to **IEEE Wireless Communications Letters**. [Preprint](https://arxiv.org/abs/2601.06858)

**[J14]** **Binggui Zhou** and Bruno Clerckx, “Beyond-Diagonal RIS Under Non-Idealities: Learning-Based Architecture Discovery and Optimization,” submitted to **IEEE Transactions on Wireless Communications**. [Preprint](https://arxiv.org/abs/2510.15701)

**[J13]** Xi Yang\*, Dahong Du, Ting Liu, **Binggui Zhou**\*, and Shaodan Ma, “Channel Recovery for UPA-assisted Massive MlMO Systems with Asymmetrical Uplink and Downlink Transceivers,” **IEEE Internet of Things Journal**, vol. 13, no. 7, pp. 14829-14843, Apr. 2026. **(JCR Q1, IF: 8.2)** [Published Version](https://ieeexplore.ieee.org/document/11328073)

**[J12]** Hao Xia, Qing Xue, Yanping Liu, **Binggui Zhou**, Meng Hua, and Qianbin Chen, “Intelligent Angle Map-based Beam Alignment for RIS-aided mmWave Communication Networks,” **IEEE Transactions on Network Science and Engineering**, vol. 13, pp. 5833-5850, 2026. **(JCR Q1, IF: 8.3)** [Published Version](https://ieeexplore.ieee.org/document/11347574) \| [Preprint](https://arxiv.org/abs/2410.23919)

**[J11]** Kehui Li, **Binggui Zhou**\*, Jiajia Guo, Feifei Gao, Guanghua Yang\*, and Shaodan Ma, “Out-of-Band Modality Synergy Based Multi-User Beam Prediction and Proactive BS Selection with Zero Pilot Overhead”, **IEEE Transactions on Communications**, vol. 74, pp. 3858-3874, 2026. **(JCR Q1, IF: 8.3)** [Published Version](https://ieeexplore.ieee.org/document/11358948) \| [Preprint](https://arxiv.org/abs/2506.15136)

**[J10]** Jintao Wang, **Binggui Zhou**, Chengzhi Ma, Shiqi Gong, Guanghua Yang, and Shaodan Ma, “Robust Beamforming Design and Antenna Selection for Dynamic HRIS-aided MISO Systems,” **IEEE Transactions on Vehicular Technology**, vol. 74, no. 9, pp. 14943-14948, Sep. 2025. **(JCR Q1, IF: 6.1)** [Published Version](https://ieeexplore.ieee.org/abstract/document/10981669) \| [Preprint](https://arxiv.org/abs/2404.00598)

**[J9]** **Binggui Zhou**, Xi Yang, Shaodan Ma, Feifei Gao, and Guanghua Yang, “Low-Overhead Channel Estimation via 3D Extrapolation for TDD mmWave Massive MIMO Systems Under High-Mobility Scenarios,” **IEEE Transactions on Wireless Communications**, vol. 24, no. 4, pp. 2797-2813, Apr. 2025. **(JCR Q1, IF: 8.9)** [Published Version](https://ieeexplore.ieee.org/document/10836149) \| [Preprint](https://arxiv.org/abs/2406.08887)

**[J8]** Jianpeng Zou, Zheng Shi, **Binggui Zhou**, Yaru Fu, Hong Wang, and Weiqiang Tan, “Throughput Maximization of HARQ-IR for ISAC,” **IEEE Communications Letters**, vol. 29, no. 3, pp. 492-496, Mar. 2025. **(JCR Q2, IF: 3.7)** [Published Version](https://ieeexplore.ieee.org/document/10833859)

**[J7]** Qing Xue, Jiajia Guo, **Binggui Zhou**, Yongjun Xu, Zhidu Li, and Shaodan Ma, “AI/ML for Beam Management in 5G-Advanced: A Standardization Perspective,” **IEEE Vehicular Technology Magazine**, vol. 19, no. 4, pp. 64-72, Dec. 2024. **(JCR Q1, IF: 5.8)** [Published Version](https://ieeexplore.ieee.org/document/10627924) \| [Preprint](https://arxiv.org/abs/2309.10575)

**[J6]** Fuchao He, Zheng Shi, **Binggui Zhou**, Guanghua Yang, Xiaofan Li, Xinrong Ye, and Shaodan Ma, “BLER Analysis and Optimal Power Allocation of HARQ-IR for Mission-Critical IoT Communications,” **IEEE Internet of Things Journal**, vol. 11, no. 21, pp. 35536-35550, 1 Nov.1, 2024. **(JCR Q1, IF: 8.2)** [Published Version](https://ieeexplore.ieee.org/document/10620242)

**[J5]** **Binggui Zhou**, Xi Yang, Jintao Wang, Shaodan Ma, Feifei Gao, and Guanghua Yang, “A Low-Overhead Incorporation-Extrapolation Based Few-Shot CSI Feedback Framework for Massive MIMO Systems,” **IEEE Transactions on Wireless Communications**, vol. 23, no. 10, pp. 14743-14758, Oct. 2024.  **(JCR Q1, IF: 8.9)** [Published Version](https://ieeexplore.ieee.org/document/10600118) \| [Preprint](https://arxiv.org/abs/2312.04062)

**[J4]** **Binggui Zhou**, Xi Yang, Shaodan Ma, Feifei Gao, and Guanghua Yang, “Pay Less But Get More: A Dual-Attention-based Channel Estimation Network for Massive MIMO Systems with Low-Density Pilots,” **IEEE Transactions on Wireless Communications**, vol. 23, no. 6, pp. 6061-6076, Jun. 2024. **(JCR Q1, IF: 8.9)** [Published Version](https://ieeexplore.ieee.org/document/10315065) \| [Preprint](https://arxiv.org/abs/2303.00986) \| [Code](https://github.com/bgzhou/DACEN)

**[J3]** Xi Yang\*, Fuqiang Zhu, **Binggui Zhou**\*, Ting Liu, and Shaodan Ma, “Gridless Hybrid-Field Channel Estimation for Extra-Large Aperture Array Massive MIMO Systems,” **IEEE Wireless Communications Letters**, vol. 13, no. 2, pp. 496-500, Feb. 2024. **(JCR Q1, IF: 4.6)** [Published Version](https://ieeexplore.ieee.org/document/10319723)

**[J2]** Xianda Wu, Xi Yang, Shaodan Ma, **Binggui Zhou**, and Guanghua Yang, “Hybrid Channel Estimation for UPA-Assisted Millimeter-Wave Massive MIMO IoT Systems,” **IEEE Internet of Things Journal**, vol. 9, no. 4, pp. 2829-2842, Feb. 2022. **(JCR Q1, IF: 8.2)** [Published Version](https://ieeexplore.ieee.org/abstract/document/9475482) 

**[J1]** Xiaohong Chen, Changxing Deng, **Binggui Zhou**, Huan Zhang, Shaodan Ma, and Guanghua Yang, “High-Accuracy CSI Feedback with Super-Resolution Network for Massive MIMO Systems,” **IEEE Wireless Communications Letters**, vol. 11, no. 1, pp. 141-145, Jan. 2022. **(JCR Q1, IF: 4.6)** [Published Version](https://ieeexplore.ieee.org/abstract/document/9585309) \| [Code](https://github.com/MoliaChen/SRNet)

**[C3]** Weiqiang Tan, Minwei Zhang, Jintao Wang, **Binggui Zhou**, Xiyuan Chen, and Chunguo Li, “Sequence-Model-Based Joint CSI Feedback and Dynamic Multiuser Precoding for FDD Massive MIMO Systems,“ in **Proceedings of IEEE INFOCOM WKSHPS**, pp. 1-6, 2026.

**[C2]** Kehui Li, **Binggui Zhou**, Jiajia Guo, Xi Yang, Qing Xue, Feifei Gao, and Shaodan Ma, “Vision-aided Multi-user Beam Tracking for mmWave Massive MIMO System: Prototyping and Experimental Results,” in **Proceedings of IEEE Vehicular Technology Conference: VTC2024-Spring**, pp. 1-6, 2024.

**[C1]** **Binggui Zhou**, Shaodan Ma, and Guanghua Yang, “Transformer-based CSI Feedback with Hybrid Learnable Non-Uniform Quantization for Massive MIMO Systems,” in **Proceedings of 2023 32nd Wireless and Optical Communications Conference (WOCC)**, pp. 1-5, 2023.

**[P3]** Shaodan Ma, Xi Yang, Chengzhi Ma, **Binggui Zhou**, and Jintao Wang. “An Enhanced Distributed Hybrid RIS Based Wireless Communication System,” **Chinese Patent Application**, Sep. 2024.

**[P2]** Shaodan Ma, Xi Yang, Chengzhi Ma, **Binggui Zhou**, and Jintao Wang. “A Distributed Hybrid RIS Based Wireless Communication System,” **Chinese Patent Grant**, CN116056118B, Mar. 2025.

**[P1]** Shaodan Ma, Changxing Deng, Xiaohong Chen, Huan Zhang, and **Binggui Zhou**. “Compression Methods, Reconstruction Methods, Devices, and Computer Equipments for Channel State Information,” **Chinese Patent Grant**, CN113938952B, Oct. 2023.

### <font color=CornflowerBlue>Machine Learning and Data Science</font>

<!-- **[J5]** Yunxuan Dong, **Binggui Zhou**, and Guanghua Yang, “Dynamic Spatial-temporal Wind Power Forecasting with a Novel Attention Mechanism,” submitted to **IEEE Internet of Things Journal**. -->

**[J5]** Yunxuan Dong, **Binggui Zhou**, Hongcai Zhang, Guanghua Yang, and Shaodan Ma, “A Deep Time-Frequency Augmented Wind Power Forecasting Model,” **Renewable Energy**, vol. 256, p. 123550, Jan. 2026. **(JCR Q1, IF: 9.0)** [Published Version](https://www.sciencedirect.com/science/article/pii/S0960148125012121)

**[J4]** **Binggui Zhou**, Guanghua Yang, Zheng Shi, and Shaodan Ma, “Natural Language Processing for Smart Healthcare,” **IEEE Reviews in Biomedical Engineering**, vol. 17, pp. 4-18, Jan. 2024. **(JCR Q1, IF: 17.2, ESI Hot Paper, ESI Highly Cited Paper, and Popular Article & Featured Article of IEEE Reviews in Biomedical Engineering)** [Published Version](https://ieeexplore.ieee.org/abstract/document/9904944) \| [Preprint](https://arxiv.org/abs/2110.15803)

**[J3]** Yunxuan Dong&dagger;, **Binggui Zhou**&dagger;, Guanghua Yang, Fen Hou, Zheng Hu, and Shaodan Ma, “A Novel Model for Tourism Demand Forecasting with Spatial–Temporal Feature Enhancement and Image-Driven Method,” **Neurocomputing**, vol. 556, p. 126663, Nov. 2023. **(JCR Q1, IF: 6.0)** [Published Version](https://www.sciencedirect.com/science/article/pii/S0925231223007865)

**[J2]** **Binggui Zhou**, Yunxuan Dong, Guanghua Yang, Fen Hou, Zheng Hu, Suxiu Xu, and Shaodan Ma, “A Graph-Attention Based Spatial-Temporal Learning Framework for Tourism Demand Forecasting,” **Knowledge-Based Systems**, vol. 263, p. 110275, Mar. 2023. **(JCR Q1, IF: 7.2)** [Published Version](https://www.sciencedirect.com/science/article/pii/S0950705123000254) 

**[J1]** **Binggui Zhou**, Guanghua Yang, Zheng Shi, and Shaodan Ma, “Interpretable Temporal Attention Network for COVID-19 Forecasting,” **Applied Soft Computing**, vol. 120, p. 108691, May 2022. **(JCR Q1, IF: 7.2)** [Published Version](https://www.sciencedirect.com/science/article/pii/S1568494622001545)

<!-- **[C3]** Yunxuan Dong, **Binggui Zhou**, and Guanghua Yang, “Dynamic Learning of Key Locations for Enhancing Spatial-Temporal Tourism Demand Forecasting,” submitted to **SIGKDD 2024**.  -->
<!-- [<font color=Blue>\[Open Review\]</font>](https://arxiv.org/abs/2309.10575) -->

**[C2]** Yunxuan Dong, **Binggui Zhou**, Guanghua Yang, Fen Hou, and Shaodan Ma, “A Spatial-temporal Model for Tourism Demand Forecasting,” in **Proceedings of 2021 IEEE 19th Int Conf on Smart City (SmartCity)**, pp. 1810-1814, 2021.

**[C1]** Nan Lin, **Binggui Zhou**, Guanghua Yang, and Shaodan Ma, “Multi-head Attention Networks for Nonintrusive Load Monitoring,” in **Proceedings of 2020 IEEE International Conference on Signal Processing, Communications and Computing (ICSPCC)**, pp. 1-5, 2020.

**[P1]** **Binggui Zhou**, Guanghua Yang, Zheng Shi, Suxiu Xu, Zheng Hu, and Haitao Jiang. “A Spatial-temporal Tourism Demand Forecasting Method Based on Graph Convolution and Attention Mechanism,” **Chinese Patent Grant**, CN115438837B, Sep. 2025.

<!-- ### <font color=CornflowerBlue>Smart Healthcare</font>

**[J1]** **Binggui Zhou**, Guanghua Yang, Zheng Shi, and Shaodan Ma, “Natural Language Processing for Smart Healthcare,” **IEEE Reviews in Biomedical Engineering**, vol. 17, pp. 4-18, Jan. 2024. **(JCR Q1, IF: 17.2, ESI Hot Paper, ESI Highly Cited Paper, and Popular Article & Featured Article of IEEE Reviews in Biomedical Engineering)** [Published Version](https://ieeexplore.ieee.org/abstract/document/9904944) \| [Preprint](https://arxiv.org/abs/2110.15803) -->

### <font color=CornflowerBlue>Miscellaneous</font>

**[J1]** **Binggui Zhou**, Qingkai Liu, and Ju Qiu. “Indoor IoT Security System Based on Raspberry Pi and WeChat,” **Transducer and Microsystem Technologies**, vol. 36, no. 11, pp. 109-111+122, Nov. 2017. **(Chinese Science Citation Database (CSCD))**

**[C1]** **Binggui Zhou**, Guanghua Yang, and Shaodan Ma, “Product-oriented Product Service System for Large-scale Vision Inspection,” in **Procedia CIRP**, vol. 83, pp. 675-679, 2019.