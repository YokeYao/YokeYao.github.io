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
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&family=JetBrains+Mono:ital,wght@0,300;0,400;0,500;0,600;0,700;0,800;1,300;1,400;1,500;1,600;1,700;1,800&display=swap" rel="stylesheet">
<style>
  :root {
    /* 高端配色方案 */
    --primary-dark: #0a0e27;
    --primary-blue: #1e3a8a;
    --accent-blue: #3b82f6;
    --accent-emerald: #10b981;
    --accent-gold: #f59e0b;
    --text-primary: #0f172a;
    --text-secondary: #475569;
    --text-tertiary: #64748b;
    --bg-primary: #ffffff;
    --bg-secondary: #f8fafc;
    --bg-tertiary: #f1f5f9;
    --border-primary: #e2e8f0;
    --border-secondary: #cbd5e1;
    --shadow-sm: 0 1px 2px 0 rgba(0, 0, 0, 0.05);
    --shadow-md: 0 4px 6px -1px rgba(0, 0, 0, 0.1), 0 2px 4px -1px rgba(0, 0, 0, 0.06);
    --shadow-lg: 0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -2px rgba(0, 0, 0, 0.05);
    --shadow-xl: 0 20px 25px -5px rgba(0, 0, 0, 0.1), 0 10px 10px -5px rgba(0, 0, 0, 0.04);
    --gradient-primary: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    --gradient-secondary: linear-gradient(135deg, #f093fb 0%, #f5576c 100%);
    --gradient-accent: linear-gradient(135deg, #4facfe 0%, #00f2fe 100%);
    --gradient-emerald: linear-gradient(135deg, #10b981 0%, #059669 100%);
    --gradient-gold: linear-gradient(135deg, #f59e0b 0%, #d97706 100%);
    --border-radius: 16px;
    --transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
  }

  * {
    box-sizing: border-box;
  }

  body {
    font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
    line-height: 1.6;
    color: var(--text-primary);
    background: var(--bg-primary);
    margin: 0;
    padding: 0;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
  }

  /* 全局样式重置和优化 */
  .page__inner-wrap {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 2rem;
  }

  /* 优雅的排版 */
  h1, h2, h3, h4, h5, h6 {
    font-weight: 600;
    line-height: 1.2;
    margin-bottom: 1rem;
    color: var(--text-primary);
  }

  h1 {
    font-size: 2.5rem;
    font-weight: 700;
  }

  h2 {
    font-size: 2rem;
    font-weight: 600;
  }

  h3 {
    font-size: 1.5rem;
    font-weight: 600;
  }

  /* 改进的链接样式 */
  a {
    color: var(--accent-blue);
    text-decoration: none;
    transition: var(--transition);
    position: relative;
  }

  a:hover {
    color: var(--primary-blue);
  }

  .link-accent {
    color: var(--accent-blue);
    font-weight: 500;
    position: relative;
    text-decoration: none;
    padding-bottom: 2px;
  }

  .link-accent::after {
    content: '';
    position: absolute;
    bottom: 0;
    left: 0;
    width: 0;
    height: 2px;
    background: var(--gradient-accent);
    transition: width 0.3s ease;
  }

  .link-accent:hover::after {
    width: 100%;
  }

  /* 高端标题设计 */
  .section-title {
    font-size: 2.5rem;
    font-weight: 700;
    color: var(--text-primary);
    margin-bottom: 3rem;
    text-align: center;
    position: relative;
    padding-bottom: 1rem;
  }

  .section-title::after {
    content: '';
    position: absolute;
    bottom: 0;
    left: 50%;
    transform: translateX(-50%);
    width: 60px;
    height: 4px;
    background: var(--gradient-primary);
    border-radius: 2px;
  }

  .section-title.left {
    text-align: left;
  }

  .section-title.left::after {
    left: 0;
    transform: none;
  }

  /* 个人信息区域 */
  .hero-section {
    background: linear-gradient(135deg, var(--bg-secondary) 0%, var(--bg-primary) 100%);
    border-radius: var(--border-radius);
    padding: 3rem;
    margin-bottom: 4rem;
    border: 1px solid var(--border-primary);
    position: relative;
    overflow: hidden;
  }

  .hero-section::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    height: 1px;
    background: var(--gradient-primary);
  }

  .hero-content {
    position: relative;
    z-index: 1;
  }

  .hero-title {
    font-size: 3rem;
    font-weight: 800;
    color: var(--text-primary);
    margin-bottom: 1rem;
    line-height: 1.2;
  }

  .hero-subtitle {
    font-size: 1.5rem;
    color: var(--text-secondary);
    margin-bottom: 2rem;
    font-weight: 400;
  }

  .hero-description {
    font-size: 1.125rem;
    color: var(--text-secondary);
    line-height: 1.7;
    margin-bottom: 2rem;
    max-width: 800px;
  }

  .accent-text {
    color: var(--accent-blue);
    font-weight: 600;
  }

  .primary-gradient-text {
    background: var(--gradient-primary);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
    font-weight: 600;
  }

  /* 高亮块设计 */
  .highlight-blocks {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 2rem;
    margin: 3rem 0;
  }

  .highlight-block {
    background: var(--bg-primary);
    border: 1px solid var(--border-primary);
    border-radius: var(--border-radius);
    padding: 2rem;
    box-shadow: var(--shadow-sm);
    transition: var(--transition);
    position: relative;
    overflow: hidden;
  }

  .highlight-block::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 3px;
    background: var(--gradient-primary);
    transform: scaleX(0);
    transition: transform 0.3s ease;
  }

  .highlight-block:hover {
    transform: translateY(-4px);
    box-shadow: var(--shadow-lg);
    border-color: var(--accent-blue);
  }

  .highlight-block:hover::before {
    transform: scaleX(1);
  }

  .highlight-block h3 {
    font-size: 1.25rem;
    font-weight: 600;
    color: var(--text-primary);
    margin-bottom: 1rem;
    display: flex;
    align-items: center;
    gap: 0.5rem;
  }

  .highlight-block h3 i {
    color: var(--accent-blue);
    font-size: 1.2rem;
  }

  .highlight-block ul {
    list-style: none;
    padding: 0;
    margin: 0;
  }

  .highlight-block li {
    color: var(--text-secondary);
    margin-bottom: 0.5rem;
    padding-left: 1.5rem;
    position: relative;
  }

  .highlight-block li::before {
    content: '▸';
    position: absolute;
    left: 0;
    color: var(--accent-blue);
    font-weight: 600;
  }

  /* 新闻时间线 */
  .news-timeline {
    position: relative;
    padding-left: 2rem;
  }

  .news-timeline::before {
    content: '';
    position: absolute;
    left: 0;
    top: 0;
    bottom: 0;
    width: 2px;
    background: var(--border-secondary);
  }

  .news-item {
    position: relative;
    margin-bottom: 2rem;
    padding-left: 2rem;
  }

  .news-item::before {
    content: '';
    position: absolute;
    left: -2.5rem;
    top: 0.5rem;
    width: 12px;
    height: 12px;
    border-radius: 50%;
    background: var(--accent-blue);
    border: 3px solid var(--bg-primary);
    box-shadow: 0 0 0 3px var(--border-secondary);
  }

  .news-date {
    font-size: 0.875rem;
    color: var(--text-tertiary);
    font-weight: 500;
    margin-bottom: 0.5rem;
  }

  .news-content {
    color: var(--text-secondary);
    line-height: 1.6;
  }

  /* 教育经历样式 */
  .education-item {
    background: var(--bg-primary);
    border: 1px solid var(--border-primary);
    border-radius: var(--border-radius);
    padding: 1.5rem;
    margin-bottom: 1rem;
    transition: var(--transition);
  }

  .education-item:hover {
    border-color: var(--accent-blue);
    box-shadow: var(--shadow-md);
  }

  .education-degree {
    font-size: 1.125rem;
    font-weight: 600;
    color: var(--text-primary);
    margin-bottom: 0.5rem;
  }

  .education-school {
    color: var(--text-secondary);
    font-size: 1rem;
    margin-bottom: 0.25rem;
  }

  .education-date {
    color: var(--text-tertiary);
    font-size: 0.875rem;
  }

  /* 实习经历样式 */
  .internship-item {
    background: var(--bg-primary);
    border: 1px solid var(--border-primary);
    border-radius: var(--border-radius);
    padding: 1.5rem;
    margin-bottom: 1rem;
    transition: var(--transition);
    border-left: 4px solid var(--accent-gold);
  }

  .internship-item:hover {
    border-color: var(--accent-gold);
    box-shadow: var(--shadow-md);
  }

  .internship-position {
    font-size: 1.125rem;
    font-weight: 600;
    color: var(--text-primary);
    margin-bottom: 0.5rem;
  }

  .internship-company {
    color: var(--text-secondary);
    font-size: 1rem;
    margin-bottom: 0.25rem;
  }

  .internship-date {
    color: var(--text-tertiary);
    font-size: 0.875rem;
  }

  /* 按钮样式 */
  .btn-primary {
    display: inline-flex;
    align-items: center;
    gap: 0.5rem;
    padding: 0.75rem 1.5rem;
    background: var(--gradient-primary);
    color: white;
    text-decoration: none;
    border-radius: 25px;
    font-weight: 500;
    font-size: 0.875rem;
    transition: var(--transition);
    box-shadow: var(--shadow-md);
    border: 1px solid rgba(255, 255, 255, 0.2);
  }

  .btn-primary:hover {
    transform: translateY(-2px);
    box-shadow: var(--shadow-lg);
    color: white;
    text-decoration: none;
  }

  .btn-secondary {
    background: var(--bg-secondary);
    color: var(--text-primary);
    border: 1px solid var(--border-primary);
    box-shadow: none;
  }

  .btn-secondary:hover {
    background: var(--bg-tertiary);
    border-color: var(--accent-blue);
  }

  /* 高端动画效果 */
  @keyframes fadeInUp {
    from {
      opacity: 0;
      transform: translateY(30px);
    }
    to {
      opacity: 1;
      transform: translateY(0);
    }
  }

  @keyframes slideInLeft {
    from {
      opacity: 0;
      transform: translateX(-50px);
    }
    to {
      opacity: 1;
      transform: translateX(0);
    }
  }

  @keyframes slideInRight {
    from {
      opacity: 0;
      transform: translateX(50px);
    }
    to {
      opacity: 1;
      transform: translateX(0);
    }
  }

  @keyframes pulse {
    0%, 100% {
      transform: scale(1);
    }
    50% {
      transform: scale(1.05);
    }
  }

  @keyframes shimmer {
    0% {
      background-position: -1000px 0;
    }
    100% {
      background-position: 1000px 0;
    }
  }

  /* 应用动画 */
  .hero-section {
    animation: fadeInUp 0.8s ease-out;
  }

  .highlight-block {
    animation: fadeInUp 0.8s ease-out;
    animation-fill-mode: both;
  }

  .highlight-block:nth-child(1) {
    animation-delay: 0.2s;
  }

  .highlight-block:nth-child(2) {
    animation-delay: 0.4s;
  }

  .highlight-block:nth-child(3) {
    animation-delay: 0.6s;
  }

  .publication-box {
    animation: fadeInUp 0.8s ease-out;
    animation-fill-mode: both;
  }

  .publication-box:nth-child(1) {
    animation-delay: 0.2s;
  }

  .publication-box:nth-child(2) {
    animation-delay: 0.4s;
  }

  .blog-card {
    animation: fadeInUp 0.8s ease-out;
    animation-fill-mode: both;
  }

  .blog-card:nth-child(1) {
    animation-delay: 0.2s;
  }

  .blog-card:nth-child(2) {
    animation-delay: 0.4s;
  }

  .blog-card:nth-child(3) {
    animation-delay: 0.6s;
  }

  /* 高光效果 */
  .shimmer {
    background: linear-gradient(90deg, transparent, rgba(255, 255, 255, 0.4), transparent);
    background-size: 1000px 100%;
    animation: shimmer 2s infinite;
  }

  /* 悬浮效果增强 */
  .premium-card:hover,
  .blog-card:hover,
  .publication-box:hover,
  .highlight-block:hover {
    transform: translateY(-8px) scale(1.02);
  }

  /* 滚动显示动画 */
  .scroll-reveal {
    opacity: 0;
    transform: translateY(50px);
    transition: all 0.8s cubic-bezier(0.4, 0, 0.2, 1);
  }

  .scroll-reveal.active {
    opacity: 1;
    transform: translateY(0);
  }

  /* 高端渐变文字效果 */
  .gradient-text {
    background: linear-gradient(135deg, var(--accent-blue), var(--accent-emerald));
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
    font-weight: 600;
  }

  .gradient-text-gold {
    background: var(--gradient-gold);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
    font-weight: 600;
  }

  /* 玻璃态效果 */
  .glass-effect {
    background: rgba(255, 255, 255, 0.1);
    backdrop-filter: blur(10px);
    border: 1px solid rgba(255, 255, 255, 0.2);
    box-shadow: 0 8px 32px 0 rgba(31, 38, 135, 0.37);
  }

  /* 加载动画 */
  .loading-skeleton {
    background: linear-gradient(90deg, #f0f0f0 25%, #e0e0e0 50%, #f0f0f0 75%);
    background-size: 200% 100%;
    animation: shimmer 1.5s infinite;
  }

  /* 打字机效果 */
  .typewriter {
    overflow: hidden;
    border-right: .15em solid var(--accent-blue);
    white-space: nowrap;
    animation: typing 3.5s steps(40, end), blink-caret .75s step-end infinite;
  }

  @keyframes typing {
    from { width: 0 }
    to { width: 100% }
  }

  @keyframes blink-caret {
    from, to { border-color: transparent }
    50% { border-color: var(--accent-blue); }
  }

  /* 3D 卡片效果 */
  .card-3d {
    transform-style: preserve-3d;
    transition: transform 0.6s;
  }

  .card-3d:hover {
    transform: rotateY(5deg) rotateX(5deg);
  }

  /* 移动端深度优化 */
  @media (max-width: 768px) {
    .hero-title {
      font-size: 2rem;
      line-height: 1.2;
    }
    
    .hero-subtitle {
      font-size: 1.2rem;
      line-height: 1.4;
    }
    
    .hero-description {
      font-size: 1rem;
      line-height: 1.6;
    }
    
    .section-title {
      font-size: 2rem;
      margin-bottom: 2rem;
    }
    
    .highlight-blocks {
      grid-template-columns: 1fr;
      gap: 1.5rem;
      margin: 2rem 0;
    }
    
    .publication-box,
    .education-item,
    .internship-item {
      margin-bottom: 1.5rem;
    }
    
    .publication-box {
      flex-direction: column;
      padding: 1rem;
    }
    
    .publication-image {
      width: 100%;
      height: 200px;
      margin: 0 0 1rem 0;
    }
    
    .publication-content {
      padding: 0 1rem;
    }
    
    .publication-title {
      font-size: 1.25rem;
    }
    
    .publication-authors {
      font-size: 0.9rem;
    }
    
    .publication-venue {
      font-size: 0.85rem;
    }
    
    .publication-links {
      flex-direction: column;
      gap: 0.5rem;
    }
    
    .publication-link {
      justify-content: center;
      text-align: center;
    }
    
    .blog-grid {
      grid-template-columns: 1fr;
      gap: 1.5rem;
      margin: 2rem 0;
    }
    
    .blog-card {
      margin-bottom: 1.5rem;
    }
    
    .blog-card-image {
      height: 180px;
    }
    
    .blog-card-content {
      height: auto;
      padding: 1.5rem;
    }
    
    .blog-title {
      font-size: 1.1rem;
    }
    
    .blog-description {
      font-size: 0.9rem;
    }
    
    .blog-links {
      flex-direction: column;
      gap: 0.5rem;
    }
    
    .btn-primary {
      width: 100%;
      justify-content: center;
      padding: 0.875rem 1.5rem;
    }
    
    .news-timeline {
      padding-left: 1.5rem;
    }
    
    .news-item {
      padding-left: 1.5rem;
      margin-bottom: 1.5rem;
    }
    
    .news-item::before {
      left: -2rem;
      width: 10px;
      height: 10px;
    }
    
    .page__inner-wrap {
      padding: 0 1rem;
    }
    
    .hero-section {
      padding: 2rem 1.5rem;
      margin-bottom: 3rem;
    }
    
    .education-item,
    .internship-item {
      padding: 1.25rem;
    }
    
    .education-degree,
    .internship-position {
      font-size: 1rem;
    }
    
    .education-school,
    .internship-company {
      font-size: 0.9rem;
    }
    
    .education-date,
    .internship-date {
      font-size: 0.8rem;
    }
  }

  /* 平板端优化 */
  @media (min-width: 769px) and (max-width: 1024px) {
    .hero-title {
      font-size: 2.5rem;
    }
    
    .hero-subtitle {
      font-size: 1.4rem;
    }
    
    .section-title {
      font-size: 2.2rem;
    }
    
    .highlight-blocks {
      grid-template-columns: repeat(2, 1fr);
      gap: 1.5rem;
    }
    
    .publication-image {
      width: 260px;
      height: 180px;
    }
    
    .blog-grid {
      grid-template-columns: repeat(2, 1fr);
      gap: 1.5rem;
    }
    
    .page__inner-wrap {
      padding: 0 1.5rem;
    }
  }

  /* 大屏幕优化 */
  @media (min-width: 1025px) {
    .hero-title {
      font-size: 3.5rem;
    }
    
    .hero-subtitle {
      font-size: 1.6rem;
    }
    
    .hero-description {
      font-size: 1.25rem;
    }
    
    .section-title {
      font-size: 2.8rem;
    }
    
    .highlight-blocks {
      grid-template-columns: repeat(3, 1fr);
      gap: 2rem;
    }
    
    .blog-grid {
      grid-template-columns: repeat(3, 1fr);
      gap: 2rem;
    }
    
    .page__inner-wrap {
      padding: 0 3rem;
    }
  }
/* 高端卡片设计 */
.premium-card {
  background: var(--bg-primary);
  border-radius: var(--border-radius);
  border: 1px solid var(--border-primary);
  box-shadow: var(--shadow-sm);
  transition: var(--transition);
  overflow: hidden;
  position: relative;
}

.premium-card::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  height: 1px;
  background: var(--gradient-primary);
  opacity: 0;
  transition: opacity 0.3s ease;
}

.premium-card:hover {
  transform: translateY(-4px);
  box-shadow: var(--shadow-xl);
  border-color: var(--accent-blue);
}

.premium-card:hover::before {
  opacity: 1;
}

/* 确保网格布局正确显示 */
.blog-grid {
  display: grid !important;
  grid-template-columns: repeat(auto-fit, minmax(320px, 1fr)) !important;
  gap: 2rem !important;
  margin: 3rem 0 !important;
}

.blog-card {
  background: var(--bg-primary) !important;
  border-radius: var(--border-radius) !important;
  border: 1px solid var(--border-primary) !important;
  overflow: hidden !important;
  box-shadow: var(--shadow-md) !important;
  transition: var(--transition) !important;
  position: relative;
}

.blog-card::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  height: 3px;
  background: var(--gradient-secondary);
  transform: scaleX(0);
  transition: transform 0.3s ease;
}

.blog-card:hover {
  transform: translateY(-8px) !important;
  box-shadow: var(--shadow-xl) !important;
  border-color: var(--accent-blue) !important;
}

.blog-card:hover::before {
  transform: scaleX(1);
}

.blog-card-image {
  position: relative !important;
  width: 100% !important;
  height: 220px !important;
  overflow: hidden !important;
  background: var(--bg-secondary);
}

.blog-card-image img {
  width: 100% !important;
  height: 100% !important;
  object-fit: cover !important;
  transition: transform 0.5s cubic-bezier(0.4, 0, 0.2, 1) !important;
}

.blog-card:hover .blog-card-image img {
  transform: scale(1.05);
}

.blog-badge {
  position: absolute !important;
  top: 16px !important;
  left: 16px !important;
  background: var(--gradient-primary) !important;
  color: white !important;
  padding: 0.5em 1em !important;
  border-radius: 20px !important;
  font-size: 0.75em !important;
  font-weight: 600 !important;
  box-shadow: var(--shadow-lg) !important;
  z-index: 10 !important;
  backdrop-filter: blur(10px);
  border: 1px solid rgba(255, 255, 255, 0.2);
}

.blog-card-content {
  padding: 1.5rem !important;
  display: flex !important;
  flex-direction: column !important;
  height: calc(100% - 220px);
}

.blog-title {
  font-size: 1.125rem !important;
  font-weight: 600 !important;
  color: var(--text-primary) !important;
  margin-bottom: 0.75rem !important;
  line-height: 1.4 !important;
  flex-grow: 0;
}

.blog-description {
  font-size: 0.875rem !important;
  color: var(--text-secondary) !important;
  line-height: 1.6 !important;
  margin-bottom: 1rem !important;
  flex-grow: 1;
}

.blog-links {
  display: flex !important;
  gap: 0.75rem !important;
  flex-wrap: wrap !important;
  align-items: center !important;
  margin-top: auto;
}

.blog-link {
  display: inline-flex !important;
  align-items: center !important;
  gap: 0.4rem !important;
  padding: 0.5em 1em !important;
  background: var(--gradient-primary) !important;
  color: white !important;
  text-decoration: none !important;
  border-radius: 20px !important;
  font-size: 0.8rem !important;
  font-weight: 500 !important;
  transition: var(--transition) !important;
  box-shadow: var(--shadow-md) !important;
  border: 1px solid rgba(255, 255, 255, 0.2);
}

.blog-link:hover {
  transform: translateY(-2px) !important;
  box-shadow: var(--shadow-lg) !important;
  color: white !important;
  text-decoration: none !important;
}

.blog-link.secondary {
  background: var(--bg-secondary) !important;
  color: var(--text-primary) !important;
  border: 1px solid var(--border-primary) !important;
  box-shadow: none !important;
}

.blog-link.secondary:hover {
  background: var(--bg-tertiary) !important;
  border-color: var(--accent-blue) !important;
}

/* 响应式设计 */
@media (max-width: 768px) {
  .blog-grid {
    grid-template-columns: 1fr !important;
    gap: 1.5rem !important;
  }
  
  .blog-card-image {
    height: 200px !important;
  }
  
  .blog-card-content {
    height: calc(100% - 200px);
  }
  
  .page__inner-wrap {
    padding: 0 1rem;
  }
}

@media (min-width: 769px) and (max-width: 1024px) {
  .blog-grid {
    grid-template-columns: repeat(2, 1fr) !important;
    gap: 1.5rem !important;
  }
  
  .publication-image {
    width: 260px !important;
    height: 180px !important;
  }
}

@media (min-width: 1025px) {
  .blog-grid {
    grid-template-columns: repeat(3, 1fr) !important;
  }
}

/* Publications统一设计风格 - 高端学术风格 */
.publication-box {
  display: flex !important;
  background: var(--bg-primary) !important;
  border-radius: var(--border-radius) !important;
  border: 1px solid var(--border-primary) !important;
  overflow: hidden !important;
  box-shadow: var(--shadow-md) !important;
  transition: var(--transition) !important;
  margin: 2rem 0 !important;
  align-items: stretch !important;
  position: relative;
}

.publication-box::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  width: 4px;
  height: 100%;
  background: var(--gradient-emerald);
  transform: scaleY(0);
  transition: transform 0.3s ease;
}

