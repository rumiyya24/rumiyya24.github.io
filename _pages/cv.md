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
* M.S. in Computer Science and Data Analytics (dual-degree program), ADA University / The George Washington University, 2023-2025
* B.S. in Computer Science, ADA University, 2019-2023

Research interests
======
Machine learning for health and biomedical applications; multimodal learning; generative modeling; computer vision and medical imaging; human sensing; trustworthy and clinically meaningful AI.

Research experience
======
* **Synthetic Mammogram Generation for Breast Imaging**, 2024-2025
  * Designed a lightweight WGAN-GP architecture and end-to-end training pipeline for mammogram synthesis, prioritizing training stability, computational efficiency, and deployment on consumer-grade hardware
  * Built a clinically grounded validation framework combining FID, SSIM, GLCM texture analysis, Sobel edge analysis, GPT-4V assessment, and blinded physician evaluation
  * Showed that quantitative image-quality metrics alone were insufficient to establish clinical plausibility

* **Synthetic Breast Imaging: Generative Methods, Simulation, and Critical Evidence Evaluation**, present
  * Leading a scoping review and critical evidence audit of synthetic breast imaging across mammography, digital breast tomosynthesis, ultrasound, and MRI (manuscript in preparation)
  * Developed the review protocol, search strategy, eligibility framework, and evidence-extraction methodology; conducting dual-reviewer screening of literature from PubMed, Scopus, and arXiv

* **Breast Cancer Detection and Labeling System**, 2022-2023
  * Collaborated with surgeons and radiologists at Azerbaijan Medical University on a clinically informed detection and image-labeling system for machine learning research
  * Combined InceptionV3 deep features with GLCM texture features and compared XGBoost, Random Forest, Logistic Regression, SVM, and K-Nearest Neighbors models

Teaching experience
======
* Adjunct Instructor, ADA University, School of IT and Engineering, Baku, Azerbaijan (Sep. 2025-present)
  * Principles of Information Systems
  * Business Process Modeling for IT Solutions
  * Production and Operations Management
  * IT Project Management
  * Supervision of undergraduate research Senior Design Projects

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Skills
======
* Languages: Python, C++, Java, SQL
* Machine learning and AI: deep learning, generative models (GANs / WGAN-GP), computer vision, image processing, NLP, model evaluation and optimization, retrieval-augmented generation (RAG)
* Frameworks and tools: PyTorch, TensorFlow, LangChain, Hugging Face, Git/GitHub
* Data and analytics: statistical analysis, data pipelines

Certification
======
* NVIDIA Certified Associate: Generative AI and LLMs (NCA-GENL), 2026

Languages spoken
======
* Azerbaijani, English, Turkish, Russian
