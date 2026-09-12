---
permalink: /
author_profile: true
stylesheets:
  - /assets/css/home.css
redirect_from:
  - /about/
  - /about.html
---
<h1 class="main-heading">Hi, I'm Tianlu Zheng.</h1>

I am an M.S. student in Robotics Science and Engineering at Northeastern University, China. My research focuses on multimodal representation learning, multimodal large language models, and efficient model training and inference.

I have worked on multimodal algorithms and large-model post-training at Tencent, Baidu, DeepGlint, and China Telecom Beijing Research Institute.

<p class="intro-links">
  <a href="mailto:zhengtianlu0216@163.com">Email</a>
  <a href="https://github.com/xiaolu-luu" target="_blank" rel="noopener">GitHub</a>
</p>

News
----
<div class="news-box">
  <ul class="news-list">
    <li><span class="news-date">2025.09</span> Our work on robust text-based person retrieval was released on arXiv and accepted to the EMNLP Main Conference.</li>
    <li><span class="news-date">2025.08</span> Joined Tencent as a Multimodal Algorithm Intern.</li>
    <li><span class="news-date">2025.07</span> Started a research project on multimodal humor understanding through lateral thinking.</li>
    <li><span class="news-date">2025.06</span> Joined Baidu ERNIE as a Large Language Model Algorithm Intern.</li>
  </ul>
</div>

Education
---------
<div class="timeline-list">
  <article class="timeline-item">
    <div class="item-header">
      <div><strong>Northeastern University</strong><span class="item-subtitle">M.S. in Robotics Science and Engineering</span></div>
      <time>Sep 2023 - Jun 2026</time>
    </div>
    <p>Recommended admission. Ranked 5/49. Research interests: multimodal representation learning and large language models.</p>
  </article>
  <article class="timeline-item">
    <div class="item-header">
      <div><strong>North China University of Technology</strong><span class="item-subtitle">B.Eng. in Automation</span></div>
      <time>Sep 2019 - Jun 2023</time>
    </div>
    <p>GPA: 3.87/4.00, top 5% of the major. CET-6.</p>
  </article>
</div>

Experience
----------
<div class="experience-container">
  <article class="experience-card">
    <div class="item-header">
      <div><strong>Tencent</strong><span class="item-subtitle">Multimodal Algorithm Intern</span></div>
      <time>Aug 2025 - Present</time>
    </div>
    <ul>
      <li>Built a video classification pipeline for Game for Peace mobile gameplay and PC emulator footage using Kafka, OCR, YOLO, and Qwen2.5-VL model distillation.</li>
      <li>Distilled Qwen2.5-VL-32B into Qwen2.5-VL-3B, reaching 95% classification accuracy and 85% recall after a coarse-filtering stage with 98% accuracy.</li>
      <li>Developed multimodal RAG, Swin Transformer, and GRPO-tuned Qwen2.5-VL-7B solutions for cheat-video detection, achieving 90% accuracy while processing about 50,000 videos per day.</li>
    </ul>
  </article>

  <article class="experience-card">
    <div class="item-header">
      <div><strong>Baidu ERNIE</strong><span class="item-subtitle">Large Language Model Algorithm Intern</span></div>
      <time>Jun 2025 - Jul 2025</time>
    </div>
    <ul>
      <li>Designed a unified atomic-instruction decomposition standard and prompt pipeline, then fine-tuned ERNIE 4.5-21B for automated decomposition and response-quality evaluation.</li>
      <li>Reached 97% decomposition accuracy and 99% recall; identified instruction-following defects in 12% of sampled SFT data and 20% of positive DPO samples.</li>
      <li>Improved ERNIE 4.5-21B multi-instruction following performance by 5% after repairing DPO training data.</li>
    </ul>
  </article>

  <article class="experience-card">
    <div class="item-header">
      <div><strong>DeepGlint</strong><span class="item-subtitle">Multimodal Algorithm Intern</span></div>
      <time>Nov 2024 - Jun 2025</time>
    </div>
    <ul>
      <li>Developed a text-based person retrieval system using continued CN-CLIP pretraining, structured representation benchmarks, NegCLIP hard negatives, clothing-logo recognition, and a quantized Qwen2.5-8B information extractor.</li>
      <li>Delivered a person retrieval model deployed in public-security and traffic-management systems across multiple cities.</li>
      <li>Enhanced an E5-V/LLaVA multimodal retrieval model with false-negative filtering and hard-negative instruction tuning, improving short-text, long-text, and composed image retrieval by 4.5%, 5.1%, and 2.1% over baseline.</li>
    </ul>
  </article>

  <article class="experience-card">
    <div class="item-header">
      <div><strong>China Telecom Beijing Research Institute</strong><span class="item-subtitle">GPU Programming and AI Operator Optimization Intern</span></div>
      <time>Jun 2024 - Sep 2024</time>
    </div>
    <ul>
      <li>Implemented and benchmarked Triton, CUDA, and native PyTorch operators across FP16, FP32, and FP64, measuring latency and TFLOPS for matrix multiplication, normalization, activation, softmax, and loss operators.</li>
      <li>Contributed to <em>A Comprehensive Survey of Triton: Artificial Intelligence Compiler and Operator Optimization</em>.</li>
    </ul>
  </article>
