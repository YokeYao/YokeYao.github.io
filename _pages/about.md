---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

My name is <span class="accent-text">Junchi Yao</span> (pronounced "JOON-chee YOW"). I am doing my sophmore year in Information System and Information Management from <i class="fas fa-university"></i> **University of Electronic Science and Technology of China (UESTC)**. Currently, I am a research intern at <i class="fas fa-university"></i> **Shanghai AI Lab**, where I have the privilege of working with Researcher <a href="https://openreview.net/profile?id=~Peng_Ye4" class="link-accent">Peng Ye</a>.
Before that, I gained valuable research experience as a research intern at <i class="fas fa-university"></i> **King Abdullah University of Science and Technology (KAUST)** under the guidance of Prof. <a href="https://shao3wangdi.github.io/" class="link-accent">Di Wang</a>.

<div class="quote-accent">
My research focuses on <span class="primary-gradient-text">Large Language Models</span>, particularly in explainability (XAI), LLM agents, and LLM4Science, including social science and physics. My goal is to advance LLM development for interpretable, robust, and impactful real-world applications.
</div>

**I am actively seeking research collaborators, whether you are new or experienced.**. Feel free to reach out, or learn more from <a href="assets/Junchi Yao CV 9.21.pdf" class="link-accent">My CV</a>.

<div class="highlight-blocks">
  <div class="highlight-block floating-card">
    <h3><i class="fas fa-microscope"></i> AI Researcher</h3>
    <ul>
      <li>Research focus on <span class="accent-text">LLMs</span></li>
      <li>Internships at <span class="primary-gradient-text">Shanghai AI Lab</span></li>
      <li>Publications at <span class="accent-text">ACL, NeurIPS</span></li>
    </ul>
  </div>
  
  <!-- <div class="highlight-block floating-card">
    <h3><i class="fas fa-pen-fancy"></i> Content Creator</h3>
    <ul>
      <li>Technical blogs with <span class="accent-text">500K+ views</span></li>
      <li>Active on <a href="https://www.xiaohongshu.com/user/profile/60c47bae000000000100b07e" class="link-accent">Xiaohongshu</a></li>
      <li><a href="https://mp.weixin.qq.com/s/5wn3NvB2FBpJD1jK0L4qbQ" class="link-accent">Articles</a> about <span class="primary-gradient-text">Tech & Humanities</span></li>
    </ul>
  </div> -->
  
  <div class="highlight-block floating-card">
    <h3><i class="fas fa-globe-asia"></i> World Explorer</h3>
    <ul>
      <li>Visited <span class="accent-text">12 countries</span> worldwide</li>
      <li>Traveled to <span class="accent-text">27 provinces</span> in China</li>
      <li>Rich experience in <span class="primary-gradient-text">hiking</span></li>
    </ul>
  </div>
</div>

# <i class="fas fa-fire"></i> News
- *2025.09*：&nbsp;🎉 1 Paper is accepted by The Thirty-Ninth Annual Conference on Neural Information Processing Systems (NeurIPS 2025). <span class="accent-text">See you in San Diago, America!</span>
- *2025.06*: &nbsp;🎉 1 Paper is accepted by The 42nd International Conference on Machine Learning（ICML 2025）Multi-Agent System Workshop.
- *2025.05*：&nbsp;🎉 2 Papers are accepted by The 63rd Annual Meeting of the Association for Computational Linguistics (ACL 2025) Findings. <span class="accent-text">See you in Vienna, Austria!</span>
- *2025.04*：&nbsp;🎉 1 Paper is accepted by Nature - Scientific Reports.
- *2025.03*: &nbsp;I have joined <span class="primary-gradient-text">Shanghai AI Lab</span> as a Research Intern under the guidance of Researcher Peng Ye, where I focus on LLM Agents and LLM for Physics.
# <i class="fas fa-file-alt"></i> Publications 

<div class='paper-box floating-card'>
  <div class='paper-box-image'>
    <div class="badge pulse-accent">NeurIPS 2025</div>
    <img src='images/scaling-physics.png' alt="Pipeline of PHYSICS Dataset" width="100%">
  </div>
  <div class='paper-box-text'>
    <h3>Scaling Physical Reasoning with the PHYSICS Dataset</h3>
    <div class="authors">Shenghe Zheng*, Qianjia Cheng*, <strong><u>Junchi Yao*</u></strong>, Mengsong Wu, Haonan He, Ning Ding, Yu Cheng, Shuyue Hu, Lei Bai, Dongzhan Zhou, Ganqu Cui, Peng Ye</div>
    <div class="venue">NeurIPS 2025</div>
    <div class="links">
      <a href="https://arxiv.org/pdf/2506.00022" class="btn-accent"><i class="fas fa-file-alt"></i> Paper</a>
      <a href="https://github.com/Zhengsh123/PHYSICS.git" class="btn-accent"><i class="fab fa-github"></i> Code</a>
    </div>
  </div>
</div>

