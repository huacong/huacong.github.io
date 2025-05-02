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


<!-- I am also lucky to have opportunities to collaborate with [Zhiyong Yang (杨智勇)](https://joshuaas.github.io/) (Assistant Professor at UCAS) and [Yangbangyan Jiang (姜阳邦彦)](https://jiangyangby.github.io/) (Postdoc at UCAS). -->

<!-- # 🔥 News
- *2022.11*: &nbsp;🎉🎉 I have obtained the National Scholarship (国家奖学金) from the Ministry of Education of the People’s Republic of China.
- *2022.09*: &nbsp;🎉🎉 Two of our papers have been accepted by NeurIPS 2022 (One paper has been selected as an oral presentation and one is a poster). 
- *2022.06*: &nbsp;🎉🎉 Our XCurve-v1.0.0 library has been released! Please Try now and give us feedback! -->

# 📝 Publications 


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2025</div><img src='images/openworldauc.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**<font size=4>OpenworldAUC: Towards Unified Evaluation and Optimization for Open-world Prompt Tuning</font>**

**Cong Hua**, Qianqian Xu<sup>\*</sup>, Zhiyong Yang, Zitai Wang, Shilong Bao, Qingming Huang<sup>\*</sup>

International Conference on Machine Learning (**ICML**) 2025

[\[Paper\]](https://huacong.github.io/) \|[\[Code\]](https://huacong.github.io/) \| [\[Project\]](https://huacong.github.io/)

- A novel metric named **OpenworldAUC** is proposed for the Open-world Prompt Tuning (OPT) task, which embraces base-to-new detection, base classification, and new classification in a **unified** way and is also insensitive towards varying domain distributions. To pursue this, a learning framework, Gated Mixture-of-Prompts (GMoP), is proposed with a theoretical guarantee, where multiple prompts jointly optimize OpenworldAUC via a divide-and-conquer strategy.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2024</div><img src='images/ReconBoost.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**<font size=4>ReconBoost: Boosting Can Achieve Modality Reconcilement</font>**

**Cong Hua**, Qianqian Xu<sup>\*</sup>, Shilong Bao, Zhiyong Yang, Qingming Huang<sup>\*</sup>

International Conference on Machine Learning (**ICML**) 2024

[\[Paper\]](https://arxiv.org/pdf/2405.09321) \|[\[Code\]](https://github.com/huacong/ReconBoost) \| [\[Project\]](https://github.com/huacong/ReconBoost)

- This paper explores a novel multi-modal **alternating** learning paradigm pursuing a reconciliation between the exploitation of uni-modal features and the exploration of cross-modal interactions.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TNNLS 2023</div><img src='images/HSR.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**<font size=4>Hierarchical Set-to-set Representation for 3D Cross-modal Retrieval</font>**

Yu Jiang, **Cong Hua**, Yifan Feng, Yue Gao<sup>\*</sup>. (Student first author)

IEEE Transactions on Neural Networks and Learning Systems (**IEEE TNNLS**) 2023

[\[Paper\]](https://ieeexplore.ieee.org/document/10316653) \|[\[Code\]](https://github.com/huacong/HSR) \| [\[Project\]](https://github.com/huacong/HSR)

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SHREC'22</div><img src='images/3DOS.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**<font size=4>SHREC'22 Track: Open-Set 3D Object Retrieval</font>**

$28$ authors including **Cong Hua**. Computers Graphics 2022

[\[Paper\]](https://doi.org/10.1016/j.cag.2022.07.020) \|[\[Track\]](https://www.moon-lab.tech/shrec22) 


- This paper reports the results of the SHREC’22 track: Open-Set 3D Object Retrieval, the goal of which is to evaluate the performance of different retrieval algorithms under the Open-Set setting and modality-missing setting, respectively. 
</div>
</div>


# 📖 Academic Services
**Conferences**

 - *NeurIPS*: Reviewer (2024, 2025)
 - *ICLR*: Reviewer (2025)
 - *AISTATS*: Reviewer (2025)
 - *ICML*: Reviewer (2025)
   
**Journals**

 - IEEE Transactions on Multimedia (T-MM): Reviewer
 - IEEE Transactions on Neural Networks and Learning Systems (IEEE TNNLS): Reviewer
 - IEEE Transactions on Circuits and Systems for Video Technology publication information (T-CSVT): Reviewer
 - ACM Transactions on Multimedia Computing, Communications and Applications (TOMM): Reviewer


 # 💬 Invited Talks & Presentations
- *2024.12*: &nbsp; TechBeat Talk of ICML 2024. [\[Video\]](https://www.techbeat.net/talk-info?id=932).
- *2024.12*: &nbsp; Gave a talk about "Modality competition and Modality reconcilement" @ Gaoling School of Artificial Intelligence, Renmin University of China! Thanks for the invitation from Prof. [Di Hu](https://dtaoo.github.io/)! [\[Slides\]](https://github.com/huacong/ReconBoost/blob/main/Reconboost-slides.pdf).
- *2024.12*: &nbsp; Young Scientists Conference of CSIG. [\[Poster\]](https://github.com/huacong/ReconBoost/blob/main/%E5%8D%8E%E8%81%AA_CSIG2024_Poster.png).


# 🎖 Honors and Awards
- *2023* Excellent graduate thesis of Jilin University. (吉林大学优秀毕业论文)
- *2023* Excellent graduate of Jilin University. (吉林大学优秀毕业生) 

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
