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

I am currently a first-year Doctor student at Harbin Institute of Technology (HIT), majoring in Computer Science and Technology under the guidance of Prof. <a href='http://ir.hit.edu.cn/~car/'>Wanxiang Che</a>. Before this, I graduated from Tsinghua University (THU) in 2021 with a Master's degree in computer science, supervised by Prof. <a href='https://nlp.csai.tsinghua.edu.cn/~ly/index_cn.html'>Yang Liu</a> and Prof. Weidong Liu. I also closely worked with Prof. <a href='https://lpeng.net/'>Peng Li</a> and <a href='https://scholar.google.com/citations?user=5vm5yAMAAAAJ&hl=zh-CN'>Shuo Wang</a> when I was in Tsinghua University. Several years ago, I graduated from the National University of Defense Technology (NUDT) in 2015 with a Bachelor's degree in Engineering. Afterward, I worked in a Chinese government department for a while before resigning (in 2020).

My current research interests are efficient Large Language Models (LLMs), LLM-based agents, and multilingual processing. I am very keen to connect with other friends in the research community to exchange and discuss ideas.

<img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations">  <a href="https://hits.seeyoufarm.com"><img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fxuyuzhuang11.github.io&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false"/></a>


# 🔥 News
- *2024.09*: &nbsp;🎉🎉 OneBit is accepted by NeurIPS 2024.
- *2024.02*: &nbsp;🎉🎉 We are the first to attempt 1-bit quantization of LLMs, achieving 90% model compression while retaining 83% of the performance (on LLaMA series). This work is featured by AK(<a href='https://twitter.com/_akhaliq/status/1759816467602665626'>@_akhaliq</a>).
- *2023.09*: &nbsp;🎉🎉 We explore playing Werewolf Game using LLMs. Some strategic and social behaviors emerged, such as trust, confrontation, etc.

# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2024</div><img src='images/paper_imgs/onebit.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[OneBit: Towards Extremely Low-bit Large Language Models](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=eUnK3msAAAAJ&citation_for_view=eUnK3msAAAAJ:9yKSN-GCB0IC)

**Yuzhuang Xu**, Xu Han, Zonghan Yang, Shuo Wang, Qingfu Zhu, Zhiyuan Liu, Weidong Liu, Wanxiang Che

