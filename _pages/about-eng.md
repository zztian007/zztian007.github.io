---
layout: alter_eng
permalink: /eng/
title: "AcademicHomepage"
excerpt: ""
author_profile: true
redirect_from: 
  - /about-eng/
  - /about-eng.html
---


{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I'm an associate professor in the School of Computer Science, Xi'an University of Posts and Telecommunications. My research is mainly on software and System Security. My research interest includes Code Similarity Detection, AI for software Engineering, Smart Contract Analysis, Vulnerability Detection. I have published 30+ papers with <a href='https://scholar.google.com/citations?user=Rz5GXAoAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>.


<span class='anchor' id='-xl'></span>

# 🎓 Educations
- *2019.07 - 2020.08*, College of Information Sciences and Technology, Pennsylvania State University, Visiting Scholar (Advisor: Prof. Dinghao Wu). 
- *2010.09 - 2016.12*, School of Computer Science and Technology, Xi'an Jiaotong University, PhD (Advisor: Prof. Qinghua Zheng, A.P. Ting Liu).
- *2006.09 - 2010.07*, School of Computer Science and Technology, Xi'an Jiaotong University, Bachelor. 

 
<span class='anchor' id='-lwzl'></span>

# 📝 Publications

### Journal
---
- `Zhenzhou Tian`, Minghao Li, Jiaze Sun, Yanping Chen, and Lingwei Chen. Enhancing Vulnerability Detection by Fusing Code Semantic Features with LLM-Generated Explanations. *Information Fusion*. 2025. (JCR 1)

- `Zhenzhou Tian`, Yudong Teng, Xianqun Ke, Yanping Chen, and Lingwei Chen. SolBERT: Advancing Solidity Smart Contract Similarity Analysis via Self-Supervised Pre-Training and Contrastive Fine-Tuning. * Information and Software Technology*. 2025. (CCF B)

- `Zhenzhou Tian`, Rui Qiu, Yudong Teng, Jiaze Sun, Yanping Chen, and Lingwei Chen. Towards Cost-Efficient Vulnerability Detection with Cross-Modal Adversarial Reprogramming. *Journal of Systems and Software*. 2025: 112365. (CCF B)

- `Zhenzhou Tian`, Haojiang Li, Hanlin Sun, Yanping Chen, and Lingwei Chen. HardVD: High-Capacity Cross-Modal Adversarial Reprogramming for Data-Efficient Vulnerability Detection. *Information Sciences*. 2025, 686:121370. (CCF B)

- `Zhenzhou Tian`, Yuchen Gong, Chenhao Chang, Jiaze Sun, Yanping Chen, and Lingwei Chen. An Empirical Study on the Divergence of Differently-Sourced LLVM IRs. *Journal of Computer Languages*. 2024, 81: 101289. (<font color='red'>Best Paper Award</font>)

- `Zhenzhou Tian`, Fanfan Wang, Yanping Chen, and Lingwei Chen. Differential Testing Solidity Compiler through Deep Contract Manipulation and Mutation. *Software Quality Journal*. 2024, 32, 765–790.

- `Zhenzhou Tian`, Ruikang He, Hongliang Zhao, and Lingwei Chen. Function-Level Code Obfuscation Detection Through Self-Attention Guided Multi-Representation Fusion. *International Journal of Software Engineering and Knowledge Engineering*. 2024, 34(04): 651-673.

- `Zhenzhou Tian`, Binhui Tian, Jiajun Lv, Yanping Chen, and Lingwei Chen. Enhancing Vulnerability Detection via AST Decomposition and Neural Sub-tree Encoding. *Expert Systems with Applications*. 2024, 238: 121865. (JCR 1)

- `Zhenzhou Tian`, Binhui Tian, Jiajun Lv, and Lingwei Chen. Learning and Fusing Multi-View Code Representations for Function Vulnerability Detection. *Electronics*. 2023, 12(11).
  
- `Zhenzhou Tian`, Jie Tian, Zhongmin Wang, Yanping Chen, Hong Xia, and Lingwei Chen. Landscape Estimation of Solidity Version Usage on Ethereum via Version Identification. *International Journal of Intelligent Systems*. 2022, 37(1): 450-477. (JCR 1)

- `Zhenzhou Tian`, Yaqian Huang, Borun Xie, Yanping Chen, Lingwei Chen, and Dinghao Wu. Fine-Grained Compiler Identification with Sequence-oriented Neural Modeling. *IEEE ACCESS*. 2021, 49160-49175.
  
- `Zhenzhou Tian`, Qing Wang, Cong Gao, Lingwei Chen, and Dinghao Wu. Plagiarism Detection of Multi-threaded Programs via Siamese Neural Networks. *IEEE ACCESS*, 2020. (8): 160802-160814.
  
- `Zhenzhou Tian`, Qing Wang, Cong Gao, Lingwei Chen, and Dinghao Wu. Plagiarism Detection of Multi-threaded Programs using Frequent Behavioral Pattern Mining. *International Journal of Software Engineering and Knowledge Engineering*, 2020. 30(11-12): 1667-1688.

- `Zhenzhou Tian`, Ningning Wang, Qing Wang, Cong Gao, Ting Liu, and Qinghua Zheng. Plagiarism Detection of Multi-threaded Programs by Mining Behavioral motifs. *Journal of Computer Research and Development*. 2020, 57(1): 202-213.

- Cong Gao, Zhongmin Wang, Yanping Chen, and `Zhenzhou Tian`. A Scalable Two-Hop Multi-Sink Wireless Sensor Network for Data Collection in Large-Scale Smart Manufacturing Facilities. *Journal of Information Science & Engineering*. 2020, 36(4): 795-819.

- Cong Gao, `Zhenzhou Tian`, Yanping Chen, and Zhongmin Wang. A Cost-Efficient Virtual Sensor Management Scheme for Manufacturing Network in Smart Factory. *Journal of Information Science & Engineering*. 2019, 35(5): 1075-1097. 

- `Zhenzhou Tian`, Ting Liu, Qinghua Zheng, Eryue Zhuang, Ming Fan, and Zijiang Yang. Reviving Sequential Program Birthmarking for Multithreaded Software Plagiarism Detection. *IEEE Transactions on Software Engineering*. 2018, 44(5): 491-511. (CCF A)

- Ming Fan, Jun Liu, Xiapu Luo, Kai Chen, `Zhenzhou Tian`, Qinghua Zheng, and Ting Liu. Android Malware Familial Classification and Representative Sample Selection via Frequent Subgraph Analysis. *IEEE Transactions on Information Forensics and Security*. 2018, 13(8): 1890-1905. (CCF A)

- Ming Fan, Jun Liu, Wei Wang, Haifei Li, `Zhenzhou Tian`, and Ting Liu. DAPASA: Detecting Android Piggybacked Apps through Sensitive Subgraph Analysis. *IEEE Transactions on Information Forensics and Security*. 2018, 12(8): 1772-1785. (CCF A)

- `Zhenzhou Tian`, Ting Liu, Qinghua Zheng, Ming Fan, Eryue Zhuang, and Zijiang Yang. Exploiting Thread-Related System Calls for Plagiarism Detection of Multithreaded Programs. Journal of Systems and Software. 2016, 119: 136-148. (CCF B)

- `Zhenzhou Tian`, Qinghua Zheng, Ting Liu, Ming Fan, Eryue Zhuang, Zijiang Yang. Software Plagiarism Detection with Birthmarks based on Dynamic Key Instruction Sequences. *IEEE Transactions on Software Engineering*. 2015, 41(12): 1217-1235. (CCF A)

- `Ming Fan`, Zhenzhou Tian, Ting Liu. SODB: A Novel method for Software Plagiarism Detection based on Stack Operation Dynamic Birthmark. *Journal of Shandong University (Natural Science)*. 2014, 49(9): 9-16.


### Conference
---

- `Zhenzhou Tian`, Yaqian Huang, Jie Tian, Zhongmin Wang, Yanping Chen, and Lingwei Chen. Ethereum Smart Contract Representation Learning for Robust Bytecode-Level Similarity Detection. *International Conference on Software Engineering and Knowledge Engineering (SEKE)*. 2022. (CCF C)

- `Zhenzhou Tian`, Hengchao Mao, Yaqian Huang, Jie Tian, and Jinrui Li. Fine-grained obfuscation scheme recognition on binary code. *International Conference on Digital Forensics and Cyber Crime (ICDF2C)*. 2021, 215-228. (CCF C)

- Qing Wang, `Zhenzhou Tian`, Cong Gao, and Lingwei Chen. Plagiarism Detection of Multi-threaded Programs using Frequent Behavioral Pattern Mining. *International Conference on Software Engineering and Knowledge Engineering (SEKE)*. 2020. (<font color='red'>Best Paper Award</font>, CCF C)

- `Zhenzhou Tian`, Jinrui Li, Peng Xue, Jie Tian, Hengchao Mao, and Yaqian Huang. Functionality Recognition on Binary Code with Neural Representation Learning. *International Conference on Artificial Intelligence and Pattern Recognition (AIPR)*. 2021, 280-286.

- Borun Xie, Zhenzhou Tian, Cong Gao, and Lingwei Chen. Towards Fine-Grained Compiler Identification with Neural Modeling. *International Conference on Software Engineering and Knowledge Engineering (SEKE)*. 2020.
  
- Zhongmin Wang, Zhen Feng, and `Zhenzhou Tian*`. Neural Representation Learning based Binary Code Authorship Attribution. *International Conference on Digital Forensics and Cyber Crime (ICDF2C)*. 2020, 244-249. (CCF C)

- Cong Gao, Zhenzhou Tian, Yanping Chen, Zhongmin Wang. A Novel Virtual Sensor Management Scheme for Manufacturing Network. *International Conference on Networking and Network Applications (NaNA)*. 2018, 29-35.

- Ming Fan, Jun Liu, Xiapu Luo, Kai Chen, Tianyi Chen, `Zhenzhou Tian`, Xiaodong Zhang, Qinghua Zheng, and Ting Liu. Frequent subgraph based familial classification of android malware. *International Symposium on Software Reliability Engineering (ISSRE)*. 2016, 24-35. (<font color='red'>Distinguished Paper Award</font>, CCF B)

- `Zhenzhou Tian`, Ting Liu, Qinghua Zheng, Feifei Tong, Ming Fan, and Zijiang Yang. A new thread-aware birthmark for plagiarism detection of multithreaded programs. *International Conference on Software Engineering Companion (ICSE-C)*. 2016, 734-736.

- Eryue Zhuang, `Zhenzhou Tian`, Xiaojun Cui, Jian Li, Zhiwen Wang. ERI: A New Method for Ensuring Request Integrity. *EAI International Conference on Mobile Multimedia Communications*. 2016, 126-129.

- `Zhenzhou Tian`, Qinghua Zheng, Ting Liu, Ming Fan, Xiaodong Zhang, and Zijiang Yang. Plagiarism detection for multithreaded software based on thread-aware software birthmarks. *International Conference on Program Comprehension*. 2014, 304-313. (CCF B)

- `Zhenzhou Tian`, Qinghua Zheng, Ming Fan, Eryue Zhuang, Haijun Wang, and Ting Liu. DBPD: A Dynamic Birthmark-based Software Plagiarism Detection Tool. *International Conference on Software Engineering and Knowledge Engineering (SEKE)*. 2014, 740-741. (<font color='red'>Best Demo Award</font>)

- `Zhenzhou Tian`, Qinghua Zheng, Ting Liu, Ming Fan. DKISB: Dynamic key instruction sequence birthmark for software plagiarism detection. *International Conference on High Performance Computing and Communications & IEEE International Conference on Embedded and Ubiquitous Computing (HPCC-EUC)*. 2013, 619-627. (CCF C)
 

### Patents
---
- `Zhenzhou Tian`, Borun Xie, Zhongmin Wang, Hengshan Zhang, Cong Gao, Jie Tian, Kunze He. A software plagiarism detection method based on reduced shortest path birthmark. Chinese Patent: ZL201910318246.6. Date: 2023-03-31.
- `Zhenzhou Tian`, Zhongmin Wang, Yanping Chen, Hengshan Zhang, Hong Xia, Ting Liu, Qinghua Zheng. Software partial plagiarism detection method based on dynamic instruction dependent graph birthmark. Chinese Patent: ZL201711072012.5. Date: 2021-05-18. 
- `Zhenzhou Tian`, Qing Wang, Cong Gao, Zhongmin Wang, Yanping Chen, Hengshan Zhang. A multi-threaded program plagiarism detection method based on frequent pattern mining. Chinese Patent: ZL201910818878.9. Date: 2021-04-30.
- Hengshan Zhang, Zhongmin Wang, Yanping Chen, `Zhenzhou Tian`, Cong Gao, Hanlin Sun, Ning Lv, Jingtao Sun, Hong Xia, Yukun Gao. User evaluation data analysis based on accuracy decision. Chinese Patent: ZL201810327374.2. Date: 2021-08-31.
- Hengshan Zhang, Zhongmin Wang, Yanping Chen, `Zhenzhou Tian`, Cong Gao, Hanlin Sun, Qingtao Yuan, Yukun Gao. Heterogeneous software trust index fusion based on rank assignment. Chinese Patent: ZL201810327392.0. Date: 2021-07-02.
- Hong Xia, Yanping Chen, Zhongmin Wang, Long Ma, Xin Wang, Hengshan Zhang, `Zhenzhou Tian`, Cong Gao. Core service discovery based on service network. Chinese Patent: ZL201810155794.7. Date: 2021-02-26.
- Jun Liu, Ting Liu, Ming Fan, Qinghua Zheng, Tianyi Chen, Heng Liu, Chunyin Nong, `Zhenzhou Tian`, Eryue Zhuang. Detection of Android malicious repackaging software based on sensitive subgraph. Chinese Patent: ZL201610590632.7. Date: 2019-02-05.
- Qinghua Zheng, Ting Liu, Jun Liu, Ming Fan, Zhenzhou Tian. Method for plagiarism detection of multithreaded program based on thread slice birthmark. US Patent: US9652601B2. Date: 2017-05-16.
- Qinghua Zheng, Jun Liu, Ming Fan, `Zhenzhou Tian`, Ting Liu, Zijiang Yang. Thread-aware birthmark based plagiarism detection of multithreaded programs. Chinese Patent: ZL201410076931.X. Date: 2016-12-07
- Qinghua Zheng, `Zhenzhou Tian`, Ting Liu, Ming Fan. Software plagiarism detection based on dynamic key instruction sequence. 授权号: ZL201310449858.1. 授权日期: 2016-03-30.
- Qinghua Zheng, `Zhenzhou Tian`, Ming Fan, Ting Liu, Eryue Zhuang. Online authentication of taxpayer identity with vary-length system call sequence birthmark. Chinese Patent: ZL201410320245.2. Date: 2015-10-21.
- Ting Liu, Ming Fan, `Zhenzhou Tian`, Qinghua Zheng, Jun Liu. Dynamic authentication of taxpayer identity utilizing stack operation birthmark. Chinese Patent: ZL201410320243.3. Date: 2015-07-08.

 
<span class='anchor' id='-xsfw'></span>

# 🏛️ Academic Service
- PC Member: ISSRE (2021-2025), SEKE (2020-2025), ICA3PP (2017)
- Reviewer: TIFS, TSE, ToSEM, TDSC, ToR, JSS, ASEJ, EMSE, IST, JSA, ESWA, IJSEKE, Frontiers of Computer Science, Neurocomputing, Mathematics and Computers in Simulation, SEKE, ISSRE, Journal of Cyber Security，Computer Science, Netinfo Security
  
