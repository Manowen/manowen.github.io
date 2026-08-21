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

<style>
  .rucred {
    display: inline-block;
    background-color: rgb(174, 11, 42);
    color: white;
    font-size: 0.8em;
    padding: 2px 6px;
    border-radius: 3px;
    margin-left: 8px;
    font-weight: bold;
    vertical-align: middle;
  }
  .badge {
    font-weight: 600;
    margin-bottom: 5px;
  }
</style>

<style>
  .logo-row {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 1.5rem;
    margin-top: 2rem; 
  }
  .logo-row img {
    height: 60px;
    width: auto;
    /* 
       border-radius: 6px;
       box-shadow: 0 0 6px rgba(0,0,0,.15); */
  }
</style>

<style>
  .site-footer {
    text-align: center;
    font-size: 0.85em;
    color: rgb(128, 128, 128);
    margin: 2rem 0 1rem; 
  }
  .site-footer a {
    color: inherit;
    text-decoration: underline;
  }
</style>

<span class='anchor' id='about-me'></span>

Hi there, I am Zhibo Man (满志博), and you can call me “Owen”. I am currently a postdoctoral researcher at the  [European Laboratory for Learning and Intelligent Systems (ELLIS)](https://ellis.eu/) and the [University of Turku (UTU)](https://www.utu.fi/en/people/zhibo-man), Finland, supervised by [Prof. Shaoxiong Ji](https://shaoxiongji.github.io/). I received my Ph.D. degree from [Beijing Jiaotong University (BJTU)](https://cs.bjtu.edu.cn/) in 2026, where I was advised by [Prof. Yujie Zhang](https://faculty.bjtu.edu.cn/8356/).

My research interests lie broadly in **natural language processing (NLP), machine translation (MT), multi-lingual LLMs, and agents**. My research is driven by a long-standing interest in **computational linguistics (CL)**, with a particular focus on leveraging linguistic knowledge to advance natural language processing tasks.


# 🔥 News
- *2026.07*: &nbsp;🎉 [MoltNet](https://inlp-lab.github.io/MoltNet/) Accepted by **COLM 2026**, **COLM-26-WAB**!

- *2026.06.12*: &nbsp;🎉 I will join the University of Turku (UTU) and European Laboratory for Learning and Intelligent Systems (ELLIS) as a postdoctoral researcher starting in August 2026, supervised by [Prof. Shaoxiong Ji](https://shaoxiongji.github.io/).

- *2026.04.07*: &nbsp;🎉 One paper was accepted by **ACL 2026**.

- *2026.02*: &nbsp;🎉 New project [MoltNet](https://inlp-lab.github.io/MoltNet/) — understanding social behavior of AI agents in the agent-native MoltBook — is now available on arXiv.
  
- *2025.11.15*: &nbsp;🎉 I am currently a visiting student at the **iNLP lab** of the Singapore University of Technology and Design (SUTD), supervised by [Prof. Wenxuan Zhang](https://isakzhang.github.io/).

- *2025.08.20*: &nbsp;🎉 Two papers were accepted by **EMNLP 2025**.



# 📝 Publications 
([Google Scholar](https://scholar.google.com/citations?hl=en&user=yqyz-1MAAAAJ&view_op=list_works&sortby=pubdate))
- <span class="rucred">COLM 2026</span> MoltNet: Understanding Social Behavior of AI Agents in the Agent-Native MoltBook
  
  Yi Feng, Chen Huang, **Zhibo Man**, Ryner Tan, Long P. Hoang, Shaoyang Xu, Wenxuan Zhang
  
- <span class="rucred">ACL-Findings 2026</span> Can Multi-agent Help Disambiguation in Multi-domain Translation?

   **Zhibo Man**, Shaoyang Xu, Yujie Zhang, Yi Feng, Yuanmeng Chen, Yufeng Chen, Xu Jinan, Wenxuan Zhang

- <span class="rucred">ESWA 2026</span> DKF: Domain Knowledge Fusion in Progressive Incremental Learning for Multi-domain Machine Translation

   **Zhibo Man**, Yujie Zhang, Yuanmeng Chen, Yufeng Chen, Jinan Xu
  
- <span class="rucred">EMNLP 2025</span> DMDTEval: An Evaluation and Analysis of LLMs on Disambiguation in Multi-domain Translation

   **Zhibo Man**, Yujie Zhang, Yuanmeng Chen, Jinan Xu

- <span class="rucred">EMNLP-Findings 2025</span> SoT: Structured-of-Thought Prompting Guides Multilingual Reasoning in Large Language Models

   Rui Qi, **Zhibo Man**, Yufeng Chen, Fengran Mo, Jinan Xu, Kaiyu Huang

- <span class="rucred">IEEE TASLP 2025</span> CCKA: Continual Cross-Domain Knowledge Adaptation for Multi-Domain Machine Translation

  **Zhibo Man**, Yujie Zhang, Yuanmeng Chen, Yufeng Chen, Jinan Xu

- <span class="rucred">CCL 2025</span> Word Semantic Disambiguation via Topic Steering in Multi-Domain Translation

   **Zhibo Man**, Yujie Zhang, Yuanmeng Chen, Yufeng Chen, Jinan Xu
  
- <span class="rucred">SIGIR 2025</span> Dual Debiasing in LLM-based Recommendation

  Sijin Lu,  **Zhibo Man**, Fangyuan Luo, Jun Wu

- <span class="rucred">EMNLP-Findings 2024</span> ICL: Iterative Continual Learning for Multi-domain Neural Machine Translation

  **Zhibo Man**, Kaiyu Huang, Yujie Zhang, Yuanmeng Chen, Yufeng Chen, Jinan Xu
  
- <span class="rucred">CCL 2024</span> A k-Nearest-Neighbor Machine Translation Method Combining Certainty Factor and Region Density

  Rui, Qi, Xiangyu Shi, **Zhibo Man**, Jinan Xu, and Yufeng Chen

- <span class="rucred">ACM TALLIP 2024</span> An Ensemble Strategy with Gradient Conflict for Multi-Domain Neural Machine Translation

  **Zhibo Man**, Yujie Zhang, Yu Li, Yuanmeng Chen, Yufeng Chen, and Jinan Xu

- <span class="rucred">IEEE TASLP 2023</span> WDSRL: Multi-domain neural machine translation with word-level domain-sensitive representation learning

  **Zhibo Man**, Zengcheng Huang, Yujie Zhang, Yu Li, Yuanmeng Chen, Yufeng Chen, Jinan Xu

- <span class="rucred">MT SUMMIT 2023</span> Exploring Domain-shared and Domain-specific Knowledge in Multi-domain Neural Machine Translation

  **Zhibo Man**, Yujie Zhang, Yuanmeng Chen, Yufeng Chen, Jinan Xu

# 💻 Work Experiences
- *2023.12 – 2024.04*: &nbsp;🇨🇳 *Research Intern*, Lenovo AI Research.

  *- Lab: Group Intelligent Decision*
  
  *- Project: LLM-based Agent*
  
- *2021.10 – 2022.01*: &nbsp;🇨🇳 *Research Intern*, Langboat Tech.

  *- Project: Machine Translation*


# 💼 Services
- Conference Reviewer: ACL Rolling Review (ACL, EMNLP, NAACL, etc.), CCMT 2025.
- Journal Reviewer: Natural Language Processing (NLP), Applied Intelligence (APIN), ACM Transactions on Asian and Low-Resource Language Information Processing (ACM TALLIP).


# 🪽 Beyond Academics

- I love reading and traveling. I long for a free and independent life, and I hope that in the future I can have my own little shop 😄, something like a café ☕️ or a bookstore 📖.