📃[**Paper**](https://arxiv.org/abs/2402.11295)    🛠[**Code**](https://github.com/xuyuzhuang11/OneBit)
<!-- <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
- Model quantification uses low bit-width values to represent the weight matrices of models, which is a promising approach to reduce both storage and computational overheads of deploying highly anticipated LLMs. However, existing quantization methods suffer severe performance degradation when the bit-width is extremely reduced, and thus focus on utilizing 4-bit or 8-bit values to quantize models. This paper boldly quantizes the weight matrices of LLMs to 1-bit, paving the way for the extremely low bit-width deployment of LLMs. For this target, we introduce a 1-bit quantization-aware training (QAT) framework named OneBit, including a novel 1-bit parameter representation method to better quantize LLMs as well as an effective parameter initialization method based on matrix decomposition to improve the convergence speed of the QAT framework. Sufficient experimental results indicate that OneBit achieves good performance (at least 83% of the non-quantized performance) with robust training processes when only using 1-bit weight matrices.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv</div><img src='images/paper_imgs/multilingual_survey.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A Survey on Large Language Models with Multilingualism: Recent Advances and New Frontiers](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=eUnK3msAAAAJ&citation_for_view=eUnK3msAAAAJ:2osOgNQ5qMEC)

Kaiyu Huang, Fengran Mo, Hongliang Li, You Li, Yuanchi Zhang, Weijian Yi, Yulong Mao, Jinchen Liu, **Yuzhuang Xu**, Jinan Xu, Jian-Yun Nie, Yang Liu

📃[**Paper**](https://arxiv.org/pdf/2405.10936)
<!-- <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
- The rapid development of Large Language Models (LLMs) demonstrates remarkable multilingual capabilities in natural language processing, attracting global attention in both academia and industry. To mitigate potential discrimination and enhance the overall usability and accessibility for diverse language user groups, it is important for the development of language-fair technology. Despite the breakthroughs of LLMs, the investigation into the multilingual scenario remains insufficient, where a comprehensive survey to summarize recent approaches, developments, limitations, and potential solutions is desirable. To this end, we provide a survey with multiple perspectives on the utilization of LLMs in the multilingual scenario. We first rethink the transitions between previous and current research on pre-trained language models. Then we introduce several perspectives on the multilingualism of LLMs, including training and inference methods, model security, multi-domain with language culture, and usage of datasets. We also discuss the major challenges that arise in these aspects, along with possible solutions. Besides, we highlight future research directions that aim at further enhancing LLMs with multilingualism. The survey aims to help the research community address multilingual problems and provide a comprehensive understanding of the core concepts, key techniques, and latest developments in multilingual natural language processing based on LLMs.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2024</div><img src='images/paper_imgs/Delta.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Delta-CoMe: Training-Free Delta-Compression with Mixed-Precision for Large Language Models](https://arxiv.org/abs/2406.08903)

Bowen Ping, Shuo Wang, Hanqing Wang, Xu Han, **Yuzhuang Xu**, Yukun Yan, Yun Chen, Baobao Chang, Zhiyuan Liu, Maosong Sun

📃[**Paper**](https://arxiv.org/abs/2406.08903)
<!-- <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
- Fine-tuning is a crucial process for adapting large language models (LLMs) to diverse applications. In certain scenarios, such as multi-tenant serving, deploying multiple LLMs becomes necessary to meet complex demands. Recent studies suggest decomposing a fine-tuned LLM into a base model and corresponding delta weights, which are then compressed using low-rank or low-bit approaches to reduce costs. In this work, we observe that existing low-rank and low-bit compression methods can significantly harm the model performance for task-specific fine-tuned LLMs (e.g., WizardMath for math problems). Motivated by the long-tail distribution of singular values in the delta weights, we propose a delta quantization approach using mixed-precision. This method employs higher-bit representation for singular vectors corresponding to larger singular values. We evaluate our approach on various fine-tuned LLMs, including math LLMs, code LLMs, chat LLMs, and even VLMs. Experimental results demonstrate that our approach performs comparably to full fine-tuned LLMs, surpassing both low-rank and low-bit baselines by a considerable margin. Additionally, we show that our method is compatible with various backbone LLMs, such as Llama-2, Llama-3, and Mistral, highlighting its generalizability.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv</div><img src='images/paper_imgs/acti_view.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[ActiView: Evaluating Active Perception Ability for Multimodal Large Language Models](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=eUnK3msAAAAJ&citation_for_view=eUnK3msAAAAJ:IjCSPb-OGe4C)

Ziyue Wang, Chi Chen, Fuwen Luo, Yurui Dong, Yuanchi Zhang, **Yuzhuang Xu**, Xiaolong Wang, Peng Li, Yang Liu

📃[**Paper**](https://arxiv.org/pdf/2410.04659)    🛠[**Code**](https://github.com/THUNLP-MT/ActiView)
<!-- <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
- Active perception, a crucial human capability, involves setting a goal based on the current understanding of the environment and performing actions to achieve that goal. Despite significant efforts in evaluating Multimodal Large Language Models (MLLMs), active perception has been largely overlooked. To address this gap, we propose a novel benchmark named ActiView to evaluate active perception in MLLMs. Since comprehensively assessing active perception is challenging, we focus on a specialized form of Visual Question Answering (VQA) that eases the evaluation yet challenging for existing MLLMs. Given an image, we restrict the perceptual field of a model, requiring it to actively zoom or shift its perceptual field based on reasoning to answer the question successfully. We conduct extensive evaluation over 27 models, including proprietary and open-source models, and observe that the ability to read and comprehend multiple images simultaneously plays a significant role in enabling active perception. Results reveal a significant gap in the active perception capability of MLLMs, indicating that this area deserves more attention. We hope that our benchmark could help develop methods for MLLMs to understand multimodal inputs in more natural and holistic ways.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2024</div><img src='images/paper_imgs/ultra_link.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[UltraLink: An Open-Source Knowledge-Enhanced Multilingual Supervised Fine-tuning Dataset](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=eUnK3msAAAAJ&citation_for_view=eUnK3msAAAAJ:d1gkVwhDpl0C)

Haoyu Wang, Shuo Wang, Yukun Yan, Xujia Wang, Zhiyu Yang, **Yuzhuang Xu**, Zhenghao Liu, Ning Ding, Xu Han, Zhiyuan Liu, Maosong Sun

📃[**Paper**](https://arxiv.org/abs/2402.04588)    🛠[**Code**](https://github.com/OpenBMB/UltraLink)
<!-- <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
- Open-source large language models (LLMs) have gained significant strength across diverse fields. Nevertheless, the majority of studies primarily concentrate on English, with only limited exploration into the realm of multilingual supervised fine-tuning. In this work, we therefore construct an open-source multilingual supervised fine-tuning dataset. Different from previous works that simply translate English instructions, we consider both the language-specific and language-agnostic abilities of LLMs. For language-specific abilities, we introduce a knowledge-grounded data augmentation approach to elicit more culture-specific knowledge of LLMs, improving their ability to serve users from different countries. For language-agnostic abilities, we find through experiments that modern LLMs exhibit strong cross-lingual transfer capabilities, thus repeatedly learning identical content in various languages is not necessary. Consequently, we can substantially prune the language-agnostic SFT data without any performance degradation, making the SFT process more efficient. The resulting UltraLink dataset comprises approximately 1 million samples across five languages, and the proposed data construction method can also be easily extended to other languages. UltraLink-LM, which is trained on UltraLink, outperforms several representative baselines across many tasks.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv</div><img src='images/paper_imgs/werewolf.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Exploring Large Language Models for Communication Games: An Empirical Study on Werewolf](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=eUnK3msAAAAJ&citation_for_view=eUnK3msAAAAJ:u-x6o8ySG0sC)

**Yuzhuang Xu**, Shuo Wang, Peng Li, Fuwen Luo, Xiaolong Wang, Weidong Liu, Yang Liu

📃[**Paper**](https://arxiv.org/abs/2309.04658)    🛠[**Code**](https://github.com/xuyuzhuang11/Werewolf)
<!-- <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
- Communication games, which we refer to as incomplete information games that heavily depend on natural language communication, hold significant research value in fields such as economics, social science, and artificial intelligence. In this work, we explore the problem of how to engage large language models (LLMs) in communication games, and in response, propose a tuning-free framework. Our approach keeps LLMs frozen, and relies on the retrieval and reflection on past communications and experiences for improvement. An empirical study on the representative and widely-studied communication game, "Werewolf", demonstrates that our framework can effectively play Werewolf game without tuning the parameters of the LLMs. More importantly, strategic behaviors begin to emerge in our experiments, suggesting that it will be a fruitful journey to engage LLMs in communication games and associated domains.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">COLING 2024</div><img src='images/paper_imgs/pluggable_nmt.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Pluggable Neural Machine Translation Models via Memory-augmented Adapters](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=eUnK3msAAAAJ&citation_for_view=eUnK3msAAAAJ:u5HHmVD_uO8C)

**Yuzhuang Xu**, Shuo Wang, Peng Li, Xuebo Liu, Xiaolong Wang, Weidong Liu, Yang Liu

📃[**Paper**](https://arxiv.org/abs/2307.06029)    🛠[**Code**](https://github.com/xuyuzhuang11/StyleMT)
<!-- <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
- Although neural machine translation (NMT) models perform well in the general domain, it remains rather challenging to control their generation behavior to satisfy the requirement of different users. Given the expensive training cost and the data scarcity challenge of learning a new model from scratch for each user requirement, we propose a memory-augmented adapter to steer pretrained NMT models in a pluggable manner. Specifically, we construct a multi-granular memory based on the user-provided text samples and propose a new adapter architecture to combine the model representations and the retrieved results. We also propose a training strategy using memory dropout to reduce spurious dependencies between the NMT model and the memory. We validate our approach on both styleand domain-specific experiments and the results indicate that our method can outperform several representative pluggable baselines.
</div>
</div>

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