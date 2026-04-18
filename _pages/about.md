---
permalink: /
title: ""
excerpt: ""
author_profile: true
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='bio'></span>

Binggui Zhou (周炳贵) received his B.Eng. degree in Electrical Engineering from Jinan University, Zhuhai, China, in 2018, and his M.Sc. degree and Ph.D. degree in Electrical and Computer Engineering from the University of Macau, Macao, China, in 2021 and 2024, respectively, with the State Key Laboratory of Internet of Things for Smart City (SKL-IOTSC) and under the supervision of [Prof. Shaodan Ma (IEEE Senior Member, IEEE ComSoc Distinguished Lecturer, Associate Director of the SKL-IOTSC)](https://www.fst.um.edu.mo/personal/shaodanma/). He is currently a Postdoctoral Research Associate with the Department of Electrical and Electronic Engineering, Imperial College London, London, United Kingdom, working with [Prof. Bruno Clerckx (IEEE Fellow, IEEE ComSoc Distinguished Lecturer)](https://profiles.imperial.ac.uk/b.clerckx). He was a recipient of the European Union's Marie Skłodowska-Curie Actions (MSCA) Postdoctoral Fellowship (2025 call).

Dr. Zhou's research interests include machine learning and data science as well as their applications in wireless communications, wireless sensing, and smart healthcare. He has published more than 20 papers in top-tier journals and flagship international conferences (e.g., IEEE TWC, IEEE TCOM, IEEE RBME, KBS, IEEE IoT-J, IEEE TNSE, IEEE TVT, IEEE WCL). He serves as an Associate Editor for IEEE WCL and as a reviewer for many top-tier journals (e.g., IEEE JSAC, IEEE TWC, IEEE TMC, IEEE TCOM, IEEE WCM, IEEE CM, IEEE TASE, PR, KBS, EAAI). He has served as a General Co-Chair for workshops in IEEE GLOBECOM 2026 and IEEE/CIC ICCC 2026, and as a Technical Program Committee (TPC) member for several flagship international conferences (e.g., IEEE GLOBECOM, IEEE ICC, IEEE VTC).

 <!-- with total <a href='https://scholar.google.com/citations?user=2RwBacMAAAAJ&hl=en'><img src='https://img.shields.io/endpoint?logo=Google%20Scholar&url=https%3A%2F%2Fraw.githubusercontent.com%2Fbgzhou%2Fbgzhou.github.io%2Fgoogle-scholar-stats%2Fgs_data_shieldsio.json&labelColor=f6f6f6&color=9cf&style=flat&label=citations'></a> citations -->

# 🔥 News
- 2026-03-27 **<font color=Blue>New submission</font>**: One co-authored paper titled [Joint Training Scattering Matrix Learning and Channel Estimation for Beyond-Diagonal Reconfigurable Intelligent Surfaces](https://arxiv.org/abs/2603.25299) has been submitted to ***IEEE Transactions on Wireless Communications*** for possible publication.

- 2026-03-05 **<font color=Green>Service</font>**: I have joined the Editorial Board of [***IEEE Wireless Communications Letters***](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=5962382) as an Associate Editor.

- 2026-02-09 **<font color=Orange>Project</font>**: Glad to share that I have been awarded the European Union's **Marie Skłodowska-Curie Actions (MSCA) Postdoctoral Fellowships** during the 2025 call (**success rate: 9.6%**).  I will move to [Delft University of Technology](https://www.tudelft.nl/en/), Netherlands, to start my project: **ISACare - Integrated WiFi Sensing and Communication for Sustainable and Robust Digital Health Monitoring**.

- 2026-02-06 **<font color=Fuchsia>New publication</font>**: One co-authored paper titled [Sequence-Model-Based Joint CSI Feedback and Dynamic Multiuser Precoding for FDD Massive MIMO Systems]() has been accepted to ***IEEE INFOCOM 2026 WORKSHOPS - DeepWireless: Deep Learning for Wireless Communications, Sensing, and Security***.

- 2026-01-08 **<font color=Fuchsia>New publication</font>**: One co-authored paper titled [Intelligent Angle Map-based Beam Alignment for RIS-aided mmWave Communication Networks](https://ieeexplore.ieee.org/document/11347574) has been accepted by ***IEEE Transactions on Network Science and Engineering***.

- 2026-01-05 **<font color=Fuchsia>New publication</font>**: One co-authored paper titled [Out-of-Band Modality Synergy Based Multi-User Beam Prediction and Proactive BS Selection with Zero Pilot Overhead](https://ieeexplore.ieee.org/document/11358948) has been accepted by ***IEEE Transactions on Communciations***.


**[👉 View all news and past updates](/news/)** 


# 🔎 Research Highlights

My research mainly focuses on **Machine Learning and Data Science** as well as their applications in **Wireless Communications, Wireless Sensing, and Smart Healthcare**. 

Recent key projects include:
* Knowledge-and-Data Driven CSI Acquisition
* Machine Learning Empowered Wireless Communications (Prototyping)
<!-- * Natural Language Processing for Smart Healthcare -->

**[👉 Read more about my research frameworks and demo systems](/research/)**
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


**[👉 Read more about my research frameworks and demo systems](/research/)**


# 📝 Selected Publications


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

</div>
</div>

**[👉 View Full List of Publications](/publications/)**
