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

I am an undergraduate researcher in **Computer Engineering** at the University of Michigan, minoring in **Mathematics (4.0 GPA)**. My research focuses on **Robotics and Embodied AI, Mobile Manipulation, Autonomous Exploration and Navigation, VLMs, Diffusion Model, Biomedical Imaging, etc.**. I work with **Asst. Prof. Cong Ma** (Umich) on scalable probabilistic models for spatial transcriptomics, with **Prof. Bernadette Bucher**(Umich) on HELIOS: Hierarchical Exploration for Language-grounded Interaction in Open Scenes and with **Prof. Min Xu** (CMU) on spatial-relation-aware diffusion models.

My long-term interest lies in the intersection of **ML/DL/CV**, including generative modeling, computational pathology, and spatial-omics representation learning.

You can find my publications on  
🧪 **Google Scholar:** <a href='https://scholar.google.com/citations?user={{site.google_scholar_id}}'><strong><span id='total_cit'>Click here</span></strong></a>  

---

<span class='anchor' id='education'></span>
# 🎓 Education

**University of Michigan, Ann Arbor** · *09/2024 – 06/2026 (Expected)*  
**B.S. in Computer Engineering, Minor in Mathematics (4.0)**

**Sichuan University, China** · *09/2022 – 07/2024*  
B.S. in Electrical & Computer Engineering

---

<span class='anchor' id='interests'></span>
# 🔬 Academic Interests
Robotics and Embodied AI • Mobile Manipulation • Autonomous Exploration and Navigation • VLMs • Machine Learning • Deep Learning • Computer Vision • Diffusion Models • Biomedical & Spatial Imaging • Radiomics • Spatial Transcriptomics • Computational Biology  

---

<span class='anchor' id='publications'></span>
# 📚 Publications  
*(† indicates co-first authors)*

1. Xiaoyan Zhu, Ruchun Jia, **Tingrui Zhang**, Song Yao.  
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

<span class='anchor' id='research'></span>
# 🧪 Research Experience

## **University of Michigan – Research Assistant**  
*Advisor: Prof. Bernadette Bucher · 1/2026–Present*

