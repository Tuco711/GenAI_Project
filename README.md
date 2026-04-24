# Comparative Analysis of Generative Models for Artistic Image Synthesis on ArtBench-10

This repository contains the implementation, trained models, and experimental results for the project:

**Comparative Analysis of Generative Models for Artistic Image Synthesis on ArtBench-10**

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
├── configs/      # Hyperparameter configurations (.json)
├── results/      # Final metrics and evaluation outputs (.json)
├── history/      # Training logs and loss curves (.json)
├── src/          # Model architectures and utilities     
└── README.md
