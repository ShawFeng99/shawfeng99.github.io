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

<!-- Hi there,  -->
I am Xiao Feng, a Ph.D. student at [TMLR group](https://bhanml.github.io/group.html) of Hong Kong Baptist University, fortunate to be advised by [Prof. Bo Han](https://bhanml.github.io/), and working with [Prof. Jiangchao Yao](https://sunarker.github.io/).
My research focuses on **agentic reasoning and learning** with foundation models. I work on: (1) building agentic systems that orchestrate foundation models and tools for complex tasks [[AlphaApollo]](https://arxiv.org/pdf/2510.06261); 
<!-- ( -->
<!-- 2) learning to reason via reinforcement learning—including reward propagation in agentic state graphs [[RewardFlow]](https://openreview.net/pdf?id=5oGJbM5u86), dynamic policy optimization for multi-turn interactive reasoning [[DyPO]](https://openreview.net/pdf?id=OWDBiMKYdo), and self-supervised RL for eliciting reasoning [[Co-rewarding]](https://arxiv.org/pdf/2508.00410); -->
(2) understanding and benchmarking reasoning—such as visualizing LLM reasoning processes [[Landscape of thoughts]](https://arxiv.org/pdf/2503.22165), active reasoning under incomplete information [[AR-Bench]](https://arxiv.org/pdf/2506.08295), and robust multi-agent debate with memory masking [[MAD-M²]](https://openreview.net/pdf?id=EdTt8nMAMA).

<!-- *Feel free to email [Prof. Bo Han](mailto:bhanml@comp.hkbu.edu.hk) and [me](mailto:xiaofeng@comp.hkbu.edu.hk) to discuss collaboration opportunities.* -->

E-mail: xiaofeng [at] comp.hkbu.edu.hk


# 📖 Education and Experience
- *2025.09 - present*, Ph.D. Student, TMLR Group, Hong Kong Baptist University, advised by [Prof. Bo Han](https://bhanml.github.io/).
- *2021.09 - 2022.11*, MSc in Artificial Intelligence, University of Southampton.
- *2017.09 - 2021.06*, B.E. in Computer Science, Lanzhou University.


# 📝 Selected Publications
\* Co-first author, ✉️ Corresponding author.

<!-- AlphaApollo -->
<div class='paper-box'><div class='paper-box-image'><div>
<img src='/images/figures/AlphaApollo.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

AlphaApollo: A System for Deep Agentic Reasoning.  
Zhanke Zhou, Chentao Cao, **Xiao Feng**, Xuan Li, Zongze Li, Xiangyu Lu, Jiangchao Yao, Weikai Huang, Linrui Xu,  
Tian Cheng, Jianghangfan Zhang, Tangyu Jiang, Linrui Xu, Yiming Zheng, Brando Miranda, Tongliang Liu, Sanmi Koyejo, Masashi Sugiyama, Bo Han✉️  
Technical Report.
[[paper]](https://arxiv.org/pdf/2510.06261)
[[code]](https://github.com/tmlr-group/AlphaApollo)
<!-- [[slides]]() -->
<!-- [[poster]]() -->
<!-- [[EN-video]]() -->
<!-- [[CN-video]]() -->
<!-- [[CN-blog]]() -->
<!-- [[twitter]]() -->
</div>
</div>


<!-- ICML 2025 AR-Bench -->
<div class='paper-box'><div class='paper-box-image'><div>
<img src='/images/figures/AR-Bench.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

From Passive to Active Reasoning: Can Large Language Models Ask the Right Questions under Incomplete Information?  
Zhanke Zhou\*, **Xiao Feng\***, Zhaocheng Zhu, Jiangchao Yao, Sanmi Koyejo, Bo Han✉️  
ICML 2025.
[[paper]](https://arxiv.org/pdf/2506.08295)
[[code]](https://github.com/tmlr-group/AR-Bench)
[[slides]](https://docs.google.com/presentation/d/1lFvnGzM6QsVUFlOe_CM6WqX8qPnNMtMkoefObJv4FAA/edit?usp=sharing)
[[poster]](/images/poster-ARBench.pdf)
[[EN-video]](https://recorder-v3.slideslive.com/?share=102661&s=59c868a3-9715-4031-a690-6128a9befc18)
[[CN-video]](https://www.bilibili.com/video/BV1i4KozXETv/)
[[CN-blog]](https://mp.weixin.qq.com/s/zU8HcZ1q9Dt0KfTRPNcowg)
<!-- [[twitter]]() -->
</div>
</div>

<!-- Landscape of thoughts -->
<div class='paper-box'><div class='paper-box-image'><div>
<img src='/images/figures/Landscape.png' alt="sym" width="100%"></div></div>
<!-- <img src='/_pages/data/poster-landscape.png' alt="sym" width="100%"></div></div> -->
<div class='paper-box-text' markdown="1">

Landscape of Thoughts: Visualizing the Reasoning Process of Large Language Models.  
Zhanke Zhou\*, Zhaocheng Zhu\*, Xuan Li\*, Mikhail Galkin, **Xiao Feng**, Sanmi Koyejo, Jian Tang, Bo Han✉️  
ICLR 2026.
<!-- on Reasoning and Planning for Large Language Models. -->
[[paper]](https://arxiv.org/pdf/2503.22165)
[[code]](https://github.com/tmlr-group/landscape-of-thoughts)
[[tutorial]](https://www.youtube.com/watch?v=Zb8CfYxSvik)
[[slides]](/images/slides-landscape.pdf)
[[poster]](/images/poster-landscape.pdf)
<!-- [[EN-video]]() -->
<!-- [[CN-video]]() -->
<!-- [[CN-blog]]() -->
[[twitter]](https://x.com/zhankezhou/status/1942730655034675426)
</div>
</div>

<!-- Co-rewarding - shared, placeholder figure
<div class='paper-box'><div class='paper-box-image'><div>
<img src='https://placehold.co/400x250/eee/999?text=Figure' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Co-rewarding: Stable Self-supervised RL for Eliciting Reasoning in Large Language Models.  
Zhengyan Zhang, Jiong Zhu, Xinyu Ge, Zihao Zhao, Zhanke Zhou, Xuan Li, **Xiao Feng**, Jiangchao Yao, Bo Han✉️  
ICLR 2026.
[[paper]](https://arxiv.org/pdf/2508.00410)
[[code]](https://github.com/tmlr-group/Co-rewarding)
</div>
</div> -->

<!-- RewardFlow - shared, placeholder figure
<div class='paper-box'><div class='paper-box-image'><div>
<img src='https://placehold.co/400x250/eee/999?text=Figure' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

RewardFlow: Propagating Reward in the State Graphs of Agentic Learning with LLMs.  
**Xiao Feng**, Bo Han✉️, Zhanke Zhou, Jiaqi Fan, Jiangchao Yao, Ka Ho Li, Dahai Yu, Michael Ng  
ICLR 2026.
[[paper]](https://openreview.net/pdf?id=5oGJbM5u86)
[[code]](https://github.com/tmlr-group/RewardFlow)
</div>
</div>

<!-- DyPO - shared, placeholder figure -->
<!-- <div class='paper-box'><div class='paper-box-image'><div>
<img src='https://placehold.co/400x250/eee/999?text=Figure' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1"> -->

<!-- DyPO: Dynamic Policy Optimization for Multi-Turn Interactive Reasoning.  
**Xiao Feng**, Bo Han✉️, Zhanke Zhou, Jiaqi Fan, Jiangchao Yao, Ka Ho Li, Dahai Yu, Michael Ng  
ICML 2025 Workshop on Programmatic Representations for Agent Learning.
[[paper]](https://openreview.net/pdf?id=OWDBiMKYdo)
[[code]](https://github.com/tmlr-group/DyPO)
</div>
</div> -->

<!-- Multi-Agent Debate with Memory Masking - Feng's own, placeholder figure -->
<div class='paper-box'><div class='paper-box-image'><div>
<img src='/images/figures/madmm.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Multi-Agent Debate with Memory Masking (MAD-M²).  
Hongduan Tian, **Xiao Feng**, Ziyuan Zhao, Xiangyu Zhu, Rolan Yan, Bo Han✉️  
ICLR 2026.
[[paper]](https://openreview.net/pdf?id=EdTt8nMAMA)
[[code]](https://github.com/tmlr-group/MAD-MM)
</div>
</div>


# 🎖 Awards
<!-- Add your awards here -->
- HKBU PhD Transdisciplinary Research Scholarship Scheme, 2025.
- Excellent Research Bronze Award of TMLR Group, 2024-2025.
- Industry Collaboration Award of TMLR Group, 2024-2025.

<!-- # 💬 Talks -->
<!-- Add your talks here -->

# 💻 Services
<!-- Add your service activities here -->
- **Conference Reviewer:** NeurIPS, ICLR, ICML, AAAI, ACL, AISTATS.
- **Journal Reviewer:** TPAMI, JAIR, TNNLS, NEUNET.

<!-- # 🏫 Teaching -->
<!-- Add your teaching experience here -->

<!-- # 📖 Experiences
- *2022.09 - present*, PhD student @HKBU-[TMLR Group](https://bhanml.github.io/group.html), advised by Prof. Bo Han.
- *2025.01 - present*, Visiting student @Stanford-[STAIR Lab](https://cs.stanford.edu/~sanmi/), advised with Prof. Sanmi Koyejo.
- *2022.02 - 2022.09*, Research assistant @HKBU-[TMLR Group](https://bhanml.github.io/group.html), advised by Prof. Bo Han and Prof. Jiangchao Yao.
- *2021.01 - 2024.05*, Visiting student @THU-[LARS Group](https://lars-group.github.io/pages/group.html), advised by Prof. Quanming Yao and Prof. Yongqi Zhang.
- *2020.06 - 2020.09*, Research intern @SJTU-[MVIG Group](https://mvig.org/), advised by Prof. Cewu Lu and Prof. Yonglu Li.
- *2018.03 - 2021.01*, Core Member @HUST-[Dian Group](https://dian.org.cn/), advised by Prof. Yayu Gao, Prof. Chengwei Zhang, and Prof. Xiaojun Hei. -->

<!-- # 💻 Resources

I champion open-source research and hope the following resources can benefit you :)

## Projects
- [Awesome-model-inversion-attack](https://github.com/AndrewZhou924/Awesome-model-inversion-attack)
<img src="https://img.shields.io/github/stars/AndrewZhou924/Awesome-model-inversion-attack?color=yellow&label=Star" alt="Stars" >
- [DeepInception](https://github.com/tmlr-group/DeepInception)
<img src="https://img.shields.io/github/stars/tmlr-group/DeepInception?color=yellow&label=Star" alt="Stars" >
- [FLDRL-in-Wireless-Communication](https://github.com/Mauriyin/FLDRL-in-Wireless-Communication)
<img src="https://img.shields.io/github/stars/Mauriyin/FLDRL-in-Wireless-Communication?color=yellow&label=Star" alt="Stars" >
- [AutoSF](https://github.com/AutoML-4Paradigm/AutoSF)
<img src="https://img.shields.io/github/stars/AutoML-4Paradigm/AutoSF?color=yellow&label=Star" alt="Stars" >
- [MC-GRA](https://github.com/tmlr-group/MC-GRA)
<img src="https://img.shields.io/github/stars/tmlr-group/MC-GRA?color=yellow&label=Star" alt="Stars" >
- [RGIB](https://github.com/tmlr-group/RGIB)
<img src="https://img.shields.io/github/stars/tmlr-group/RGIB?color=yellow&label=Star" alt="Stars" >
- [AdaProp](https://github.com/LARS-research/AdaProp)
<img src="https://img.shields.io/github/stars/LARS-research/AdaProp?color=yellow&label=Star" alt="Stars" >
- [KGTuner](https://github.com/LARS-research/KGTuner)
<img src="https://img.shields.io/github/stars/LARS-research/KGTuner?color=yellow&label=Star" alt="Stars" >
- [graph-ood-detection](https://github.com/AndrewZhou924/graph-ood-detection)
<img src="https://img.shields.io/github/stars/AndrewZhou924/graph-ood-detection?color=yellow&label=Star" alt="Stars" >
- [one-shot-subgraph](https://github.com/tmlr-group/one-shot-subgraph)
<img src="https://img.shields.io/github/stars/tmlr-group/one-shot-subgraph?color=yellow&label=Star" alt="Stars" >
- [NeuralAtom](https://github.com/tmlr-group/NeuralAtom)
<img src="https://img.shields.io/github/stars/tmlr-group/NeuralAtom?color=yellow&label=Star" alt="Stars" >
- [Awesome-Graph-Prompting](https://github.com/AndrewZhou924/Awesome-Graph-Prompting)
<img src="https://img.shields.io/github/stars/AndrewZhou924/Awesome-Graph-Prompting?color=yellow&label=Star" alt="Stars" > -->


<!-- ## Source Files of My Talks or Posters
- All my posters are here.
[[slides-pdf]](/_pages/data/all-the-posters.pdf)
[[slides-pptx]](/_pages/data/all-the-posters.pptx)
- 20240420: Less is more: One-shot subgraph reasoning on large-scale knowledge graphs.
[[slides-pdf]](/_pages/data/talks/20240420-one-shot-subgraph.pdf)
[[slides-pptx]](/_pages/data/talks/20240420-one-shot-subgraph.pptx)
- 20240327: Experience sharing on my research career.
[[slides-pdf]](/_pages/data/talks/20240327-experience-sharing.pdf)
[[slides-pptx]](/_pages/data/talks/20240327-experience-sharing.pptx)
- 20231214: Robust graph information bottleneck.
[[slides-pdf]](/_pages/data/talks/20231214-robust-GIB.pdf)
[[slides-pptx]](/_pages/data/talks/20231214-robust-GIB.pptx)
- 20231114: Graph reconstruction attack.
[[slides-pdf]](/_pages/data/talks/20231114-graph-reconstruction-attack.pdf)
[[slides-pptx]](/_pages/data/talks/20231114-graph-reconstruction-attack.pptx)
- 20231109: Recent advances on LLM reasoning with graphs.
[[slides-pdf]](/_pages/data/talks/20231109-Recent-Advances-on-LLM-Reasoning-with-Graphs.pdf)
[[slides-pptx]](/_pages/data/talks/20231109-Recent-Advances-on-LLM-Reasoning-with-Graphs.pptx)
- 20230705: Paper reading of [AAGOD](http://shichuan.org/doc/150.pdf).
[[slides-pdf]](/_pages/data/talks/20230705-paper-reading-AAGOD.pdf)
[[slides-pptx]](/_pages/data/talks/20230705-paper-reading-AAGOD.pptx)
- 20230705: Paper reading of [CFLP](https://proceedings.mlr.press/v162/zhao22e/zhao22e.pdf).
[[slides-pdf]](/_pages/data/talks/20230209-paper-reading-CFLP.pdf)
[[slides-pptx]](/_pages/data/talks/20230209-paper-reading-CFLP.pptx)
- 20230207: Model inversion attack: From images to graphs.
[[slides-pdf]](/_pages/data/talks/20230207-model-inversion-attack.pdf)
[[slides-pptx]](/_pages/data/talks/20230207-model-inversion-attack.pptx)
- 20221028: A review of GNN explanation methods.
[[slides-pdf]](/_pages/data/talks/20221028-explainable-GNN.pdf)
[[slides-pptx]](/_pages/data/talks/20221028-explainable-GNN.pptx)
- 20221026: Paper reading of [CoLE](https://arxiv.org/pdf/2208.09828.pdf).
[[slides-pdf]](/_pages/data/talks/20221026-paper-reading-CoLE.pdf)
[[slides-pptx]](/_pages/data/talks/20221026-paper-reading-CoLE.pptx)
- 20220630: Paper reading of [GSAT](https://arxiv.org/pdf/2201.12987.pdf).
[[slides-pdf]](/_pages/data/talks/20220630-paper-reading-GSAT.pdf)
[[slides-pptx]](/_pages/data/talks/20220630-paper-reading-GSAT.pptx)
- 20220325: Learning query-dependent propagation for knowledge graph reasoning.
[[slides-pdf]](/_pages/data/talks/20220325-structual-learning.pdf)
[[slides-pptx]](/_pages/data/talks/20220325-structual-learning.pptx)
- 20211112: Paper reading of [GraIL](http://proceedings.mlr.press/v119/teru20a/teru20a.pdf).
[[slides-pdf]](/_pages/data/talks/20211112-paper-reading-GraIL.pdf)
[[slides-pptx]](/_pages/data/talks/20211112-paper-reading-GraIL.pptx)
- 20210709: Understanding and benchmarking model search for knowledge graph embedding.
[[slides-pdf]](/_pages/data/talks/20210709-benchmarking-KGE.pdf)
[[slides-pptx]](/_pages/data/talks/20210709-benchmarking-KGE.pptx)
- 20211112: Paper reading of [interstellar](https://neurips.cc/virtual/2020/public/poster_722caafb4825ef5d8670710fa29087cf.html).
[[slides-pdf]](/_pages/data/talks/20210401-paper-reading-interstellar.pdf)
[[slides-pptx]](/_pages/data/talks/20210401-paper-reading-interstellar.pptx)
- 20201213: Paper reading of [UAMT](https://arxiv.org/pdf/1907.07034).
[[slides-pdf]](/_pages/data/talks/20201213-paper-reading-UAMT.pdf)
[[slides-pptx]](/_pages/data/talks/20201213-paper-reading-UAMT.pptx) -->


<!-- ## References
I benefit a lot from these awesome materials. Thanks!
- TODO -->



<p style="text-align: center; color: #999; font-size: 0.9em; margin-bottom: 1em;">© {{ "now" | date: "%Y" }} {{ site.author.name }} | Last Update: {{ "now" | date: "%Y.%m" }}</p>
<div style="text-align: center;">
  <a href="https://mapmyvisitors.com/web/1c34m" title="Visit tracker">
    <img src="https://mapmyvisitors.com/map.png?d=-4kffgolvTNKlw4xGPAiWjsh7--JLTmh8PrdAETH9JE&cl=ffffff" />
  </a>
</div>