.publication-box:hover {
  transform: translateY(-4px) !important;
  box-shadow: var(--shadow-xl) !important;
  border-color: var(--accent-emerald) !important;
}

.publication-box:hover::before {
  transform: scaleY(1);
}

.publication-image {
  position: relative !important;
  width: 300px !important;
  height: 200px !important;
  flex-shrink: 0 !important;
  overflow: hidden !important;
  background: var(--bg-secondary) !important;
  margin: 1rem !important;
  border-radius: 12px !important;
  box-shadow: inset 0 2px 8px rgba(0, 0, 0, 0.1) !important;
}

.publication-image img {
  width: 100% !important;
  height: 100% !important;
  object-fit: cover !important;
  transition: transform 0.5s cubic-bezier(0.4, 0, 0.2, 1) !important;
}

.publication-image:hover img {
  transform: scale(1.05) !important;
}

.publication-badge {
  position: absolute !important;
  top: 16px !important;
  left: 16px !important;
  background: var(--gradient-emerald) !important;
  color: white !important;
  padding: 0.5em 1em !important;
  border-radius: 20px !important;
  font-size: 0.75em !important;
  font-weight: 600 !important;
  box-shadow: var(--shadow-lg) !important;
  z-index: 10 !important;
  backdrop-filter: blur(10px);
  border: 1px solid rgba(255, 255, 255, 0.2);
}

