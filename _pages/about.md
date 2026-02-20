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

😎 Hi, I am **Junting Lu (Aidan Lew)**, currently a final-year master student at Institute for Software Engineering, Peking University (PKU). Prior to that, I received the B.S. degree from Northwestern Polytechnical University (NWPU) in 2023. 

My current research interests primarily focus on:
- **Tool Learning**: Explore how to endow large models with human-level tool use abilities.
- **OS Agent**: Develop intelligent agents that utilize (multi-modal) large language models ((M)LLMs) to operate within operating systems (OS) environments.
- **Native VLM Agent**: Advancing research on equipping MLLMs with hybird Agent abilities.


# 📖 Educations
- [2023.09-2026.06] M.S. Peking University (PKU)
- [2019.09-2023.06] B.S. Northwestern Polytechnical University (NWPU)


# 🔥 News
- 🎉 [2026.02.16]: **Seed 2.0** made its debut in the LM Arena rankings, securing **6th** place in the Text Arena and **3rd** place in the Vision Arena respectively ! 🎉🎉🎉
- 🔥 [2026.02.14]: We released **Seed 2.0**. It is a powerful unified model with comprehensive capabilities surpassing Gemini 3 Pro with extreme superior agent capabilities.
As a core contributor, I mainly contribute to **general tool use ability** (MCPmark 54.7, BFCLv4 73.4, tau^ 2 retail 90.9, WorldTravel 23.3), which has been greatly improved compared to version 1.8. More details check the [model card](https://lf3-static.bytednsdoc.com/obj/eden-cn/lapzild-tss/ljhwZthlaukjlkulzlp/seed2/0214/Seed2.0%20Model%20Card.pdf).
- 🌟 [2025.12.18]: Our team is releasing **Seed1.8**, a model designed for generalized real-world agency. It supports text and image inputs and with its powerful multimodal processing capabilities, it demonstrates good performance across various complex application scenarios such as information retrieval, coding, Graphical User Interface (GUI) interaction. More details check the [model card](https://lf3-static.bytednsdoc.com/obj/eden-cn/lapzild-tss/ljhwZthlaukjlkulzlp/research/Seed-1.8-Modelcard.pdf).
- 🎉 [2025.10.29]: We released [Game-Tars](https://arxiv.org/abs/2510.23691): A generalist game agent trained with a unified, scalable action space anchored to human-aligned native keyboard-mouse inputs.
- 🌟 [2025.09.04]: We’re excited to announce the release the **UI-TARS-2**, which is a major upgrade from UI-TARS-1.5, featuring with enhanced capabilities in GUI, Game, Code and Tool Use. It is an **"All In One"** Agent model, enabling seamless integration of multiple abilities for complex tasks. Please check our new [technical report](https://arxiv.org/abs/2509.02544) for more details. Refer to more fantastic showcases at our [website](https://seed-tars.com/showcase/ui-tars-2/).
- 🎉 [2025.07.21]: [LAM](https://arxiv.org/abs/2412.10047) been accepted by TMLR 2025. The first paper to systematically expound how to transform a **Large Language Model** into a **Large Action Model** through different training stages.
- 🎉 [2025.05.16]: [AXIS](https://arxiv.org/abs/2409.17140) been accepted by ACL 2025. We proposes a pioneering agent framework to hybrid **GUI actions with API actions** through **Skill exploration**, so as to improve the efficiency of the OS Agent.
- 🌟 [2025.04.16]: We shared the latest progress of the UI-TARS-1.5 model in our [blog](https://seed-tars.com/1.5), which excels in playing games and performing GUI tasks, and we open-sourced the [UI-TARS-1.5-7B](https://huggingface.co/ByteDance-Seed/UI-TARS-1.5-7B).
- 🔥 [2025.02.22] We released [EasyR1](https://github.com/hiyouga/EasyR1) 🎉🎉🎉, an Efficient, Scalable, Multi-Modality RL Training Framework based on veRL.
- 🔥 [2024.12.13] We released the [UFO](https://github.com/microsoft/UFO) v1.2.0 with the code and sample data for Large Action Model (LAM) data collection! Please checkout our new paper and documentation for more details.
- 🎉 [2023.11.23] We released the [XAgent](https://github.com/OpenBMB/XAgent) v1.0.0! 🎉🎉🎉



# 💌 Projects
- [UI-TARS](https://github.com/bytedance/UI-TARS): **An open-source multimodal agent built upon a powerful vision-language model**. ![Github stars](https://img.shields.io/github/stars/bytedance/UI-TARS.svg)
- [XAgent](https://github.com/OpenBMB/XAgent): **An Autonomous Agent for Complex Task Solving.** ![Github stars](https://img.shields.io/github/stars/OpenBMB/XAgent.svg)
- [UFO](https://github.com/microsoft/UFO): **A UI-Focused Agent for Windows OS Interaction.** ![Github stars](https://img.shields.io/github/stars/microsoft/UFO.svg)
- [EasyR1](https://github.com/hiyouga/EasyR1): **An Efficient, Scalable, Multi-Modality RL Training Framework based on veRL.** ![Github stars](https://img.shields.io/github/stars/hiyouga/EasyR1.svg)


# 📝 Selected Publications 
- **Seed 2.0 Model Card: Towards Intelligence Frontier for Real-World Complexity** \
 Seed Team \
 Model card 2026, [[Paper](https://lf3-static.bytednsdoc.com/obj/eden-cn/lapzild-tss/ljhwZthlaukjlkulzlp/seed2/0214/Seed2.0%20Model%20Card.pdf)]
- **Seed 1.8 Model Card: Towards Generalized Real-World Agency** \
  Seed Team \
  Model card 2025, [[Paper](https://lf3-static.bytednsdoc.com/obj/eden-cn/lapzild-tss/ljhwZthlaukjlkulzlp/research/Seed-1.8-Modelcard.pdf)]
- **Game-TARS: Pretrained Foundation Models for Scalable Generalist Multimodal Game Agents** \
  UI-TARS Team \
  Technical Report 2025, [[Paper](https://arxiv.org/pdf/2510.23691)]
- **UI-TARS-2 Technical Report: Advancing GUI Agent with Multi-Turn Reinforcement Learning** \
  UI-TARS Team \
  Technical Report 2025, [[Paper](https://arxiv.org/abs/2509.02544)]
- **Seed1.5-VL Technical Report** \
  Seed VLM Team \
  Technical Report 2025, [[Paper](arxiv.org/abs/2505.07062)]
- **AXIS: Efficient Human-Agent-Computer Interaction with API-First LLM-Based Agents** \
  <i>**Junting Lu\***</i>, Zhiyang Zhang\*, Fangkai Yang, Jue Zhang, Lu Wang, Chao Du, Qingwei Lin, Saravan Rajmohan, Dongmei Zhang, Qi Zhang \
  ACL 2025 Main, [[Paper](https://arxiv.org/abs/2409.17140)]
- **Large Action Models: From Inception to Implementation** \
  Lu Wang\*, Fangkai Yang\*, Chaoyun Zhang\*, <i>**Junting Lu**</i>, Jiaxu Qian, Shilin He, Pu Zhao, Bo Qiao, Ray Huang, Si Qin, Qisheng Su, Jiayi Ye, Yudi Zhang, Jian-Guang Lou, Qingwei Lin, Saravan Rajmohan, Dongmei Zhang, Qi Zhang \
  TMLR 2025, [[Paper](https://arxiv.org/abs/2412.10047)]

> Full paper list refer to [google scholar](https://scholar.google.com/citations?user=ZyvZWYYAAAAJ).

# 🎖 Honors and Awards
- [2024] Luo Yuehua Scholarship at Peking University
- [2023] Shaanxi Province Outstanding Undergraduate at NWPU
- [2022] Huawei Scholarship at NWPU
- [2020,2021,2022] National Scholarship for Undergraduate at NWPU  


# 💻 Internships
- [2025.2-present] Bytedance-Seed (supervised by Dr. [Yujia Qin](https://yujia-qin.github.io/))
- [2024.3-2024.10] Microsoft DKI Group (supervised by Dr. [Fangkai Yang](https://www.microsoft.com/en-us/research/people/fangkaiyang/))
- [2023.8-2024.2] ModelBest && TsinghuaNLP (supervised by Dr. Yinxu Pan, Prof. [Zhiyuan Liu](https://nlp.csai.tsinghua.edu.cn/~lzy/))

# 📚 Academic Services
- Serving as a reviewer of KDD 2026

# 💡 Lifestyle

- My hobbies include but are not limited to 🎤singing, 🎸guitar, 🧙 magic and 🫘 bean.
