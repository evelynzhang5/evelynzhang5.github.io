---
layout: single
author_profile: true
title: "Home"
permalink: /
classes: wide
---

Hi, I'm Evelyn Zhang, a UCSD undergraduate pursuing dual B.S. degrees in Data Science and Cognitive Science with a specialization in Machine Learning and Neural Computation. My interests lie at the intersection of machine learning, computer vision, biomedical imaging, and scalable research tools. I have worked on projects ranging from histopathological cancer diagnosis and whole-slide image analysis platforms to brain EM segmentation, functional brain imaging prediction, and open-source text-to-video model development. I enjoy building end-to-end systems that combine data preprocessing, model development, visualization, and deployment to solve real-world scientific and biomedical problems.

## Recent Projects

### Hybrid CNN–gMLP for Histopathological Cancer Diagnosis

Designed a hybrid CNN–gMLP architecture for endometrial cancer diagnosis, combining local morphological feature extraction with global contextual modeling. Improved classification accuracy from 91.7% to 95.9% over the baseline ECgMLP model through ablation studies and hyperparameter tuning.

[GitHub](https://github.com/evelynzhang5/ECgMLP){: .btn .btn--primary}
[Paper / Report](https://drive.google.com/file/d/1eSybQ0bE_mykKyYjzsb69BWIZNzDV_a-/view?usp=sharing){: .btn .btn--inverse}

---

### Lipid Histopathology Web Platform

Built a cloud-native web platform for whole-slide histopathology analysis using GCP, FastAPI, Cloud Run, Firestore, QuPath, Cellpose, React, and Firebase. The system supports secure authentication, real-time job tracking, automated segmentation pipelines, OME-TIFF and overlay exports, and interactive WSI visualization.

[GitHub](https://github.com/evelynzhang5/lipid-workers){: .btn .btn--primary}

---

### Predicting Sex and ADHD Diagnosis from Functional Brain Imaging

Built machine learning models using LightGBM and CatBoost to predict ADHD diagnosis and biological sex from functional brain imaging data. The project achieved approximately 80% accuracy for ADHD prediction and 60% accuracy for sex prediction.

[GitHub](https://github.com/evelynzhang5/ADHD_Classification){: .btn .btn--primary}

---

### FastVideo Open-Source Text-to-Video Development

Contributed to FastVideo open-source development at Hao AI Lab, supporting text-to-video preprocessing, training, and fine-tuning workflows for HunyuanVideo models. Work included writing CI tests, integrating model pipeline components, and resolving user-reported issues.

[GitHub](https://github.com/hao-ai-lab/FastVideo){: .btn .btn--primary}

--- 

### Decoding Linearly Separable Neural Fingerprints via Discrete Wavelet Transform

Traditional EEG biometrics often rely on active cognitive tasks (e.g., motor imagery), which are intrusive and unstable. Our project asks: Can we identify individuals purely from their background "hardware" brainwaves, regardless of what they are looking at? We hypothesized that by suppressing task-evoked potentials (ERPs) using mathematical phase cancellation, we could isolate a stable, task-independent neural fingerprint in the occipital lobe.

[GitHub](https://github.com/evelynzhang5/EEG-Biometrics-Neural-Identity){: .btn .btn--primary}
[Paper / Report](https://github.com/evelynzhang5/EEG-Biometrics-Neural-Identity/blob/main/final_bci_report.pdf){: .btn .btn--inverse}

---

### Rhythms of the Night: Two-Week Mouse Activity & Temperature Across Estrus Cycles

Created an interactive website for visualizing mouse activity and body temperature patterns across the ovulation cycle. The project allows users to explore two weeks of behavioral and physiological data through interactive visualizations.

[GitHub](https://github.com/evelynzhang5/Mouse_final){: .btn .btn--primary}
[Demo](https://youtu.be/6VLHxTpM_mY/){: .btn .btn--inverse}
[Website](https://evelynzhang5.github.io/Mouse_final/){: .btn .btn--primary}

---

### Bike Traffic in Boston and Cambridge

Built an interactive Mapbox GL JS visualization exploring bike lanes and bike traffic in Boston and Cambridge during March 2024. The project visualizes approximately 260,000 individual rides and connects ride patterns with geographic bike infrastructure.

[GitHub](https://github.com/evelynzhang5/bikewatching){: .btn .btn--primary}
[Demo](https://evelynzhang5.github.io/bikewatching/){: .btn .btn--inverse}

---

### Alzheimer’s Disease Progression Study and MRI Classification

Built and trained a convolutional neural network to classify stages of Alzheimer’s disease based on MRI scans. The project focused on medical image classification and using deep learning to support disease progression analysis.

[GitHub](https://github.com/YOUR_USERNAME/YOUR_REPO){: .btn .btn--primary}
[Report](https://your-report-link.com){: .btn .btn--inverse}

---

### Recipe Rating Prediction with Meat Inclusion

Developed a machine learning pipeline to predict recipe ratings using random forest classification, feature engineering, and feature transformers. Improved model performance by using grid search to tune hyperparameters and evaluate precision and recall.

[GitHub](https://github.com/YOUR_USERNAME/YOUR_REPO){: .btn .btn--primary}
[Website](https://evelynzhang5.github.io/recipe_rating/){: .btn .btn--primary}

---

### Can Relationship Affect Serial Killer’s Weapon Choice?

Investigated whether offender-victim relationship type influences weapon choice in solved Alaska homicide cases from 2000 to 2023. Using data cleaning, visualization, statistical tests, and Random Forest modeling, the project found that stranger-related incidents were more strongly associated with firearms, while close-relationship cases showed more complex patterns influenced by additional demographic and situational factors.

[Report](https://github.com/evelynzhang5/weapon_choice/blob/main/FinalProject_Group081-FA24.ipynb){: .btn .btn--inverse}

---

### Bootstrapper & Local Shape Descriptor Models for Brain EM Data

Developed a bootstrapped training pipeline for predicting 3D brain tissue volumes from sparse labels. This project involved automated grid search for hyperparameter optimization, large-scale GPU runs, and visualization of segmentation outputs using Neuroglancer.
