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

Hi there, I am Zhibo Man (满志博), you can call me “Owen”. I am currently a Ph.D. student at [Beijing Jiaotong University](https://cs.bjtu.edu.cn/), where I was advised by [Prof. Yujie Zhang](https://faculty.bjtu.edu.cn/8356/).
My research interests lie broadly in **natural language processing, machine translation, large language models**. My research is driven by a long-standing interest in **computational linguistics**, with a particular focus on leveraging linguistic knowledge to advance natural language processing tasks.



# 🔥 News
- *2025.08.20*: &nbsp;🎉 Two papaers was accepted by **EMNLP 2025**.



# 📝 Publications ([Google Scholar](https://scholar.google.com/citations?hl=en&user=yqyz-1MAAAAJ&view_op=list_works&sortby=pubdate))

- DMDTEval: An Evaluation and Analysis of LLMs on Disambiguation in Multi-domain Translation

  **Zhibo Man**, Yuanmeng Chen, Yujie Zhang, Jinan Xu.

  EMNLP 2025

- SoT: Structured-of-Thought Prompting Guides Multilingual Reasoning in Large Language Models

  Rui Qi, **Zhibo Man**, Yufeng Chen, Fengran Mo, Jinan Xu, Kaiyu Huang

  EMNLP-Findings 2025

- CCKA: Continual Cross-Domain Knowledge Adaptation for Multi-Domain Machine Translation

  **Zhibo Man**, Yujie Zhang, Yuanmeng Chen, Yufeng Chen, Jinan Xu

  IEEE TASLP 2025
  
- Dual Debiasing in LLM-based Recommendation

  Sijin Lu,  **Zhibo Man**, Fangyuan Luo, Jun Wu

  SIGIR 2025
  
- ICL: Iterative Continual Learning for Multi-domain Neural Machine Translation

  **Zhibo Man**, Kaiyu Huang, Yujie Zhang, Yuanmeng Chen, Yufeng Chen, Jinan Xu

  EMNLP-Findings 2024
  
- A k-Nearest-Neighbor Machine Translation Method Combining Certainty Factor and Region Density

  Rui, Qi, Xiangyu Shi, **Zhibo Man**, Jinan Xu, and Yufeng Chen

  CCL 2024

- An Ensemble Strategy with Gradient Conflict for Multi-Domain Neural Machine Translation

  **Zhibo Man**, Yujie Zhang, Yu Li, Yuanmeng Chen, Yufeng Chen, and Jinan Xu

  ACM TALLIP 2024

- WDSRL: Multi-domain neural machine translation with word-level domain-sensitive representation learning

  **Zhibo Man**, Zengcheng Huang, Yujie Zhang, Yu Li, Yuanmeng Chen, Yufeng Chen, Jinan Xu

  IEEE TASLP 2023

- Exploring Domain-shared and Domain-specific Knowledge in Multi-domain Neural Machine Translation

  **Zhibo Man**, Yujie Zhang, Yuanmeng Chen, Yufeng Chen, Jinan Xu

  MT SUMMIT 2023





# 💻 Work Experiences
- *2025.07 – 2025.10*: &nbsp;🇨🇦 *Mitacs Globalink Research Intern & Visiting Research Student*, [Faculty of Computer Science](https://www.dal.ca/faculty/computerscience.html), Dalhousie University

  *- Lab: [Dalhousie Applied Machine Learning Research Lab](https://web.cs.dal.ca/~gaw/), Collaborator: [Dr. Ga Wu](https://wuga214.github.io/)*
  
  *- Project: AI safety for recommender systems in social media services*
  
- *2024.05 – 2024.09*: &nbsp;🇨🇳 *Summer Intern*, Pinecone Talent Elite Project, Baidu Inc.


# 💼 Services
- Artifact badging reviewer, KDD 2025


# 🪽 Beyond Academics

I love **music, literature, travel and badminton**. I am a **campus singer** at Renmin University of China and have been invited to participate in various concerts and music festivals at RUC. I am also a **musician at NetEase Cloud Music**, and my stage name is [艾诺 Ayinor](http://music.163.com/#/artist?id=36180214). Recently, I am also working on my own new song, so stay tuned!


# 🌍 Visitor Map

<script type='text/javascript' id='clustrmaps' src='//cdn.clustrmaps.com/map_v2.js?cl=1838a3&w=400&t=tt&d=opzTPaTNgNUrWvD_vjzXkFUMNo05ptM6XPnZfkpH53E&co=ffffff&cmo=af1616&cmn=1fba1f&ct=000000'></script>



<div class="logo-row">
  <img src="../images/ruc_logo.png"      alt="">
  <img src="../images/ucdavis_logo.png"  alt="">
  <img src="../images/dal_logo.png"      alt="">
  <img src="../images/mitacs_logo.png"      alt="">
</div>


<footer class="site-footer">
  <p>&copy; 2025 Zhiyuan Su. All rights reserved.</p>
  <p>
    Template adapted from
    <a href="https://github.com/RayeRen/acad-homepage.github.io"
       target="_blank" rel="noopener">Yi Ren</a>.
  </p>
</footer>
