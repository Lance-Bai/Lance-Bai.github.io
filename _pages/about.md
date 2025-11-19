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

A PhD student in cryptography at the **Institute of Information Engineering, Chinese Academy of Sciences (IIE, CAS)**.  
Focusing on **fully homomorphic encryption (FHE)**, especially:

- TFHE-style **programmable bootstrapping and homomorphic lookup tables (LUT)**  
- Algebraic and tensor-based **bootstrapping frameworks**  
- **FHE system / ISA design** and implementation  
- **Trusted Execution Environments (TEE)** and hybrid **FHE+TEE** architectures

Interested in closing the gap between theoretical FHE constructions and **deployable systems**, through better bootstrapping algorithms, LUT frameworks, and hardware-/compiler-friendly abstractions.  

You can find my publications and citation statistics on my  
<a href='https://scholar.google.com/citations?user=kAH3Ha8AAAAJ'>Google Scholar profile</a>, and view the current citation count via this badge:  
<a href='https://scholar.google.com/citations?user=kAH3Ha8AAAAJ'>
  <img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations">
</a>

---

# 🔥 News

- *2025.10* &nbsp;🎉 Our work **“FH-TEE: Single Enclave for all Applications”** was presented at **Inscrypt 2025**, exploring hybrid designs that combine trusted execution environments with FHE for practical secure computation.
- *2025.09* &nbsp;🎉 **“Bootstrapping over Free \\(\mathcal{R}\\)-Module”** appeared on the IACR ePrint Archive, introducing a new accumulator structure that decouples the modulus and ring dimension in TFHE-style bootstrapping.
- *2025.09* &nbsp;🎉 **“Tetris: Versatile TFHE LUT and Its Application to FHE Instruction Set Architecture”** was posted to IACR ePrint, proposing a general TFHE LUT framework and an FHE-ISA for high-precision homomorphic computation.

<!-- *(Replace or extend the items above with your real news as needed.)* -->

---

# 📝 Selected Publications

<!-- Tetris -->
<div class='paper-box'>
  <!-- 有配图时可启用 -->
  <!--
  <div class='paper-box-image'>
    <div>
      <div class="badge">ePrint 2025</div>
      <img src='images/500x300.png' alt="Tetris" width="100%">
    </div>
  </div>
  -->
  <div class='paper-box-text' markdown="1">

**Tetris: Versatile TFHE LUT and Its Application to FHE Instruction Set Architecture**  
*Ruida Wang, **Jikang Bai**, Xuan Shen, Xianhui Lu, Zhihao Li, Binwu Xiang, Zhiwei Wang, Hongyu Wang, Lutan Zhao, Kunpeng Wang*  

[**Paper (IACR ePrint 2025/1623)**](https://eprint.iacr.org/2025/1623)  
<span class='show_paper_citations' data='TODO_REPLACE_TETRIS_ID'></span>  

Tetris proposes a versatile TFHE LUT framework that supports higher-precision homomorphic instructions and enables the design of an FHE instruction set architecture (FHE-ISA). It integrates GLWE-based LUTs, batched circuit bootstrapping, and parallel evaluation strategies to significantly improve precision and performance.
  </div>
</div>

<!-- Free R-module -->
<div class='paper-box'>
  <!--
  <div class='paper-box-image'>
    <div>
      <div class="badge">ePrint 2025</div>
      <img src='images/500x300.png' alt="Free R-module" width="100%">
    </div>
  </div>
  -->
  <div class='paper-box-text' markdown="1">

**Bootstrapping over Free \\(\mathcal{R}\\)-Module**  
*Ruida Wang, **Jikang Bai**, Yijian Liu, Xinxuan Zhang, Xianhui Lu, Lutan Zhao, Kunpeng Wang, Rui Hou*  

[**Paper (IACR ePrint 2025/1753)**](https://eprint.iacr.org/2025/1753)  
<span class='show_paper_citations' data='TODO_REPLACE_FREE_R_MODULE_ID'></span>  

This work revisits algebraic accumulator-based bootstrapping and introduces a free \\(\mathcal{R}_N\\)-module structure to decouple modulus \\(q\\) and polynomial dimension \\(N\\), achieving asymptotic and concrete improvements in precision, performance, and key size.
  </div>
</div>

<!-- FH-TEE -->
<div class='paper-box'>
  <!--
  <div class='paper-box-image'>
    <div>
      <div class="badge">Inscrypt 2025</div>
      <img src='images/500x300.png' alt="FH-TEE" width="100%">
    </div>
  </div>
  -->
  <div class='paper-box-text' markdown="1">

**FH-TEE: Single Enclave for all Applications**  
***Jikang Bai**, Ruida Wang, Xianhui Lu, Chunling Chen, Kunpeng Wang*  

*Presented at Inscrypt 2025*  
<span class='show_paper_citations' data='TODO_REPLACE_FH_TEE_ID'></span>  

FH-TEE studies how to combine trusted execution environments and FHE in a single-enclave architecture, aiming to balance security, performance, and programmability for practical encrypted computing.
  </div>
</div>


# 🎖 Honors and Awards

---

# 📖 Educations

- **Ph.D. in Cryptography**, *Institute of Information Engineering, Chinese Academy of Sciences (IIE, CAS)*, Beijing, China  
  *2023 – Present*

- **B.Eng. in Internet of Things Engineering**, *Beijing University of Technology (BJUT)*, Beijing, China  
  *2019 – 2023*

# 🧪 Research Keywords

**Fully Homomorphic Encryption (FHE)** · **TFHE / FHEW** · **Programmable Bootstrapping** · **Homomorphic LUTs** ·  
**FHE Instruction Set Architecture (FHE-ISA)** · **Bootstrapping over Algebraic Structures** ·  
**Trusted Execution Environments (TEE)** · **Secure Computation** · **Privacy-Preserving Systems**
