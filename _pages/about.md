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

I am currently a final-year Master's student at Tsinghua University, majoring in Computer Science and Technology under the guidance of Prof. Weidong Liu and Prof. <a href='https://nlp.csai.tsinghua.edu.cn/~ly/index_cn.html'>Yang Liu</a>. Before this, I graduated from the National University of Defense Technology in 2015 with a Bachelor's degree in Engineering. Afterward, I worked in a Chinese government department for a while before resigning (in 2020). In September this year (2024), I will join the Harbin Institute of Technology to pursue a Ph.D. in Computer Science and Technology supervised by Prof. <a href='http://ir.hit.edu.cn/~car/'>Wanxiang Che</a>.

My current research interests are efficient Large Language Models (LLMs), LLM-based agents, and multilingual processing. I am very keen to connect with other friends in the research community to exchange and discuss ideas.

<img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations">  <a href="https://hits.seeyoufarm.com"><img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fxuyuzhuang11.github.io&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false"/></a>


# 🔥 News
- *2024.02*: &nbsp;🎉🎉 We are the first to attempt 1-bit quantization of LLMs, achieving 90% model compression while retaining 83% of the performance (on LLaMA series). 
- *2023.09*: &nbsp;🎉🎉 We explore playing Werewolf Game using LLMs. Some strategic and social behaviors emerged, such as trust, confrontation, etc.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">COLING 2024</div><img src='images/paper_imgs/pluggable_nmt.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Pluggable Neural Machine Translation Models via Memory-augmented Adapters](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC)

**Yuzhuang Xu**, Shuo Wang, Peng Li, Xuebo Liu, Xiaolong Wang, Weidong Liu, Yang Liu

[📃**Paper**](https://arxiv.org/abs/2307.06029) [🛠**Code**](https://github.com/xuyuzhuang11/StyleMT)
<!-- <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
- Although neural machine translation (NMT) models perform well in the general domain, it remains rather challenging to control their generation behavior to satisfy the requirement of different users. Given the expensive training cost and the data scarcity challenge of learning a new model from scratch for each user requirement, we propose a memory-augmented adapter to steer pretrained NMT models in a pluggable manner. Specifically, we construct a multi-granular memory based on the user-provided text samples and propose a new adapter architecture to combine the model representations and the retrieved results. We also propose a training strategy using memory dropout to reduce spurious dependencies between the NMT model and the memory. We validate our approach on both styleand domain-specific experiments and the results indicate that our method can outperform several representative pluggable baselines.
</div>
</div>

<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📖 Educations
- *2024.09 - Future*, Harbin Institute of Technology, Harbin, China, Doctor candidate, Computer science and technology.
- *2021.09 - 2024.06 (now)*, Tsinghua University, Beijing, China, Master, Computer science and technology. 
- *2011.09 - 2015.06*, National University of Defense Technology, Changsha, China, Undergraduate, Command and Automation. 

# 💬 Invited Talks
- *2024.03*, Exploration and Innovation in Extreme Quantization Methods for Large Language Models, Jiqizhixin, Online.
- *2024.03*, The Era of LLM-based Agents: Ability, Methodology and Future, Swarma Club, Online.

# 💻 Internships
- *2022.01 - 2022.07*, Chinese Academy of Sciences, Institute of Software, Beijing, China.