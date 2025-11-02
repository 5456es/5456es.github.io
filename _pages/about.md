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
# About
I am Zhennan Shen, a B.E. candidate in Computer Science and Engineering at Shanghai Jiao Tong University (Zhiyuan Honors Program, Class of 2025). My research focuses on **language-model agents** and **agentic reinforcement learning** (Especially on computer-use-agent). I have worked closely with [Prof. Tao Yu](https://taoyds.github.io/) at [HKU NLP](https://hkunlp.github.io/) and with [Prof. Lu Chen](https://coai-sjtu.github.io/) and [Prof. Kai Yu](https://x-lance.github.io/kaiyu/) at the [X-LANCE Lab](https://x-lance.github.io/). I currently work on RL and SFT initiatives at [Moonshot AI](https://www.moonshot.ai/) ([Kimi](https://www.kimi.com/en/)), supporting large-scale agent training pipelines. 

- GPA: 3.9/4.3; Outstanding Graduate and Zhiyuan Honors Scholarship recipient.
- Research directions: large language models, agentic reinforcement learning, robust LLM evaluation.
- Collaborations with [Moonshot AI](https://www.moonshot.ai/), [HKU NLP Group](https://hkunlp.github.io/), and [SJTU X-LANCE Lab](https://x-lance.github.io/).
- <span style="font-size: 1.2em; font-weight: bold; color: red">I am actively seeking PhD opportunities starting in Fall 2026; if you are interested in my work, please feel free to contact me.</span>

**Contact:** 1641225799szn@gmail.com · [Google Scholar](https://scholar.google.com/citations?user=JPwg5MwAAAAJ) · [LinkedIn](https://www.linkedin.com/in/zhennan-shen-188a632b6) · [Resume]({{ "/ZhennanShen_Resume.pdf" | relative_url }})

<span class='anchor' id='research-interests'></span>
# Research Interests
- **(α) Agentic reinforcement learning** that strengthens exploration, planning, and generalization for LLM-based agents.
- **(β) Human-aligned evaluation** frameworks and **scalable benchmarks** for LLM agents.
- **(γ) Scalable data synthesis pipelines** that mix supervised, reinforcement, and self-improvement signals for continual agent growth.

<u>I see reinforcement learning as the key to unlocking the full agentic potential of large language models.</u> To get there, we need **(α)** richer training paradigms that fuse supervised, reinforcement, and self-improvement signals; rigorous, **(β)** human-aligned evaluation suites to keep agents grounded; and **(γ)** scalable data pipelines that deliver the fuel these systems need to continually improve. Aligned with these agendas, I have worked on agentic foundation models ([OpenCUA](https://opencua.xlang.ai/)), agent data synthesis ([AgentTrek](https://agenttrek.github.io/)), agent evaluation ([OSWorld-Verified](https://xlang.ai/blog/osworld-verified)), and related initiatives.


<span class='anchor' id='news'></span>
# News
- *2025.09* [OpenCUA](https://opencua.xlang.ai/) recognized with a <span style="color:red;">Spotlight at NeurIPS 2025</span>.
- *2025.07* [OSWorld-Verified](https://xlang.ai/blog/osworld-verified) launched  <span style="color:red;">verified OSWorld evaluation suite</span>, delivering more reliable infrastructure and task quality.
- *2025.03* Joined <a href="https://www.moonshot.ai/" style="color:red;">Moonshot AI</a> (<a href="https://www.kimi.com/en/" style="color:red;">Kimi</a>) to develop RL pipelines for advanced computer-use agents.
- *2025.01* [AgentTrek](https://agenttrek.github.io/) selected as a <span style="color:red;">Spotlight paper at ICLR 2025</span>.
- *2024.09* Completed research internship at HKU NLP Group working on large-scale agent data synthesis.

<span class='anchor' id='publications'></span>
# Publications & Preprints
- **[AgentTrek: Agent Trajectory Synthesis via Guiding Replay with Web Tutorials.](https://openreview.net/forum?id=EEgYUccwsV)** \* Yiheng Xu, \* Dunjie Lu, \* **Zhennan Shen (co-lead)**, Junli Wang, Zekun Wang, Yuchen Mao, Caiming Xiong, Tao Yu. *<span style="color: red;">ICLR 2025 (Spotlight)</span>.* Introduced guided replay pipelines that transform web tutorials into scalable agent trajectories.
- **[OpenCUA: Open Foundations for Computer-Use Agents.](https://opencua.xlang.ai/)** Xinyuan Wang, Bowen Wang, Dunjie Lu, Junlin Yang, Tianbao Xie, Junli Wang, Jiaqi Deng, Xiaole Guo, Yiheng Xu, Chen Henry Wu, **Zhennan Shen**, et al. *<span style="color: red;">NeurIPS 2025 (Spotlight)</span>.* Released a community-driven foundation for building and benchmarking computer-use agents.
- **[OSWorld-Verified: Reliable Evaluation for Computer-Use Agents.](https://xlang.ai/blog/osworld-verified)** **Zhennan Shen** (contributor) et al. Documented 300+ task fixes, migrated OSWorld infrastructure to AWS for massive parallelization, and launched a verified leaderboard for reproducible evaluation.
- **[MobileEnv: Building Qualified Evaluation Benchmarks for LLM-GUI Interaction.](https://arxiv.org/abs/2305.08144)** Zhang Danyang, **Shen Zhennan**, Xie Rui, Zhang Situo, Xie Tianbao, Zhao Zihan, Chen Siyuan, Chen Li, Xu Hongshen, Cao Ruisheng, Yu Kai. Under review (AAAI 2026). Established high-fidelity GUI tasks for fine-grained capability assessment.
- **[CATP: Contextually Adaptive Token Pruning for Efficient and Enhanced Multimodal In-Context Learning.](https://arxiv.org/abs/2508.07871)** Yanshu Li, Jiangnan Wang, **Zhennan Shen**, Lihong Han, Haoyan Xu, Ruixiang Tang. Under review (AAAI 2026). Proposed adaptive pruning for efficient multimodal reasoning.
- **[SciEval: A Multi-Level Large Language Model Evaluation Benchmark for Scientific Research.](https://ojs.aaai.org/index.php/AAAI/article/view/29872/31521)** Sun Liangtai, Han Yang, Zhao Zihan, Ma Da, **Shen Zhennan**, Chen Baocai, Chen Lu, Yu Kai. <span style="color:red">*AAAI 2024.*</span> Delivered hierarchical evaluation tasks for science-focused LLMs.
- **[SciDFM: A Large Language Model with Mixture-of-Experts for Science.](https://neurips.cc/virtual/2024/workshop/84714)** Sun Liangtai, Liu Danyu, Ma Da, Zhao Zihan, Chen Baocai, **Shen Zhennan**, Zhu Su, Chen Lu, Chen Xin, Yu Kai. <span style="color:red">*NeurIPS 2024 Workshop on FM4Science.*</span> Built science-specialized Mixture-of-Experts models with robust evaluation.

<span class='anchor' id='experience'></span>
# Experience

## Education
- *Shanghai Jiao Tong University*, B.E. in Computer Science and Engineering (Zhiyuan Honors Program), Sep 2021 – Jun 2025, Shanghai, China. GPA 3.9/4.3 (22/127). Outstanding Graduate; Zhiyuan Honors Scholarship (2021–2023).

## Research
- *[HKU NLP Group](https://hkunlp.github.io/)*, Research Intern, Jul 2024 – Sep 2024, Hong Kong, China (Advisor: [Prof. Tao Yu](https://taoyds.github.io/))  
  Built LLM-based GUI agent pipelines and large-scale data synthesis workflows; co-led AgentTrek and contributed to OpenCUA.
- *[X-LANCE Lab, SJTU](https://x-lance.github.io/)*, Research Intern, Jul 2023 – Jul 2024, Shanghai, China (Advisors: [Prof. Lu Chen](https://coai-sjtu.github.io/) & [Prof. Kai Yu](https://x-lance.github.io/kaiyu/))  
  Developed MobileEnv benchmark and scientific LLM agents including SciDFM and SciEval for AI4Science reasoning.

## Industry
- [Moonshot AI](https://www.moonshot.ai/) ([Kimi](https://www.kimi.com/en/)), Agent Training Intern, Mar 2025 – Present, Beijing, China  
  Design reinforcement learning workflows for GUI-centric computer-use agents; scale SFT + RLHF data pipelines with quantitative and qualitative evaluation; optimize automation for large-scale agent training and deployment.

<span class='anchor' id='honors'></span>
# Honors & Awards
- Zhiyuan Honors Scholarship, Shanghai Jiao Tong University (2021–2024).
- Outstanding Graduate, Zhiyuan Honors Program (2024).
- University-Level Scholarship B (2023).
- University-Level Scholarship C (2022).
