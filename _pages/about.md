---
permalink: /
title: ""
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

I am an Algorithm Engineer in the Vision AI Department, Meituan. Before that, I received my M.S. degree from the School of Computer Science and Engineering, Beihang University in 2022, supervised by Prof. [**Xingxing Wei**](https://sites.google.com/site/xingxingwei1988/) and Prof. [**Bo Li**](https://scse.buaa.edu.cn/info/1078/5211.htm).
I obtained my B.E. degree from the School of Computer Science at Xidian University in 2019, ranking first among 600 students.

<div style="display:none">
I was a research intern from June, 2021 to September, 2021 in the [TAJI](https://yc.alibaba.com/taji#/home) team of Alibaba Security Department, advised by [Yining Lang](https://scholar.google.com/citations?user=b8grj9MAAAAJ), [Dr. Yuan He](https://scholar.google.com/citations?user=cWbXLzgAAAAJ&hl=zh-CN), and [Dr. Hui Xue](https://scholar.google.com/citations?user=lrf-wkQAAAAJ&hl=en). From August, 2020 to June, 2021, I was the project student leader of [Rhinoceros Bird Project](https://ur.tencent.com/talent/program) of Tencent.
</div>

My research interests are primarily on face video generation, deepfake detection, and adversarial machine learning (especially real-world physical attacks on face recognition). Recently, I work on the application of video generation in the field of portraits, including but not limited to img2video, 2D head generation, face animation, face swapping, and Sync-lip generation.

# 💻 Working Experience
- *2022.03 - present*, Algorithm Engineer @ Vision AI Department, [Meituan](https://www.meituan.com/). 
- *2021.06 - 2021.09*, Research Intern @ [TAJI team](https://yc.alibaba.com/taji#/home), Security Department, Alibaba. \\
  advised by [Yining Lang](https://scholar.google.com/citations?user=b8grj9MAAAAJ), Dr. [Yuan He](https://scholar.google.com/citations?user=cWbXLzgAAAAJ&hl=zh-CN), and Dr. [Hui Xue](https://scholar.google.com/citations?user=lrf-wkQAAAAJ&hl=en).
- *2020.08 - 2021.06*, Project Student Leader @ Blade team, TEG, [Tencent](https://www.tencent.com/en-us/about.html). \\
   [Rhinoceros Bird Project](https://ur.tencent.com/talent/program), the project theme is analysis of face verification security.

# 🔥 News
- *2024.03*: &nbsp;🎉🎉 Two papers on Head Generation and Audio-Visual Segmentation are accepted to CVPR 2024.
- *2023.11*: I will serve as a reviewer for CVPR 2024.
- *2023.07*: &nbsp;🎉🎉 One paper on deepfake detection is accepted to ICCV 2023. 

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TPAMI 2022</div><img src='images/advsticker2.png' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">
[Adversarial sticker: A stealthy attack method in the physical world]((https://arxiv.org/abs/2104.06728))

Xingxing Wei (Supervisor),  **<u>Ying Guo</u>**, and Jie Yu

_IEEE Transaction on Pattern Analysis and Machine Intelligence (**TPAMI**), 2022_

📃[**Paper**](https://arxiv.org/pdf/2104.06728)     💾[**Code**](https://github.com/jinyugy21/Adv-Stickers_RHDE)     💾[**VALSE**](https://mp.weixin.qq.com/s/fRRpQuV3fB9s0IEVacnkmQ) (<span style="color:red;">Valse2022 Spotlight</span>)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TPAMI 2022</div><img src='images/rl_sticker.png' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">
[Simultaneously Optimizing Perturbations and Positions for Black-box Adversarial Patch Attacks]((https://arxiv.org/abs/2212.12995))

Xingxing Wei (Supervisor),  **<u>Ying Guo</u>**, Jie Yu, Bo Zhang

_IEEE Transaction on Pattern Analysis and Machine Intelligence (**TPAMI**), 2022_

📃[**Paper**](https://arxiv.org/pdf/2212.12995)     💾[**Code**](https://github.com/shighghyujie/newpatch-rl)     💾[**CSIG**](https://mp.weixin.qq.com/s/wiag_5hhyfbAd19s6eXnSw)
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='images/customlistener.png' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">
[CustomListener: Text-guided Responsive Interaction for User-friendly Listening Head Generation]((https://arxiv.org/abs/2403.00274))

Xi liu<sup>#</sup>, **<u>Ying Guo<sup>#+</sup></u>**, Cheng Zhen, Tong Li, Yingying Ao, Pengfei Yan

_IEEE/CVF Conference on Computer Vision and Pattern Recognition (**CVPR**), Seattle, USA, 2024_

(# denotes equal contribution; + indicates project manager)

📃[**Paper**](https://arxiv.org/pdf/2403.00274)     💾[**Homapage**](https://customlistener.github.io/)
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2023</div><img src='images/guidespace.png' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">
[Controllable Guide-Space for Generalizable Face Forgery Detection]((https://openaccess.thecvf.com/content/ICCV2023/html/Guo_Controllable_Guide-Space_for_Generalizable_Face_Forgery_Detection_ICCV_2023_paper.html))

**<u>Ying Guo</u>**, Cheng Zhen, Pengfei Yan

_International Conference on Computer Vision (**ICCV**), Paris, France, 2023_

📃[**Paper**](https://openaccess.thecvf.com/content/ICCV2023/html/Guo_Controllable_Guide-Space_for_Generalizable_Face_Forgery_Detection_ICCV_2023_paper.html)
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TPAMI 2022_arxiv</div><img src='images/meaningful_sticker.png' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">
[Meaningful adversarial stickers for face recognition in physical world]((https://arxiv.org/abs/2104.06728v1))

**<u>Ying Guo</u>**, Xingxing Wei, Guoqiu Wang, Bo Zhang

_arXiv preprint. Full version accepted by **TPAMI** 2022_

📃[**Paper**](https://arxiv.org/pdf/2104.06728v1) 
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPRW 2022</div><img src='images/sf_deepfake.png' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">
[More generalized DFD: Model matters, so does data representation]((https://arxiv.org/pdf/2207.13505))

**<u>Ying Guo</u>**, Yingying Ao, Pengfei Gao

_IEEE Computer Society workshop on Biometrics at **CVPR**, 2022_

📃[**Paper**](https://arxiv.org/pdf/2207.13505)

- Won the 3-rd place in Multi-Forgery Detection Challenge held in CVPR 2022.
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">INS 2020</div><img src='images/attribute.png' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">
[Black-box adversarial attacks by manipulating image attributes]((https://www.sciencedirect.com/science/article/abs/pii/S0020025520310239))

Xingxing Wei (Supervisor),  **<u>Ying Guo</u>**, Bo Li 

_Information Sciences (**INS**), 2020_

📃[**Paper**](https://www.sciencedirect.com/science/article/abs/pii/S0020025520310239) 
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPRW 2021</div><img src='images/r-dti-fgsm.png' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">
[Improving adversarial transferability with gradient refining]((https://arxiv.org/abs/2105.04834))

Guoqiu Wang<sup>#</sup>, Huanqian Yan<sup>#</sup>, **<u>Ying Guo</u><sup>#</sup>**, Xingxing Wei

_Adversarial Machine Learning workshop on unrestricted attacks at **CVPR**, 2021_

📃[**Paper**](https://arxiv.org/pdf/2105.04834)

- Won the 2-nd place in attack success rates in Unrestricted Adversarial Attacks Challenge held in CVPR 2021.
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='images/avs.png' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">
[Cooperation Does Matter: Exploring Multi-Order Bilateral Relations for Audio-Visual Segmentation]((https://arxiv.org/abs/2312.06462))

Qi Yang, Xing Nie, Tong Li, Pengfei Gao, **<u>Ying Guo</u>**, Cheng Zhen, Pengfei Yan, Shiming Xiang

_IEEE/CVF Conference on Computer Vision and Pattern Recognition (**CVPR**), Seattle, USA, 2024_

📃[**Paper**](https://arxiv.org/pdf/2312.06462)     💾[**Homapage**](https://yannqi.github.io/AVS-COMBO/)     💾[**Code**](https://github.com/yannqi/COMBO-AVS) 

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TOMM 2024</div><img src='images/hanqin.png' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">
[Audio-Visual Contrastive Pre-train for Face Forgery Detection]((https://dl.acm.org/doi/abs/10.1145/3651311))

Hanqing Zhao, Wenbo Zhou, Dongdong Chen, Weiming Zhang, **<u>Ying Guo</u>**, Zhen Cheng, Pengfei Yan, Nenghai Yu

_ACM Transactions on Multimedia Computing, Communications, and Applications (**TOMM**), 2024_

📃[**Paper**](https://dl.acm.org/doi/abs/10.1145/3651311)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICME 2023</div><img src='images/drnet.png' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">
[DR-Net: Multi-View Face Synthesis by Dual Representation]((https://ieeexplore.ieee.org/abstract/document/10219741))

Xianliang Huang, Yining Lang, **<u>Ying Guo</u>**, Yuan He, Hui Xue, Li Zhao, Shuigeng Zhou

_IEEE International Conference on Multimedia and Expo (**ICME**), 2023_

📃[**Paper**](https://ieeexplore.ieee.org/abstract/document/10219741)
</div>
</div>



# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.
