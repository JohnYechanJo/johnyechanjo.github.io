---
title: "Projects"
layout: single
permalink: /projects/
toc: true
toc_sticky: true
toc_label: "Projects"
---

## Research Projects

### Test-Time Adaptation for MRI Reconstruction
**[MAI-LAB](https://www.mai-lab.net/), [Yonsei University](https://yonsei.ac.kr/sites/en_sc/index.do)** | Jul - Dec 2025 | Capstone Design Project

* Validated the method's architectural versatility by extending experiments from U-Net to NAFNet, consistently proving Buffer's superior performance across five k-space sampling patterns at 4x and 8x acceleration.
* Conducted rigorous ablation studies revealing an acceleration-dependent adaptation mechanism, where the critical component for adaptation shifts from the encoder (at 4x) to the decoder (at 8x).
* Demonstrated superior generalization across mismatched train-test scenarios (e.g., 4x↔8x acceleration), verifying the method's potential for real-world clinical deployment.
* **[Excellence Award](https://drive.google.com/file/d/1z9gTuxco3AalX4z2MVWeH5z7XwBuMv5n/view?usp=sharing) (2nd place)** among 67 teams at 2025 Yonsei University EE-Festival.

---

## Professional Projects ([Mediark](https://mediark.io/en))

### Automated EMR Generation System
[[PDF]](https://drive.google.com/file/d/17saadefuxTK8tdXUick2qMRUcjjt05Yo/view?usp=sharing)

* Built an **end-to-end automated Electronic Medical Record (EMR) generation pipeline** using Speech-to-Text (STT) and NLP to reduce clinical documentation time.
* **Fine-tuned LLMs** on medical terminology and context to streamline clinical documentation.

### Estrogen (E2) Level Prediction for Menopausal Women
[[PDF]](https://drive.google.com/file/d/1VPGi1iXsMsgWcueMqUChXAorIOYkMkCd/view?usp=sharing)

* Designed a **deep feedforward neural network** to predict E2 levels using Age and Kupperman Index (KI) scores.
* Overcame small dataset limitations (N = 145) by engineering a novel data augmentation strategy (Inverse Relationship Model, GPR, SMOTE) that preserved physiological inverse correlations, expanding data by 14.2x.

### AI-Based Medical Test Recommendation System
[[PDF]](https://drive.google.com/file/d/142rNYpICWWlaLNQ8iSZSprOU36AvHUTd/view?usp=sharing)

* Built a **weight-based scoring engine** with [EXAONE](https://huggingface.co/LGAI-EXAONE/EXAONE-3.5-7.8B-Instruct) for explanations, which will be deployed at [OmniCare](https://omnicare.biz/) and [KMI](https://global.kmi.or.kr/?lang=en).
* Implemented **dual-factor prompt strategy** to effectively separate primary symptoms from reference information.

---

## Personal Projects

### [FastMRI: High-Quality Brain MRI Reconstruction](https://github.com/JohnYechanJo/FastMRI-High-Quality-Brain-MRI-Reconstruction)
Jul - Aug 2025

* Developed DR-CAM-GAN from scratch for high-quality MRI reconstruction at 4x/8x acceleration.
* Integrated SRGAN techniques into WGAN-GP's generator, boosting PSNR by 6.75% and SSIM by 5.97%.

### [Smart Glasses: Brain Tumor Detection and Description from MRI Images](https://github.com/JohnYechanJo/Smart-Glasses-Brain-Tumor-Detection-and-Description-from-MRI-Images)
May - Aug 2025

* Designed Smart Glasses with NVIDIA Jetson Nano and Ubuntu for brain tumor detection using "YOLOv11".
* Utilized "Grok 3 API" to generate detailed tumor descriptions for enhanced medical analysis.

### [Tuning of Diffusion Model for Enhancing Synthetic Data Usage Ratio](https://github.com/JohnYechanJo/Tuning-of-Diffusion-Model-for-Enhancing-Synthetic-Data-Usage-Ratios)
Mar - May 2025

* Fine-tuned a distilled Stable Diffusion model on 30,000 CNV images to generate 640 synthetic CNV images.
* Mixed real and synthetic data in varying ratios from 0% to 100% for binary CNV vs. Normal classification.

### [Masked Autoencoders for Retina Blood Vessel Segmentation](https://github.com/JohnYechanJo/Masked-Autoencoders-for-Retina-Blood-Vessel-Segmentation)
Jan - Feb 2025

* Developed a self-supervised segmentation pipeline with ResNet-based MAE for a 1,056-retina blood vessel dataset.
* Integrated Focal Tversky Loss to handle class imbalance, and applied ReduceLROnPlateau for faster convergence.

### Granvix: EV Safety System (UniverCT)
Aug - Nov 2024

* Developed an EV safety system utilizing TDR-based signal processing and Vision AI for hazard detection.
* **1st Place** at Yonsei-Asan UniverCT Demo Day, **2nd Place** at The 1st Asan UniverCT Demo Day.

---

## Technical Skills

**Programming Languages:** Python, C/C++, R, MATLAB

**Frameworks/Libraries:** PyTorch, TensorFlow, LangChain, Neo4j

**Languages:** English (Professional Proficiency), Korean (Native)
