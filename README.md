# Comparative Analysis of Generative Models for Artistic Image Synthesis on ArtBench-10

This repository contains the implementation, trained models, and experimental results for the project:

**Comparative Analysis of Generative Models for Artistic Image Synthesis on ArtBench-10**

**Authors**:

- Arthur Sophiatti [2022115599]
- Giovanni Faedo [2025267503]

Developed at the University of Coimbra.

---

## 📌 Project Overview

The goal of this project is to compare three major generative modeling paradigms for artistic image synthesis on the ArtBench-10 dataset:

- Variational Autoencoders (VAE)
- Generative Adversarial Networks (DCGAN)
- Diffusion Models (Pixel and Latent)

All models were trained on 32x32 RGB images across ten artistic styles.

Evaluation was performed using:

- Fréchet Inception Distance (FID)
- Kernel Inception Distance (KID)

---

## 📁 Repository Structure

```text
GenAI_Project/
│
├── TP1-alunos-search-only/
│   └── student_start_pack/
│       └── ArtBench-10_Student_Start_Pack.ipynb   # Main notebook
│
├── configs/      # Hyperparameter configurations (.json)
├── results/      # Evaluation metrics and outputs (.json)
├── history/      # Training logs (.json)
├── Comparative_Analysis_of_Generative_Models_for_Artistic_Image_Synthesis_on_ArtBench_10.pdf
└── README.md
