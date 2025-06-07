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

[cite_start]I am a final-year undergraduate student pursuing a dual degree in Communication Engineering from Xidian University and Heriot-Watt University.  [cite_start]I have strong hands-on experience in developing, evaluating, and training MLLM-based GUI Agents.  [cite_start]My primary research interest lies in GUI Agent Training, and I am also enthusiastic about exploring related fields such as Reinforcement Learning for Large Language Models (including GRPO and DPO), LLM reasoning, and ToolUse Agents.  [cite_start]I am actively seeking a research intern position where I can apply and further develop my expertise in these areas while contributing to a research team. 

# 🔥 News
- [cite_start]*2025.05*: &nbsp;🎉🎉 Our paper "RealDev World: Benchmarking Production-Ready Software Engineering" is under review at COLM 2025. 

# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">COLM 2025 (Under Review)</div><img src='images/RealDev_World_logo.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[RealDev World: Benchmarking Production-Ready Software Engineering](https://github.com/tanghaom/AppEvalPilot)

[cite_start]Sirui Hong, **Yutong Bian**, Xinbing Liang, et al. 

[**Project**](https://example.com/link_to_project_page)
- [cite_start]As the lead for AppEvalPilot, I designed and implemented a system to dynamically assess software functionality through UI interaction, moving beyond the limitations of static analysis for LLM-based software engineers. 
- [cite_start]My work involved creating automated test case generation and a test execution agent capable of complex GUI interactions. 
- [cite_start]The experimental results demonstrated a high correlation (0.91) between AppEvalPilot's assessments and those of human experts, while also being 55% faster and 94.8% cheaper. 
</div>
</div>

# 📖 Educations
- [cite_start]*2021.09 - 2026.06*, B.Eng. in Communication Engineering (Dual Degree), Xidian University, China & Heriot-Watt University, UK. 
  - [cite_start]GPA: 3.8/4.0 

# 💻 Internships
- [cite_start]*2024.09 - Present*, [Deep Wisdom](https://www.deepwisdom.ai/), Shenzhen, China. 
  - Research Intern | [cite_start]Supervisor: Jinlin Wang, Chenglin Wu 
  - Topic: GUI Agent; Agent Training; [cite_start]Benchmark 

# 🚀 Projects
- **OSAgent: Cross-platform Intelligent Assistant** (Sep. 2024 - May. 2025)
  - [cite_start]Focused on developing a universal, stable, and efficient GUI agent framework. 
  - [cite_start]Contributed to the architecture design, perception, planning, and execution modules. 
  - [cite_start]Achieved state-of-the-art performance on SpaBench (mobile) cross-application tasks (26.7% vs. 13.3% by the previous SOTA). 
- **R1-Like GUI Agent Training** (Apr. 2024 - May. 2025)
  - [cite_start]Focused on enhancing the core element grounding capability of GUI agents using GRPO. 
  - [cite_start]Designed a data collection and refinement pipeline and a multi-component reward function. 
  - [cite_start]Demonstrated that 1k meticulously selected data points can achieve performance comparable to SOTA models trained on millions of samples, significantly improving GUI grounding accuracy on benchmarks like ScreenSpot and ScreenSpotPro.