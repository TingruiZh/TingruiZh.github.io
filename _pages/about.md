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

# 👋 Hi, I'm **Tingrui Zhang**  
Phone: +1 734-913-3498 · Email: tingruiz@umich.edu · Ann Arbor, MI

I am an undergraduate researcher in **Computer Engineering** at the University of Michigan, minoring in **Mathematics (4.0 GPA)**. My research focuses on **machine learning, computer vision, diffusion models, and spatial/biomedical imaging**. I work with **Asst. Prof. Cong Ma** on scalable probabilistic models for spatial transcriptomics, and with **Prof. Min Xu** (CMU) on spatial-relation-aware diffusion models.

My long-term interest lies in the intersection of **ML + Bio/Health**, including generative modeling, computational pathology, and spatial-omics representation learning.

You can find my publications on  
🧪 **Google Scholar:** <a href='https://scholar.google.com/citations?user={{site.google_scholar_id}}'><strong><span id='total_cit'>Click here</span></strong></a>  


---

# 🎓 Education

**University of Michigan, Ann Arbor** · *09/2024 – 06/2026 (Expected)*  
**B.S. in Computer Engineering, Minor in Mathematics (4.0)**

**Sichuan University, China** · *09/2022 – 07/2024*  
B.S. in Electrical & Computer Engineering

---

# 🔬 Academic Interests
Machine Learning • Deep Learning • Computer Vision • Diffusion Models  
Biomedical & Spatial Imaging • Radiomics • Spatial Transcriptomics • Computational Biology  

---

# 📚 Publications  
*(† indicates co-first authors)*

1. **Xiaoyan Zhu, Ruchun Jia, Tingrui Zhang**, Song Yao.  
   *Research on Data Tampering Prevention Method for ATC Network Based on Zero Trust.*  
   **Computers, Materials & Continua**, 78(3), 2024, pp. 4363–4377.  
   <span class='show_paper_citations' data=''></span>

2. Rui Ye, ZeKun Jiang, Rong Shao, Qian Yan, Li-Juan Zhou, **Ting-Rui Zhang**, Ying-Chun Sun.  
   *Tongue Imaging-Based Radiomics Tool for Diagnosis of Insomnia Degree.*  
   **Medical Data Mining**, 2024.  
   <span class='show_paper_citations' data=''></span>

3. Wen Wen, **Tingrui Zhang**, Haina Zhao, Jingyan Liu, Heng Jiang, Yusheng He*, Zekun Jiang*.  
   *Multimodal ML Model Enhances Benign–Malignant Differentiation of Hypervascular Thyroid Nodules.*  
   **Gland Surgery**, 2025.  
   <span class='show_paper_citations' data=''></span>

4. **Tingrui Zhang†**, Honglin Wu†, Zekun Jiang, et al.  
   *Machine Learning for Endometrial Cancer Diagnosis Using CT Imaging.*  
   **Preprint**: https://doi.org/10.21203/rs.3.rs-6300206/v1  
   <span class='show_paper_citations' data=''></span>

5. Hexiao Huang†, **Tingrui Zhang†**, Haoyuan Hu†, Zekun Jiang†, et al.  
   *A Robust Deep Learning PET/CT Biomarker for POD24 and Survival Risk Stratification in Follicular Lymphoma.*  
   **Submitted to BMC**  
   <span class='show_paper_citations' data=''></span>

6. Jeongbin Park†, **Tingrui Zhang†**, Cong Ma†.  
   *COMPOSITION: Cell Type and Spatial Organization Modeling via Probabilistic Optimization of Spatially Informed Topics.*  
   **Submitted to RECOMB 2026**  
   <span class='show_paper_citations' data=''></span>

7. Jeongbin Park†, **Tingrui Zhang†**, Cong Ma†.  
   *Scalable Cell Type and Spatial Domain Modeling using Topic Inference of Cancer Niches.*  
   **Submitted to AACR**  
   <span class='show_paper_citations' data=''></span>

---

# 🧪 Research Experience

## **University of Michigan – Research Assistant**  
*Advisor: Asst. Prof. Cong Ma · 11/2024–Present*

**Project: COMPOSITION – Scalable Probabilistic Modeling for Spatial Transcriptomics**  
- Developed a probabilistic framework for reference-free inference of **cell types** and **spatial domains** in SRT data.  
- Designed a **neural network equivalent** to the probabilistic model for GPU-accelerated inference.  
- Demonstrated the ability to compare microenvironments across tissues to reveal biological heterogeneity.

---

## **Carnegie Mellon University – Research Intern**  
*Advisor: Prof. Min Xu · 03/2024–Present*

**Project: Relation-Aware Text-to-Image Diffusion**  
- Built a **multi-object, spatial-relation-aware diffusion pipeline** on top of Stable Diffusion.  
- Added layout priors via **keypoint tokens + relation embeddings**.  
- Designed **relation consistency losses** and **mask-guided attention control** to improve generation fidelity.

---

## **West China Medical Sciences & Big Data Center – Research Intern**  
### *Project: Hybrid Radiomics Framework for NACT Response Prediction* (09/2024–01/2025)  
- Built a hybrid HCR + DLR radiomics pipeline for ESCC patient treatment response prediction.  
- Designed a **Transformer fusion network (TFR-Net)** and integrated with AutoML for optimal model search.  
- Validated across multi-center datasets with improved accuracy and generalizability.

### *Project: Machine Learning-Assisted Diagnosis of Endometrial Cancer* (03/2023–11/2024)  
- Led development of ML models combining **ITK-Snap**, U-Net, Logistic Regression, SVC, Random Forest, XGBoost, TabPFN, etc.  
- Identified **Random Forest** as the best-performing classifier across metrics.

### *Project: Tongue Radiomics for Insomnia Diagnosis* (03/2023–01/2024)  
- Built a tongue-imaging-based radiomics tool using **PyRadiomics + U-Net + LASSO**.  
- Achieved accurate classification of insomnia severity.

### *Project: Zero-Trust Data Tampering Prevention for ATC Networks* (03/2023–01/2024)  
- Developed a zero-trust–based tampering prevention system integrating RDTP protocol + physical-layer authentication.  
- Achieved **>99% tamper-proof success rate**.

---

# 🛠 Skills

**Programming:** Python, C/C++, MATLAB, VHDL, Verilog  
**ML Frameworks:** PyTorch, TensorFlow, Scikit-learn, XGBoost  
**Tools:** Git, SHAP, AWS, Greatlakes HPC, Slurm, Snakemake  
**OS:** Linux, Windows  

---

# 🏆 Awards & Honors

- UMich Dean’s Honor List: *2025 Summer*, *2024 Fall*  
- Distinguished Student Award (Top 10%) – 2024, 2023  
- First-Class Scholarship (Top 10%) – 2024  
- 3rd Prize, National Smart Supply Chain Innovation Challenge – 2023  
- Honor Undergraduate Research Program (Top 15%) – 2023  
- Vice President, Algorithmic Robot Association, Sichuan University (2023–Present)

---

# 📌 Posters & Presentations
- DCMB/CCMB Annual Retreat  
- Michigan AI Symposium — *AI for Science*  
- BGSG/OGPS Poster Session  

