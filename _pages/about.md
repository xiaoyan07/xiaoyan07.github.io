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

# 👋 Hi there
I am currently a Research Fellow in the Department of Mechanical Engineering at the National University of Singapore (NUS), working on multimodal remote sensing data fusion, analysis, and applications for disaster response and sustainable development.

Email: xiaoyan.lu@nus.edu.sg; luxiaoyan@whu.edu.cn


# 🎉 News
- *2025.05*: &nbsp;Co-organize the 2025 ICCV workshop: [SEA: Sustainability with Earth Observation & AI](https://sustain-eo-ai.github.io/), <span style="color:red;">Submission Deadline: 22 June 2025</span>. 
- *2025.01*: &nbsp;Leading Guest Editor (Special Issue: [Multimodal Remote Sensing Data Fusion, Analysis and Application](https://www.mdpi.com/journal/remotesensing/special_issues/C1B5QOZKFX)), <span style="color:red;">Submission Deadline: 30 September 2026</span>. 

# 📝 Publications 
(\*Corresponding Author)

- **Xiaoyan Lu**, Qihao Weng\*. Semantic segmentation of single SAR imagery leveraging historical Sentinel-1 and Sentinel-2 data. *International Journal of Applied Earth Observation and Geoinformation (**JAG**)*, SCI Q1 TOP, 2026. [paper](https://www.sciencedirect.com/science/article/pii/S1569843226000300?via%3Dihub), [code and data](https://github.com/xiaoyan07/DEMFuse)

  <span style="color:red;">Highlight:</span> Globally distributed SAR-to-optical image translation dataset and SAR semantic segmentation dataset, SAR-to-optical translation, Degradable multimodal fusion.

- **Xiaoyan Lu**, Qihao Weng\*. Tree Mapping with Limited Data: Fine-Tuning Foundation Models for Multimodal Fusion. IEEE/CVF International Conference on Computer Vision Workshops (ICCVW), 2025.[paper](https://openaccess.thecvf.com/content/ICCV2025W/SEA/html/Lu_Tree_Mapping_with_Limited_Data_Fine-Tuning_Foundation_Models_for_Multimodal_ICCVW_2025_paper.html)
  
  <span style="color:red;">Highlight:</span> Fine-tuning foundation models, Fusion of visual features and deep features, Depth estimation.

- **Xiaoyan Lu**, Qihao Weng\*. Deep learning-based road extraction from remote sensing imagery: Progress, problems, and perspectives. *ISPRS Journal of Photogrammetry and Remote Sensing (**ISPRS**)*, SCI Q1 TOP, 2025. [paper](https://www.sciencedirect.com/science/article/pii/S0924271625002758), [project](https://github.com/xiaoyan07/GRE-Hub)
  
  <span style="color:red;">Highlight:</span> Review of road segmentation and road graph extraction, 2017-2024.
  
- **Xiaoyan Lu**, Qihao Weng\*. Multi-LoRA Fine-Tuned Segment Anything Model for Urban Man-Made Object Extraction. *IEEE Transactions on Geoscience and Remote Sensing (**TGRS**)*, SCI Q1 TOP, 2024. [paper](https://ieeexplore.ieee.org/abstract/document/10637992), [code and data](https://github.com/xiaoyan07/SAM_MLoRA)

  <span style="color:red;">Highlight:</span> Fine-tuning the SAM foundation model, Multi-LoRA alleviates overfitting; Supervised and unsupervised fine-tuning strategies.

- **Xiaoyan Lu**, Yanfei Zhong\*, Zhuo Zheng, Junjue Wang, Dingyuan Chen, Yu Su. Global road extraction using a pseudo-label guided framework: from benchmark dataset to cross-region semi-supervised learning. *Geo-spatial Information Science (**GSIS**)*, SCI Q1, 2024. [paper](https://www.tandfonline.com/doi/full/10.1080/10095020.2024.2362760?src=), [code and data](https://github.com/xiaoyan07/GRNet_GRSet)

  <span style="color:red;">Highlight:</span> Global-scale road benchmark dataset: GRSet and GSRV; Semi-supervised learning adapts the model from GRSet to new imagery across diverse geographical regions worldwide.

- **Xiaoyan Lu**, Yanfei Zhong\*, Liangpei Zhang. Open-Source Data-Driven Cross-Domain Road Detection From Very High Resolution Remote Sensing Imagery. *IEEE Transactions on Image Processing (**TIP**)*, SCI Q1 TOP, CCF-A, 2022. [paper](https://ieeexplore.ieee.org/abstract/document/9931623)

  <span style="color:red;">Highlight:</span> Utilizing OSM road centerlines to generate the supervised information of the target domain; Domain-specific representation framework designed to learn domain-invariant structure features and domain-specific texture information.
  
- **Xiaoyan Lu**, Yanfei Zhong\*, Zhuo Zheng, Junjue Wang. Cross-domain road detection based on global-local adversarial learning framework from very high resolution satellite imagery. *ISPRS Journal of Photogrammetry and Remote Sensing (**ISPRS**)*, SCI Q1 TOP, 2021. [paper](https://www.sciencedirect.com/science/article/abs/pii/S0924271621002240)

  <span style="color:red;">Highlight:</span> Unsupervised domain adaptation requires only target domain images; Global-local adversarial learning adaptively reweights the adversarial loss according to the recognition difficulty of each pixel.

- **Xiaoyan Lu**, Yanfei Zhong\*, Zhuo Zheng, Dingyuan Chen, Yu Su, Ailong Ma, Liangpei Zhang. Cascaded multi-task road extraction network for road surface, centerline, and edge extraction. *IEEE Transactions on Geoscience and Remote Sensing (**TGRS**)*, SCI Q1 TOP, 2022. [paper](https://ieeexplore.ieee.org/abstract/document/9756441)
- **Xiaoyan Lu**, Yanfei Zhong\*, Zhuo Zheng, Liangpei Zhang. GAMSNet: Globally aware road detection network with multi-scale residual learning. *ISPRS Journal of Photogrammetry and Remote Sensing (**ISPRS**)*. SCI Q1 TOP, 2021. [paper](https://www.sciencedirect.com/science/article/abs/pii/S0924271621000770), [data](http://rsidea.whu.edu.cn/resource_LSRV_sharing.htm), [code](https://github.com/WanderRainy/OARENet)
- Li Huang, **Xiaoyan Lu (co-first author)**, Xu Huang, Xiaoping Zou, Lianlian Wu, Zhongyin Zhou, Deqing Wu, Dehua Tang, Dingyuan Chen, Xinyue Wan, Zhongchao Zhu, Tao Deng, Lei Shen, Jun Liu, Yijie Zhu, Dexin Gong, Di Chen, Yanfei Zhong, Feng Liu, Honggang Yu\*. Intelligent difficulty scoring and assistance system for endoscopic extraction of common bile duct stones based on deep learning: multicenter study. *Endoscopy*, SCI Q1 TOP, 2021. [paper](https://www.thieme-connect.com/products/ejournals/abstract/10.1055/a-1244-5698),  [video](https://www.thieme-connect.de/products/ejournals/abstract/10.1055/a-1289-5529)
- **Xiaoyan Lu**, Yanfei Zhong\*, Zhuo Zheng, Ji Zhao, Liangpei Zhang. Edge-reinforced convolutional neural network for road detection in very-high-resolution remote sensing imagery. *Photogrammetric Engineering & Remote Sensing (**PE&RS**)*, SCI, 2020. [paper](https://www.ingentaconnect.com/content/asprs/pers/2020/00000086/00000003/art00006), [John I. Davidson President' s Award](https://www.asprs.org/Main/Education---Careers/Award-Winners/2021-Award-Winners.aspx)
- **Xiaoyan Lu**, Yanfei Zhong\*, Zhuo Zheng, Yanfei Liu, Ji Zhao, Ailong Ma, Jie Yang. Multi-scale and multi-task deep learning framework for automatic road extraction. *IEEE Transactions on Geoscience and Remote Sensing (**TGRS**)*, SCI Q1 TOP, 2019. [paper](https://ieeexplore.ieee.org/abstract/document/8792386)

# 🎖 Selected Honors and Awards
- *2023*, PolyU Distinguished Postdoctoral Fellowship Scheme
- *2022*, Second Prize of Graduate Academic Innovation Award, Wuhan University. ([武汉大学“研究生学术创新奖”二等奖](https://liesmars.whu.edu.cn/info/1058/6731.htm))
- *2022*, Outstanding Graduate of Wuhan University. [武汉大学优秀毕业生](https://liesmars.whu.edu.cn/info/1058/3977.htm)
- *2021*, First Prize of Wang Zhizhuo Innovation Talent, Wuhan University. [武汉大学“王之卓创新人才奖”一等奖](https://rsgis.whu.edu.cn/info/1080/9862.htm)
- *2021*, First Prize of Graduate Academic Innovation Award, Wuhan University. [武汉大学“研究生学术创新奖”一等奖](https://gs.whu.edu.cn/info/1162/8687.htm)
- *2021*, First-place of the 2021 John I. Davidson President' s Award, ASPRS. [美国摄影测量与遥感学会 约翰·戴维森主席奖 一等奖](https://www.asprs.org/Main/Education---Careers/Award-Winners/2021-Award-Winners.aspx)
- *2020*, First Prize of Hongtu Chuangzhan Scholarship, Wuhan University. [武汉大学“宏图创展奖学金”一等奖](https://info.whu.edu.cn/info/1447/17855.htm)
- *2019*, Outstanding Graduate of Wuhan University. [武汉大学优秀毕业生](https://liesmars.whu.edu.cn/info/1004/2285.htm)

# 📖 Educations
- *2019.09 - 2022.06*,  Ph.D.,  [LIESMARS](https://liesmars.whu.edu.cn/),  [Wuhan University](https://www.whu.edu.cn/). Supervisor: [Prof. Yanfei Zhong](http://rsidea.whu.edu.cn/zhongyanfei.htm) and [Prof. Liangpei Zhang](https://www.zhangliangpei.cn/).
- *2017.09 - 2019.06*,  M.E.,  [LIESMARS](https://liesmars.whu.edu.cn/),  [Wuhan University](https://www.whu.edu.cn/). Supervisor: [Prof. Yanfei Zhong](http://rsidea.whu.edu.cn/zhongyanfei.htm) and [Prof. Liangpei Zhang](https://www.zhangliangpei.cn/).
- *2013.09 - 2017.06*,  B.E.,  [School of GeoSciences and Info-Physics](https://gip.csu.edu.cn/),  [Central South University](https://www.csu.edu.cn/). 

# 🙆‍♀️ Services
- Journal Reviewer: IEEE Transactions on Image Processing (TIP); ISPRS Journal of Photogrammetry and Remote Sensing (ISPRS); IEEE Transactions on Geoscience and Remote Sensing (TGRS); International Journal of Digital Earth (IJDE); IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing (JSTARS); European Journal of Remote Sensing (EuJRS); Remote Sensing; Conference on Neural Information Processing Systems (NeurIPS);
- Program Chair (SEA: Sustainability with Earth Observation & AI) of ICCVW 2025.
- Session Chair (Infrastructure Detection) of IGARSS 2021.
- Guest Editor, Remote Sensing.

