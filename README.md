# Patch-Wise Neighborhood Feature Distribution Modeling for Anomaly Detection in Locomotive Roof Inspections

This repository contains the description and dataset for the **Patch-Wise Neighborhood Feature Distribution Modeling (PNFDM)** algorithm for anomaly detection in locomotive roof inspections, as described in our paper:

**[Patch-Wise Neighborhood Feature Distribution Modeling for Anomaly Detection in Locomotive Roof Inspections](https://github.com/zzfu-buaa/PNFDM)**

## Abstract

Electric locomotives rely heavily on their roof power supply systems, which are susceptible to foreign objects due to the complex outdoor environments. Detecting these objects accurately and in a timely manner is crucial for ensuring train safety. Traditional methods face challenges such as the diverse and unpredictable nature of foreign objects, difficulty in obtaining abnormal samples, and inconsistencies in image quality. To overcome these issues, we introduce the Patch-Wise Neighborhood Feature Distribution Modeling (PNFDM) algorithm. Experimental results demonstrate that our method significantly outperforms existing approaches on a locomotive roof anomaly dataset and generalizes effectively to the public MVTec AD dataset. The PNFDM algorithm allows for rapid model updates without needing abnormal samples, training on 100 samples in just 39.76 seconds.

## Dataset

Currently, only the locomotive roof anomaly detection dataset is publicly available. The dataset can be downloaded from the following link:

- [Dataset Download (Baidu Netdisk)](https://pan.baidu.com/s/1bzwh56EQWkKeYPufUTu7kg)(Extraction code：pij3）

After downloading, extract the dataset into the `data/` directory within this repository.

## Current Status and Future Work

The PNFDM code will be made available after the paper is accepted for publication. At this stage, we are providing the dataset and preliminary results to allow the community to explore the data and understand the challenges involved in locomotive roof anomaly detection.

## Preliminary Results

Our experiments show that the PNFDM algorithm achieves state-of-the-art performance on the locomotive roof anomaly dataset. Additionally, the method is also applicable to the MVTec AD dataset. Below are examples of the results for each dataset:
1. Locomotive Roof Anomaly Dataset:

![Locomotive Roof Anomaly Detection Example](Results/Roof_AD.png "Anomaly Detection Example on Locomotive Roof")

2. MVTec AD Dataset:

![MVTec AD Anomaly Detection Example](Results/MVTec_AD.png "Anomaly Detection Example on MVTec AD Dataset")


We will update this repository with the full codebase once the paper is officially published. Stay tuned for updates!

## Citation

If you find our dataset or preliminary results useful in your research, please cite our paper:

## Contact

For any questions or issues, please open an issue in this repository or contact us at [zzfu_mt@buaa.edu.cn].
