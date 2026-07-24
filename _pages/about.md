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

My name is Yue Li (李越). I am currently a master's student at the School of Computer Science and Technology, [East China Normal University](https://www.ecnu.edu.cn/), under the supervision of Professor [Linlin Wang](https://scholar.google.com/citations?user=AeLAUE4AAAAJ&hl=zh-CN). My primary collaborator, Dr. [Xin Yi](https://scholar.google.com/citations?user=WZ2FVkcAAAAJ&hl=zh-CN), provides me with invaluable guidance and support throughout my studies. Prior to this, I earned my BEng degree from [Xiangtan University](https://www.xtu.edu.cn/), where I was mentored by Associate Professor [Xuan Lin](https://scholar.google.com/citations?hl=zh-CN&user=8B0t8AYAAAAJ).

In 2026, I started my industry internships. I first joined the Shanghai Artificial Intelligence Laboratory on the Xuhui West Bund in Shanghai, where I spent a rewarding few months with my supportive mentor and colleagues. I then moved to Ant Group in Hangzhou, where I investigated the inherent safety of large language models, particularly in reinforcement learning (RL) and on-policy distillation (OPD) for agents.

My research interests mainly lie in Trustworthy AI and Model Post-Training (current focus). I have published 5+ papers <a href='https://scholar.google.com/citations?user=Tyk8UuwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a> at the top international AI conferences and journals such as ACL, KDD, KBS and ESWA. 

# 🔥 News
- *2026.06*: 💼 I joined Ant Group as a research intern in Hangzhou.
- *2026.05*: 🎉 My first-authored paper has been accepted to KDD 2026!
- *2026.04*: 💼 I joined Shanghai AI Lab (Pjlab) as a research intern in Shanghai.
- *2025.05*: 🎉 My first-authored paper has been accepted to ACL 2025!

{% include_relative includes/pub.md %}

# 💼 Internships
<div style="display: flex; align-items: flex-start; gap: 18px; margin-bottom: 20px; padding: 16px; border-radius: 8px; background: #f8f9fa;">
  <div style="flex-shrink: 0;">
    <div style="border: 1px solid #e0e0e0; border-radius: 8px; overflow: hidden; background: white; padding: 10px;">
      <img src="https://TheShineyue.github.io/images/Ant_Group_logo.svg.png" alt="Ant Group" style="width: 125px; height: 110px; object-fit: contain; display: block;">
    </div>
  </div>
  <div style="flex: 1;">
    <strong>Ant Group</strong>, Security and Risk Management | Hangzhou<br>
    <ul style="margin-top: 6px; margin-bottom: 0; padding-left: 20px;">
      <li><strong>Duration:</strong> June 2026 – Present</li>
      <li><strong>Mentors:</strong> Feng Wen and Qiu Zhi</li>
      <li><strong>Focus:</strong> Intrinsic safety of LLMs, with a particular emphasis on agent tool calling, including agentic reinforcement learning and on-policy distillation.</li>
    </ul>
  </div>
</div>

<div style="display: flex; align-items: flex-start; gap: 18px; margin-bottom: 20px; padding: 16px; border-radius: 8px; background: #f8f9fa;">
  <div style="flex-shrink: 0;">
    <div style="border: 1px solid #e0e0e0; border-radius: 8px; overflow: hidden; background: white; padding: 10px;">
      <img src="/images/ailab-logo.png" alt="Shanghai AI Lab" style="width: 125px; height: 110px; object-fit: contain; display: block;">
    </div>
  </div>
  <div style="flex: 1;">
    <strong>Shanghai AI Laboratory</strong>, Center for Safe and Trustworthy AI | Shanghai<br>
    <ul style="margin-top: 6px; margin-bottom: 0; padding-left: 20px;">
      <li><strong>Duration:</strong> April 2026 – June 2026</li>
      <li><strong>Mentor:</strong> Jie Li</li>
      <li><strong>Focus:</strong> LLM/Agent Safety, including participation in the construction of the OpenClaw evaluation benchmark and support for safety testing of the Intern series models.</li>
    </ul>
  </div>
</div>

# 🎖 Honors and Awards
- *2025.10*, East China Normal University Outstanding Academic Scholarship (First Prize)
- *2023.05*, The 2023 China College Student Programming Competition (CCPC) National Invitational (Hunan), Silver Medal
- *2022.04*, The 46th International Collegiate Programming Contest (ICPC) Asian Regional Competition (Kunming), Bronze Medal
 
# 🎓 Education
- *2024.09 - Present*, Master of Engineering, <img src='./images/ecnu.png' style="height: 1.2em; vertical-align: middle; margin-right: 0.3em;">East China Normal University, Shanghai.
- *2020.09 - 2024.06*, Bachelor of Engineering, <img src='./images/xtu.jpg' style="height: 1.2em; vertical-align: middle; margin-right: 0.3em;">Xiangtan University, Xiangtan.
  
# 📋 Academic Services
- The ACM Web Conference (The International World Wide Web Conference, WWW)
- Association for the Advancement of Artificial Intelligence (AAAI)
- IEEE/INNS International Joint Conference on Neural Networks (IJCNN)
- Association for Computational Linguistics Rolling Review (ARR)
