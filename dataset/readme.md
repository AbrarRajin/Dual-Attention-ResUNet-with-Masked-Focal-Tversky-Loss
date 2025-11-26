# Dataset

We have used two SAR based datasets that are publicly available for the project:  

1. [SEN1FLOODS11](#1-sen1floods11-dataset)
2. [S1GFloods]()
---

## 1. Sen1Floods11 Dataset

**Sen1Floods11** is a georeferenced remote sensing dataset developed by *Cloud to Street* for training and evaluating deep learning models for flood mapping using Sentinel-1 (SAR) and Sentinel-2 (optical) imagery. Each sample consists of 512×512 chips containing paired radar, optical, and hand-labeled flood masks, all projected to **WGS84 (EPSG:4326)** at **10 m** resolution.

This dataset was introduced in:

**Bonafilia, D., Tellman, B., Anderson, T., & Issenberg, E. (2020).**  
*Sen1Floods11: A Georeferenced Dataset to Train and Test Deep Learning Flood Algorithms for Sentinel-1.*  
CVPR Workshops, 2020.



### Dataset Access  
The link to the dataset repository: https://github.com/cloudtostreet/Sen1Floods11

The dataset is publicly available on Google Cloud Storage. For detailed setup and download instructions, please follow the guidelines provided in the GitHub repository.

---

## 2. S1GFlood dataset
**S1GFloods** is a global-scale flood detection dataset introduced alongside **DAM-Net** (Differential Attention Metric-based Vision Transformers). The dataset contains high-resolution **paired Sentinel-1 SAR images** (pre-flood and post-flood) covering **42 flood events** worldwide between **2016–2022**, along with pixel-level ground truth flood masks. It includes diverse environments such as rivers, lakes, vegetation, and urban areas, supporting robust SAR-based flood detection research.

This dataset accompanies:

**Saleh, T., Xia, G-S., Holail, S., Weng, X., & Hao, C. (2023).**  
*DAM-Net: Global Flood Detection from SAR Imagery Using Differential Attention Metric-Based Vision Transformers.*  
ISPRS Journal of Photogrammetry and Remote Sensing.



### Dataset Overview

- Sensor: **Sentinel-1 SAR (IW, GRD)**
- Resolution: High-resolution chips, clipped into **256 × 256** patches  
- Events: **42 global flood events (2016–2022)**
- Labels: Pixel-level binary ground truth (flood / non-flood)
- Coverage: Bangladesh, Iran, Nigeria, China (Wuhan, Nanchang), Sudan, Zambia, USA (Red River North), and others

### Dataset Access
The github repository of the dataset: https://github.com/Tamer-Saleh/S1GFlood-Detection

For detailed setup and download instructions, please follow the guidelines provided in the GitHub repository.

---