.publication-content {
  flex: 1 !important;
  padding: 2rem 1.5rem 2rem 0 !important;
  display: flex !important;
  flex-direction: column !important;
  gap: 1rem !important;
  justify-content: center;
}

.publication-title {
  font-size: 1.375rem !important;
  font-weight: 600 !important;
  color: var(--text-primary) !important;
  margin: 0 !important;
  line-height: 1.3 !important;
}

.publication-authors {
  font-size: 1rem !important;
  color: var(--text-secondary) !important;
  line-height: 1.5 !important;
  font-weight: 400 !important;
}

.publication-authors strong {
  color: var(--text-primary) !important;
  font-weight: 600 !important;
}

.publication-venue {
  font-size: 0.95rem !important;
  color: var(--text-tertiary) !important;
  font-style: italic !important;
  font-weight: 400 !important;
}

.publication-links {
  display: flex !important;
  gap: 1rem !important;
  flex-wrap: wrap !important;
  margin-top: 1rem !important;
}

.publication-link {
  display: inline-flex !important;
  align-items: center !important;
  gap: 0.5rem !important;
  padding: 0.6em 1.2em !important;
  background: var(--gradient-emerald) !important;
  color: white !important;
  text-decoration: none !important;
  border-radius: 20px !important;
  font-size: 0.875rem !important;
  font-weight: 500 !important;
  transition: var(--transition) !important;
  box-shadow: var(--shadow-md) !important;
  border: 1px solid rgba(255, 255, 255, 0.2);
}

