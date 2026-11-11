---
layout: single
author_profile: true
title: "Home"
permalink: /
classes: wide
---

Hi, I'm Evelyn Zhang, a UCSD undergraduate pursuing dual B.S. degrees in Data Science and Cognitive Science with a specialization in Machine Learning and Neural Computation. My interests lie at the intersection of machine learning, computer vision, biomedical imaging, and scalable research tools. I have worked on projects ranging from histopathological cancer diagnosis and whole-slide image analysis platforms to brain EM segmentation, functional brain imaging prediction, open-source text-to-video model development, and steering diffusion models. I enjoy building end-to-end systems that combine data preprocessing, model development, visualization, and deployment to solve real-world scientific and biomedical problems.

## Recent Projects

### Diffusion Steering: Classifier-Free Guidance Across Noise Levels

Research on how to steer diffusion models, starting with whether the classifier-free guidance (CFG) weight should change across noise levels instead of staying fixed. Trained EDM on the full CIFAR-10 dataset on a GPU cluster (~14 GPU hours, FID 412 → 50.2), trained an MNIST CFG network from scratch, and replicated Table 2 of the NA-RFM steering paper (Wang, Belkin & Wang, ICML 2026) on CIFAR-10. Ongoing work tests what makes a steering intervention actually control the final image on MNIST and Stable Diffusion 1.5. For example, a reference set biased toward portraits produced a "blur" direction that enlarged people in 4 of 4 prompts, and depth-of-field steering reduced background sharpness by 35.6% (the paper reports 27.6%).

[GitHub](https://github.com/evelynzhang5/dsc180-diffusion-steering){: .btn .btn--primary}
[Report](https://drive.google.com/file/d/1g770Y5qUykiv7fV8qXJDeAzsil7pHX60/view?usp=sharing){: .btn .btn--inverse}

---

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

### Reinforcement Learning and Test-Time Verification for Small-Model Mathematical Reasoning

Improved a fixed 4B Qwen math-reasoning model for the CSE 151B/251B competition using GRPO fine-tuning, judge-aware prompting, 12-way majority voting, and selective self-verification for free-form answers. The pipeline raised validation accuracy from 61.6% to roughly 68% and placed 16th out of 105 teams on the private leaderboard.

[GitHub](https://github.com/ZiyaoZzz/151B_SP26_Competition){: .btn .btn--primary}
[Paper / Report](/assets/reports/cse-151b-251b-final-report.pdf){: .btn .btn--inverse}

---

### Predicting Chronic Kidney Disease from Clinical and Laboratory Measurements

Built a supervised classification workflow for predicting chronic kidney disease from routine clinical and laboratory measurements. Compared logistic regression, KNN, and decision tree models with stratified cross-validation; the selected regularized logistic regression model achieved strong cross-validation performance and highlighted clinically meaningful predictors such as albumin, serum creatinine, blood urea, hemoglobin, hypertension, and diabetes.

[Paper / Report](/assets/reports/cogs109-ckd-final-report.pdf){: .btn .btn--inverse}

---

### Optimized ResNet18 for Low-Resolution Image Classification

Adapted ResNet18 for Tiny-ImageNet-200 by preserving early spatial detail with a smaller stride-1 convolution and removing the initial max-pooling layer. Ran optimizer ablations, metric analysis, and Grad-CAM visualizations, with the optimized ResNet18 and cosine-annealed SGD reaching 62.65% top-1 validation accuracy.

[GitHub](https://github.com/evelynzhang5/cogs181-final){: .btn .btn--primary}
[Paper / Report](/assets/reports/cogs181-final-project.pdf){: .btn .btn--inverse}

---

### Adversarial vs. Likelihood-Based Generation on CIFAR-10 and CelebA

Compared DCGAN, WGAN-GP, and VAE image generation across CIFAR-10 and CelebA under CPU-constrained training. The study analyzed fidelity, diversity, stability, runtime, and proxy classifier metrics, showing that GANs produced sharper samples, VAEs offered stronger coverage, and WGAN-GP reduced DCGAN-style mode collapse.

[Paper / Report](/assets/reports/cogs185-generative-models-report.pdf){: .btn .btn--inverse}

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
