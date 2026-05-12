---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<link rel="stylesheet" href="{{ site.baseurl }}/assets/css/language-toggle.css">
<button class="lang-toggle-btn" onclick="toggleLanguage()">🌍 中文/English</button>

<script>
function toggleLanguage() {
  const body = document.body;
  if (body.classList.contains('show-both')) {
    body.classList.remove('show-both');
    body.classList.remove('show-en');
    localStorage.setItem('language', 'zh');
  } else if (body.classList.contains('show-en')) {
    body.classList.remove('show-en');
    body.classList.add('show-both');
    localStorage.setItem('language', 'both');
  } else {
    body.classList.add('show-en');
    localStorage.setItem('language', 'en');
  }
}

// Load saved language preference
document.addEventListener('DOMContentLoaded', function() {
  const lang = localStorage.getItem('language') || 'zh';
  if (lang === 'en') {
    document.body.classList.add('show-en');
  } else if (lang === 'both') {
    document.body.classList.add('show-both');
  }
});
</script>

## 👋 <span class="lang-zh">欢迎来到我的主页</span><span class="lang-divider">|</span><span class="lang-en">Welcome to my academic homepage!</span>

我是<span class="lang-zh">**王可欣** (Kexin Wang)，一名来自[江南大学](https://www.jiangnan.edu.cn/)  [计算机科学与技术](https://ai.jiangnan.edu.cn/)专业的三年级学生，致力于在**多模态学习**、**计算机视觉**和**大语言模型**等领域探索🏄‍♀️。</span><span class="lang-divider">|</span><span class="lang-en">a third-year undergraduate student majoring in Computer Science and Technology at [Jiangnan University](https://www.jiangnan.edu.cn/), a **National 211 Project University** under China's Ministry of Education. With a strong foundation in AI and deep learning, I am passionate about **multimodal fusion**, **computer vision**, and **large language models**.</span>

---

## 🎯 <span class="lang-zh">核心亮点</span><span class="lang-divider">|</span><span class="lang-en">Key Highlights</span>

<span class="lang-zh">**学术成就**
- 📄 以第一作者身份完成**中科院1区Top SCI期刊**论文（IF=15.5）
- 🏆 **GPA 3.74/4.0**，专业排名 **5/140**（前3.6%）
- 🥇 四项国家级与省级竞赛奖项若干（美国数学建模竞赛国际一等奖(队长)、中国大学生服务外包创新创业大赛全国三等奖等）

**研究方向**
- 🤖 多模态分析 & 融合 & 对齐 
- 🧠 基于LLM的应用系统设计
- 👁️ 计算机视觉与边缘计算</span>

<span class="lang-divider">|</span>

<span class="lang-en">**Academic Achievements**
- 📄 First-author paper submitted to **Information Fusion** (SCI Q1, IF=15.5)
- 🏆 **GPA 3.74/4.0**, ranked **5/140** (Top 3.6%) in major
- 🥇 Multiple national and international awards (ICM Meritorious Winner, etc.)

**Research Areas**
- 🤖 Multimodal Analysis & Fusion & Alignment
- 🧠 LLM-based Application Systems
- 👁️ Computer Vision & Edge Computing</span>

---<span class="lang-zh">研究特色</span><span class="lang-divider">|</span><span class="lang-en">Research Strengths</span>

<span class="lang-zh">✅ **完整的科研闭环**: 从方法创新、模型训练、系统实验到论文撰写  
✅ **多领域交叉**: PyTorch深度学习、CLIP微调、LLM应用、机械臂控制  
✅ **工程化实践**: 主导参与多个项目，其中包括国家级创新训练项目与多个落地项目
✅ **团队协作与领导力**: 担任项目队长，带领团队完成从调研到交付的全流程</span>

<span class="lang-divider">|</span>

<span class="lang-en">✅ **Complete Research Cycle**: From methodology innovation to model training, comprehensive experiments, and manuscript writing  
✅ **Interdisciplinary**: Deep learning with PyTorch, CLIP fine-tuning, LLM applications, and robotic control  
✅ **Engineering Practice**: Involved in multiple projects, including national-level innovation training projects and several on-ground projects
✅ **Leadership & Teamwork**: Team leader with end-to-end project delivery experience</span>ons, and robotic control  
✅ **Engineering Practice**: Involved in multiple projects, including national-level innovation training projects and several on-ground projects
✅ **Leadership & Teamwork**: Team leader with end-to-end project delivery experience

---<span class="lang-zh">科研基础</span><span class="lang-divider">|</span><span class="lang-en">What I Can Offer</span>

<span class="lang-zh">📊 **深度学习与模型开发**: 熟悉PyTorch、Transformers等框架，具备模型优化与微调经验  
📖 **学术写作与论文投稿**: 英文论文撰写、LaTeX排版、Overleaf协作经验  
🎯 **系统设计与工程化**: 从需求分析、架构设计到原型实现的完整能力  
🌍 **英语水平与国际视野**: CET6获566分，CET4 594分，新加坡南洋理工大学交流经验</span>

<span class="lang-divider">|</span>

<span class="lang-en">📊 **Deep Learning & Model Development**: Proficient in PyTorch, Transformers; experienced in model optimization and fine-tuning  
📖 **Academic Writing**: English manuscript writing, LaTeX typesetting, Overleaf collaboration  
🎯 **System Design & Engineering**: Full-cycle capability from requirements analysis to prototype implementation  
🌍 **English and International Experience**: CET6 English 566, CET4 English 594, NTU Singapore exchange</span>
🎯 **System Design & Engineering**: Full-cycle capability from requirements analysis to prototype implementation  
🌍 📮 <span class="lang-zh">联系我</span><span class="lang-divider">|</span><span class="lang-en">Get in Touch</span>

📧 **Email**: 1033230405@stu.jiangnan.edu.cn  
📧 **Spare Email**: kethy_wang@qq.com  
⌛ **Updated**: 2026-5-12

<span class="lang-zh">*保研升学申请中*</span><span class="lang-divider">|</span><span class="lang-en">*Currently applying for graduate school admission*</span>
---

## 🎓 <span class="lang-zh">快速导航</span><span class="lang-divider">|</span><span class="lang-en">Quick Navigation</span>

<span class="lang-zh">
- 📋 **[完整简历](/cv/)** - 教育背景、竞赛获奖、核心技能
- 📚 **[科研项目](/portfolio/)** - 主要研究项目
- 📰 **[论文发表](/publications/)** - 学术论文与研究成果
- 🏅 **[学习与成就](/learning/)** - 竞赛奖项与成就经历
</span>

<span class="lang-divider">|</span>

<span class="lang-en">
- 📋 **[Full CV](/cv/)** - Education, awards, and technical skills
- 📚 **[Research Projects](/portfolio/)** - Featured research projects
- 📰 **[Publications](/publications/)** - Academic papers and research outcomes
- 🏅 **[Learning & Achievements](/learning/)** - Competition awards and accomplishments
</span>📧 **Spare Email**: kethy_wang@qq.com
⌛ **Updated**: 2026-5-12

*保研升学申请中*  *Currently applying for graduate school admission*
