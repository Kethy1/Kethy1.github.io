---
layout: archive
title: "CV | 简历"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education | 教育背景
======

**江南大学**，National 211 Project University under Ministry of Education
* Major: Computer Science and Technology | GPA: 3.74/4.0 | Major Ranking: 5/140 (Top 3.6%)
* Expected Graduation: June 2027
* **Honors & Scholarships**:
  * 江苏省优秀大学生暑期境外学习奖学金 (Top 0.1%)
  * 江南大学综合一等奖学金 (Top 3%)
  * 江南大学三好学生 (Top 3%)
  * 德新优秀学生奖学金(Top 1%)
  * 上海商业储蓄银行文教基金会海外奖学金(Top 1%)

* **Core Coursework**: 
  * Mathematics: 概率论与数理统计 (98), 高等数学 (90), 线性代数 (93)
  * CS Fundamentals: 数据结构 (90), 计算机组成原理 (92), 数据库系统原理 (90)
  * Networks & Systems: 计算机网络 (95), C语言程序设计 (91)
  * AI/ML Related: 计算机图像与视觉基础 (优秀), 大数据分析 (优秀)
  * Language: 大学英语 (92)

* **English Proficiency**: CET-4 (594), CET-6 (566)

* **Professional Certifications**:
  * CCF-CSP Certification (Top 15%)
  * 计算机技术与软件专业技术资格（水平）
  * 国家计算机二级证书 (C语言)


Research Experience | 科研经历
======

**First-Author Research Paper** | 第一作者研究论文
* Paper: "Expert as Prompt: Prototype-Routed Mixture of Experts for Multimodal Sentiment Analysis"
* Status: Under review at **Information Fusion** (SCI Q1, IF=15.5)
* Timeline: 2025.09 - Present
* **Contributions**: 
  * Designed and implemented a novel prototype-routed Mixture of Experts (MoE) architecture
  * Conducted comprehensive experiments including ablation studies and parameter analysis
  * Independently wrote the manuscript and created all visualization diagrams
  * Key innovation: Learnable emotion prototypes for dynamic expert routing, enhancing model robustness

**National College Student Innovation Training Program** | 国家级大学生创新训练项目
* Project: "LLaMa-based Career Consulting LLM for College Students" | **Project Leader**
* Timeline: 2024.09 - Present
* **Contributions**:
  * Led the entire project from conception to execution
  * Designed system architecture and technical roadmap
  * Constructed custom career Q&A dataset and fine-tuned LLaMA model
  * Implemented database design, backend API, and system integration
  * **Result**: Functional system deployed with software copyright obtained

**Intelligent Robotic Arm Waste Sorting System** | 基于多模态交互与视觉的机械臂垃圾分拣系统
* Role: Team Captain | Timeline: 2025.09 - 2026.01
* **Contributions**:
  * Trained CLIP-based waste classification model
  * Designed full system pipeline: multimodal interaction → vision perception → LLM understanding → robotic control
  * Integrated Qwen-7B LLM for instruction parsing and task planning
  * Implemented real-time execution on Jetson Nano edge computing device
  * **Key Features**: Natural language/voice command interface, automated garbage sorting

**Privacy Protection Intelligent Decision System for Social Networks** | 多模态数据驱动的社交网络隐私保护系统
* Role: Individual Contributor | Timeline: 2025.09 - 2026.01
* **Contributions**:
  * Trained CN-CLIP based privacy risk assessment model
  * Developed multi-label classification for sensitive information detection (faces, locations, documents, etc)
  * Designed and implemented complete prototype with frontend UI and backend services
  * **Key Features**: Real-time risk detection, graduated warnings, in-app image editing tools (blur, mask, crop)


Competitions & Awards | 竞赛与获奖
======

![获奖证书]({{ site.baseurl }}/images/awards.png)
*各类奖项证书 | Competition Awards & Certificates*

