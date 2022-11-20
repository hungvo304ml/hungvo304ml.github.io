---
title: "NII Hitachi UIT at TREC Video Retrieval Evaluation 2019 ‑ Instance Search Track."
collection: publications
permalink: /publication/trecvid-2019
excerpt: Duy-Dinh Le\* <b>Hung-Quoc Vo*</b>, ..., Vinh-Tiep Nguyen, Tien-Van Do, Thanh-Duc Ngo, Zheng Wang, Shin'ichi Satoh<br/><a href="https://www-nlpir.nist.gov/projects/tvpubs/tv19.papers/nii_hitachi_uit.pdf">[paper]</a><a href="https://github.com/hungvo304ml/Instance-Search">[code]</a><a href="https://youtu.be/uWH5L22imkU">[demo]</a><br/><img src='/images/publications/trecvid-2019.gif'>
date: 2019-10-01
venue: 'TRECVID 2019, Gaithersburg, MD, USA'
---
TRECVID INS 2019 [1] gives us a new task which is to find a specific person doing a specific action as denoted in query examples. In this work, we split the problem into two separate tasks: finding a person and finding action. To find person, we first use VGGFace2 for face representation, then face is matched and reranked using cosine similarity. For action, two different approaches are used for audio type (e.g.: laughing, shouting, crying) and visual type (e.g.: holding glass, carrying bag), respectively. With audio-type action, we use VGGish for audio representation while for visual-type action, C3D and Semantic feature extracted from VGG-1K are used. Similar to person task, matching and ranking are then applied using cosine similarity. In the end, we fused two computed similarity scores of person and action for the final rank list. Our team achieves 3rd rank in TRECVID INS 2019.

[Download paper here](https://www-nlpir.nist.gov/projects/tvpubs/tv19.papers/nii_hitachi_uit.pdf)
