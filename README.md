# 🧠 NEXUS Computer Vision

This repository contains all computer vision publications related to the NEXUS (Netherlands Ecosystem for Cross-specialty Unified Surgical intelligence) consortium.

---

## ⚡ Quick intro

This repository aims to gather publications, code and datasets produced by our group related to surgical foundation models, anatomy recognition/segmentation, and surgical phase recognition. 

---
## 🦁 Model zoo

We have opensourced multiple in-domain-pretrained DINOv1-3 models across various architectures including Vision Transformers (ViT), ConvNeXts, and more. These models are pretrained on **SurgeNet**, the largest reported surgical dataset to date, comprising over **4.7 million video frames** from more than **23 different procedures**. Available in different sizes, ranging from lightweight to large-scale architectures, they can be deployed for diverse surgical computer vision applications with varying computational requirements—from real-time intraoperative systems to high-accuracy offline analysis.

![DINO Model Zoo](images/dino_model_zoo.png)

Explore our complete model collection and implementation at [SurgeNet](https://github.com/TimJaspers0801/SurgeNet).

---

## 🛠️ Applications

### Surgical Annotation Tool

**ATLAS-Interactive** is an open-source framework for clip-level anatomical segmentation in minimally invasive surgery. It combines keyframe annotation with temporal mask propagation, enabling fast, temporally consistent labeling. The tool was trained on over 100 videos, 500 clips, and 120k surgical video frames including 14 surgical procedures and 42 distinct classes.

![ATLAS-Interactive Demo](videos/SurgeNetSeg_Labeling_Tool_Demo.gif)

Explore the tool and implementation at [ATLAS-Interactive](https://github.com/rlpddejong/ATLAS-Interactive/tree/main).

---

## 📄 Publications

### Surgical foundation models

| Journal / Conference | Title                                                                                              | Paper                                     | Code                                               | Citation | 
|--------------------|----------------------------------------------------------------------------------------------------| ----------------------------------------- | -------------------------------------------------- | --------- |
| MIDL 2026          | Towards Effective Surgical Representation Learning with DINO models                                | [Paper](https://openreview.net/forum?id=6FoIDPKzRV#discussion)                  | [Code](https://github.com/rlpddejong/SurgeNetDINO)                             | [BibTeX](bibtex/midl2026.bib) |
| MedIA 2025         | Scaling up self-supervised learning for improved surgical foundation models                        | [Paper](https://www.sciencedirect.com/science/article/pii/S1361841525004190) | [Code](https://github.com/TimJaspers0801/SurgeNet) | [BibTeX](bibtex/media2025.bib) |
| MICCAI-DEMI 2024   | Exploring the Effect of Dataset Diversity in Self-Supervised Learning for Surgical Computer Vision | [Paper](https://arxiv.org/abs/2407.17904) | [Code](https://github.com/TimJaspers0801/SurgeNet) | [BibTeX](bibtex/demi2025.bib) |

### Surgical anatomy recognition & segmentation


| Journal / Conference        | Title                                                                                                              | Paper                                                           | Code     | Citation                   |
|-----------------------------|--------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------|----------|----------------------------|
| Surg Endosc 2025            | Do segmentation metrics reflect clinical reality? A surgeon-centered evaluation in robot-assisted minimally invasive esophagectomy | [Paper](https://link.springer.com/article/10.1007/s00464-025-12266-3) |          | [BibTeX](bibtex/surgendosc2025.bib) |
| SPIE-Medical imaging 2024   | Benchmarking pretrained attention-based models for real-time recognition in RAMIE                                  | [Paper](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/13408/1340810/Benchmarking-pretrained-attention-based-models-for-real-time-recognition-in/10.1117/12.3045187.full)                                        |          | [BibTeX](bibtex/spie2024-recognition.bib) |
| Journal of Endourology 2024 | Estimating surgical urethral length on intraoperative robot-assisted prostatectomy images using artificial intelligence anatomy recognition| [Paper](https://www.liebertpub.com/doi/full/10.1089/end.2023.0697)    |          | [BibTeX](bibtex/journalendourology.bib) |
| Surg Endosc 2023            | Deep learning-based recognition of key anatomical structures during robot-assisted minimally invasive esophagectomy | [Paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10322962/) |          | [BibTeX](bibtex/surgendoscopy2023.bib) |
| Surg Endosc 2022            | Computer-aided anatomy recognition in intrathoracic and-abdominal surgery: a systematic review               | [Paper](https://link.springer.com/article/10.1007/s00464-022-09421-5) |          | [BibTeX](bibtex/surgendoscopy2022.bib) |

### Surgical phase recognition

| Journal / Conference      | Title                                                                                         | Paper                                     | Code                   | Citation                   |
|---------------------------| --------------------------------------------------------------------------------------------- | ----------------------------------------- | ---------------------- | --------------------------- |
| MICCAI 2025               | SemiVT-Surge: Semi-Supervised Video Transformer for Surgical Phase Recognition                | [Paper](https://link.springer.com/chapter/10.1007/978-3-032-05127-1_46) | [Code](https://github.com/IntraSurge/SemiVT-Surge) | [BibTeX](bibtex/miccai2025.bib) |
| SPIE-Medical imaging 2024 | Benchmarking and Enhancing Surgical Phase Recognition Models for Robot-Assisted Esophagectomy | [Paper](https://arxiv.org/abs/2412.04039)                  |  | [BibTeX](bibtex/spie2024-phase-recognitioin.bib) |



