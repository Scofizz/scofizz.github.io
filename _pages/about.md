---
layout: page
title: "About Me"
permalink: /
author_profile: true
---
<div class="profile-card">
  <div class="profile-header">
    <h1>Zihuai Zhao</h1>
    <p>Ph.D. Candidate in Computing</p>
    <p><a href="https://www.polyu.edu.hk/" target="_blank">Hong Kong Polytechnic University</a></p>
  </div>
  
  <div class="profile-content">
    <div class="education-timeline">
      <div class="timeline-item">
        <span class="timeline-date">2023 - Present</span>
        <h3>Ph.D. in Computing</h3>
        <p>Hong Kong Polytechnic University</p>
        <p>Supervisors: 
          <a href="https://www4.comp.polyu.edu.hk/~csqli/" target="_blank">Prof. Qing Li</a>, 
          <a href="https://wenqifan03.github.io/" target="_blank">Dr. Wenqi Fan</a>
        </p>
      </div>
      <div class="timeline-item">
        <span class="timeline-date">2020 - 2023</span>
        <h3>MPhil in Engineering</h3>
        <p>University of Sydney</p>
      </div>
      <div class="timeline-item">
        <span class="timeline-date">2016 - 2020</span>
        <h3>B.Eng. (Hons) in Electrical Engineering</h3>
        <p>University of Sydney</p>
      </div>
    </div>
  </div>
</div>
## Research Interests
<div class="research-grid">
  <div class="research-item">
    <i class="fas fa-robot"></i>
    <h3>Recommender Systems (RecSys)</h3>
  </div>
  <div class="research-item">
    <i class="fas fa-language"></i>
    <h3>Natural Language Processing (NLP)</h3>
  </div>
  <div class="research-item">
    <i class="fas fa-brain"></i>
    <h3>Deep Reinforcement Learning (DRL)</h3>
  </div>
  <div class="research-item">
    <i class="fas fa-network-wired"></i>
    <h3>Wireless Networked Control Systems (WNCS)</h3>
  </div>
</div>
## News & Updates
<div class="news-card">
  <div class="news-header">
    <span class="news-date">Dec 2023</span>
    <span class="news-badge">Conference</span>
  </div>
  <h3>Recommender Systems in the Era of Large Language Models (LLMs)</h3>
  <p>Tutorial accepted by ICDM 2023</p>
  
  <div class="news-image">
    <img src='/images/LLMs_tasks.png' alt="LLM Tasks Overview">
  </div>
  
  <div class="news-actions">
    <a href="https://advanced-recommender-systems.github.io/llms_rec_tutorial/" class="btn">
      <i class="fas fa-globe"></i> Tutorial Website
    </a>
    <a href="/files/LLM4Rec.pdf" class="btn">
      <i class="fas fa-file-pdf"></i> Paper
    </a>
    <a href="https://advanced-recommender-systems.github.io/llms_rec_tutorial/doc/RecSys+LLMs.pdf" class="btn">
      <i class="fas fa-presentation"></i> Slides
    </a>
  </div>
</div>
## Publications
<div class="publication-list">
  <div class="publication-item">
    <div class="pub-header">
      <h3>Recommender Systems in the Era of Large Language Models (LLMs)</h3>
      <span class="pub-year">2023</span>
    </div>
    <p class="pub-authors">Zihuai Zhao, Wenqi Fan*, Jiatong Li, Yunqing Liu, Xiaowei Mei, Yiqi Wang, Jiliang Tang, Qing Li</p>
    <p class="pub-journal">arXiv preprint</p>
    <div class="pub-links">
      <a href="https://arxiv.org/abs/2307.02046" target="_blank">
        <i class="ai ai-arxiv"></i> arXiv:2307.02046
      </a>
    </div>
  </div>

  <div class="publication-item">
    <div class="pub-header">
      <h3>Deep Learning for Wireless Networked Systems: A Joint Estimation-Control-Scheduling Approach</h3>
      <span class="pub-year">2023</span>
    </div>
    <p class="pub-authors">Zihuai Zhao, Wanchun Liu*, Daniel E. Quevedo, Yonghui Li, Branka Vucetic</p>
    <p class="pub-journal">IEEE Internet of Things Journal (Early Access)</p>
    <div class="pub-links">
      <a href="https://ieeexplore.ieee.org/document/10197647" target="_blank">
        <i class="ai ai-doi"></i> 10.1109/JIOT.2023.3300074
      </a>
    </div>
  </div>
</div>
/* 基础样式 */
.profile-card {
  background: #f8f9fa;
  border-radius: 10px;
  padding: 2rem;
  box-shadow: 0 4px 6px rgba(0,0,0,0.1);
}

/* 时间线样式 */
.timeline-item {
  position: relative;
  padding-left: 30px;
  margin-bottom: 2rem;
  border-left: 2px solid #3498db;
}

.timeline-date {
  background: #3498db;
  color: white;
  padding: 3px 8px;
  border-radius: 4px;
  font-size: 0.9rem;
}

/* 研究兴趣网格 */
.research-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 1.5rem;
}

.research-item {
  text-align: center;
  padding: 1.5rem;
  background: white;
  border-radius: 8px;
  box-shadow: 0 2px 4px rgba(0,0,0,0.05);
  transition: transform 0.3s ease;
}

.research-item:hover {
  transform: translateY(-5px);
}

/* 新闻卡片 */
.news-card {
  background: white;
  border-radius: 8px;
  overflow: hidden;
  box-shadow: 0 4px 8px rgba(0,0,0,0.1);
}

.news-header {
  display: flex;
  justify-content: space-between;
  padding: 1rem;
  background: #2c3e50;
  color: white;
}

.news-badge {
  background: #e74c3c;
  padding: 3px 8px;
  border-radius: 4px;
  font-size: 0.8rem;
}

/* 按钮样式 */
.btn {
  display: inline-flex;
  align-items: center;
  padding: 8px 15px;
  background: #3498db;
  color: white;
  border-radius: 4px;
  text-decoration: none;
  margin-right: 10px;
  transition: background 0.3s;
}

.btn:hover {
  background: #2980b9;
}

/* 出版物样式 */
.publication-item {
  padding: 1.5rem;
  margin-bottom: 1.5rem;
  background: white;
  border-radius: 8px;
  box-shadow: 0 2px 4px rgba(0,0,0,0.05);
}

.pub-header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 0.5rem;
}

.pub-year {
  background: #3498db;
  color: white;
  padding: 2px 10px;
  border-radius: 12px;
  font-size: 0.9rem;
}
