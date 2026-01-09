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

I am currently a second-year Doctor Candidate at Harbin Institute of Technology (HIT), majoring in Computer Science and Technology under the guidance of Prof. <a href='https://chewanxiang.com/'>Wanxiang Che</a>. Before this, I graduated from Tsinghua University (THU) in 2024 with a Master's degree in computer science, supervised by Prof. <a href='https://nlp.csai.tsinghua.edu.cn/~ly/index_cn.html'>Yang Liu</a> and Prof. Weidong Liu. I also closely worked with Prof. <a href='https://lpeng.net/'>Peng Li</a> and <a href='https://scholar.google.com/citations?user=5vm5yAMAAAAJ&hl=zh-CN'>Shuo Wang</a> when I was in Tsinghua University. Several years ago, I graduated from the National University of Defense Technology (NUDT) in 2015 with a Bachelor's degree in Engineering. Afterward, I worked in a Chinese government department for a while before resigning (in 2020).

My current research interests are efficient Large Language Models (LLMs), LLM-based agents, and multilingual processing. I am very keen to connect with other friends in the research community to exchange and discuss ideas.

<img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations">  <a href="https://hits.seeyoufarm.com"><img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fxuyuzhuang11.github.io&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false"/></a>


# 🔥 News
- *2024.09*: &nbsp;🎉🎉 OneBit is accepted by NeurIPS 2024.
- *2024.02*: &nbsp;🎉🎉 We are the first to attempt 1-bit quantization of LLMs, achieving 90% model compression while retaining 83% of the performance (on LLaMA series). This work is featured by AK(<a href='https://twitter.com/_akhaliq/status/1759816467602665626'>@_akhaliq</a>).
- *2023.09*: &nbsp;🎉🎉 We explore playing Werewolf Game using LLMs. Some strategic and social behaviors emerged, such as trust, confrontation, etc.

# 📝 Publications

- [OneBit: Towards Extremely Low-bit Large Language Models](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=eUnK3msAAAAJ&citation_for_view=eUnK3msAAAAJ:9yKSN-GCB0IC)
  - **Yuzhuang Xu**, Xu Han, Zonghan Yang, Shuo Wang, Qingfu Zhu, Zhiyuan Liu, Weidong Liu, Wanxiang Che
  - In ***Advances in Neural Information Processing Systems (NeurIPS 2024)***
  - Keywords: Onebit, Extreme Quantization, 1-bit Quantization

- [Exploring Large Language Models for Communication Games: An Empirical Study on Werewolf](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=eUnK3msAAAAJ&citation_for_view=eUnK3msAAAAJ:u-x6o8ySG0sC)
  - **Yuzhuang Xu**, Shuo Wang, Peng Li, Fuwen Luo, Xiaolong Wang, Weidong Liu, Yang Liu
  - ***ArXiv Technical Report***
  - Keywords: Werewolf, LLM for Games, Social Behaviors

- [CAMERA: Multi-Matrix Joint Compression for MoE Models via Micro-Expert Redundancy Analysis](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=eUnK3msAAAAJ&citation_for_view=eUnK3msAAAAJ:YsMSGLbcyi4C)
  - **Yuzhuang Xu**, Xu Han, Yuanchi Zhang, Yixuan Wang, Yijun Liu, Shiyu Ji, Qingfu Zhu, Wanxiang Che
  - In ***Proceedings of the AAAI Conference on Artificial Intelligence (AAAI 2026)***
  - Keywords: Micro-expert, Pruning, Quantization, MoE

- [CRVQ: Channel-relaxed Vector Quantization for Extreme Compression of LLMs](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=eUnK3msAAAAJ&citation_for_view=eUnK3msAAAAJ:zYLM7Y9cAGgC)
  - **Yuzhuang Xu**, Shiyu Ji, Qingfu Zhu, Wanxiang Che
  - In ***Transactions of the Association for Computational Linguistics (TACL 2025), EMNLP 2025***
  - Keywords: Extreme Compression, Codebook, Hardware-friendly

- [Pluggable Neural Machine Translation Models via Memory-augmented Adapters](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=eUnK3msAAAAJ&citation_for_view=eUnK3msAAAAJ:UeHWp8X0CEIC)
  - **Yuzhuang Xu**, Shuo Wang, Peng Li, Xuebo Liu, Xiaolong Wang, Weidong Liu, Yang Liu
  - In ***Proceedings of the Joint International Conference on Computational Linguistics, Language Resources and Evaluation (LREC-COLING 2024)***
  - Keywords: Machine Translation, Plugin, Style Translation

- [A Survey on Large Language Models with Multilingualism: Recent Advances and New Frontiers](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=eUnK3msAAAAJ&citation_for_view=eUnK3msAAAAJ:2osOgNQ5qMEC)
  - Kaiyu Huang, Fengran Mo, Hongliang Li, You Li, Yuanchi Zhang, Weijian Yi, Yulong Mao, Jinchen Liu, **Yuzhuang Xu**, Jinan Xu, Jian-Yun Nie, Yang Liu
  - ***ArXiv Preprint***
  - Keywords: Survey, Multilingualism, Machine Translation

