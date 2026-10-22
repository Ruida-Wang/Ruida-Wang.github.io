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

I’m a Research Associate at Institute of Information Engineering, Chinese Academy of Sciences (IIE, CAS).

My research focuses on Cryptography, with a particular emphasis on the theory, implementation and application of Fully Homomorphic Encryption **(FHE)**.

You can find my publications and citation statistics on my  
<a href='https://scholar.google.com/citations?user=hpoTTfgAAAAJ'>Google Scholar profile</a>, and view the current citation count via this badge:  
<a href='https://scholar.google.com/citations?user=hpoTTfgAAAAJ'>
  <img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations">
</a>

---
- My research focuses on Cryptography, with a particular emphasis on the theory, implementation and application of Fully Homomorphic Encryption (FHE).
- I obtained my PhD degree in cybersecurity at IIE, CAS. 
- Before coming to IIE, I obtained my Bachelor’s degree in Mathematics and Applied Mathematics at Taishan College, Shandong University.



# 🔥 News

- Our paper **Can Verifiable PIR Match the Online Efficiency of SimplePIR?** has been accepted to **IEEE S&P 2027**.
- Our paper [**Three-Round Weak Non-Malleable Zero-Knowledge Argument**](https://eprint.iacr.org/2026/1964) has been accepted to **ASIACRYPT 2026**.
- Our paper **Decoupled TFHE-type Functional Bootstrapping** has been accepted to **ACM CCS 2026**.

---

# 📝 Selected Publications

**Can Verifiable PIR Match the Online Efficiency of SimplePIR?**<br>
Xinxuan Zhang, **Ruida Wang\***, Zirui Wang, Yuming Guo, Jikang Bai, Yuanju Wei, Yi Deng, Xianhui Lu<br>
[**IEEE Symposium on Security and Privacy (S&P) • 2027**](https://sp2027.ieee-security.org/)<br>
Accepted, to appear.

**Three-Round Weak Non-Malleable Zero-Knowledge Argument**<br>
Xinxuan Zhang, Yuanju Wei, Zhichao Wang, Zhongliang Zhang, Ming Yang, **Ruida Wang**, Yi Deng\*, Hailong Wang<br>
[**International Conference on the Theory and Application of Cryptology and Information Security (ASIACRYPT) • 2026**](https://asiacrypt.iacr.org/2026/)<br>
Accepted, to appear. [Paper](https://eprint.iacr.org/2026/1964) · [PDF](https://eprint.iacr.org/2026/1964.pdf)

**Circuit Bootstrapping: Faster and Smaller**<br>
**Ruida Wang**, Yundi Wen, Zhihao Li, Xianhui Lu\*, Benqiang Wei, Kun Liu, Kunpeng Wang<br>
[**Annual International Conference on the Theory and Applications of Cryptographic Techniques (EUROCRYPT) • 2024**](https://link.springer.com/chapter/10.1007/978-3-031-58723-8_12)<span class='show_paper_citations' data='hpoTTfgAAAAJ:WbkHhVStYXYC'></span>

**Refined TFHE Leveled Homomorphic Evaluation and Its Application**<br>
**Ruida Wang**, Jincheol Ha (co-first author), Xuan Shen, Xianhui Lu\*, Chunling Chen, Kunpeng Wang, Jooyoung Lee\*<br>
[**ACM SIGSAC Conference on Computer and Communications Security (CCS) • 2025**](https://dl.acm.org/doi/abs/10.1145/3719027.3744873)<span class='show_paper_citations' data='hpoTTfgAAAAJ:KxtntwgDAa4C'></span>


**Phalanx: An FHE-Friendly SNARK for Verifiable Computation on Encrypted Data**<br>
Xinxuan Zhang, **Ruida Wang\***, Zeyu Liu, Binwu Xiang, Yi Deng\*, Xianhui Lu\*<br>
[**ACM SIGSAC Conference on Computer and Communications Security (CCS) • 2025**](https://dl.acm.org/doi/10.1145/3719027.3765226)<span class='show_paper_citations' data='hpoTTfgAAAAJ:WbkHhVStYXYC'></span>

**Decoupled TFHE-type Functional Bootstrapping**<br>
Zhihao Li, Xuan Shen, Xianhui Lu\*, **Ruida Wang**, Yuan Zhao, Zhiwei Wang<br>
[**ACM SIGSAC Conference on Computer and Communications Security (CCS) • 2026**](https://www.sigsac.org/ccs/CCS2026/)

\* Corresponding author.

# 💻 Code and Open Source

**LightFHE: Circuit Bootstrapping**<br>
Our NTT-based (EUROCRYPT 2024) and FFT-based (CCS 2025) circuit bootstrapping implementations are available in [LightFHE](https://github.com/LightFHE).<br>
[NTT-based implementation (C++ / OpenFHE)](https://github.com/LightFHE/NTT-based-circuit-bootstrapping) · [FFT-based implementation (Rust)](https://github.com/LightFHE/FFT-based-circuit-bootstrapping)

**AES Transciphering in the HE.org Benchmark Suite**<br>
Our AES transciphering code from *Refined TFHE Leveled Homomorphic Evaluation and Its Application* (CCS 2025) is included as the reference implementation for the AES transciphering workload in the FHE benchmarking suite of [HomomorphicEncryption.org (HE.org)](https://www.homomorphicencryption.org/).<br>
[Benchmark project](https://github.com/fhe-benchmarking/transciphering) · [Reference implementation and attribution](https://github.com/fhe-benchmarking/transciphering/blob/main/submission/README.md)

---

# 📖 Educations

- I obtained my PhD degree in cybersecurity at IIE, CAS. 
- Before coming to IIE, I obtained my Bachelor’s degree in Mathematics and Applied Mathematics at Taishan College, Shandong University.

# 🧪 Research Keywords

**Cryptography** · **FHE**
