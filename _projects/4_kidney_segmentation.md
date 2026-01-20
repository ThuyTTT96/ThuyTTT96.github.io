---
layout: page
title: Kidney Pathology Segmentation
description: Comparative study of CNNs and Transformer models for CKD gland segmentation using MONAI
img: assets/img/project_kidney.jpg
importance: 4
category: research
---

## Overview

A deep learning project comparing CNN and Transformer-based architectures for segmenting kidney glands in chronic kidney disease (CKD) pathology images.

### Key Features

- **Model Comparison**: Trained and evaluated multiple architectures including UNet, UNetR, and Swin UNetR
- **MONAI Framework**: Leveraged MONAI (Medical Open Network for AI) for medical image analysis
- **Pathology Focus**: Specialized in CKD gland segmentation from histopathology images
- **Architecture Analysis**: Compared performance of CNNs vs. Transformer-based models

### Models Evaluated

| Model | Architecture Type | Key Features |
|-------|------------------|--------------|
| UNet | CNN | Classic encoder-decoder with skip connections |
| UNetR | Transformer | Vision Transformer encoder with CNN decoder |
| Swin UNetR | Transformer | Shifted window attention for efficiency |

### Technologies Used

- **Framework**: MONAI, PyTorch
- **Languages**: Python
- **Tools**: Slurm (HPC), Docker

### Key Learnings

- Transformer models showed promising results for medical image segmentation
- MONAI provides excellent tools for medical AI development
- Comparison insights useful for selecting appropriate architectures for pathology tasks

