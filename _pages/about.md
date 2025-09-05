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

😎 Hi, I am **Junting Lu (Aidan Lew)**, currently a second-year master student at Institute for Software Engineering, Peking University (PKU). Prior to that, I received the B.S. degree from Northwestern Polytechnical University (NWPU) in 2023. 

My current research interests primarily focus on:
- **Tool Learning**: Explore how to endow large models with human-level tool use abilities.
- **OS Agent**: Develop intelligent agents that utilize (multi-modal) large language models ((M)LLMs) to operate within operating systems (OS) environments.
- **Native VLM Agent**: Advancing research on equipping MLLMs with hybird Agent abilities.


# 📖 Educations
- [2023.09-2026.06] M.S. Peking University (PKU)
- [2019.09-2023.06] B.S. Northwestern Polytechnical University (NWPU)


# 🔥 News
- 🌟 [2025.09.04]: We’re excited to announce the release the **UI-TARS-2**, which is a major upgrade from UI-TARS-1.5, featuring with enhanced capabilities in GUI, Game, Code and Tool Use. It is an "All In One" Agent model, enabling seamless integration of multiple abilities for complex tasks. Please check our new [technical report](https://arxiv.org/abs/2509.02544) for more details. Refer to more fantastic showcases at our [website](https://seed-tars.com/showcase/ui-tars-2/).
- 🎉 [2025.08.21] 2 papers been accepted by EMNLP 2025.
- 🎉 [2025.07.21] [LAM](https://arxiv.org/abs/2412.10047) been accepted by TMLR 2025.
- 🎉 [2025.05.16] [AXIS](https://arxiv.org/abs/2409.17140) been accepted by ACL 2025.
- 🌟 [2025.04.16]: We shared the latest progress of the UI-TARS-1.5 model in our [blog](https://seed-tars.com/1.5), which excels in playing games and performing GUI tasks, and we open-sourced the [UI-TARS-1.5-7B](https://huggingface.co/ByteDance-Seed/UI-TARS-1.5-7B).
- 🔥 [2025.02.22] We released [EasyR1](https://github.com/hiyouga/EasyR1) 🎉🎉🎉, an Efficient, Scalable, Multi-Modality RL Training Framework based on veRL.
- 🔥 [2024.12.13] We released the [UFO](https://github.com/microsoft/UFO) v1.2.0 with the code and sample data for Large Action Model (LAM) data collection! Please checkout our new paper and documentation for more details.
- 🔥 [2024.07.04] Nissist been accepted by ECAI 2024.
- 🎉 [2023.11.23] We released the [XAgent](https://github.com/OpenBMB/XAgent) v1.0.0! 🎉🎉🎉



# 💌 Projects
- [UI-TARS](https://github.com/bytedance/UI-TARS): **An open-source multimodal agent built upon a powerful vision-language model**. ![Github stars](https://img.shields.io/github/stars/bytedance/UI-TARS.svg)
- [XAgent](https://github.com/OpenBMB/XAgent): **An Autonomous Agent for Complex Task Solving.** ![Github stars](https://img.shields.io/github/stars/OpenBMB/XAgent.svg)
- [UFO](https://github.com/microsoft/UFO): **A UI-Focused Agent for Windows OS Interaction.** ![Github stars](https://img.shields.io/github/stars/microsoft/UFO.svg)
- [EasyR1](https://github.com/hiyouga/EasyR1): **An Efficient, Scalable, Multi-Modality RL Training Framework based on veRL.** ![Github stars](https://img.shields.io/github/stars/hiyouga/EasyR1.svg)


# 📝 Publications 
- **UI-TARS-2 Technical Report: Advancing GUI Agent with Multi-Turn Reinforcement Learning** \
  UI-TARS Team \
  Technical Report 2025, [[Paper](https://arxiv.org/abs/2509.02544)],
- **Seed1.5-VL Technical Report** \
  Seed VLM Team \
  Technical Report 2025, [[Paper](arxiv.org/abs/2505.07062)]
- **AXIS: Efficient Human-Agent-Computer Interaction with API-First LLM-Based Agents** \
  <i>**Junting Lu\***</i>, Zhiyang Zhang\*, Fangkai Yang, Jue Zhang, Lu Wang, Chao Du, Qingwei Lin, Saravan Rajmohan, Dongmei Zhang, Qi Zhang \
  ACL 2025 Main, [[Paper](https://arxiv.org/abs/2409.17140)]
- **Large Action Models**: From Inception to Implementation \
  Lu Wang\*, Fangkai Yang\*, Chaoyun Zhang\*, <i>**Junting Lu**</i>, Jiaxu Qian, Shilin He, Pu Zhao, Bo Qiao, Ray Huang, Si Qin, Qisheng Su, Jiayi Ye, Yudi Zhang, Jian-Guang Lou, Qingwei Lin, Saravan Rajmohan, Dongmei Zhang, Qi Zhang \
  TMLR 2025, [[Paper](https://arxiv.org/abs/2412.10047)]
- **Thread: A Logic-Based Data Organization Paradigm for How-To Question Answering with Retrieval Augmented Generation** \
  Kaikai An, Fangkai Yang, Liqun Li, <i>**Junting Lu**</i>, Sitao Cheng, Lu Wang, Pu Zhao, Lele Cao, Qingwei Lin, Saravan Rajmohan, Dongmei Zhang, Qi Zhang \
  EMNLP 2025, [[Paper](https://arxiv.org/abs/2406.13372)]
- **Nissist: An Incident Mitigation Copilot based on Troubleshooting Guides** \
  Kaikai An, Fangkai Yang, <i>**Junting Lu**</i>, Liqun Li, Zhixing Ren, Hao Huang, Lu Wang, Pu Zhao, Yu Kang, Hua Ding, Qingwei Lin, Saravan Rajmohan, Dongmei Zhang, Qi Zhang \
  ECAI 2024, [[Paper](https://arxiv.org/abs/2402.17531)]
- **PMPO: Probabilistic Metric Prompt Optimization for Small and Large Language Models** \
  Chenzhuo Zhao\*, Ziqian Liu\*, Xingda Wang, <i>**Junting Lu**</i>, Chaoyi Ruan \
  EMNLP 2025, [[Paper](https://arxiv.org/abs/2505.16307)]
- **Code-vision: Evaluating multimodal llms logic understanding and code generation capabilities** \
  Hanbin Wang\*, Xiaoxuan Zhou\*, Zhipeng Xu, Keyuan Cheng, Yuxin Zuo, Kai Tian, Jingwei Song, <i>**Junting Lu**</i>, Wenhui Hu, Xueyang Liu \
  Preprint 2025, [[Paper](https://arxiv.org/abs/2502.11829)]
- **TASE: Token Awareness and Structured Evaluation for Multilingual Language Models** \
  Chenzhuo Zhao\*, Xinda Wang\*, Yue Huang, <i>**Junting Lu**</i>, Ziqian Liu \
  Preprint 2025, [[Paper](https://arxiv.org/pdf/2508.05468)]


# 🎖 Honors and Awards
- [2024] Luo Yuehua Scholarship at Peking University
- [2023] Shanxi Province Outstanding Undergraduate at NWPU
- [2022] Huawei Scholarship at NWPU
- [2020,2021,2022] National Scholarship for Undergraduate at NWPU  


# 💻 Internships
- [2025.2-present] Bytedance-Seed (supervised by Dr. [Yujia Qin](https://yujia-qin.github.io/))
- [2024.3-2024.10] Microsoft DKI Group (supervised by Dr. [Fangkai Yang](https://www.microsoft.com/en-us/research/people/fangkaiyang/))
- [2023.8-2024.2] ModelBest && TsinghuaNLP (supervised by Dr. Yinxu Pan, Prof. [Zhiyuan Liu](https://nlp.csai.tsinghua.edu.cn/~lzy/))

# 💡 Lifestyle

- My hobbies include but are not limited to 🎤singing, 🎸guitar, 🧙 magic.