.publication-link:hover {
  transform: translateY(-2px) !important;
  box-shadow: var(--shadow-lg) !important;
  color: white !important;
  text-decoration: none !important;
}

.publication-link.secondary {
  background: var(--bg-secondary) !important;
  color: var(--text-primary) !important;
  border: 1px solid var(--border-primary) !important;
  box-shadow: none !important;
}

.publication-link.secondary:hover {
  background: var(--bg-tertiary) !important;
  border-color: var(--accent-emerald) !important;
}

.publication-link i {
  font-size: 0.9em !important;
}

/* 响应式设计 - Publications */
@media (max-width: 768px) {
  .publication-box {
    flex-direction: column !important;
    margin: 1.5rem 0 !important;
  }
  
  .publication-image {
    width: 100% !important;
    height: 180px !important;
    margin: 1rem !important;
    margin-bottom: 0 !important;
  }
  
  .publication-content {
    padding: 1.5rem !important;
    gap: 0.8rem !important;
  }
  
  .publication-title {
    font-size: 1.25rem !important;
  }
  
  .publication-authors,
  .publication-venue {
    font-size: 0.95rem !important;
  }
  
  .publication-links {
    gap: 0.75rem !important;
  }
}

@media (min-width: 769px) and (max-width: 1024px) {
  .publication-image {
    width: 260px !important;
    height: 180px !important;
    margin: 1rem !important;
  }
  
  .publication-content {
    padding: 1.5rem 1rem !important;
  }
  
  .publication-title {
    font-size: 1.25rem !important;
  }
}

