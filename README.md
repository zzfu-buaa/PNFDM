# Patch-Wise Neighborhood Feature Distribution Modeling for Anomaly Detection in Locomotive Roof Inspections

This repository contains the implementation of the **Patch-Wise Neighborhood Feature Distribution Modeling (PNFDM)** algorithm for anomaly detection in locomotive roof inspections, as described in our paper:

**[Patch-Wise Neighborhood Feature Distribution Modeling for Anomaly Detection in Locomotive Roof Inspections](https://github.com/zzfu-buaa/PNFDM)**

## Abstract

Electric locomotives rely heavily on their roof power supply systems, which are susceptible to foreign objects due to the complex outdoor environments. Detecting these objects accurately and in a timely manner is crucial for ensuring train safety. Traditional methods face challenges such as the diverse and unpredictable nature of foreign objects, difficulty in obtaining abnormal samples, and inconsistencies in image quality.

To overcome these issues, we introduce the Patch-Wise Neighborhood Feature Distribution Modeling (PNFDM) algorithm. This method models normal image features at the patch level using multiple multivariate Gaussian distributions and employs Mahalanobis distances to create an anomaly heatmap. Additionally, a patch-wise neighborhood feature sharing strategy enhances the signal-to-noise ratio of the anomaly heatmap.

To optimize storage and loading times, our approach utilizes a low-rank approximation via SVD decomposition, reducing model size by nearly 110 times and accelerating loading by 103 times. We also apply a chi-square distribution-based normalization to map Mahalanobis distances to a 0-1 range, aiding in threshold selection for anomaly localization.

Experimental results demonstrate that our method significantly outperforms existing approaches on a locomotive roof anomaly dataset and generalizes effectively to the public MVTec AD dataset. The PNFDM algorithm allows for rapid model updates without needing abnormal samples, training on 100 samples in just 39.76 seconds.

## Repository Contents
