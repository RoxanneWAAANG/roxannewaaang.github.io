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
* M.Eng. in Artificial Intelligence, Duke University, 2026 (Expected)
* B.S. in Data Science, Hong Kong Baptist University, 2024

Internship Experience
======
* Spring 2024: Multi-modal Learning Algorithm Intern
  * Guangdong Institute of Intelligence Science and Technology 
  * Aligned latent spaces of EEG and image data using cosine similarity, inspired by CLIP’s modal alignment approach.
  * Developed an EEG-Image MLLM using temporal convolution and transformer as the EEG encoder, and the CLIP
pre-trained ViT for image encoding.
  * Applied the EEG-MLLM for zero-shot image prediction, achieving a 5% accuracy improvement.
  * Developed a Mixture of Experts (MoE) model with an EEG encoder and Mamba module, optimizing EEG
processing for improved semantic extraction and model specialization.

* Spring 2024: Natural Language Processing Research Intern
  * Shanghai Zhangjiang Laboratory
  * Investigated developments in Multimodal Knowledge Graphs (MMKG) and devised a framework for MMKG construction
and completation tasks.
  * Applied knowledge distillation techniques to MLLMs to derive a compact GNN model, leveraging it for advanced
feature extraction in various graph learning applications.
  * Implemented multitask learning for Multimodal Named Entity Recognition and Relation Extraction, to initialize
MMKG with enriched semantic relationships found in GNN.

* Summer 2022: Logistics Data Analysis and Visualization
  * Han's Laser
  * Developed detailed customer profiles using RFM Analysis with over four key metrics, facilitating precision marketing strategies that reduced push marketing costs by 12\%, from \$2000 to \$1760 per campaign.
  * Implemented funnel analysis to enhance user targeting for push notifications; conducted A/B testing in Python to refine the website’s navigation structure, boosting loyalty user numbers by 6\% (from 15,000 to 16,000).
  * Engineered a data visualization website using HTML, CSS, and JavaScript, incorporating advanced visual analytics tools like \textbf{Pyecharts} and \textbf{ggplot2} for dynamic data representation.

Research Experience
======
* Spring 2025: Multi-modal Medical Agent Research 
  * Duke University
  * Based on MMedAgent framework, innovated a comprehensive medical agent solving fifteen tasks across eight modalities.
  * Aim to extend single-turn interactions into multi-turn dialogues, enabling agent to handle complex problems by
reasoning and adjustment.
  * Integrated voting-based methods consolidate results from multiple tools across modalities, enhancing the ability to utilize
multiple tools for complex queries.

* Spring 2024: Computer Vision Research 
  * Hong Kong Baptist University
  * Developed a brand-new CNN for brain tumor segmentation, using Deformable Large Kernel Attention and Swin Spatial
Pyramid Pooling to enhance multi-scale mapping, established SOTA benchmark on BraTS datasets.
  * Designed a Combined Attention Module that integrates Discrete Cosine Transform (DCT) with convolutional operations
to optimize spatial weighting, effectively enhancing the focus on tumors while minimizing background noise.
  * Formulated a novel frequency loss function paired with deep supervision strategies to emphasize high-frequency details,
enabling the model to leverage textural nuances for more precise segmentation.

Honors & Achievements
======
* Duke AI Hackathon 2024: Inception Swarm 
  * 1st Grand Prize, Enterprise Tools, and Productivity Track Winner, Best Use of LLM Agents Award
  * Developed ’Inception Swarm,’ a multi-agent swarm for rapid prototyping based on OpenAI’s Swarm framework, enabling
automatic creation of functional swarms through simple prompts.
  * Implemented core modules including the ’Manager Agent’ for concept refinement, ’Agent Creator’ for custom agents, and
’Tool Creator’ for specialized tool development.
  * Successfully applied Inception Swarm across 10+ real-world scenarios, contributed code to the OpenAI Swarm GitHub.

* 2024 Excellent Reward for Computer Science Poster Exhibition in HKBU
* 2024 Hong Kong Baptist University First Class Scholarship
* 2023 Hong Kong Baptist University First Class Scholarship
* 2022 Hong Kong Baptist University First Class Scholarship
* 2022 National Undergraduate Mathematical Contest in Modeling
* 2021 Hong Kong Baptist University Second Class Scholarship
* 2021 National Undergraduate Mathematical Contest in Modeling

Skills
======
* Programming Languages
  * Python
  * R
  * SQL
  * C++
  * Java
  * Go
  * Matlab
  * JavaScript
  * HTML/CSS

* Data Science & Machine Learning
  * NumPy/Pandas
  * Scikit-Learn
  * PyTorch
  * Tensorflow
  * NLTK/SpaCy

* Cloud Computing & DevOps
  * AWS/GCP/Azure
  * Docker
  * GitLab CI/CD

* Big Data & Distributed Systems
  * Hadoop
  * Spark

* Systems & Tools
  * Linux
  * Git
  * SSH


Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
<!-- Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> -->
  
Service and leadership
======
* Data Science Student Union
