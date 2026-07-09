
# **Multi-label Thoracic Disease Predictions from Chest X-ray Images**



![Workflow](https://github.com/harishmuh/AI-biomedical-research-and-disease-prediction/blob/main/Data/Multi-label%20Thoracic%20Diseases/Overall%20workflow.png?raw=true)

**Table 1. Summary of the Dataset Used in This Study**

| Attribute | Description |
|-----------|-------------|
| **Dataset Name** | NIH ChestX-ray14 |
| **Original Dataset** | 112,120 frontal chest X-ray images from 30,805 unique patients |
| **Dataset Source** | NIH Clinical Center |
| **Original Disease Labels** | 14 thoracic disease categories (multi-label classification) |
| **Image Modality** | Frontal chest radiographs (PA/AP views) |
| **Image Format** | PNG |
| **Subset Used in This Study** | 1,000 chest X-ray images |
| **Purpose of the Subset** | Inference and explainability analysis using a pretrained DenseNet121 model |
| **Primary Explainability Method** | Gradient-weighted Class Activation Mapping (Grad-CAM) |
| **Dataset License** | Publicly available for research purposes |

> **Dataset Resources**
>
> - Original dataset paper: [ChestX-ray8: Hospital-scale Chest X-ray Database and Benchmarks](https://arxiv.org/abs/1705.02315)
> - Official NIH clinical center, US research hospital, ChestX-ray14 dataset: https://nihcc.app.box.com/v/ChestXray-NIHCC
> - Curated 1,000-image subset used in this notebook: https://drive.google.com/file/d/1U23OnS30DkPxR4rPTXf2Msul7AJMc7A5/view