@media (min-width: 1025px) {
  .blog-grid {
    grid-template-columns: repeat(auto-fit, minmax(350px, 1fr)) !important;
  }
}
</style>

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<!-- Hero Section -->
<div class="hero-section">
  <div class="hero-content">
    <h1 class="hero-title">Jinxiang Xie</h1>
    <p class="hero-subtitle">AI Researcher & Computational Scientist</p>
    <p class="hero-description">
      Incoming graduate student at <span class="accent-text">Nanjing University</span> | Research intern at <span class="accent-text">Microsoft</span> | 
      Former research intern at <span class="accent-text">Peking University</span>. Passionate about leveraging 
      <span class="primary-gradient-text">Large Language Models</span> to solve complex problems in NLP, quantitative trading, and scientific discovery.
    </p>
    <div style="display: flex; gap: 1rem; flex-wrap: wrap;">
      <a href="assets/Jinxiang's CV.pdf" class="btn-primary">
        <i class="fas fa-file-pdf"></i>
        View CV
      </a>
      <a href="mailto:jxTse@outlook.com" class="btn-primary btn-secondary">
        <i class="fas fa-envelope"></i>
        Contact Me
      </a>
    </div>
  </div>
</div>

<!-- Expertise Highlights -->
<div class="highlight-blocks">
  <div class="highlight-block">
    <h3><i class="fas fa-microscope"></i> AI Researcher</h3>
    <ul>
      <li>Research focus on <span class="accent-text">LLMs and NLP</span></li>
      <li>Internships at <span class="primary-gradient-text">top institutions</span></li>
      <li>Publications at <span class="accent-text">AAAI</span>, <span class="accent-text">ACL</span></li>
    </ul>
  </div>
  
  <div class="highlight-block">
    <h3><i class="fas fa-pen-fancy"></i> Content Creator</h3>
    <ul>
      <li>Technical blogs with <span class="accent-text">500K+ views</span></li>
      <li>Active on <a href="https://www.xiaohongshu.com/user/profile/60c47bae000000000100b07e" class="link-accent">Xiaohongshu</a></li>
      <li><a href="https://mp.weixin.qq.com/s/5wn3NvB2FBpJD1jK0L4qbQ" class="link-accent">Articles</a> about <span class="primary-gradient-text">Tech & Humanities</span></li>
    </ul>
  </div>
  
  <div class="highlight-block">
    <h3><i class="fas fa-globe-asia"></i> Life Explorer</h3>
    <ul>
      <li>Visited <span class="accent-text">9 countries</span> worldwide</li>
      <li>Traveled to <span class="accent-text">32 provinces</span> in China</li>
      <li>Rich experience in <span class="primary-gradient-text">social work</span></li>
    </ul>
  </div>
