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

Welcome to Haoyuan Jiang's Personal Homepage!

I am currently a Ph.D. student at the Technical University of Munich (TUM), where I also work as a Research Assistant. I build AI algorithms at the intersection of reinforcement learning, large foundation models and autonomous agents.

Before joining TUM, I worked as an Algorithm Expert at Alibaba Group and as a Senior Algorithm Engineer at Baidu, focusing on using reinforcement learning to improve model capabilities and performance, which has been used in large foundation models (Qwen and Ernie) and end2end autonomous driving.

I am particularly interested in building autonomous agents capable of reasoning, adaptation, self-improvement and generalization across diverse environments, with a long-term goal of contributing to the development of **AGI**. My research interests include **Reinforcement Learning, General Agentic AI, LLM Reasoning and World model**.


<!-- I worked closely with <a href='https://bonaldli.github.io'>Prof. Ziyue Li</a> at the University of Cologne and Researcher <a href='https://maohangyu.github.io'>Hangyu Mao</a>. -->

[//]: # (op international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> &#40;You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>&#41;)

<!-- In my experiences, I have been investigating how to enable autonomous agents to learn, make decisions in complex environments, and apply them in reality. This includes developing new reinforcement learning algorithms that allow agents to cooperate, easily adapt to new environments and meet industry requirements. -->

If you are interested in my research or experience, please feel free to contact me!

# News
- *2026.06*: &nbsp;🎓🚀 I started a new journey as a Ph.D. student at **TUM**!
- *2026.02*: &nbsp;💼🚀 I joined **Alibaba Group**.
- *2024.05*: &nbsp;🎉🎉 One paper is accepted by **KDD 2024**.
- *2024.04*: &nbsp;🎉🎉 One **first-author** paper is accepted by **IJCAI 2024**.
- *2024.02*: &nbsp;🎉🎉 One **first-author** paper is accepted by **IEEE TITS**.

<!-- - *2023.12*: &nbsp;🎉🎉 One paper is accepted by **AAMAS 2024**.
- *2023.09*: &nbsp;💼🚀 I joined **Baidu Inc.**. -->

# Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCAI 2024</div><img src='images/main_fig_v8.pdf' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[X-Light: Cross-City Traffic Signal Control Using Transformer on Transformer as Meta Multi-Agent Reinforcement Learner](https://arxiv.org/abs/2404.12090)

**Haoyuan Jiang**, Ziyue Li, Hua Wei, Xuantang Xiong, Jingqing Ruan, Jiaming Lu, Hangyu Mao, Rui Zhao.

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=86wzq9oAAAAJ&citation_for_view=86wzq9oAAAAJ:2osOgNQ5qMEC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We propose a reinforcement learning algorithm for the multiple traffic signals control field that has good generalization and transferability while achieving SOTA performance. 
<!-- - [code](https://github.com/jiang-haoyuan/X-Light) -->
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TITS</div><img src='images/model-structure.pdf' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A General Scenario-Agnostic Reinforcement Learning for Traffic Signal Control](https://ieeexplore.ieee.org/abstract/document/10481508/)

**Haoyuan Jiang**, Ziyue Li, Zhishuai Li, Lei Bai, Hangyu Mao, Wolfgang Ketter, Rui Zhao.

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=86wzq9oAAAAJ&citation_for_view=86wzq9oAAAAJ:9yKSN-GCB0IC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We proposed a reinforcement learning algorithm for the traffic signal control field, which can easily cope with different scenarios and various types of intersections. Through training in large-scale scenarios, we found that the performance has been significantly improved and has strong generalization.
<!-- - [code](https://github.com/jiang-haoyuan/GESA) -->
</div>
</div>

- **[CoSLight: Co-optimizing Collaborator Selection and Decision-making to Enhance Traffic Signal Control](https://arxiv.org/abs/2405.17152)** \\
*ACM SIGKDD Conference on Knowledge Discovery and Data Mining*(**KDD**), in Barcelona, Spain, 2024. \\
Jingqing Ruan, Ziyue Li, Hua Wei, **Haoyuan Jiang**, Jiaming Lu, Xuantang Xiong, Hangyu Mao, Rui Zhao. \\
- **[DuaLight: Enhancing Traffic Signal Control by Leveraging Scenario-Specific and Scenario-Shared Knowledge](https://arxiv.org/abs/2312.14532)** \\
*International Conference on Autonomous Agents and Multi-Agent Systems*(**AAMAS**), in Auckland, New Zealand, 2024. (**Oral**) \\
Jiaming Lu, Jingqing Ruan, **Haoyuan Jiang**, Ziyue Li, Hangyu Mao, Rui Zhao. \\

# Preprint
- [GuideLight: "Industrial Solution" Guidance for More Practical Traffic Signal Control Agents]( https://arxiv.org/abs/2407.10811). **Haoyuan Jiang**, Xuantang Xiong, Ziyue Li, Hangyu Mao, Guanghu Sui, Jingqing Ruan, Yuheng Cheng, Hua Wei, Wolfgang Ketter, Rui Zhao.

# Educations
- *2026.06 - Present*, Ph.D. in RL & ML, TUM, Germany.
- *2017.09 - 2019.06*, Master in Software Engineering, Zhejiang University.

# Work and Research Experience
- *2026.06 - Present*, Research Assistant, TUM, Germany.
- *2026.02 - 2026.04*, Algorithm Expert, Alibaba, China.
- *2023.09 - 2026.01*, Senior Algorithm Engineer, Baidu Inc., China.
<!-- - *2019.07 - 2023.09*, Sensetime Research, China. -->

# Selected Services
**Program Committee Member or Reviewer**:
- Conference on Neural Information Processing Systems (**NeurIPS 2025, 2026**)
- International Joint Conference on Artificial Intelligence (**IJCAI 2025, 2026**)
- International Conference on Autonomous Agents and Multiagent Systems (**AAMAS 2025, 2026**)

# Honors and Awards
- *2017*, 14th National Graduate Mathematical Modeling Competition, Second Prize.
- *2017*, Honor Student in IBM Innovation Bootcamp.
- *2018*, 11th China College Students’ Entrepreneurship Competition, Bronze Award in Zhejiang Province.
- *2022*, IJCAI 2022 - Neural MMO Challenge, Bronze Tier Award.
- *2022*, Outstanding Individual of the Year in Sensetime SCG R&D Department.
- *2024*, Outstanding AIT Project in Baidu Inc. 


[//]: # (# 💬 Invited Talks)

[//]: # (- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. )

[//]: # (- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]]&#40;https://github.com/&#41;)
