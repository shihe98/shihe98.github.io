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

I am currently a PhD Candidate at the [University of Technology Sydney](https://www.uts.edu.au/), Australia. I received my B.Eng. degree from Nanjing Normal University (NNU), China, in 2020, and my M.Sc. degree in Cyber Security from Nanjing University of Science and Technology (NJUST), China, in 2023, under the supervision of Prof. [Anmin Fu](http://202.119.85.163/open/TutorInfo.aspx?dsbh=11083&yxsh=106&zydm=0839) and Prof. [Yansong Gao](https://garrisongys.github.io/garrison/). I am now advised by Prof. [Tianqing Zhu](https://fds.cityu.edu.mo/en/members/179) and Prof. [Bo Liu](https://profiles.uts.edu.au/Bo.Liu).

My research centers on **AI Security & Privacy**, with a particular focus on **backdoor attacks**, **dataset/model copyright protection (watermarking)**, **machine unlearning**, and **LLM safety**. I have published in top venues including **NDSS**, **USENIX Security**, **ACM CCS**, **IEEE TIFS**, **IEEE TDSC**, and **ACM Computing Surveys**. I am the recipient of the **ACM ASIACCS Distinguished Paper Award**, two **Outstanding Master Thesis** awards (Jiangsu Province & NJUST), and an **Outstanding Bachelor Thesis** award.

# 🔥 News

- *2026.06*: 🤝 Invited to serve as a **PC Member** for **USENIX Security 2027**.
- *2026.06*: 📝 Our paper on parameter-agnostic LLM unlearning accepted by **IEEE TIFS 2026** (CCF A).
- *2026.01*: 🎉🎉 One paper on robust probabilistic watermarking for dataset copyright protection accepted by **NDSS 2026** (CCF A, Big 4).
- *2025.10*: 📚 Our comprehensive survey *Unique Security and Privacy Threats of Large Language Models* accepted by **ACM Computing Surveys**.
- *2025.06*: 📝 One paper on machine unlearning via RAG accepted by **IEEE TDSC 2025** (CCF A).
- *2025.03*: 🎉🎉 One paper on data-free model-related attacks accepted by **USENIX Security 2025** (CCF A, Big 4).
- *2024.10*: 📝 One paper on horizontal class backdoor accepted by **ACM CCS 2024** (CCF A, Big 4, Co-First Author).
- *2024.10*: 📝 One paper on Byzantine-robust federated learning accepted by **IEEE TIFS 2024** (CCF A).

<details>
  <summary>More News ...</summary>

  <ul>
  <li> <em>2023.09</em>: 🎓 Started my PhD at the University of Technology Sydney, supported by the <strong>ARC Linkage Scholarship</strong> and <strong>International Research Scholarship</strong>.</li>
  <li> <em>2023.06</em>: 🏆 Awarded the <strong>Outstanding Master Thesis</strong> of Jiangsu Province and NJUST.</li>
  <li> <em>2023.05</em>: 🏆 One paper <em>CASSOCK</em> accepted by <strong>ACM ASIACCS 2023</strong> with <strong>Distinguished Paper Award</strong>.</li>
  </ul>
</details>

# ✨ Selected Papers

(<sup>†</sup>: Equal Contribution)

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NDSS 2026</div><img src='images/DIP.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Unshaken by Weak Embedding: Robust Probabilistic Watermarking for Dataset Copyright Protection

**Shang Wang**, Tianqing Zhu, Dayong Ye, Hua Ma, Bo Liu, Ming Ding, Shengfang Zhai, Yansong Gao, **NDSS 2026**. `CCF A (Big 4)`

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM CSUR 2025</div><img src='images/CSUR.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Unique Security and Privacy Threats of Large Language Models: A Comprehensive Survey

**Shang Wang**, Tianqing Zhu, Bo Liu, Ming Ding, Dayong Ye, Wanlei Zhou, Philip S. Yu, **ACM Computing Surveys 2025**. `Top Journal, IF=28`

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TDSC 2025</div><img src='images/RAG.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

When Machine Unlearning Meets Retrieval-Augmented Generation (RAG): Keep Secret or Forget Knowledge?

**Shang Wang**, Tianqing Zhu, Dayong Ye, Wanlei Zhou, **IEEE Transactions on Dependable and Secure Computing 2025**. `CCF A`

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">USENIX Security 2025</div><img src='images/USENIX.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Data-Free Model-Related Attacks: Unleashing the Potential of Generative AI

Dayong Ye, Tianqing Zhu, **Shang Wang**, Bo Liu, Leo Yu Zhang, Wanlei Zhou, Yang Zhang, **USENIX Security 2025**. `CCF A (Big 4)`

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM CCS 2024</div><img src='images/HCB.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Watch Out! Simple Horizontal Class Backdoor Can Trivially Evade Defense

Hua Ma<sup>†</sup>, **Shang Wang<sup>†</sup>**, Yansong Gao, Zhi Zhang, Huming Qiu, Minhui Xue, Alsharif Abuadbba, Anmin Fu, Surya Nepal, Derek Abbott, **ACM CCS 2024**. `CCF A (Big 4)`

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ASIACCS 2023, Distinguished Paper</div><img src='images/AsiaCCS.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

CASSOCK: Viable Backdoor Attacks against DNN in The Wall of Source-Specific Backdoor Defences

**Shang Wang**, Yansong Gao, Anmin Fu, Zhi Zhang, Yuqing Zhang, Willy Susilo, Dongxi Liu, **ACM ASIACCS 2023**. `CCF C, Distinguished Paper Award`

</div>
</div>


# 📝 Publications

{: #publications}

## 🎙 Conferences

- Unshaken by Weak Embedding: Robust Probabilistic Watermarking for Dataset Copyright Protection, **Shang Wang**, Tianqing Zhu, Dayong Ye, Hua Ma, Bo Liu, Ming Ding, Shengfang Zhai, Yansong Gao, **Network and Distributed System Security Symposium, NDSS 2026**. `CCF A (Big 4)`
- Data-Free Model-Related Attacks: Unleashing the Potential of Generative AI, Dayong Ye, Tianqing Zhu, **Shang Wang**, Bo Liu, Leo Yu Zhang, Wanlei Zhou, Yang Zhang, **The 34th USENIX Security Symposium, USENIX Security 2025**. `CCF A (Big 4)`
- Watch Out! Simple Horizontal Class Backdoor Can Trivially Evade Defense, Hua Ma<sup>†</sup>, **Shang Wang<sup>†</sup>**, Yansong Gao, Zhi Zhang, Huming Qiu, Minhui Xue, Alsharif Abuadbba, Anmin Fu, Surya Nepal, Derek Abbott, **ACM Conference on Computer and Communications Security, ACM CCS 2024**. `CCF A (Big 4)`
- CASSOCK: Viable Backdoor Attacks against DNN in The Wall of Source-Specific Backdoor Defences, **Shang Wang**, Yansong Gao, Anmin Fu, Zhi Zhang, Yuqing Zhang, Willy Susilo, Dongxi Liu, **ACM ASIA Conference on Computer and Communications Security, ACM ASIACCS 2023**. `CCF C, Distinguished Paper Award`

## 🧾 Journals

- Parameter-agnostic Privacy-preserving Machine Unlearning for Large Language Models, Lefeng Zhang, Tianqing Zhu, Zihan Xie, **Shang Wang**, Binxing Fang, Wanlei Zhou, IEEE Transactions on Information Forensics and Security 2026. `CCF A`
- Unique Security and Privacy Threats of Large Language Models: A Comprehensive Survey, **Shang Wang**, Tianqing Zhu, Bo Liu, Ming Ding, Dayong Ye, Wanlei Zhou, Philip S. Yu, **ACM Computing Surveys 2025**. `Top Journal, IF=28`
- When Machine Unlearning Meets Retrieval-Augmented Generation (RAG): Keep Secret or Forget Knowledge?, **Shang Wang**, Tianqing Zhu, Dayong Ye, Wanlei Zhou, **IEEE Transactions on Dependable and Secure Computing 2025**. `CCF A`
- Isolate Trigger: Detecting and Eradicating Evade-Adaptive Backdoors, Chengrui Sun, Hua Zhang, Haoran Gao, Zian Tian, Jianjin Zhao, Hongliang Zhu, Zongliang Shen, **Shang Wang**, Anmin Fu, **arXiv:2508.04094, 2025**.
- CareFL: Contribution Guided Byzantine-Robust Federated Learning, Qihao Dong, Shengyuan Yang, Zhiyang Dai, Yansong Gao, **Shang Wang**, Yuan Cao, Anmin Fu, Willy Susilo, **IEEE Transactions on Information Forensics and Security 2024**. `CCF A`
- LinkBreaker: Breaking the Backdoor-Trigger Link in DNNs via Neurons Consistency Check, Zhenzhu Chen, **Shang Wang**, Anmin Fu, Yansong Gao, Shui Yu, Robert H. Deng, **IEEE Transactions on Information Forensics and Security 2022**. `CCF A`
- A Trigger Sample Detection Scheme Based on Custom Backdoor Behaviors, **Shang Wang**, Xin Li, Yongli Song, Mang Su, Anmin Fu, **Journal of Cyber Security 2022**. `CCF B (Chinese Journal)`
- Research and Challenge of Distributed Deep Learning Privacy and Security Attack, Chunyi Zhou, Dawei Chen, **Shang Wang**, Anmin Fu, Yansong Gao, **Journal of Computer Research and Development 2021**. `CCF A (Chinese Journal)`

## 📜 Patents

- A Plug-in Trigger Inputs Detection Method, Anmin Fu, **Shang Wang**, 2022.

# 🎖 Honors and Awards

- *2023* **Outstanding Master Thesis**, Jiangsu Province.
- *2023* **Outstanding Master Thesis**, Nanjing University of Science and Technology.
- *2023* ARC Linkage Scholarship & International Research Scholarship, University of Technology Sydney.
- *2023* Outstanding Graduate Student, Nanjing University of Science and Technology.
- *2023* ACM ASIACCS **Distinguished Paper Award** (for CASSOCK).
- *2022* 2nd place, NeurIPS 2022 competition (**Top 2**).
- *2021* 1st prize, National Cryptography Competition (**Top 5%**).
- *2020–2023* First-Class Scholarship (×2) & Second-Class Scholarship, NJUST.
- *2020* **Outstanding Bachelor Thesis**, Nanjing Normal University.
- *2016–2020* First-Class Scholarship (×3), Second-Class Scholarship, Zhu Jingwen Scholarship, Merit Student, Outstanding Student Leader, Outstanding SRTP, Excellence in Learning Award, NNU.

# 🏛️ Educations

{: #educations}

- *2023.09 – present*, Ph.D. Candidate, University of Technology Sydney, Sydney, Australia. Advisor: Prof. Tianqing Zhu and Prof. Bo Liu.
- *2020.09 – 2023.06*, M.Sc. in Cyber Security, Nanjing University of Science and Technology, Nanjing, China. GPA: 3.87/4.0 (Rank 8). Advisors: Prof. Anmin Fu and Prof. Yansong Gao.
- *2016.09 – 2020.06*, B.Eng. in Computer Science, Nanjing Normal University, Nanjing, China. GPA: 3.96/4.0 (Rank 1).

# 🧑‍🎨 Service

- International Conference on Knowledge Science, Engineering and Management 2025
- International Conference on Algorithms and Architectures for Parallel Processing 2024
- Australasian Conference on Information Security and Privacy 2024
- IEEE Transactions on Information Forensics and Security
- IEEE Transactions on Neural Networks and Learning Systems
- IEEE Transactions on Circuits and Systems for Video Technology
- IEEE Transactions on Emerging Topics in Computing
- IEEE Transactions on Artificial Intelligence
- Journal of Systems Architecture
- Computer Standards & Interfaces
- Knowledge-Based Systems
- Neural Networks