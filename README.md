# AMIA Public Challenge 2026

This repository contains the code for the **AMIA Public Challenge 2026** (VinDr-CXR dataset). The project focuses on automated thoracic abnormality detection and segmentation using single-pass transformer-convolutional ensembling techniques.

---

## 📂 Repository Layout

```text
├── 📁 original_uncleaned/              # Raw execution notebooks, uncleaned 
├── 📄 01_eda.ipynb                     # Exploratory Data Analysis & generating plots for report
├── 📄 02_1_unet_baseline.ipynb         # UNet segmentation baseline model training
├── 📄 02_2_unet_eval_and_submit.ipynb  # UNet evaluation & submission
├── 📄 02_3_unet-annotations.ipynb      # Annotation handling : multi-radiologist consensus strategies
├── 📄 03_yolo.ipynb                    # YOLOv8m
├── 📄 04_1_rt-detr.ipynb               # RT-DETR transformer detector implementation
├── 📄 04_2_rt-detr_threshold.ipynb     # Post-processing & confidence threshold analysis
├── 📄 05_ensemble.ipynb                # Class-wise Weighted Box Fusion (WBF) final ensemble
├── 📄 ComputerVision_report_Hyunji_Lee.pdf # Final project report pdf file
└── 📄 README.md                        # Project documentation
