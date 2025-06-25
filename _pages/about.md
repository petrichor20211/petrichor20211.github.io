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

As a third-year undergraduate pursuing a dual degree in Communication Engineering from Xidian University and Heriot-Watt University, I have developed strong hands-on experience in the development, evaluation, and training of MLLM-based Graphical User Interface (GUI) Agents. My primary research interest lies in advancing the cognitive capabilities of GUI Agents to exhibit more human-like reasoning and generalization, with a core focus on pioneering novel training methodologies. I am also enthusiastic about exploring related fields such as Reinforcement Learning for Large Language Models (RL4LLM), LLM Reasoning, and Tool-Use Agents. I am seeking a PhD position where I can apply and expand my expertise to contribute to your research team.
# 🔥 News
- *2025.05*: &nbsp;🎉🎉 Our paper "RealDev World: Benchmarking Production-Ready Software Engineering" is under review at COLM 2025. 

# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">COLM 2025 (Under Review)</div><img src='images/RealDev_World_logo.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[RealDevWorld: Benchmarking Production-Ready Software Engineering](https://github.com/tanghaom/AppEvalPilot)

**Sirui Hong**\*, **Yutong Bian**\*, Xinbing Liang, et al. 

[**Project**](https://github.com/tanghaom/AppEvalPilot)
- As the lead for AppEvalPilot, I designed and implemented a system to dynamically assess software functionality through UI interaction, moving beyond the limitations of static analysis for LLM-based software engineers. 
- My work involved creating automated test case generation and a test execution agent capable of complex GUI interactions. 
- The experimental results demonstrated a high correlation (0.91) between AppEvalPilot's assessments and those of human experts, while also being 55% faster and 94.8% cheaper. 
</div>
</div>

# 📖 Educations
- *2021.09 - 2026.06*, B.Eng. in Communication Engineering, Xidian University, China & Heriot-Watt University, UK. 
  - GPA: 3.8/4.0 

# 💻 Internships
- *2024.09 - 2025.05*, [MetaGPT](https://github.com/FoundationAgents/MetaGPT), Shenzhen, China. 
  - Research Intern | Supervisor: [Sirui Hong](https://scholar.google.com.hk/citations?user=O-yMFdUAAAAJ&hl=zh-CN), [Jinlin Wang](https://scholar.google.com.hk/citations?user=ypzAHmIAAAAJ&hl=zh-CN&oi=ao), [Chenglin Wu](https://scholar.google.com.hk/citations?user=nYIj020AAAAJ&hl=zh-CN&oi=ao) 
  - Topic: GUI Agent; Agent Training; Benchmark 

# 🚀 Projects
- **OSAgent: Cross-platform Intelligent Assistant** (Sep. 2024 - May. 2025)
  - Focused on developing a universal, stable, and efficient GUI agent framework. 
  - Contributed to the architecture design, perception, planning, and execution modules. 
  - Achieved state-of-the-art performance on SpaBench (mobile) cross-application tasks (26.7% vs. 13.3% by the previous SOTA). 
- **R1-Like GUI Agent Training** (Apr. 2024 - May. 2025)
  - Focused on enhancing the core element grounding capability of GUI agents using GRPO. 
  - Designed a data collection and refinement pipeline and a multi-component reward function. 
  - Demonstrated that 1k meticulously selected data points can achieve performance comparable to SOTA models trained on millions of samples, significantly improving GUI grounding accuracy on benchmarks like ScreenSpot and ScreenSpotPro.