</div>

<!-- News Section -->
<h2 class="section-title">Latest News</h2>
<div class="news-timeline">
  <div class="news-item">
    <div class="news-date">December 2024</div>
    <div class="news-content">
      🎉 One paper accepted by The 39th Annual AAAI Conference on Artificial Intelligence (AAAI-25). See you in Philadelphia!
    </div>
  </div>
  <div class="news-item">
    <div class="news-date">August 2024</div>
    <div class="news-content">
      Joined Microsoft as a Research Intern under the guidance of Principal Researcher Justin Ding, focusing on evaluating and enhancing LLM outputs.
    </div>
  </div>
</div>

<!-- Publications Section -->
<h2 class="section-title">Publications</h2> 

<div class="publication-box">
  <div class="publication-image">
    <div class="publication-badge">Preprint</div>
    <img src="images/Example_page-0002.png" alt="CAST Paper">
  </div>
  <div class="publication-content">
    <h3 class="publication-title">CAST: Achieving Stable LLM-based Text Analysis for Data Analytics</h3>
    <div class="publication-authors">
      <strong>Jinxiang Xie</strong>, Zihao Li, Wei He, Rui Ding, Shi Han, Dongmei Zhang
    </div>
    <!-- <div class="publication-venue">
      In The 39th Annual AAAI Conference on Artificial Intelligence (AAAI-25)
    </div>
    <div class="publication-links">
      <a href="https://arxiv.org/abs/2412.12832" class="publication-link">
        <i class="fas fa-file-pdf"></i> Arxiv
      </a>
      <a href="https://github.com/jxtse/GEC-Metrics-DSGram" class="publication-link">
        <i class="fab fa-github"></i> Code
      </a>
    </div> -->
  </div>
</div>

<div class="publication-box">
  <div class="publication-image">
    <div class="publication-badge">AAAI 2025</div>
    <img src="images/Example_page-0001.png" alt="DSGram Paper">
  </div>
  <div class="publication-content">
    <h3 class="publication-title">DSGram: Dynamic Weighting Sub-Metrics for Grammartical Error Correction in the Era of Large Language Models</h3>
    <div class="publication-authors">
      <strong>Jinxiang Xie</strong>, Yilin Li, Xunjian Yin, Xiaojun Wan
    </div>
    <div class="publication-venue">
      In The 39th Annual AAAI Conference on Artificial Intelligence (AAAI-25)
    </div>
    <div class="publication-links">
      <a href="https://arxiv.org/abs/2412.12832" class="publication-link">
        <i class="fas fa-file-pdf"></i> Arxiv
      </a>
      <a href="https://github.com/jxtse/GEC-Metrics-DSGram" class="publication-link">
        <i class="fab fa-github"></i> Code
      </a>
    </div>
  </div>
