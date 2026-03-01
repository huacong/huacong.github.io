---
permalink: /
title: ""
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

# About Me 

<span class='anchor' id='about-me'></span> 

Hi! I'm Cong Hua (华聪, E-mail: huacong23z@ict.ac.cn). Now I am a PhD. Student of **Institute of Computing Technology, Chinese Academy of Sciences (ICT, CAS)**, supervised by Prof. [Qingming Huang](https://qmhuang-ucas.github.io/) (IEEE Fellow) and [Qianqian Xu](https://qianqianxu010.github.io/) (Professor at ICT, CAS). I have received the B.E. degree in computer science and technology from [Jilin University](https://www.jlu.edu.cn/), advised by [Yu Jiang](https://ccst.jlu.edu.cn/info/1028/19116.htm) and [Yue Gao](https://www.gaoyue.org/). My research interests include machine learning and multi-modal learning. I have authored or co-authored several academic papers in top-tier international conferences and journals, including ICML and TNNLS. If you are interested in my research, please email me at <a href="huacong23z@ict.ac.cn">huacong23z@ict.ac.cn</a>. 




<!-- # 🔥 News

- *2022.11*: &nbsp;🎉🎉 I have obtained the National Scholarship (国家奖学金) from the Ministry of Education of the People’s Republic of China. 
- *2022.09*: &nbsp;🎉🎉 Two of our papers have been accepted by NeurIPS 2022 (One paper has been selected as an oral presentation and one is a poster). 
- *2022.06*: &nbsp;🎉🎉 Our XCurve-v1.0.0 library has been released! Please try now and give us feedback! -->

# 📝 Publications 


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2025</div><img src='images/openworldauc.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
**<font size=4>OpenworldAUC: Towards Unified Evaluation and Optimization for Open-world Prompt Tuning</font>**

**Cong Hua**, Qianqian Xu<sup>\*</sup>, Zhiyong Yang, Zitai Wang, Shilong Bao, Qingming Huang<sup>\*</sup>

International Conference on Machine Learning (**ICML**) 2025