</div>

Publications
------------
<div class="publication-list">
  <article class="publication-card">
    <div class="publication-meta"><span class="venue-badge">EMNLP Main</span><span>First author</span></div>
    <h3>Gradient-Attention Guided Dual-Masking Synergetic Framework for Robust Text-based Person Retrieval</h3>
    <p>A dual-masking and gradient-attention framework for improving robustness in text-based person retrieval.</p>
    <a href="https://arxiv.org/abs/2509.09118" target="_blank" rel="noopener">arXiv</a>
  </article>

  <article class="publication-card">
    <div class="publication-meta"><span class="venue-badge venue-badge--green">IROS Oral</span><span>First author</span></div>
    <h3>Dual-Level Open-Vocabulary 3D Scene Representation for Instance-Aware Robot Navigation</h3>
    <p>Open-vocabulary 3D scene representations designed for instance-aware robotic navigation.</p>
  </article>

  <article class="publication-card">
    <div class="publication-meta"><span class="venue-badge venue-badge--gold">WWW '25 Workshop Oral</span><span>Co-first author</span></div>
    <h3>The Solution to the WWW25 Text-based Person Anomaly Search Challenge</h3>
    <p>A multimodal solution for text-based person anomaly search presented at the WWW '25 workshop.</p>
    <a href="https://dl.acm.org/doi/abs/10.1145/3701716.3717651" target="_blank" rel="noopener">DOI</a>
  </article>

  <article class="publication-card">
    <div class="publication-meta"><span class="venue-badge venue-badge--neutral">Patent</span><span>Application 2025110619980</span></div>
    <h3>Indoor Semantic Mapping and Navigation Method and System Based on Multimodal Models</h3>
  </article>
</div>

Research
--------
<article class="research-project">
  <div class="item-header">
    <div><strong>Multimodal Humor Image Understanding via Lateral Thinking</strong><span class="item-subtitle">Research Project</span></div>
    <time>Jul 2025 - Present</time>
  </div>
  <p>Improving Qwen2.5-VL's ability to understand humor that requires divergent, multi-step reasoning.</p>
  <ul>
    <li>Trained a humor judge on selection, ranking, and rewriting tasks.</li>
    <li>Built a multi-agent generation framework with expander, generator, and supervisor roles.</li>
    <li>Combined LoRA supervised fine-tuning with a second DPO stage and judge-guided preference-data updates.</li>
    <li>Improved performance by about 35% over Qwen2.5-VL-7B, 6% over GPT-4o, and 3% over the referenced state-of-the-art method on the humor dataset.</li>
  </ul>
</article>

Skills
------
<div class="skills-grid">
  <div><strong>Programming</strong><span>Python, Linux, shell scripting, Git, Docker</span></div>
  <div><strong>Acceleration</strong><span>CUDA, Triton operator development, TensorRT</span></div>
  <div><strong>Model Training</strong><span>DDP, multi-GPU training, LoRA, QLoRA, DPO, GRPO, post-training</span></div>
  <div><strong>Multimodal AI</strong><span>CLIP, SigLIP, BLIP, LLaVA, Qwen-VL, multimodal RAG</span></div>
</div>

Awards
------
<ul class="award-list">
  <li><strong>First-Class Graduate Scholarship</strong></li>
  <li><strong>National Encouragement Scholarship</strong> - awarded three times</li>
  <li><strong>Second Prize, Provincial Level</strong> - iFLYTEK Cup National Intelligent Vehicle Competition, Home Service Robot Challenge</li>
  <li><strong>Second Prize, North China Region</strong> - Siemens Cup China Intelligent Manufacturing Challenge, Information and Networking Track</li>
</ul>