</div>

<!-- Additional Publications -->
<div class="publication-box">
  <div class="publication-content" style="padding: 2rem;">
    <h3 class="publication-title">Additional Publications</h3>
    <div class="publication-authors">
      <strong>Selected Collaborations</strong>
    </div>
    <ul style="margin-top: 1rem; padding-left: 1.5rem;">
      <li style="margin-bottom: 1rem;">
        <strong>Qiyang Chen, Yuezhi Wang, Jinxiang Xie</strong>, et al. <br>
        <em>$M^3$ Trader: Multimodal Macro–Micro Inference with LLM-Guided Reinforcement Learning for Quantitative Trading</em><br>
        <span class="publication-venue">Preprint</span>
      </li>
      <li style="margin-bottom: 1rem;">
        <strong>Yingjian Chen, Haoran Liu, Yinhong Liu, Jinxiang Xie</strong>, et al. <br>
        <em>GraphCheck: Breaking Long-Term Text Barriers with Extracted Knowledge Graph-Powered Fact-Checking</em><br>
        <span class="publication-venue">ACL 2025</span>
      </li>
    </ul>
  </div>
</div>

<!-- Education Section -->
<h2 class="section-title">Education</h2>
<div class="education-item">
  <div class="education-degree">Master of Science</div>
  <div class="education-school">Kuang Yaming Honors School, Nanjing University</div>
  <div class="education-date">2025.09 - Present</div>
</div>
<div class="education-item">
  <div class="education-degree">Bachelor of Science in Information and Computing Science</div>
  <div class="education-school">Beijing Jiaotong University</div>
  <div class="education-date">2021.09 - 2025.06</div>
</div>

<!-- Internships Section -->
<h2 class="section-title">Research Experience</h2>
<div class="internship-item">
  <div class="internship-position">Research Intern</div>
  <div class="internship-company">Data, Knowledge and Intelligence (DKI) Group, Microsoft</div>
  <div class="internship-date">2024.08 - 2025.08</div>
</div>
<div class="internship-item">
  <div class="internship-position">Research Intern</div>
  <div class="internship-company">Wangxuan Institute of Computer Technology, Peking University</div>
  <div class="internship-date">2023.11 - 2024.08</div>
</div>
<div class="internship-item">
  <div class="internship-position">Summer Workshop Student</div>
  <div class="internship-company">School of Computer, National University of Singapore</div>
  <div class="internship-date">2023.05 - 2023.07</div>
</div>

<!-- Blog Section -->
<h2 class="section-title">Blog & Creative Work</h2>

<div class="blog-grid">
<div class="blog-card">
    <div class="blog-card-image">
      <div class="blog-badge">June, 2025</div>
      <img src="images/pic06.jpg" alt="The Limits of My Language Mean the Limits of My World">
    </div>
    <div class="blog-card-content">
      <div class="blog-title">The Limits of My Language Mean the Limits of My World</div>
      <div class="blog-description">Drawing on Wittgenstein's philosophy, a recent paper argues that our existing language might be the fundamental bottleneck.</div>
      <div class="blog-links">
        <a href="https://www.xiaohongshu.com/discovery/item/683c300d000000000f03b1ca?source=webshare&xhsshare=pc_web&xsec_token=AB0PoaiA05YKKE_dU2SOcfxhEzDIPcLsNtqo4slfNuuXw=&xsec_source=pc_share" class="blog-link">
          <i class="fas fa-language"></i> 中文版
        </a>
        <a href="https://jxtse.medium.com/the-limits-of-my-language-are-the-limits-of-my-world-can-we-ever-truly-understand-ai-f7cc72327dac" class="blog-link">
          <i class="fas fa-globe"></i> English
        </a>
      </div>
    </div>
  </div>

  <div class="blog-card">
    <div class="blog-card-image">
      <div class="blog-badge">January, 2025</div>
      <img src="images/pic04.jpg" alt="Beyond the Future of AI">
    </div>
    <div class="blog-card-content">
      <div class="blog-title">Beyond the Future of AI: The Dreams and Deceptions of Cryptocurrency</div>
      <div class="blog-description">My vision of the future: from Bitcoin to an AGI-driven decentralized society. We must design a more sophisticated trust mechanism than blockchain to install “guardrails” for AI.</div>
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
        <a href="https://www.xiaohongshu.com/discovery/item/67a48f0d000000001800721c?source=webshare&xhsshare=pc_web&xsec_token=ABXUfGRE_zHTnXbEyaNmuelBHrgbyYI_AxjJL2AYctNxE=&xsec_source=pc_share" class="blog-link">
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
        <a href="https://www.xiaohongshu.com/discovery/item/668a35c8000000001e010600?source=webshare&xhsshare=pc_web&xsec_token=ABl3IEpctnnXxbjsYlUul3nTDdCUYhZP7SljcVPMl9I6s=&xsec_source=pc_share" class="blog-link">
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

