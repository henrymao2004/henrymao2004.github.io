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
* B.S. in Computer Science, Vanderbilt University, 2022-2025 (expected)
  * GPA: 3.867/4.0
  * Key courses: AI, Foundation of Machine Learning, Data Mining and AI, Privacy & Security (PhD-Level)
  * Dean's List for all semesters (Fall 2022-Spring 2025)
  * Vanderbilt University Summer Research Scholarship (2025)

Work experience
======
* May 2024 - August 2024: Cloud Engineer Intern
  * Pegasystems, Boston, MA
  * Designed an automated security alert system for CI/CD pipelines using AWS CloudWatch, Lambda, and Elasticsearch
  * Generated over 10 security reports and reduced vulnerability exposure by 40%
  * Implemented proactive early-stage issue detection

Research experience
======
* September 2023 - May 2025: Research on Fake Voice Generation and Fake Voice Detection
  * Leader & First Author, Supervised by Dr. Dan (Linda) Lin, Vanderbilt University
  * Investigated the evolving threat landscape targeting voice-based systems, identifying potential misuse scenarios of fake voice generation about advanced TTS and voice conversion technologies
  * Benchmarked the resilience of 20+ fake voice generators and 8 fake voice detectors to investigate the interaction and threats between fake voice generation and detection

* October 2024 - July 2025: Research on Personalization Imputation on Textual Edge Graph
  * Key Contributor & Co-first Author, Supervised by Dr. Tyler Derr, Vanderbilt University
  * Designed and implemented a graph-aware LLM aggregator that captures higher-order context through line-graph views, enabling the generation of coherent, personalized reviews that are more helpful, authentic, and specific
  * Conducted comprehensive evaluations on Amazon and Goodreads benchmarks, demonstrating superior performance over numeric, graph-based, and LLM baselines in both recommendation quality and review generation

* April 2025 - June 2025: Research on Opinion Distribution Prediction in Social Media (MindVote)
  * Leader & First Author
  * Developed MindVote, a comprehensive benchmark for evaluating LLMs' ability to predict human opinions within naturalistic social discourse, addressing critical limitations of existing sanitized survey-based evaluation methods
  * Revealed substantial performance gaps and systematic biases invisible to traditional benchmarks, including domain-specific knowledge limitations, source of origin bias, and social media context dependencies, enabling authentic assessment of LLM social reasoning capabilities

* June 2025 - August 2025: Research on Text-to-SQL Optimization via Graph-guided Reasoning
  * Co-first Author, Supervised by Dr. Hongying Zan, Zhengzhou University
  * Developed SteinerSQL, a novel three-stage framework that reformulates complex mathematical Text-to-SQL generation as a unified graph optimization problem
  * Addressed the dual challenge of multi-step computation decomposition and intricate database schema navigation, achieving state-of-the-art performance with 36.10% execution accuracy on LogicCat and 36.75% on Spider2.0-Lite

Skills
======
* Programming Languages: Python, Java, C++, JavaScript, SQL
* Machine Learning: TensorFlow, PyTorch, Scikit-learn, Natural Language Processing
* Cloud Technologies: AWS (CloudWatch, Lambda, Elasticsearch), CI/CD pipelines
* Research Areas: Fake Voice Detection, Graph Neural Networks, Large Language Models, Text-to-SQL
* Languages: English (Native), Chinese (Native)

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
* Vanderbilt University Summer Research Scholarship recipient (2025)
* Consistent Dean's List recognition (Fall 2022-Spring 2025)