<div class='paper-box floating-card'>
  <div class='paper-box-image'>
    <div class="badge pulse-accent">ICML 2025 Workshop</div>
    <img src='images/wandaplan.png' alt="WandaPlan's Framework" width="100%">
  </div>
  <div class='paper-box-text'>
    <h3>Is Your LLM-Based Multi-Agent a Reliable Real-World Planner? Exploring Fraud Detection in Travel Planning</h3>
    <div class="authors"><strong><u>Junchi Yao*</u></strong>, Jianhua Xu*, Tianyu Xin*, Ziyi Wang, Shenzhe Zhu, Shu Yang, Di Wang</div>
    <div class="venue">The 42nd International Conference on Machine Learning（ICML 2025）Multi-Agent System Workshop</div>
    <div class="links">
      <a href="https://arxiv.org/pdf/2505.16557" class="btn-accent"><i class="fas fa-file-alt"></i> Paper</a>
      <a href="#" class="btn-accent"><i class="fab fa-github"></i> Code (Incoming)</a>
    </div>
  </div>
</div>

<div class='paper-box floating-card'>
  <div class='paper-box-image'>
    <div class="badge pulse-accent">ACL 2025 Findings</div>
    <img src='images/repeat-curse.png' alt="Repeat Curse Framework" width="100%">
  </div>
  <div class='paper-box-text'>
    <h3>Understanding the Repeat Curse in Large Language Models from a Feature Perspective</h3>
    <div class="authors"><strong><u>Junchi Yao*</u></strong>, Shu Yang*, Jianhua Xu, Lijie Hu, Mengdi Li, Di Wang</div>
    <div class="venue">In The 63rd Annual Meeting of the Association for Computational Linguistics (ACL 2025) Findings</div>
    <div class="links">
      <a href="https://arxiv.org/pdf/2504.14218" class="btn-accent"><i class="fas fa-file-alt"></i> ArXiv</a>
      <a href="https://github.com/kaustpradalab/repeat-curse-llm" class="btn-accent"><i class="fab fa-github"></i> Code</a>
    </div>
  </div>
</div>

<div class='paper-box floating-card'>
  <div class='paper-box-image'>
    <div class="badge pulse-accent">ACL 2025 Findings</div>
    <img src='images/fraud-r1-copy.png' alt="Fraud-R1 Pipeline" width="100%">
  </div>
  <div class='paper-box-text'>
    <h3>Fraud-R1 : A Multi-Round Benchmark for Assessing the Robustness of LLM Against Augmented Fraud and Phishing Inducements</h3>
    <div class="authors">Shu Yang*, Shenzhe Zhu*, Zeyu Wu, Keyu Wang, <strong><u>Junchi Yao</u></strong>, Junchao Wu, Lijie Hu, Mengdi Li, Derek F. Wong, Di Wang</div>
    <div class="venue">In The 63rd Annual Meeting of the Association for Computational Linguistics (ACL 2025) Findings</div>
    <div class="links">
      <a href="https://arxiv.org/pdf/2502.12904" class="btn-accent"><i class="fas fa-file-alt"></i> ArXiv</a>
      <a href="https://github.com/kaustpradalab/Fraud-R1?utm_source=catalyzex.com" class="btn-accent"><i class="fab fa-github"></i> Code</a>
    </div>
  </div>
</div>

<div class='paper-box floating-card'>
  <div class='paper-box-image'>
    <div class="badge pulse-accent">Nature SR</div>
    <img src='images/socialagent.png' alt="Social Opinion Prediction Framework" width="100%">
  </div>
  <div class='paper-box-text'>
    <h3>Social opinions prediction utilizes fusing dynamics equation with LLM-based agents</h3>
    <div class="authors"><strong><u>Junchi Yao*</u></strong>, Hongjie Zhang*, Jie Ou, Dingyi Zuo, Zheng Yang, Zhicheng Dong</div>
    <div class="venue">Nature Scientific Reports</div>
    <div class="links">
      <a href="https://www.nature.com/articles/s41598-025-99704-3" class="btn-accent"><i class="fas fa-file-alt"></i> ArXiv</a>
      <!-- <a href="https://github.com/kaustpradalab/Fraud-R1?utm_source=catalyzex.com" class="btn-accent"><i class="fab fa-github"></i> Code</a> -->
    </div>
  </div>
</div>

# <i class="fas fa-graduation-cap"></i> Educations
<!-- - *2025.09 - Present*: &nbsp;Master of Science at <span class="primary-gradient-text">Kuang Yaming Honors School, Nanjing University</span>. -->
- *2022.09 - 2026.06*: &nbsp;Bachelor of Engineer in Information System and Information Management, <span class="primary-gradient-text">University of Electronic Science and Technology of China</span>.
- *2023.11 - 2024.04*: &nbsp;<a href="https://yfel.ku.ac.ae/yfel/" class="link-accent">Young Future Energy Leader Programme Student</a>, <span class="primary-gradient-text">Khalifa University</span>.
# <i class="fas fa-laptop-code"></i> Internships
- *2025.03 - Present*: &nbsp;Research Intern, <a href="https://www.shlab.org.cn/" class="link-accent">AI4Science</a>, **Shanghai AI Lab**.
- *2024.07 - 2025.03*：&nbsp;LLM Agent Engineer, <a href="https://mountainguests.com" class="link-accent">Product Design and R&D Department</a>, **GoAfarAI (Startup)**.
- *2024.06 - 2025.06*: &nbsp;Research Intern, <a href="https://pradalab1.github.io/" class="link-accent">Provable Responsible Al and Data Analytics Lab</a>, **KAUST**.
- *2024.04 - 2025.02*: &nbsp;Research Intern, <a href="https://cs.sicnu.edu.cn/" class="link-accent">School of Computer Science</a>, **Sichuan Normal University**.