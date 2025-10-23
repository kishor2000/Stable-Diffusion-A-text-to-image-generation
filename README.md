
# Stable-Diffusion: A Text-to-Image Generation

This repository contains a complete implementation for generating images from text using a two-stage approach with **VQ-VAE** and **Diffusion Models**. The project is designed to train on high-quality datasets like CelebA-HQ and generate images in various styles.

---

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Repository Structure](#repository-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Training](#training)
- [Images](#images)
- [License](#license)

---

## Overview

This project implements a **text-to-image pipeline** using Stable Diffusion architecture:

1. **Stage 1: VQ-VAE**  
   Compresses images into discrete latent codes.
2. **Stage 2: Diffusion Model**  
   Generates high-quality images from latent codes guided by text prompts.

This modular approach allows easy experimentation with different datasets and diffusion parameters.

---

## Features

- Text-to-image synthesis
- Preprocessing and training scripts for VQ-VAE and Diffusion models
- Supports high-resolution datasets like CelebA-HQ
- Python-based implementation with PyTorch
- Easy-to-use inference scripts

---

## Repository Structure