- [Delta-CoMe: Training-Free Delta-Compression with Mixed-Precision for Large Language Models](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=eUnK3msAAAAJ&citation_for_view=eUnK3msAAAAJ:qjMakFHDy7sC)
  - Bowen Ping, Shuo Wang, Hanqing Wang, Xu Han, **Yuzhuang Xu**, Yukun Yan, Yun Chen, Baobao Chang, Zhiyuan Liu, Maosong Sun
  - In ***Advances in Neural Information Processing Systems (NeurIPS 2024)***
  - Keywords: Delta-compression, Training-free, Mixed-precision

- [Judge Q: Trainable Queries for Optimized Information Retention in KV Cache Eviction](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=eUnK3msAAAAJ&citation_for_view=eUnK3msAAAAJ:eQOLeE2rZwMC)
  - Yijun Liu, Yixuan Wang, **Yuzhuang Xu**, Shiyu Ji, Yang Xu, Qingfu Zhu, Wanxiang Che
  - In ***Proceedings of the AAAI Conference on Artificial Intelligence (AAAI 2026)***
  - Keywords: KV Eviction, Trainable Query, KV Compression

- [ActiView: Evaluating Active Perception Ability for Multimodal Large Language Models](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=eUnK3msAAAAJ&citation_for_view=eUnK3msAAAAJ:IjCSPb-OGe4C)
  - Ziyue Wang, Chi Chen, Fuwen Luo, Yurui Dong, Yuanchi Zhang, **Yuzhuang Xu**, Xiaolong Wang, Peng Li, Yang Liu
  - In ***Proceedings of the Annual Meeting of the Association for Computational Linguistics (ACL 2025)***
  - Keywords: Active Perception, Visual Question Answering, Benchmark

- [UltraLink: An Open-Source Knowledge-Enhanced Multilingual Supervised Fine-tuning Dataset](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=eUnK3msAAAAJ&citation_for_view=eUnK3msAAAAJ:d1gkVwhDpl0C)
  - Haoyu Wang, Shuo Wang, Yukun Yan, Xujia Wang, Zhiyu Yang, **Yuzhuang Xu**, Zhenghao Liu, Ning Ding, Xu Han, Zhiyuan Liu, Maosong Sun
  - In ***Proceedings of the Annual Meeting of the Association for Computational Linguistics (ACL 2024)***
  - Keywords: Multilingual, Dataset, Knowledge-Enhanced

- [Lookahead Q-Cache: Achieving More Consistent KV Cache Eviction via Pseudo Query](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=eUnK3msAAAAJ&citation_for_view=eUnK3msAAAAJ:Y0pCki6q_DkC)
  - Yixuan Wang, Shiyu Ji, Yijun Liu, **Yuzhuang Xu**, Yang Xu, Qingfu Zhu, Wanxiang Che
  - In ***Proceedings of the Conference on Empirical Methods in Natural Language Processing (EMNLP 2025)***
  - Keywords: KV Eviction, Pseudo Query, Lookahead

- [Perspective Transition of Large Language Models for Solving Subjective Tasks](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=eUnK3msAAAAJ&citation_for_view=eUnK3msAAAAJ:Tyk-4Ss8FVUC)
  - Xiaolong Wang, Yuanchi Zhang, Ziyue Wang, **Yuzhuang Xu**, Fuwen Luo, Yile Wang, Peng Li, Yang Liu
  - In ***Findings of the Association for Computational Linguistics: ACL 2025***
  - Keywords: Perspective Transition, Subjective Tasks, Multi-Agent

- [Think Before You Accept: Semantic Reflective Verification for Faster Speculative Decoding](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=eUnK3msAAAAJ&citation_for_view=eUnK3msAAAAJ:W7OEmFMy1HYC)
  - Yixuan Wang, Yijun Liu, **Yuzhuang Xu**, Yang Xu, Qingfu Zhu, Wanxiang Che
  - ***ArXiv Preprint***
  - Keywords: Speculative Decoding, Semantic Reflective, Relaxed Verification


<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📖 Educations
- *2024.09 - Future*, Harbin Institute of Technology, Harbin, China, Doctor student, Computer science and technology.
- *2021.09 - 2024.06*, Tsinghua University, Beijing, China, Master, Computer science and technology. 
- *2011.09 - 2015.06*, National University of Defense Technology, Changsha, China, Undergraduate, Command and Automation. 

# 💬 Invited Talks
- *2024.07*, Hotpot Paper Oral (OneBit), CCL 2024, Taiyuan, China.
- *2024.03*, Exploration and Innovation in Extreme Quantization Methods for Large Language Models, Jiqizhixin, Online.
- *2024.03*, The Era of LLM-based Agents: Ability, Methodology and Future, Swarma Club, Online.

# 💻 Internships
- *2023.08 - 2024.08*, National Laboratory, Beijing, China.
- *2022.01 - 2022.07*, Chinese Academy of Sciences, Institute of Software, Beijing, China.

# 💻 Services
- Reviewer-Conference: ACL RR 2024, ACL RR 2025, NeurIPS 2025
- Reviewer-Journal: TPAMI, FCS, Neurocomputing, IEEE Games