<!-- 增强用户体验的JavaScript -->
<script>
  // 滚动显示动画
  function revealOnScroll() {
    const reveals = document.querySelectorAll('.scroll-reveal');
    
    reveals.forEach(element => {
      const windowHeight = window.innerHeight;
      const elementTop = element.getBoundingClientRect().top;
      const elementVisible = 150;
      
      if (elementTop < windowHeight - elementVisible) {
        element.classList.add('active');
      }
    });
  }

  // 平滑滚动
  document.querySelectorAll('a[href^="#"]').forEach(anchor => {
    anchor.addEventListener('click', function (e) {
      e.preventDefault();
      const target = document.querySelector(this.getAttribute('href'));
      if (target) {
        target.scrollIntoView({
          behavior: 'smooth',
          block: 'start'
        });
      }
    });
  });

  // 防抖函数
  function debounce(func, wait) {
    let timeout;
    return function executedFunction(...args) {
      const later = () => {
        clearTimeout(timeout);
        func(...args);
      };
      clearTimeout(timeout);
      timeout = setTimeout(later, wait);
    };
  }

  // 滚动事件监听
  window.addEventListener('scroll', debounce(revealOnScroll, 10));
  
  // 页面加载完成后初始化
  document.addEventListener('DOMContentLoaded', function() {
    revealOnScroll();
    
    // 为卡片添加3D效果
    const cards = document.querySelectorAll('.premium-card, .blog-card, .publication-box, .highlight-block');
    
    cards.forEach(card => {
      card.addEventListener('mousemove', function(e) {
        const rect = this.getBoundingClientRect();
        const x = e.clientX - rect.left;
        const y = e.clientY - rect.top;
        
        const centerX = rect.width / 2;
        const centerY = rect.height / 2;
        
        const rotateX = (y - centerY) / 10;
        const rotateY = (centerX - x) / 10;
        
        this.style.transform = `perspective(1000px) rotateX(${rotateX}deg) rotateY(${rotateY}deg) translateZ(10px)`;
      });
      
      card.addEventListener('mouseleave', function() {
        this.style.transform = 'perspective(1000px) rotateX(0) rotateY(0) translateZ(0)';
      });
    });
    
    // 添加链接点击反馈
    const links = document.querySelectorAll('a, .btn-primary, .blog-link, .publication-link');
    links.forEach(link => {
      link.addEventListener('click', function(e) {
        // 创建涟漪效果
        const ripple = document.createElement('span');
        const rect = this.getBoundingClientRect();
        const size = Math.max(rect.width, rect.height);
        const x = e.clientX - rect.left - size / 2;
        const y = e.clientY - rect.top - size / 2;
        
        ripple.style.width = ripple.style.height = size + 'px';
        ripple.style.left = x + 'px';
        ripple.style.top = y + 'px';
        ripple.classList.add('ripple');
        
        this.appendChild(ripple);
        
        setTimeout(() => {
          ripple.remove();
        }, 600);
      });
    });
    
    // 添加打字机效果到标题
    const heroTitle = document.querySelector('.hero-title');
    if (heroTitle) {
      const text = heroTitle.textContent;
      heroTitle.textContent = '';
      heroTitle.style.opacity = '1';
      
      let index = 0;
      function typeWriter() {
        if (index < text.length) {
          heroTitle.textContent += text.charAt(index);
          index++;
          setTimeout(typeWriter, 100);
        }
      }
      
      setTimeout(typeWriter, 500);
    }
    
    // 添加滚动进度条
    const progressBar = document.createElement('div');
    progressBar.style.cssText = `
      position: fixed;
      top: 0;
      left: 0;
      width: 0%;
      height: 3px;
      background: linear-gradient(90deg, var(--accent-blue), var(--accent-emerald));
      z-index: 9999;
      transition: width 0.3s ease;
    `;
    document.body.appendChild(progressBar);
    
    window.addEventListener('scroll', debounce(() => {
      const scrollTop = window.pageYOffset;
      const docHeight = document.body.scrollHeight - window.innerHeight;
      const scrollPercent = (scrollTop / docHeight) * 100;
      progressBar.style.width = scrollPercent + '%';
    }, 10));
  });

  // 添加键盘导航
  document.addEventListener('keydown', function(e) {
    if (e.key === 'Tab') {
      document.body.classList.add('keyboard-navigation');
    }
  });

  // 添加鼠标导航
  document.addEventListener('mousedown', function() {
    document.body.classList.remove('keyboard-navigation');
  });

  // 添加页面可见性API
  document.addEventListener('visibilitychange', function() {
    if (document.hidden) {
      document.title = '👋 Come back to Jinxiang\'s homepage';
    } else {
      document.title = 'Jinxiang Xie - AI Researcher';
    }
  });

  // 添加性能优化
  let ticking = false;
  function requestTick() {
    if (!ticking) {
      window.requestAnimationFrame(updateAnimations);
      ticking = true;
    }
  }

  function updateAnimations() {
    // 更新动画帧
    ticking = false;
  }

  window.addEventListener('scroll', requestTick);
  window.addEventListener('resize', requestTick);
</script>

<!-- 添加涟漪效果的CSS -->
<style>
  .ripple {
    position: absolute;
    border-radius: 50%;
    background: rgba(255, 255, 255, 0.6);
    transform: scale(0);
    animation: ripple-animation 0.6s linear;
    pointer-events: none;
  }

  @keyframes ripple-animation {
    to {
      transform: scale(4);
      opacity: 0;
    }
  }

  /* 键盘导航优化 */
  .keyboard-navigation *:focus {
    outline: 2px solid var(--accent-blue);
    outline-offset: 2px;
  }

  /* 加载动画 */
  .fade-in {
    animation: fadeIn 0.8s ease-out;
  }

  @keyframes fadeIn {
    from {
      opacity: 0;
      transform: translateY(20px);
    }
    to {
      opacity: 1;
      transform: translateY(0);
    }
  }
</style>