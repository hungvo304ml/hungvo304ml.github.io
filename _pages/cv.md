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
* Ph.D in Electrical and Computer Engineering, University of Houston, 2021-2015 (expected)
  * Machine Learning for Multi-modal Medical Data: Multi-modal Learning, Unsupervised Learning, and Data with limited labels learning.
  * Advisor: [Prof. Hien V. Nguyen](https://www.hvnguyen.com/)
  * Co-Advisor: [Dr. Stephen T.C. Wong](https://scholar.google.com/citations?user=C2gJxXYAAAAJ&hl=en)
* B.S. in Computer Science, Vietnam National University-University of Information Technology, 2015-2019
  * Honor Degree in Computer Science
  * Thesis: Multi‑modal Person Retrieval with limited and noisy query data in Large‑scale video database
  * Advisor: [Prof. Duy-Dinh Le](https://researchmap.jp/ledduy)

Work experience
======
* Houston Learning Algorithms Laboratory (HULA Lab), University of Houston
  * Research Assistant, Jan. 2021 ‑ Present
	* Machine learning for multimodal medical data: Images (Mammograms, Lung CT scans), Text (Clinical reports), Tabular (EHR records)
	* Self-supervised learning, Weakly-supervised learning, and Limited data Learning for medical domain where data annotation is expensive, requiring expert knowledge, and sometimes limited (e.g: rare diseases).
* Systems Medicine and Bioengineering Laboratory (SMAB Lab), Houston Methodist Research Institute, Houston Methodist Hospital
  * Visiting Graduate Research Fellow, Jan. 2022 ‑ Present
	* Working with a multi‑disciplinary team from the Houston Methodist Hospital.
	* Develop AI algorithms to apply on real patients multi‑modal data from Houston Methodist Cancer Center including medical images, structured EHR, and clinical reports for Breast and Lung Cancer Risk Assessment.
	* Human-AI collaboration for extracting useful clinical concepts from a large numbers of radiology reports. Specifically, we explore clinical concepts from ~400k radiology reports using expert-augmented deep learning.
* Multimedia Communications Laboratory (MMLab‑UIT), VNUHCM‑University of Information Technology
  * Research Assistant, Research Student, Oct. 2017 ‑ Oct. 2020
	* Person Retrieval re‑ranking through representation learning with weakly‑supervised hard negative mining.
	* Person Retrieval, Place Retrieval, and Action Retrieval in large‑scale video database (~470k videos) using image, video, and audio embeddings and set‑to‑set matching.
	* Adaptive weighting scheme for effective fusion of multiple rank lists by applying learning‑to‑rank technique.
  
Skills
======
* Programming Languages
  * Python
  * C++ 
* Libraries 
  * Pytorch, Keras, scikit-learn, Tensorflow
  * OpenCV, Numpy, Pandas
  * Stanza NLP, Spacy, Flair NLP
* Languages:
  * English: Professional Proficiency 

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Achievements
======
  <ul>{% for post in site.achievements reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
