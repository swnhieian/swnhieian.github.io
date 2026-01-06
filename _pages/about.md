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

<span class='anchor' id='about-me'></span>

I am an assistant researcher in the Department of Computer Science and Technology at Tsinghua University. I received my bachelor’s and doctorate degrees from Tsinghua University in 2016 and 2021. My research focuses on **intelligent human-computer interaction**, including **text entry**, **context-aware technology**, **wearable devices**, and **accessibility**. I proposed a Bayesian model of finger movement control ability, which has been used as a critical feature in the Sogou input method. This method now benefits over 600 million users, facilitating the input of approximately 90 billion words daily, and has markedly enhanced recall and correction click rate. I also proposed the world’s first smart keyboard for visually impaired people, significantly reducing the input error rate. I have won the ACM CHI Honorable Mention Award and the first prize in the China Human-Factors Engineering Design Competition.

<!-- Weinan Shi is an assistant researcher in the Department of Computer Science and Technology at Tsinghua University. He received his bachelor's and doctorate degrees from Tsinghua University in 2016 and 2021. His research focuses on **intelligent human-computer interaction**, including **text entry**, **context-aware technology**, **wearable devices**, and **accessibility**. He proposed a Bayesian model of finger movement control ability, which has been used as a critical feature in the Sogou input method. This method now benefits over 600 million users, facilitating the input of approximately 90 billion words daily, and has markedly enhanced recall and correction click rate. He also proposed the world's first smart keyboard for visually impaired people, significantly reducing the input error rate. He won the ACM CHI Honorable Mention Award and the first prize in the China Human-Factors Engineering Design Competition. -->  

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=CngLjRkAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=CngLjRkAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- *2024.10*: &nbsp;🎉🎉 Two papers are accepted by IMWUT 2024. 
- *2024.10*: &nbsp;🎉🎉 Our smart ring is exhibited on [Lenovo Tech World 2024](https://www.lenovo.com/us/en/events/techworld/?srsltid=AfmBOooAuR1-wjHR2lAeneZNXpWOy1nSUQ6SbrQ9lf3xdXp3LlttRxNA). See introduction in this [video]({{ "/assets/videos/techworld.webm" | relative_url }}).

# 📝 Publications 

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div> -->

- `UbiComp 2025` [τ-Ring: A Smart Ring Platform for Multimodal Physiological and Behavioral Sensing](https://dl.acm.org/doi/abs/10.1145/3714394.3756252), Jiankai Tang, Zhe He, Mingyu Zhang, Wei Geng, Chengchi Zhou, **Weinan Shi**, Yuanchun Shi, Yuntao Wang
- `UIST 2025` [InterQuest: A Mixed-Initiative Framework for Dynamic User Interest Modeling in Conversational Search](https://dl.acm.org/doi/abs/10.1145/3746059.3747753), Yu Mei, Yuanxi Wang, Shiyi Wang, Qingyang Wan, Zhuojun Li, Chun Yu, **Weinan Shi\***, Yuanchun Shi
- `CHI 2025` [From Operation to Cognition: Automatic Modeling Cognitive Dependencies from User Demonstrations for GUI Task Automation](https://dl.acm.org/doi/abs/10.1145/3706598.3713356), Yiwen Yin, Yu Mei, Chun Yu, Toby Jia-Jun Li, Aamir Khan Jadoon, Sixiang Cheng, **Weinan Shi**, Mohan Chen, Yuanchun Shi
- `CHI 2025` [Investigating Context-Aware Collaborative Text Entry on Smartphones using Large Language Models](https://dl.acm.org/doi/full/10.1145/3706598.3713944), Weihao Chen, Yuanchun Shi, Yukun Wang, **Weinan Shi\***, Meizhu Chen, Cheng Gao, Yu Mei, Yeshuang Zhu, Jinchao Zhang, Chun Yu
- `ToCHI 2025` [Prompt2Task: Automating UI Tasks on Smartphones from Textual Prompts](https://dl.acm.org/doi/abs/10.1145/3716132), Tian Huang, Chun Yu, **Weinan Shi**, Zijian Peng, David Yang, Weiqi Sun, Yuanchun Shi
- `IMWUT 2024` [AngleSizer: Enhancing Spatial Scale Perception for the Visually Impaired with an Interactive Smartphone Assistant](https://dl.acm.org/doi/abs/10.1145/3678525), Xiaoqing Jing, Chun Yu, Kun Yue, Liangyou Lu, Nan Gao, **Weinan Shi\***, Mingshan Zhang, Ruolin Wang, Yuanchun Shi
- `IMWUT 2024` [EasyAsk: An In-App Contextual Tutorial Search Assistant for Older Adults with Voice and Touch Inputs](https://dl.acm.org/doi/abs/10.1145/3678516), Weiwei Gao, Kexin Du, Yujia Luo, **Weinan Shi\***, Chun Yu, Yuanchun Shi
- `CHI 2024` [ContextCam: Bridging Context Awareness with Creative Human-AI Image Co-Creation](https://dl.acm.org/doi/abs/10.1145/3613904.3642129), Xianzhe Fan, Zihan Wu, Chun Yu, Fenggui Rao, **Weinan Shi\***, Teng Tu
- `Preprint` [PromptRPA: Generating Robotic Process Automation on Smartphones from Textual Prompts](https://arxiv.org/abs/2404.02475), Tian Huang, Chun Yu, **Weinan Shi**, Zijian Peng, David Yang, Weiqi Sun, Yuanchun Shi
- `UIST 2023` [From Gap to Synergy: Enhancing Contextual Understanding through Human-Machine Collaboration in Personalized Systems](https://dl.acm.org/doi/abs/10.1145/3586183.3606741), Weihao Chen, Chun Yu, Huadong Wang, Zheng Wang, Lichen Yang, Yukun Wang, **Weinan Shi**, Yuanchun Shi
- `IMWUT 2023` [Interaction Proxy Manager: Semantic Model Generation and Run-time Support for Reconstructing Ubiquitous User Interfaces of Mobile Services](https://dl.acm.org/doi/abs/10.1145/3610929), Tian Huang, Chun Yu, **Weinan Shi**, Bowen Wang, David Yang, Yihao Zhu, Zhaoheng Li, Yuanchun Shi
- `CHI 2019` [VIPBoard: Improving screen-reader keyboard for visually impaired people with character-level auto correction](https://dl.acm.org/doi/abs/10.1145/3290605.3300747), **Weinan Shi***, , Chun Yu, Shuyi Fan, Feng Wang, Tong Wang, Xin Yi, Xiaojun Bi, Yuanchun Shi `Honorable Mention Award`
- `IMWUT 2018` [TOAST: Ten-finger eyes-free typing on touchable surfaces](https://dl.acm.org/doi/abs/10.1145/3191765), **Weinan Shi**, Chun Yu, Xin Yi, Zhen Li, Yuanchun Shi
- `UIST 2018` [Lip-interact: Improving mobile device interaction with silent speech commands](https://dl.acm.org/doi/abs/10.1145/3242587.3242599), Ke Sun, Chun Yu, **Weinan Shi**, Lan Liu, Yuanchun Shi
- `IJHCS 2017` [Is it too small?: Investigating the performances and preferences of users when typing on tiny QWERTY keyboards](https://www.sciencedirect.com/science/article/pii/S1071581917300654), Xin Yi, Chun Yu, **Weinan Shi**, Yuanchun Shi
- `CHI 2017` [Word clarity as a metric in sampling keyboard test sets](https://dl.acm.org/doi/abs/10.1145/3025453.3025701), Xin Yi, Chun Yu, **Weinan Shi**, Xiaojun Bi, Yuanchun Shi

# 🎖 Honors and Awards
- *2024.10* Third prize in Ubiquitous Intelligent Sensing Technology Innovation Application Competition
- *2021.06* Outstanding Graduate, Department of CS, Tsinghua University
- *2021.04* Second prize in "Challenge Cup" Academic Science and Technology Works Competition, Tsinghua University
- *2020.10* First prize in the China Human-Factors Engineering Design Competition
- *2019.10* National Scholarship, Ministry of Education, China
- *2019.09* First prize in 84 "Future Innovation" Scholarship (Only 1), Department of CS, Tsinghua University
- *2019.05* Honorable Mention Award (Top 5%), ACM CHI 2019
- *2019.01* Qingfeng Scholarship, Tsinghua University
- *2016.06* Outstanding Graduate, Department of CS, Tsinghua University


# 📖 Experience
- *2023.08 -  Present*, Assistant Researcher, Department of Computer Science and Technology, Tsinghua University.
- *2021.07 - 2023.07*, Postdoctoral Researcher, Department of Computer Science and Technology, Tsinghua University.
- *2016.09 - 2021.06*, Ph.D., Department of Computer Science and Technology, Tsinghua University. 
- *2013.09 - 2016.06*, B.Econ., School of Economics and Management, Tsinghua University.
- *2012.09 - 2016.06*, B.E., Department of Computer Science and Technology, Tsinghua University.

# 💬 Invited Talks
- *2024.10*, Smart Human Computer Interaction Based on Context Awareness. China Graph 2024. 
- *2024.08*, Understanding Context in Natural Human-Computer Interaction Using Large Language Models. HCIX Project. 
- *2024.06*, Natural Human-Computer Interaction Technology Based on Context Awareness. Usability Engineering course, Academy of Arts & Design, Tsinghua Univerisity.
- *2024.03*, Natural Human-Computer Interaction Technology Based on Context Awareness. Workshop, MSRA.

<!-- # 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->