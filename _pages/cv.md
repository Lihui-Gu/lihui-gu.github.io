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

* ​​M.S. in Computer Science​​, Zhejiang University, 2023 - 2026(Expected)

* ​​B.S. in Computer Science and Technology​​, Zhejiang University of Technology, 2019 - 2023 
  * Computer Aided Design and Graphics System National Key Laboratory, Zhejiang University
  * School of Computer Science and Technology, Zhejiang University of Technology
  * Double Major: Computer Science and Technology; Minor: Intelligent Science and Technology
  * GPA: 4.23/5, Major Ranking: 1/23


Work experience
======
* Large Model Inference Optimization Intern​, *Kuaishou* - Keling Technology Department, Beijing 2025.06 - 2025.09:
  * Optimized feature cache reuse strategy for DiT models by leveraging the similarity of adjacent denoising time-step features. Achieved a 2.5x end-to-end acceleration on the Wan2.1/Hunyuan video generation model and 3.0x on the Flux image generation model, surpassing SOTA solutions like Taylorseer/Easycache under the same acceleration ratio. Nearly lossless 1.4x end-to-end acceleration verified on the un-distilled Keling i2v model.

* Navigation Group Algorithm Intern​​, Hangzhou Feibu Technology, Zhejiang, 2024.09-2025.04
  * ​​Predictive-Interactive Integrated Modeling​​: Designed an end-to-end data-driven model to replace rule-based strategies, enhancing decision-making in complex scenarios.

  * ​​Reinforcement Learning Optimization​​: Implemented model iterations based on the PPO algorithm, continuously improving port intersection traffic efficiency and reducing collision risks.

  * ​​Engineering Implementation​​: Reduced average intersection passage time by 0.5s across 1000+ simulation cases, completed real vehicle deployment of the model, and received an S-level performance evaluation during the internship.


  
Skills
======
* ​​Deep Learning & Inference Optimization​​:
  * Familiar with DIT/LLM inference optimization techniques, core functionalities of mainstream inference frameworks (vLLM, xDiT), and multi-card distributed inference technology.
  * Skilled in the underlying implementation of speculative decoding, combining FP8 quantization, communication optimization, tensor parallelism, and CUDA Graph techniques.
  * Knowledgeable in the implementation details of high-performance fusion operators (Megakernel), achieving extreme acceleration by fusing the entire LLM decoding process into one kernel.

* ​​Industrial Project Experience​​:
  * Led deep learning/reinforcement learning projects in autonomous driving scenarios (prediction-interaction tasks), with comprehensive experience from algorithm to engineering.

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
