---
permalink: /
title: "Jianxiong Zhou's Homepage"
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

**Greetings from Evanston.** 

I am currently a fourth-year Ph.D. student at Northwestern University under the supervision of [Prof. Ying Wu](http://users.ece.northwestern.edu/~yingwu/). I am interested in computer vision, multi-modality, embodied AI, and vision-language models. My current research areas are <ins>**multi-modality**</ins> and <ins>**embodied AI**</ins>, especially active visual recognition with vision-language understanding, which integrates intelligent control strategies into the visual recognition process to solve various recognition challenges.
I am constantly investigating the challenges inherent to active vision agents in an open-world context. These challenges include, but are not limited to, *multi-modality*, *vision-language models*, and *few-sample learning*.

In addition to embodied AI, I also have project experience in other real-world vision challenges, including temporal action localization, anomaly detection, and medical image analysis. 

My detailed resume/CV is [here](./files/JianxiongZhou_Resume_Sep_2024.pdf) (last updated on September 2024).

# 🔥 News
- *2024.05*: &nbsp;🎉🎉 Our paper *Outlier-Probability-Based Feature Adaptation for Robust Unsupervised Anomaly Detection on Contaminated Training Data* has been accepted by IEEE Transactions on Circuits and Systems for Video Technology!
- *2024.02*: &nbsp;🎉🎉 Our paper *Active Open-Vocabulary Recognition: Let Intelligent Moving Mitigate CLIP Limitations* has been accepted by CVPR 2024!

# 📖 Educations
- *2021.09 - 2025.06 (expected)*, Ph.D. cadidate in Electrical Engineering, advised by [Prof. Ying Wu](http://users.ece.northwestern.edu/~yingwu/), Northwestern University.
- *2019.09 - 2021.03*, M.S. in Electrical Engineering, advised by [Prof. Jenq-Neng Hwang](https://people.ece.uw.edu/hwang/), University of Washington.
- *2015.09 - 2019.07*, B.S. in Information Engineering, Shanghai Jiao Tong University. 

# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='images/overview/AOVR.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Active Open-Vocabulary Recognition: Let Intelligent Moving Mitigate CLIP Limitations](https://openaccess.thecvf.com/content/CVPR2024/html/Fan_Active_Open-Vocabulary_Recognition_Let_Intelligent_Moving_Mitigate_CLIP_Limitations_CVPR_2024_paper.html)

Lei Fan, **Jianxiong Zhou**, Xiaoying Xing, Ying Wu

[**Video**](./files/cvpr24_supp.mp4) <strong><span class='' data=''></span></strong> |
[**Supplementary**](./files/cvpr24_supp.pdf) <strong><span class='' data=''></span></strong>
- Investigate CLIP's limitations in embodied perception scenarios, emphasizing diverse viewpoints and occlusion degrees.
- Propose an active agent to mitigate CLIP's limitations, aiming for active open-vocabulary recognition.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TCSVT 2024</div><img src='images/overview/TCSVT24.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Outlier-Probability-Based Feature Adaptation for Robust Unsupervised Anomaly Detection on Contaminated Training Data](https://ieeexplore.ieee.org/document/10542974)

**Jianxiong Zhou**, Ying Wu

- Propose a robust unsupervised anomaly detection method OPFA that can mitigate the influence of contaminated training data and improve the detection of anomalous samples.
- OPFA improves features by contracting normal features and contrasting normal features with outlier features, allowing it to outperform other methods in contaminated data scenarios.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">PRL 2024</div><img src='images/overview/PRL24.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Micro-expression spotting with a novel wavelet convolution magnification network in long videos](https://www.sciencedirect.com/science/article/pii/S0167865524000035)

**Jianxiong Zhou**, Ying Wu

- Our approach combines wavelet decomposition and a learnable motion magnification module to enhance the optical flow features of micro-expressions, making them easy to detect.
- We design a selective magnification attention module to suppress background disturbances and highlight MEs. The ablation study and visualization results show that it works as expected.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">WACV 2023</div><img src='images/overview/wacv23.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Temporal Feature Enhancement Dilated Convolution Network for Weakly-supervised Temporal Action Localization](https://openaccess.thecvf.com/content/WACV2023/html/Zhou_Temporal_Feature_Enhancement_Dilated_Convolution_Network_for_Weakly-Supervised_Temporal_Action_WACV_2023_paper.html)

**Jianxiong Zhou**, Ying Wu

[**Video**](./files/wacv23-supp.mp4) <strong><span class='' data=''></span></strong> |
[**Supplementary**](./files/wacv23-supp.pdf) <strong><span class='' data=''></span></strong> |
[**Poster**](./files/wacv23-poster.pdf) <strong><span class='' data=''></span></strong>
- The proposed TFE-DCN has an enlarged receptive field that covers a long temporal span to observe the full dynamics of action instances, making it powerful to capture temporal dependencies between snippets.
- The Modality Enhancement Module can enhance RGB features with enhanced optical flow features to make the overall features suitable for the WTAL task.
</div>
</div>

- [Hierarchical Pose Classification for Infant Action Analysis and Mental Development Assessment](https://ieeexplore.ieee.org/abstract/document/9415088), **Jianxiong Zhou**, Zhongyu Jiang, Jang-Hee Yoo, and Jenq-Neng Hwang, accepted by International Conference on Acoustics, Speech, and Signal Processing (ICASSP), 2021.

- [State‐of‐charge estimation for LiNi0. 6Co0. 2Mn0. 2O2/graphite batteries using the compound method with improved extended Kalman filter and long short‐term memory network](https://onlinelibrary.wiley.com/doi/full/10.1002/er.6234), Shuai Xu, **Jianxiong Zhou**, Fei Zhou, and Yuchen Liu, accepted by International Journal of Energy Research, 2021.

- [State-of-charge estimation of lithium-ion batteries based on improved H infinity filter algorithm and its novel equalization method](https://www.sciencedirect.com/science/article/pii/S0959652620352240), Zhenggang Chen, **Jianxiong Zhou**, Fei Zhou, and Shuai Xu, accepted by Journal of Cleaner Production, 2021.

- [Unfolded coprime planar array for 2D direction of arrival estimation: An aperture-augmented perspective](https://ieeexplore.ieee.org/abstract/document/8344118), Wang Zheng, Xiaofeng Zhang, Le Xu, and **Jianxiong Zhou**, accepted by IEEE Acess, 2018.

# 💻 Internships
- *2024.06 - 2024.08*, Summer Internship, [Blinkfire Analytics, Inc.](https://www.blinkfire.com/), Chicago, US.<br />
  <span style="color:grey">- Topic: Be responsible for various engineering tasks including computer vision related tasks.</span>
- *2020.06 - 2020.12*, Research Intern, [Information Processing Lab](https://ipl-uw.github.io/index.html), Seattle, US.<br />
  <span style="color:grey">- Topic: Hierarchical pose classification for infant action analysis and mental development assessment.</span><br />
  <span style="color:grey">- Advisors: [Prof. Jenq-Neng Hwang](https://people.ece.uw.edu/hwang/).</span>
- *2019.08 - 2019.09*, Research Intern, Nanjing Zhenchao Technology Co., Ltd., Nanjing, China.<br />
  <span style="color:grey">- Topic: Intelligent audit for documents.</span>

- # 🎖 Honors and Awards
- *2019.07* Outstanding Graduate of Shanghai Jiao Tong University.
- *2019.04* China Electronic Instrument Scholarship, Shanghai Jiao Tong University
- *2018.04* Honorable Mention, Interdisciplinary Contest in Modeling, COMAP
- *2016.11* China National Scholarship.
