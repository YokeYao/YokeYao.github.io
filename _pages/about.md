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
<style>
/* 确保网格布局正确显示 */
.blog-grid {
  display: grid !important;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)) !important;
  gap: 1.5rem !important;
  margin: 2rem 0 !important;
}

.blog-card {
  background: #ffffff !important;
  border-radius: 12px !important;
  overflow: hidden !important;
  box-shadow: 0 2px 12px rgba(1, 47, 99, 0.08) !important;
  transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1) !important;
}

.blog-card:hover {
  transform: translateY(-8px) !important;
  box-shadow: 0 8px 25px rgba(1, 47, 99, 0.15) !important;
}

.blog-card-image {
  position: relative !important;
  width: 100% !important;
  height: 200px !important;
  overflow: hidden !important;
}

.blog-card-image img {
  width: 100% !important;
  height: 100% !important;
  object-fit: cover !important;
  transition: transform 0.3s ease !important;
}

.blog-badge {
  position: absolute !important;
  top: 12px !important;
  left: 12px !important;
  background: linear-gradient(135deg, #FE667B 0%, #ff8599 100%) !important;
  color: white !important;
  padding: 0.4em 0.8em !important;
  border-radius: 20px !important;
  font-size: 0.75em !important;
  font-weight: 600 !important;
  box-shadow: 0 2px 8px rgba(254, 102, 123, 0.3) !important;
  z-index: 10 !important;
}

.blog-card-content {
  padding: 1.2rem !important;
}

.blog-title {
  font-size: 1.1rem !important;
  font-weight: 700 !important;
  color: #012F63 !important;
  margin-bottom: 0.8rem !important;
  line-height: 1.3 !important;
}

.blog-description {
  font-size: 0.9rem !important;
  color: #666 !important;
  line-height: 1.5 !important;
  margin-bottom: 1rem !important;
}

.blog-links {
  display: flex !important;
  gap: 0.6rem !important;
  flex-wrap: wrap !important;
}

.blog-link {
  display: inline-flex !important;
  align-items: center !important;
  gap: 0.3rem !important;
  padding: 0.4em 0.8em !important;
  background: linear-gradient(135deg, #FE667B 0%, #ff8599 100%) !important;
  color: white !important;
  text-decoration: none !important;
  border-radius: 20px !important;
  font-size: 0.8rem !important;
  font-weight: 500 !important;
  transition: all 0.3s ease !important;
  box-shadow: 0 2px 8px rgba(254, 102, 123, 0.2) !important;
}

.blog-link:hover {
  transform: translateY(-2px) !important;
  box-shadow: 0 4px 12px rgba(254, 102, 123, 0.3) !important;
  color: white !important;
  text-decoration: none !important;
}

/* 响应式设计 */
@media (max-width: 768px) {
  .blog-grid {
    grid-template-columns: 1fr !important;
    gap: 1rem !important;
  }
  
  .blog-card-image {
    height: 180px !important;
  }
}

@media (min-width: 769px) and (max-width: 1024px) {
  .blog-grid {
    grid-template-columns: repeat(2, 1fr) !important;
  }
}

@media (min-width: 1025px) {
  .blog-grid {
    grid-template-columns: repeat(3, 1fr) !important;
  }
}
</style>

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

My name is <span class="accent-text">Jinxiang Xie</span> (pronounced "JIN-shee-ahng SHEE-eh"). I am an incoming graduate student at <i class="fas fa-university"></i> **Nanjing University**. I earned my Bachelor's degree in Information and Computing Science from <i class="fas fa-university"></i> **Beijing Jiaotong University**. Currently, I am a research intern at <i class="fab fa-microsoft"></i> **Microsoft**, where I have the privilege of working with Principal Researcher <a href="https://www.microsoft.com/en-us/research/people/juding/" class="link-accent">Justin Ding</a>.
Prior to this, I gained valuable research experience at <i class="fas fa-university"></i> **Peking University** under the guidance of Prof. <a href="https://wanxiaojun.github.io/" class="link-accent">Xiaojun Wan</a>.

<div class="quote-accent">
My research focuses on leveraging <span class="primary-gradient-text">Large Language Models</span> to address complex systems. This includes applications in natural language processing for unstructured data, quantitative trading, and advancing scientific discovery.
</div>

**I am actively seeking research assistant opportunities in LLM applications and natural language processing**. Feel free to reach out, or learn more from <a href="assets/Jinxiang's CV.pdf" class="link-accent">My CV</a>.

<div class="highlight-blocks">
  <div class="highlight-block floating-card">
    <h3><i class="fas fa-microscope"></i> AI Researcher</h3>
    <ul>
      <li>Research focus on <span class="accent-text">LLMs and NLP</span></li>
      <li>Internships at <span class="primary-gradient-text">top institutions</span></li>
      <li>Publications at <span class="accent-text">AAAI</span>, <span class="accent-text">ACL</span></li>
    </ul>
  </div>
  
  <div class="highlight-block floating-card">
    <h3><i class="fas fa-pen-fancy"></i> Content Creator</h3>
    <ul>
      <li>Technical blogs with <span class="accent-text">500K+ views</span></li>
      <li>Active on <a href="https://www.xiaohongshu.com/user/profile/60c47bae000000000100b07e" class="link-accent">Xiaohongshu</a></li>
      <li><a href="https://mp.weixin.qq.com/s/5wn3NvB2FBpJD1jK0L4qbQ" class="link-accent">Articles</a> about <span class="primary-gradient-text">Tech & Humanities</span></li>
    </ul>
  </div>
  
  <div class="highlight-block floating-card">
    <h3><i class="fas fa-globe-asia"></i> Life Explorer</h3>
    <ul>
      <li>Visited <span class="accent-text">9 countries</span> worldwide</li>
      <li>Traveled to <span class="accent-text">32 provinces</span> in China</li>
      <li>Rich experience in <span class="primary-gradient-text">social work</span></li>
    </ul>
  </div>
</div>

# <i class="fas fa-fire"></i> News
- *2024.12*: &nbsp;🎉🎉 One paper is accepted by The 39th Annual AAAI Conference on Artificial Intelligence (AAAI 2025). <span class="accent-text">See you in Philadelphia!</span>
- *2024.08*: &nbsp;I have joined <span class="primary-gradient-text">Microsoft</span> as a Research Intern under the guidance of Principal Researcher Justin Ding, where I focus on evaluating and enhancing LLM outputs.

# <i class="fas fa-file-alt"></i> Publications 

<div class='paper-box floating-card'><div class='paper-box-image'><div><div class="badge pulse-accent">AAAI 2025</div><img src='images/Example_page-0001.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**DSGram: Dynamic Weighting Sub-Metrics for Grammartical Error Correction in the Era of Large Language Models**

- **Jinxiang Xie**, Yilin Li, Xunjian Yin, Xiaojun Wan
- In The 39th Annual AAAI Conference on Artificial Intelligence (AAAI-25)
<a href="https://arxiv.org/abs/2412.12832" class="btn-accent">Arxiv</a> <a href="https://github.com/jxtse/GEC-Metrics-DSGram" class="btn-accent">Code</a>

</div>
</div>

# <i class="fas fa-graduation-cap"></i> Educations
- *2025.09 - Present*: &nbsp;Master of Science at <span class="primary-gradient-text">Kuang Yaming Honors School, Nanjing University</span>.
- *2021.09 - 2025.06*: &nbsp;Bachelor of Science in Information and Computing Science, <span class="primary-gradient-text">Beijing Jiaotong University</span>.

# <i class="fas fa-laptop-code"></i> Internships
- *2024.08 - 2025.08*: &nbsp;Research Intern, <a href="https://www.microsoft.com/en-us/research/group/data-knowledge-intelligence/" class="link-accent">Data, Knowledge and Intelligence (DKI) Group</a>, **Microsoft**.
- *2023.11 - 2024.08*: &nbsp;Research Intern, <a href="https://sai.pku.edu.cn/znxyenglish/" class="link-accent">Wangxuan Institute of Computer Technology</a>, **Peking University**.
- *2023.05 - 2023.07*: &nbsp;Summer Workshop Student, <a href="https://www.comp.nus.edu.sg/" class="link-accent">School of Computer</a>, **National University of Singapore**.

# <i class="fas fa-blog"></i> Blogs

<div class="blog-grid">
  <div class="blog-card">
    <div class="blog-card-image">
      <div class="blog-badge">January, 2025</div>
      <img src="images/pic04.jpg" alt="Beyond the Future of AI">
    </div>
    <div class="blog-card-content">
      <div class="blog-title">Beyond the Future of AI: The Dreams and Deceptions of Cryptocurrency</div>
      <div class="blog-description">My vision of the future: from Bitcoin to an AGI-driven decentralized society</div>
      <div class="blog-links">
        <a href="https://mp.weixin.qq.com/s/luu2qEzPnYAuryJ9mYoJ6Q" class="blog-link">
          <i class="fas fa-language"></i> 中文版
        </a>
        <a href="https://jxtse.medium.com/beyond-the-future-of-ai-the-dreams-and-deceptions-of-cryptocurrency-5da8d4bbf69e" class="blog-link">
          <i class="fas fa-globe"></i> English
        </a>
      </div>
    </div>
  </div>

  <div class="blog-card">
    <div class="blog-card-image">
      <div class="blog-badge">November, 2024</div>
      <img src="images/pic05.jpg" alt="LexiMind">
    </div>
    <div class="blog-card-content">
      <div class="blog-title">LexiMind: An Open-Source LLM-Powered Vocabulary Builder</div>
      <div class="blog-description">LexiMind is an AI-powered vocabulary builder that integrates LLM-based translation with smart word retention.</div>
      <div class="blog-links">
        <a href="https://www.xiaohongshu.com/explore/67a48f0d000000001800721c?xsec_token=ABXUfGRE_zHTnXbEyaNmuelNX3M4527lw3zirVu2KJUKA=&xsec_source=pc_user" class="blog-link">
          <i class="fas fa-info-circle"></i> Introduction
        </a>
        <a href="https://github.com/jxtse/LexiMind" class="blog-link">
          <i class="fab fa-github"></i> Project
        </a>
      </div>
    </div>
  </div>

  <div class="blog-card">
    <div class="blog-card-image">
      <div class="blog-badge">July, 2024</div>
      <img src="images/pic02.jpg" alt="NLP Learning Path">
    </div>
    <div class="blog-card-content">
      <div class="blog-title">My NLP Learning Path as a Mathematics Undergraduate Student</div>
      <div class="blog-description">I share my learning path and some insights on natural language processing as a mathematics undergraduate student.</div>
      <div class="blog-links">
        <a href="https://www.xiaohongshu.com/explore/668a35c8000000001e010600?xsec_token=ABl3IEpctnnXxbjsYlUul3nZBcA622VEEpS6zNOEPrxVI=&xsec_source=pc_user" class="blog-link">
          <i class="fas fa-language"></i> 中文版
        </a>
        <a href="https://www.linkedin.com/posts/jinxiang-xie_naturallanguageprocessing-nlp-learningpath-activity-7215638435393359872-dPr8?utm_source=social_share_send&utm_medium=member_desktop_web&rcm=ACoAAEmWk88Bhyvl-E41lfo1McNlpiC4YSsk7WQ" class="blog-link">
          <i class="fas fa-globe"></i> English
        </a>
      </div>
    </div>
  </div>

  <div class="blog-card">
    <div class="blog-card-image">
      <div class="blog-badge">November, 2023</div>
      <img src="images/pic03.jpg" alt="LLMs Technology">
    </div>
    <div class="blog-card-content">
      <div class="blog-title">LLMs: Cutting-Edge Technology and Future Applications</div>
      <div class="blog-description">My notes from a presentation on LLMs at the Gaoling School of Artificial Intelligence, Renmin University of China.</div>
      <div class="blog-links">
        <a href="https://mp.weixin.qq.com/s?__biz=Mzg5NzczMzM3MA==&mid=2247483926&idx=1&sn=c6dcaf93ec8d7ecaa760df4682589b21" class="blog-link">
          <i class="fas fa-language"></i> 中文版
        </a>
      </div>
    </div>
  </div>

  <div class="blog-card">
    <div class="blog-card-image">
      <div class="blog-badge">August, 2023</div>
      <img src="images/pic01.jpg" alt="Prompt Engineering">
    </div>
    <div class="blog-card-content">
      <div class="blog-title">Prompt Engineering: How to Better Ask LLMs</div>
      <div class="blog-description">Introduce a number of methods for optimizing the output of large language models and reducing the probability of irrelevant or incorrect responses.</div>
      <div class="blog-links">
        <a href="https://sspai.com/post/82322" class="blog-link">
          <i class="fas fa-language"></i> 中文版
        </a>
      </div>
    </div>
  </div>
</div>