* **美国大学生数学建模竞赛 (MCM/ICM)** - Meritorious Winner | Team Captain | 2025.01
* **中国大学生服务外包创新创业大赛** - National Third Prize | Core Member | 2025.07
* **CCF全国大数据和智能计算竞赛** - National Third Prize | Core Member | 2024.12
* **第十六届全国大学生数学竞赛** - Second Prize | Individual | 2024.12
* **江苏省普通高等学校高等数学竞赛** - Second Prize | Individual | 2024.06
* **第十六届"蓝桥杯"全国软件和信息技术专业人才省赛** - Third Prize | Individual | 2025.06


Technical Skills | 技术技能
======

**Deep Learning & AI**
* PyTorch, Transformers, HuggingFace
* Model fine-tuning: LLaMA, Qwen, CLIP, CN-CLIP, Deberta
* Computer vision: Object detection, image classification, semantic segmentation
* Multimodal learning: Feature fusion, cross-modal alignment

**Programming Languages**
* Python (Advanced) - Data processing, model development, system implementation
* C/C++ (Proficient)
* SQL (Proficient)
* JavaScript/HTML/CSS (Proficient)

**Tools & Frameworks**
* LaTeX & Overleaf (Experienced in academic manuscript writing)
* Git & GitHub (Version control)
* Edge computing: Jetson Nano deployment and optimization
* [CSDN](https://blog.csdn.net/Kethy__?type=blog): Learning Records and Public Welfare Sharing

**Domain Knowledge**
* Multimodal sentiment analysis
* Large language model application
* Computer vision systems
* Data privacy and security
* Natural language processing


Overseas Exchange | 海外交流
======

**Nanyang Technological University (NTU), Singapore**
* Program: "Data Science & Artificial Intelligence"
* Period: July 2025 (4-week intensive program)
* Grade: A+
* **Key Learnings**: 
  * Data analysis and machine learning fundamentals
  * Leadership training
  * Applied case studies: K-means clustering, regression models, ARIMA time-series prediction
  * Analysis of economic growth vs. carbon emissions relationships across nations

Volunteer Service & Leadership | 志愿服务与领导力
======

**Volunteer Service**: 159.5 cumulative hours
* Campus orientation volunteer (2 years) - Led new student onboarding
* Wuxi Marathon supporter & campus career fair assistant
* Department computer clinic volunteer (IT support for students)
* **Awards**: "Outstanding Volunteer" & "Star of Practice" titles

**Academic Support**
* Calculus peer tutor (2 consecutive years)
* Provided tutoring and mentoring for underclassmen in advanced mathematics

**Extracurricular Activities**
* Poetry recitation competitions
* Campus gala performances
* Track & field opening ceremony dance performance
* Demonstrated strong teamwork and well-rounded character development


Publications | 论文发表
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  

Featured Projects | 项目展示
======
  <ul>{% for post in site.portfolio reversed %}
    {% include archive-single.html %}
  {% endfor %}</ul>
  

**[Learning & Mentoring | 学习与指导](/learning/)**
======
  <ul>{% for post in site.learning reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>


Self-Summary & Future Plans | 自我总结与未来规划
======

### 个人特质 | Personal Strengths
我具备扎实的数学和编程基础，逻辑思维严谨，善于从复杂问题中提炼关键信息并进行系统性分析。科研热情饱满，拥有优秀的自主学习能力与独立思考习惯。性格开朗坚韧，具备出色的抗压能力与团队协作精神，在科研攻关中能保持专注与高效。

### 未来规划 | Future Plans
我志在投身学术研究，有意攻读**直博/学硕项目**，致力于在**多模态融合**、**计算机视觉****自然语言处理**等方向开展长期、系统的研究工作。我期望在研究生阶段夯实理论基础，紧跟领域前沿，产出高水平的创新成果。若有幸能获得直博机会，我将视之为宝贵的学术起点，以最大的热忱与专注投入其中。

**Looking forward to contributing to the AI research community as a rigorous and passionate researcher!**
