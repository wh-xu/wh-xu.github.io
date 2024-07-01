---
permalink: /
title: "About Me | Weihong Xu"
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

I am a fourth-year PhD student in [SeeLab at UCSD](http://seelab.ucsd.edu/), advised by [Prof. Tajana Rosing](https://cseweb.ucsd.edu/~trosing/).
My research interests include a) emerging processing-in-memory (PIM) architectures, b) near-storage computing system, c) hyperdimensional computing. 
Before joining UCSD, I received B.E. and M.E. degrees from [Southeast University](https://www.seu.edu.cn/english), under supervision of [Prof. Chuan Zhang](https://www.researchgate.net/profile/Chuan_Zhang24) and [Prof. Yair Be'ery](http://www.eng.tau.ac.il/~ybeery). I finished a four-month research intern in [Intel Labs China](http://intel.com) where I developed the Flexible MIMO Processor for networks beyond 5G. 
  

% My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).


# 🔥 News
- *2024.06*: &nbsp;🎉🎉 I am currently looking for a postdoc position!

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>

- **[Under Review]** [Tri-HD: Train, Re-train, and Infer with Hyperdimensional Computing in Memory]() \
  **Weihong Xu**, Saransh Gupta, Justin Morris, Xincheng Shen, Mohsen Imani, Baris Aksanli, and Tajana Rosing \
  *Under revision of IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems (TCAD), 2024*
- **[Under Review]** [HyperGen: Compact and Efficient Genome Sketching using Hyperdimensional Vectors](https://github.com/wh-xu/Hyper-Gen) \
  **Weihong Xu**, Po-kai Hsu, Niema Moshiri, Shimeng Yu, and Tajana Rosing \
  *Under revision of Bioinformatics, 2024* \
  [![Repo](https://badgen.net/badge/icon/GitHub?icon=github&label)](https://github.com/wh-xu/Hyper-Gen)
- **[Under Review]** [Proxima: Near-storage Acceleration for Graph-based Approximate Nearest Neighbor Search in 3D NAND](https://arxiv.org/abs/2312.04257) \
  **Weihong Xu**, Junwei Chen, Po-Kai Hsu, Jaeyoung Kang, Minxuan Zhou, Sumukh Pinge, Shimeng Yu, and Tajana Rosing \
  *Under review of IEEE Transactions on Computers, 2024* 
  
- **[JPR 2023]** [HyperSpec: Fast Mass Spectra Clustering in Hyperdimensional Space](https://pubs.acs.org/doi/10.1021/acs.jproteome.2c00612) \
  **Weihong Xu**, Jaeyoung Kang, Wout Bittremieux, Niema Moshiri, and Tajana Rosing \
  *Journal of Proteome Research, 2023* \
  [![Repo](https://badgen.net/badge/icon/GitHub?icon=github&label)](https://github.com/wh-xu/Hyper-Spec)
- **[TCAD 2020]** [RAPIDx: High-performance ReRAM Processing in-Memory Accelerator for DNA Alignment](https://ieeexplore.ieee.org/document/10025378) \
  **Weihong Xu**, Saransh Gupta, Niema Moshiri, and Tajana Rosing \
  *IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems (TCAD), 2023*
- **[TCAD 2020]** [Reconfigurable and Low-complexity Accelerator for Convolutional and Generative Networks over Finite Fields](https://ieeexplore.ieee.org/document/8994049) \
  **Weihong Xu**, Zaichen Zhang, Xiaohu You, and Chuan Zhang \
  *IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems (TCAD), 2020*
- **[JETCAS 2020]** [Deep Learning-aided Belief Propagation Decoder for Polar Codes](https://ieeexplore.ieee.org/document/9097207) \
  **Weihong Xu**, Xiaosi Tan, Yair Be'ery, Zaichen Zhang, Xiaohu You, and Chuan Zhang \
  *IEEE Journal on Emerging and Selected Topics in Circuits and Systems (JETCAS), 2020*
- **[HPCA 2022]** [TransPIM: A Memory-based Acceleration via Software-Hardware Co-Design for Transformers](https://ieeexplore.ieee.org/document/9773212) \
  Minxuan Zhou∗, **Weihong Xu**∗, Jaeyoung Kang, and Tajana Rosing \
  *IEEE International Symposium on High-Performance Computer Architecture (HPCA), 2022*
- **[DAC 2022]** [A Near-Storage Framework for Boosted Data Preprocessing of Mass Spectrum Clustering](https://dl.acm.org/doi/abs/10.1145/3489517.3530449) \
  **Weihong Xu**, Jaeyoung Kang, and Tajana Rosing \
  *IEEE/ACM Design Automation Conference (DAC), 2022*
- **[DATE 2023]** [FSL-HD: Accelerating Few-Shot Learning on ReRAM using Hyperdimensional Computing](https://ieeexplore.ieee.org/document/10136901/) \
  **Weihong Xu**, Jaeyoung Kang, and Tajana Rosing \
  *Design, Automation and Test in Europe Conference (DATE), 2023*
- **[ICCD 2023]** [HyperMetric: Robust Hyperdimensional Computing on Error-prone Memories using Metric Learning](https://www.computer.org/csdl/proceedings-article/iccd/2023/429100a243) \
  **Weihong Xu**, Viji Swaminathan, Sumukh Pinge, Sean Fuhrman, and Tajana Rosing \
  *IEEE International Conference on Computer Design (ICCD), 2023*
- **[TACO 2024]** [Abakus: Accelerating k-mer Counting With Storage Technology](https://dl.acm.org/doi/full/10.1145/3632952) \
  Lingxi Wu*, Minxuan Zhou*, **Weihong Xu**, Ashish Venkat, Tajana Rosing, and Kevin Skadron \
  *ACM Transactions on Architecture and Code Optimization (TACO), 2024*
- **[ESSERC 2024]** [FSL-HDnn: A 5.7 TOPS/W End-to-end Few-shot Learning Classifier Accelerator with Feature Extraction and Hyperdimensional Computing]() \
  Haichao Yang, Chang Eun Song, **Weihong Xu**, Behnam Khaleghi, Uday Mallappa, Monil Shah, Keming Fan, Mingu Kang, and Tajana Rosing \
  *to be presented at European Solid-State Electronics Research Conference (ESSERC), 2024*

# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📖 Education
- *2020 - 2024 (now)*, Ph.D. in Computer Science and Engineering, University of California, San Diego, La Jolla, USA. 
- *2017 - 2020*, M.E. in Information and Communication Engineering, Southeast University, Nanjing, China. 
- *2013 - 2017*, B.E. in Information Engineering, Southeast University, Nanjing, China. 

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.
