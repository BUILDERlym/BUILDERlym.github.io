---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---
{% include base_path %}

[Download the pdf version here.](../assets/CV_Yiming_Emory.pdf)

Education
======
* Ph.D. in Computer Science, Emory University, 2023-Present
  * Advisors: Dr. Wei Jin; Dr. Fei Liu (2023-2026)
  * GPA: 4.0/4.0
* B.E. in Automation, Tsinghua University, 2019-2023
  * GPA: 3.5/4.0

Research Interests
======
* Self-evolving LLM agents that improve from experience through memory, skills, and execution traces
* Multi-agent collaboration and communication
* LLM reasoning and decision-making in high-stakes domains such as finance and public health

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Work Experience
======
* AI R&D Engineer Intern, Nokia (Sep. 2026 - Dec. 2026)
  * Sunnyvale, CA
  * Develop self-evolving agents and skills on Nokia's internal SkillMesh platform and Merlin, an assistant that equips telecom engineers with product and domain knowledge to ramp up on or switch between projects
  * Use internal agent traces to drive skill evolution, refining existing skills and distilling new ones from past executions
* Intern, Internal Alpha Capture (IAC), Point72 (Jun. 2026 - Aug. 2026)
  * New York City, NY
  * Built LLM pipelines over internal analyst text data for alpha capture
  * Extracted company KPIs from unstructured analyst text with LLMs and turned them into structured data
  * Generated trading signals from the extracted KPIs and LLM-derived views
* Research Intern, GenAI, Zoom Video Communications (Jun. 2025 - Aug. 2025)
  * Bellevue, WA
  * Researched cost-aware communication in LLM multi-agent teams: when agents should work solo, message asynchronously, or meet synchronously to finish shared tasks
  * Built a discrete-event simulator of team workflows, evaluated on 15 software engineering workflows with 5-17 agents and three frontier LLMs; led to the first-author C2C preprint

Research Presentations
======
* Poster, NAACL 2025: STRUX: An LLM for Decision-Making with Structured Explanations

Research Experience
======
* Instant NGP and Neural Scene Reconstruction, Tsinghua BBNC Laboratory (Jan. 2022 - May 2022)
  * Built drone-swarm multi-view capture system for large scenes; achieved real-time NeRF rendering with hash encoding
* High-speed Compressive Imaging System, Tsinghua BBNC Laboratory (Jan. 2022)
  * Achieved 4.6G voxels/s throughput at 10MP resolution; designed HCA-SCI system integrating dynamic LCoS and lithography mask
* Super-resolution Network Development, Student Research Project (Apr. 2021 - Jul. 2021)
  * Implemented SoTA super-resolution architectures from top conferences; conducted systematic literature review on deep learning approaches for video enhancement

Teaching
======
* Teaching Assistant, CS 571: Natural Language Processing
  * Emory University, Spring 2024 & Fall 2024 & Spring 2025
* Teaching Assistant, CS 534: Machine Learning
  * Emory University

Service
======
* Reviewer: KDD 2026 Workshop

Awards
======
* National Engineering Practice Competition (Nov. 2021)
  * Excellent Achievement Award, Ministry of Education
* Hardware Design Competition (Sep. 2020)
  * Third Prize, School Level Science and Technology Competition

Skills
======
* Programming
  * Python, C, C++, LaTeX, MATLAB
* Frameworks
  * PyTorch, Transformers, TRL, LLaMA Factory, VeRL, OpenRLHF, TensorFlow
* Interests
  * Piano, Classical Music, Swimming