[\[Paper\]](https://proceedings.mlr.press/v267/hua25d.html) \|[\[Code\]](https://huacong.github.io/) 

- This paper proposes **OpenworldAUC**, a metric for Open-World Prompt Tuning, unifying base-to-new detection, base/new classification, and robustness to domain shifts.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2024</div><img src='images/ReconBoost.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**<font size=4>ReconBoost: Boosting Can Achieve Modality Reconcilement</font>**

**Cong Hua**, Qianqian Xu<sup>\*</sup>, Shilong Bao, Zhiyong Yang, Qingming Huang<sup>\*</sup>

International Conference on Machine Learning (**ICML**) 2024

[\[Paper\]](https://arxiv.org/pdf/2405.09321) \|[\[Code\]](https://github.com/huacong/ReconBoost)

- This paper explores a novel multi-modal **alternating** learning paradigm pursuing a reconciliation between the exploitation of uni-modal features and the exploration of cross-modal interactions.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TNNLS 2023</div><img src='images/HSR.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**<font size=4>Hierarchical Set-to-set Representation for 3D Cross-modal Retrieval</font>**

Yu Jiang, **Cong Hua**, Yifan Feng, Yue Gao<sup>\*</sup>. (Student first author)

IEEE Transactions on Neural Networks and Learning Systems (**IEEE TNNLS**) 2023

[\[Paper\]](https://ieeexplore.ieee.org/document/10316653) \|[\[Code\]](https://github.com/huacong/HSR) \| [\[Project\]](https://github.com/huacong/HSR)

- This paper proposes a hierarchical set-to-set representation  and a corresponding hierarchical similarity that incorporates global-to-global and local-to-local similarity metrics for 3-D object cross-modal retrieval.

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR'26</div><img src='images/OOD.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**<font size=4>Mind the Way You Select Negative Texts:Pursuing the Distance Consistency in OOD Detection with VLMs</font>**

Zhikang Xu, Qianqian Xu<sup>\*</sup>, Zitai Wang, **Cong Hua**, Sicong Li, Zhiyong Yang, Qingming Huang<sup>\*</sup>. 


Conference on Computer Vision and Pattern Recognition (**CVPR**) 2026

[\[Paper\]]() \|[\[Code\]]()

- This paper reveals the inherent inconsistency in existing VLM-based OOD detection methods that rely on intra-modal distances, which contradict the CLIP' original inter-modal optimization objectives. To address this, the proposed method pursues distance consistency by systematically leveraging inter-modal guidance for negative text selection.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI'26</div><img src='images/TUCK.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**<font size=4>TuckA: Hierarchical Compact Tensor Experts for Efficient Fine-Tuning</font>**

Qifeng Lei, Zhiyong Yang<sup>\*</sup>, Qianqian Xu, **Cong Hua**, Peisong Wen, Qingming Huang<sup>\*</sup>. 


Association for the Advancement of Artificial Intelligence (**AAAI**) 2026

[\[Paper\]](https://arxiv.org/pdf/2511.06859) \|[\[Code\]](https://github.com/LQF39466/TuckA)

- This paper proposes a novel **tensor-based PEFT framework** that leverages Tucker decomposition to create a compact ensemble of adaptation experts.
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI'26</div><img src='images/BEP.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**<font size=4>Quantifying the Potential to Escape Filter Bubbles: A Behavior-Aware Measure via Contrastive Simulation</font>**

Difu feng, Qianqian Xu<sup>\*</sup>, Zitai Wang, **Cong Hua**, Zhiyong Yang, Qingming Huang<sup>\*</sup>.

Association for the Advancement of Artificial Intelligence (**AAAI**) 2026

[\[Paper\]](https://arxiv.org/pdf/2512.03067) \|[\[Code\]](https://github.com/fengdifu24/bepmetric)


- This paper introduce Bubble Escape Potential, a novel behavior-aware metric for **measuring filter bubble sever ity by contrastive user behavioral intent**.
</div>
</div>




<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CJC'25</div><img src='images/robustauc.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**<font size=4>Efficient Adversarial Training for AUC Optimization</font>**

Shilong Bao, Qianqian Xu<sup>\*</sup>, Zhiyong Yang, **Cong Hua**, Boyu Han, Xiaochun Cao, Qingming Huang<sup>\*</sup>. Chinese Journal of Computers 2025

[\[Paper\]](https://kns.cnki.net/kcms2/article/abstract?v=RNPVX-4KY7hsOlChNoeEB7PZxZNApTf5MM9Ru5Di7mEAlIuIH4bDlwMPE6O7eyxR54h9THYXD8oJK0WTuRU7oXZD8WjRHjbXmIdxGP8Lq6LJSUPAo7oRMEZemAbYjKYfUW9UG4hdU9G_HrtbIE_TAutiMhu9iHcvNpm_sRm1Llg=&uniplatform=NZKPT)


- This paper presents a systematic investigation of a more generalized and efficient AdAUC framework, introducing a novel Ranking-aware Adversarial Regularization algorithm to achieve a better balance between standard and robust AUC performance.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SHREC'22</div><img src='images/3DOS.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**<font size=4>SHREC'22 Track: Open-Set 3D Object Retrieval</font>**

$28$ authors including **Cong Hua**. Computers and Graphics 2022

[\[Paper\]](https://doi.org/10.1016/j.cag.2022.07.020) \|[\[Track\]](https://www.moon-lab.tech/shrec22) 


- This paper reports the results of the SHREC’22 track: Open-Set 3D Object Retrieval, the goal of which is to evaluate the performance of different retrieval algorithms under the Open-Set setting and modality-missing setting, respectively. 
</div>
</div>

# 🏆 Competitions

**<font size=4>3DCoMPaT Grounded CoMPaT Recognition Challenge (Coarse Track) @ CVPR 2025, 1st Place</font>**

Team: **Cong Hua**, Qianqian Xu, Zitai Wang, Zhiyong Yang, Shilong Bao, Qingming Huang

[\[Website\]](https://3dcompat-dataset.org/workshop/C3DV25/) \| [\[Leaderboard\]](https://eval.ai/web/challenges/challenge-page/2455/leaderboard/6095)


**<font size=4>3DCoMPaT Grounded CoMPaT Recognition Challenge (Fine track) @ CVPR 2025, 1st Place</font>**

Team: Sicong Li, Qianqian Xu, **Cong Hua**, Yangbangyan Jiang, Qingming Huang

[\[Website\]](https://3dcompat-dataset.org/workshop/C3DV25/) \| [\[Leaderboard\]](https://eval.ai/web/challenges/challenge-page/2455/leaderboard/6096) 

# 📖 Academic Services
**Conferences**

 - *NeurIPS*: Reviewer (2024, 2025)
 - *ICLR*: Reviewer (2025, 2026)
 - *AISTATS*: Reviewer (2025, 2026)
 - *ICML*: Reviewer (2025)
 - *CVPR*: Reviewer (2026)
 - *ECCV*: Reviewer (2026)

**Journals**

 - IEEE Transactions on Multimedia (T-MM): Reviewer
 - IEEE Transactions on Neural Networks and Learning Systems (TNNLS): Reviewer
 - IEEE Transactions on Circuits and Systems for Video Technology publication information (T-CSVT): Reviewer
 - ACM Transactions on Multimedia Computing, Communications and Applications (TOMM): Reviewer


# 💬 Invited Talks
- *2025.09* Give a talk at the Graduate Student Academic Forum of the Journal of Image and Graphics (JIG), and receive the **Distinguished Presentation 🏆**. [\[Video\]](https://www.bilibili.com/video/BV1qpxyziE6K/?share_source=copy_web&vd_source=ea077257773f02e483ce2b845ccb3f41)
- *2025.09*: &nbsp; Give a talk at the PhD Student Forum of the CSIG Young Scientists Conference 2025. [\[Website\]](https://mp.weixin.qq.com/s/d8OEev4AejSY9dCW7t9G2Q).
- *2025.05*: &nbsp; Give a talk at the 7th Academic Forum on Artificial Intelligence of Beijing Universities – Workshop on Pattern Recognition and Multimodal Learning, and receive the **Best Student Presentation Award 🏆**. [\[Website\]](https://mp.weixin.qq.com/s/xxkoJ6stNL9KL0jxUpDKTw).
- *2024.12*: &nbsp; TechBeat Talk of ICML 2024. [\[Video\]](https://www.techbeat.net/talk-info?id=932).
- *2024.12*: &nbsp; Give a talk about "Boosting Can Achieve Modality Reconcilement" @ Gaoling School of Artificial Intelligence, Renmin University of China! Thanks for the invitation from Prof. [Di Hu](https://dtaoo.github.io/)! [\[Slides\]](https://github.com/huacong/ReconBoost/blob/main/Reconboost-slides.pdf).
- *2024.12*: &nbsp; Young Scientists Conference of CSIG. [\[Poster\]](https://github.com/huacong/ReconBoost/blob/main/%E5%8D%8E%E8%81%AA_CSIG2024_Poster.png).


# 🎖 Honors and Awards
- Youth Talents Support Project - Doctoral Student Special Program, 2025 December. (中国科协青年人才托举工程-博士生专项)
- Excellent graduate thesis of Jilin University, 2023 June. (吉林大学优秀毕业论文)
- Excellent graduate of Jilin University, 2023 June. (吉林大学优秀毕业生) 

# 🎓 Educations

<div class='school-box'>
<div><img src='images/ucas.jpg' alt="sym" width="80"></div>
<div class='school-box-text' markdown="1">
2023.09 - now, Ph.D. Student.

Institute of Computing Technology, Chinese Academy of Sciences.

University of Chinese Academy of Sciences, Beijing.
</div>
</div>

<div class='school-box'>
<div><img src='images/JLU.png' alt="sym" width="80"></div>
<div class='school-box-text' markdown="1">
2019.09 - 2023.06, Undergraduate.

School of Computer Science and Technology.

Jilin University, Changchun, Jilin.
</div>
</div>

<div class='school-box'>
<div><img src='images/UA.png' alt="sym" width="80"></div>
<div class='school-box-text' markdown="1">
2022.11 - 2023.02, Research internship funded by the China Scholarship Council.

Department of Radiology and Diagnostic Imaging in the Faculty of Medicine and Dentistry.

University of Alberta, Edmonton, Alberta, Canada.
</div>
</div>


<!-- # 💻 Project

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">XCurve</div><img src='images/Xcurve.png' alt="sym" width="120%"></div></div>
<div class='paper-box-text' markdown="1">

*2020.02 - now*: &nbsp; **<font color='red'> As a core member, </font>** I participated in the development of [XCurve: Machine Learning with X-Curve Metrics](https://github.com/statusrank/XCurve). 

- XCurve focuses on **the design criteria of the objective function for ML tasks**, which can be formulated as a series of X-metric (say AUROC, AUPRC, AUTKC) optimization problems considering the **average performance of all decision thresholds** during the training phase. Welcome to try now and give us feedback!
</div>
</div> -->
