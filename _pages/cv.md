---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D. in Computer Science, Emory University, 2023-Present
  * Advisor: Dr. Fei Liu
  * GPA: 4.0/4.0
* B.E. in Automation, Tsinghua University, 2019-2023
  * GPA: 3.5/4.0

Research Interests
======
* Large Language Models
* Natural Language Processing
* Reasoning
* Decision Making
* Deep Learning
* Reinforcement Learning
* Artificial Intelligence

Publications
======
* **STRUX: An LLM for Decision-Making with Structured Explanations**
  * Yiming Lu, Yebowen Hu, Hassan Foroosh, Wei Jin, Fei Liu
  * Under Review
  * [arXiv:2410.12583](https://arxiv.org/pdf/2410.12583)
  * Project focused on enhancing LLM decision-making through structured explanations, demonstrating superior performance in stock investment decisions based on earnings call transcripts.

Research Experience
======
* **Instant NGP and Neural Scene Reconstruction** (January 2022 - May 2022)
  * Tsinghua BBNC Laboratory
  * Developed multi-view data collection system using drone swarm
  * Implemented CUDA-Python interface for neural graphics primitives
  * Optimized NeRF rendering pipeline with hash-based encoding

* **High-speed Compressive Imaging System** (January 2022)
  * Tsinghua BBNC Laboratory
  * Designed HCA-SCI system with dynamic LCoS and lithography mask
  * Developed cascaded denoising algorithm for PnP-based reconstruction
  * Achieved 4.6G voxels/s throughput with 10-megapixel resolution

* **Super-resolution Network Development** (April 2021 - July 2021)
  * Implemented state-of-the-art super-resolution architectures
  * Conducted systematic literature review on video enhancement

Technical Skills
======
* **Programming Languages**
  * Python, C, C++, LaTeX, MATLAB
* **Frameworks & Libraries**
  * PyTorch, LLaMA Factory, TensorFlow, HuggingFace, OpenCV
  * scikit-learn, NumPy, Pandas, spaCy

Selected Courses
======
* Natural Language Processing
* Machine Learning
* Operations Research
* Information Retrieval
* Pattern Recognition
* Digital Video Applications
* Foundation of AI
* Digital Image Processing
* Computer Programming

Contact Information
======
* Address: 400 Dowman Drive, W302, Atlanta, GA 30322
* Email: yiming.lu@emory.edu
* GitHub: [github.com/BUILDERlym](https://github.com/BUILDERlym)
* Phone: 404-703-9392
* Website: [YimingLu.github.io](https://YimingLu.github.io)

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
