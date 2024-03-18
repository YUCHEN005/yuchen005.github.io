---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am currently a 3<sup>rd</sup>-year Ph.D. student at School of Computer Science and Engineering, Nanyang Technological University, supervised by Prof. [Eng Siong Chng](https://scholar.google.com/citations?hl=en&user=FJodrCcAAAAJ). 
Prior to this, I received my B.Eng. degree from University of Science and Technology of China in 2020.

My research focus on **large language model (LLM), automatic speech recognition (ASR), and multimodal**.

# 📖 Educations
Nanyang Technological University (NTU),&nbsp; *08/2021 - 08/2025*

* Ph.D. in Computer Science. Supervisor: Eng Siong Chng.

University of Science and Technology of China (USTC),&nbsp; *09/2016 - 06/2020*

* B.Eng. in Automation. GPA: 3.76/4.3 (Rank: top 5%)&nbsp; [[Transcript]](https://yuchen005.github.io/files/transcript_en_zh.pdf)


# 📝 Publications 

- <span style="display:inline-block; background-color:#00369F; color:#fff; padding:0px 7px; margin-right:5px; font-size:13px;">Preprint</span> [GenTranslate: Large Language Models are Generative Multilingual Speech and Machine Translators](https://arxiv.org/abs/2402.06894), **<u>Yuchen Hu</u>**, Chen Chen, Chao-Han Huck Yang, Ruizhe Li, Dong Zhang, Zhehuai Chen, Eng Siong Chng. [[Code]](https://github.com/YUCHEN005/GenTranslate) [[Data]](https://huggingface.co/datasets/PeacefulData/HypoTranslate)

- <span style="display:inline-block; background-color:#00369F; color:#fff; padding:0px 7px; margin-right:5px; font-size:13px;">ICLR 2024</span> [Large Language Models are Efficient Learners of Noise-Robust Speech Recognition](https://openreview.net/pdf?id=ceATjGPTUD), **<u>Yuchen Hu</u>**, Chen Chen, Chao-Han Huck Yang, Ruizhe Li, Chao Zhang, Pin-Yu Chen, Eng Siong Chng. [[Code]](https://github.com/YUCHEN005/RobustGER) [[Data]](https://huggingface.co/datasets/PeacefulData/Robust-HyPoradise)

- <span style="display:inline-block; background-color:#00369F; color:#fff; padding:0px 7px; margin-right:5px; font-size:13px;">NeurIPS 2023</span> [HyPoradise: An Open Baseline for Generative Speech Recognition with Large Language Models](https://arxiv.org/abs/2309.15701), Chen Chen\*, **<u>Yuchen Hu</u>\***, Chao-Han Huck Yang, Sabato Marco Siniscalchi, Pin-Yu Chen, Eng Siong Chng. [[Code]](https://github.com/Hypotheses-Paradise/Hypo2Trans) [[Data]](https://huggingface.co/datasets/PeacefulData/HP-v0)

- <span style="display:inline-block; background-color:#00369F; color:#fff; padding:0px 7px; margin-right:5px; font-size:13px;">ACL 2023</span> [Hearing Lips in Noise: Universal Viseme-Phoneme Mapping and Transfer for Robust Audio-Visual Speech Recognition](https://aclanthology.org/2023.acl-long.848.pdf), **<u>Yuchen Hu</u>**, Ruizhe Li, Chen Chen, Chengwei Qin, Qiushi Zhu, Eng Siong Chng. [[Code]](https://github.com/YUCHEN005/UniVPM)

- <span style="display:inline-block; background-color:#00369F; color:#fff; padding:0px 7px; margin-right:5px; font-size:13px;">ACL 2023</span> [MIR-GAN: Refining Frame-Level Modality-Invariant Representations with Adversarial Network for Audio-Visual Speech Recognition](https://aclanthology.org/2023.acl-long.649.pdf), **<u>Yuchen Hu</u>**, Chen Chen, Ruizhe Li, Heqing Zou, Eng Siong Chng. [[Code]](https://github.com/YUCHEN005/MIR-GAN)

- <span style="display:inline-block; background-color:#00369F; color:#fff; padding:0px 7px; margin-right:5px; font-size:13px;">IJCAI 2023</span> [Cross-Modal Global Interaction and Local Alignment for Audio-Visual Speech Recognition](https://www.ijcai.org/proceedings/2023/0564.pdf), **<u>Yuchen Hu</u>**, Ruizhe Li, Chen Chen, Heqing Zou, Qiushi Zhu, Eng Siong Chng. [[Code]](https://github.com/YUCHEN005/GILA)

- <span style="display:inline-block; background-color:#00369F; color:#fff; padding:0px 7px; margin-right:5px; font-size:13px;">IEEE/ACM TASLP 2023</span>  [Wav2code: Restore Clean Speech Representations via Codebook Lookup for Noise-Robust ASR](https://arxiv.org/abs/2304.04974), **<u>Yuchen Hu</u>**, Chen Chen, Qiushi Zhu, Eng Siong Chng.

- <span style="display:inline-block; background-color:#00369F; color:#fff; padding:0px 7px; margin-right:5px; font-size:13px;">Preprint</span>  [Noise-aware Speech Enhancement using Diffusion Probabilistic Model](https://arxiv.org/abs/2307.08029), **<u>Yuchen Hu</u>**, Chen Chen, Ruizhe Li, Qiushi Zhu, Eng Siong Chng. [[Code]](https://github.com/YUCHEN005/NASE)

- <span style="display:inline-block; background-color:#00369F; color:#fff; padding:0px 7px; margin-right:5px; font-size:13px;">ICASSP 2023</span>  [Unifying Speech Enhancement and Separation with Gradient Modulation for End-to-End Noise-Robust Speech Separation](https://arxiv.org/abs/2302.11131), **<u>Yuchen Hu</u>**, Chen Chen, Heqing Zou, Xionghu Zhong, Eng Siong Chng. [[Code]](https://github.com/YUCHEN005/Unified-Enhance-Separation)

- <span style="display:inline-block; background-color:#00369F; color:#fff; padding:0px 7px; margin-right:5px; font-size:13px;">ICASSP 2023</span>  [Gradient Remedy for Multi-Task Learning in End-to-End Noise-Robust Speech Recognition](https://arxiv.org/abs/2302.11362), **<u>Yuchen Hu</u>**, Chen Chen, Ruizhe Li, Qiushi Zhu, Eng Siong Chng. [[Code]](https://github.com/YUCHEN005/Gradient-Remedy)

- <span style="display:inline-block; background-color:#00369F; color:#fff; padding:0px 7px; margin-right:5px; font-size:13px;">InterSpeech 2023</span>  [Dual-Path Style Learning for End-to-End Noise-Robust Speech Recognition](https://www.isca-archive.org/interspeech_2023/hu23_interspeech.pdf), **<u>Yuchen Hu</u>**, Nana Hou, Chen Chen, Eng Siong Chng. [[Code]](https://github.com/YUCHEN005/DPSL-ASR)

- <span style="display:inline-block; background-color:#00369F; color:#fff; padding:0px 7px; margin-right:5px; font-size:13px;">ICASSP 2022</span>  [Interactive Feature Fusion for End-to-End Noise-Robust Speech Recognition](https://arxiv.org/abs/2110.05267), **<u>Yuchen Hu</u>**, Nana Hou, Chen Chen, Eng Siong Chng. [[Code]](https://github.com/YUCHEN005/DPSL-ASR)

- <span style="display:inline-block; background-color:#00369F; color:#fff; padding:0px 7px; margin-right:5px; font-size:13px;">IWSLT 2021</span>  [The USTC-NELSLIP Systems for Simultaneous Speech Translation Task at IWSLT 2021](https://arxiv.org/abs/2110.05267), Dan Liu, Mengge Du, Xiaoxi Li, **<u>Yuchen Hu</u>**, Lirong Dai. [[Paper]](https://aclanthology.org/2021.iwslt-1.2.pdf)


# 💻 Internships
Iflytek AI Research, *05/2020 - 07/2021*
* Research intern at ASR group. Supervisor: Lirong Dai.
* Work on end-to-end ASR and speech translation.


# 🧑‍🔬 Service
- **Reviewer:**&nbsp; ACL (23-24), ARR (23-24), EMNLP (23), AAAI (24), ICASSP (22,24), InterSpeech (22-23)
- **Volunteer:**&nbsp; EMNLP (23), ICASSP (22)


# 🎖 Honors and Awards
- Winner of IWSLT 2021 Evaluation Campaign,&nbsp; *08/2021*
- USTC Excellent Graduate (Top 10%),&nbsp; *06/2020*
- Scholarship of SIMIT, Chinese Academy of Sciences (Top 5%),&nbsp; *10/2018*
- USTC Outstanding Student Scholarship (Top 5%),&nbsp; *10/2017 \& 10/2019*



Thanks for the template of <a href="https://github.com/RayeRen/acad-homepage.github.io">Yi Ren</a>

<script type="text/javascript" id="clustrmaps" src="//cdn.clustrmaps.com/map_v2.js?cl=ffffff&w=300&t=n&d=tWtQE7TmvuyYwZoMvhZ03hz9JwVV2jqLDfST5K4doxk&co=9fc7e3&cmo=3acc3a&cmn=ff5353&ct=ffffff"></script>