**Project: HELIOS: Hierarchical Exploration for Language-grounded Interaction in Open Scenes**  
[[Project Page]](https://helios-robot-perception.github.io/) [[arXiv]](https://arxiv.org/abs/2509.22498) [[Code]](https://github.com/m-and-m-lab/helios)

<div style="display: flex; align-items: flex-start; gap: 20px; margin: 20px 0;">
  <div style="flex: 0 0 40%;">
    <img src="/images/2025_helios.png" alt="HELIOS Overview" style="width: 100%; border-radius: 6px;"/>
  </div>
  <div style="flex: 1;">
    <p>Proposed <strong>HELIOS</strong>, a hierarchical scene representation for language-specified mobile manipulation in partially observed environments, integrating 2D semantic navigation maps with 3D Gaussian object representations.</p>
    <ul>
      <li>Developed multi-view observation fusion and search objective balancing exploration with exploitation.</li>
      <li>Achieved state-of-the-art on <strong>OVMM benchmark</strong> in Habitat.</li>
      <li>Demonstrated real-world language-guided pick-and-place on a <strong>Spot robot</strong>.</li>
    </ul>
    <p>
      <a href="https://helios-robot-perception.github.io/">[Project Page]</a> &nbsp;
      <a href="https://arxiv.org/abs/2509.22498">[arXiv]</a> &nbsp;
      <a href="https://github.com/m-and-m-lab/helios">[Code]</a>
    </p>
  </div>
</div>

---

*Advisor: Prof. Cong Ma · 11/2024–Present*

**Project: COMPOSITION: Cell Type and Spatial Organization Modeling via Probabilistic Optimization of Spatially Informed Topics**  
[[Project Page]](https://github.com/CM-Compbio-Group/COMPOSITION)

<div style="display: flex; align-items: flex-start; gap: 20px; margin: 20px 0;">
  <div style="flex: 0 0 40%;">
    <img src="/images/composition.png" alt="COMPOSITION Overview" style="width: 100%; border-radius: 6px;"/>
  </div>
  <div style="flex: 1;">
    <ul>
      <li>Developed a probabilistic framework for reference-free inference of <strong>cell types</strong> and <strong>spatial domains</strong> in SRT data.</li>
      <li>Designed a <strong>neural network equivalent</strong> to the probabilistic model for GPU-accelerated inference.</li>
      <li>Demonstrated the ability to compare microenvironments across tissues to reveal biological heterogeneity.</li>
    </ul>
    <p>
      <a href="https://github.com/CM-Compbio-Group/COMPOSITION">[Project Page]</a>
    </p>
  </div>
</div>

---

## **Carnegie Mellon University – Research Intern**  
*Advisor: Prof. Min Xu · 03/2025–Present*

**Project: Relation-Aware Text-to-Image Diffusion**

<div style="display: flex; align-items: flex-start; gap: 20px; margin: 20px 0;">
  <div style="flex: 0 0 40%;">
    <img src="/images/SD.jpg" alt="Relation-Aware Diffusion Overview" style="width: 100%; border-radius: 6px; background: #f0f0f0; min-height: 150px;"/>
    <!-- TODO: replace with actual image -->
  </div>
  <div style="flex: 1;">
    <ul>
      <li>Built a <strong>multi-object, spatial-relation-aware diffusion pipeline</strong> on top of Stable Diffusion.</li>
      <li>Added layout priors via <strong>keypoint tokens + relation embeddings</strong>.</li>
      <li>Designed <strong>relation consistency losses</strong> and <strong>mask-guided attention control</strong> to improve generation fidelity.</li>
    </ul>
  </div>
</div>

---

## **West China Medical Sciences & Big Data Center – Research Intern**

**Project: Hybrid Radiomics Framework for NACT Response Prediction** *(09/2024–01/2025)*

<div style="display: flex; align-items: flex-start; gap: 20px; margin: 20px 0;">
  <div style="flex: 0 0 40%;">
    <img src="/images/nact_radiomics.png" alt="NACT Radiomics Overview" style="width: 100%; border-radius: 6px; background: #f0f0f0; min-height: 150px;"/>
    <!-- TODO: replace with actual image -->
  </div>
  <div style="flex: 1;">
    <ul>
      <li>Built a hybrid HCR + DLR radiomics pipeline for ESCC patient treatment response prediction.</li>
      <li>Designed a <strong>Transformer fusion network (TFR-Net)</strong> and integrated with AutoML for optimal model search.</li>
      <li>Validated across multi-center datasets with improved accuracy and generalizability.</li>
    </ul>
  </div>
</div>

---

**Project: Machine Learning-Assisted Diagnosis of Endometrial Cancer** *(03/2023–11/2024)*
[[Paper]](https://link.springer.com/article/10.1186/s12938-025-01462-w)
<div style="display: flex; align-items: flex-start; gap: 20px; margin: 20px 0;">
  <div style="flex: 0 0 40%;">
    <img src="/images/endometrial_cancer.webp" alt="Endometrial Cancer ML Overview" style="width: 100%; border-radius: 6px; background: #f0f0f0; min-height: 150px;"/>
  </div>
  <div style="flex: 1;">
    <ul>
      <li>Led development of ML models combining <strong>ITK-Snap</strong>, U-Net, Logistic Regression, SVC, Random Forest, XGBoost, TabPFN, etc.</li>
      <li>Identified <strong>Random Forest</strong> as the best-performing classifier across metrics.</li>
    </ul>
    <p>
      <a href="https://link.springer.com/article/10.1186/s12938-025-01462-w">[Paper]</a>
    </p>
  </div>
</div>

---

**Project: Tongue Radiomics for Insomnia Diagnosis** *(03/2023–01/2024)*
[[Paper]](https://www.tmrjournals.com/article.html?J_num=11&a_id=2958)
<div style="display: flex; align-items: flex-start; gap: 20px; margin: 20px 0;">
  <div style="flex: 0 0 40%;">
    <img src="/images/tongue_radiomics.png" alt="Tongue Radiomics Overview" style="width: 100%; border-radius: 6px; background: #f0f0f0; min-height: 150px;"/>
    <!-- TODO: replace with actual image -->
  </div>
  <div style="flex: 1;">
    <ul>
      <li>Built a tongue-imaging-based radiomics tool using <strong>PyRadiomics + U-Net + LASSO</strong>.</li>
      <li>Achieved accurate classification of insomnia severity.</li>
    </ul>
    <p>
      <a href="https://www.tmrjournals.com/article.html?J_num=11&a_id=2958">[Paper]</a>
    </p>
  </div>
</div>

---

**Project: Zero-Trust Data Tampering Prevention for ATC Networks** *(03/2023–01/2024)*
[[Paper]](https://www.sciencedirect.com/org/science/article/pii/S1546221824003461)
<div style="display: flex; align-items: flex-start; gap: 20px; margin: 20px 0;">
  <div style="flex: 0 0 40%;">
    <img src="/images/zero_trust.png" alt="Zero Trust Overview" style="width: 100%; border-radius: 6px;"/>
  </div>
  <div style="flex: 1;">
    <ul>
      <li>Developed a zero-trust–based tampering prevention system integrating RDTP protocol + physical-layer authentication.</li>
      <li>Achieved <strong>>99% tamper-proof success rate</strong>.</li>
    </ul>
    <p>
      <a href="https://www.sciencedirect.com/org/science/article/pii/S1546221824003461">[Paper]</a>
    </p>
  </div>
</div>
---

<span class='anchor' id='skills'></span>
# 🛠 Skills

**Programming:** Python, C/C++, MATLAB, VHDL, Verilog  
**ML Frameworks:** PyTorch, TensorFlow, Scikit-learn, XGBoost  
**Tools:** Git, SHAP, AWS, Greatlakes HPC, Slurm, Snakemake  
**OS:** Linux, Windows  

---

<span class='anchor' id='honors'></span>
# 🏆 Awards & Honors

- UMich Dean’s Honor List: *2025Winter* *2025 Summer*, *2024 Fall*  
- Distinguished Student Award (Top 10%) – 2024, 2023  
- First-Class Scholarship (Top 10%) – 2024  
- 3rd Prize, National Smart Supply Chain Innovation Challenge – 2023  
- Honor Undergraduate Research Program (Top 15%) – 2023  
- Vice President, Algorithmic Robot Association, Sichuan University (2023–Present)

---

<span class='anchor' id='posters'></span>
# 📌 Posters & Presentations
- DCMB/CCMB Annual Retreat  
- Michigan AI Symposium — *AI for Science*  
- BGSG/OGPS Poster Session  
